- Bad Inputs
- Porous Defenses
	- Bad authentication, hard coded credentials, etc...

## Security Flaws
- Critical web application security flaws include injection
- FLaws occur as consequence of insufficient checking and validation of data and error codes in programs
- Awareness of these issues is a critical initial step in writing more secure program code
- Emphasis should be placed on need for software developers LOOK ON SLIDES

## Reducing Software Vulnerabilities
- Recommended:
	- Stopping vulnerabiliteis before occuring by using improved methods for specifying, designing, and building software
	- Fiding vulnerabilities before can be exploited by using better techniques and more efficient use of multiple testing methods
	- REducing impact of vulnerabilities by building more resilient architectures

## Software Security, Quality, and Relaibility
- Software quality and reliability:
	- Accidental fialure
	- Improve structured design
	- How often are bugs triggered
- Software security
	- Attacker chooses probability distribution
	- Triggered by inputs that differ from expected
	- Unlikely to be identified by using common testing approaches

## Defensive Programming
- Designign software that works under attack
- Requires attention on all appects
- Software able to detect attack result
- Look on slides
- Code built with not expecting normal in mind
## Security by Design
- Security and reliability common
- Softwarae development not as mature
- SAFECode
	- Develops piublications outlining industry best practices

## Handling Program Inputs
- LOOK ON SLIDES

## Input Size & Buffer Overflow
- Programmers often guess max size of input
- Safe coding treats all input as dangerous

## Interpretation of Program Input
- LOOK ON SLIDES

## Injection Attacks
- Flaws relating to invalid handling of input data
- Most often occur in scripting languages

## Cross Site Scripting (XSS) Attacks
- Attacks were input provided by one user is subsequently output ti anither user
- commonly seen in scritped Web applications
- Exploit assumption that all content from one site is equally trusted and hence permitted to interact with other content from the site
- LOOK ON SLIDES

## Validating Input Syntax
- Necessary to ensure data conform with any assumptions made about data before subsequent use
- Input dat ashould be compared against what is wanted
- Alternative is to compare input data with known dangerous values
- By only accepting known safe data, program is more likely to remain secure

## Alternate Encodings
- Growing requirements to support users with any language
- Unicode used for internationalization
- Canonicalizaiton
	- Transform input data into single, standard, minimal representation
	- Compared then easily validated

## Validating Numeric Input
- More concern for numeric data input
- First stored in fixed-size value
- Must correctly interpret text form and process consistently
	- Having issues comparing signed and unsigned

## Input Fuzzing
- Devleoped by Prof. Barton Miller
- Software tesitn gtehcnique that uses randomly generated data as inputs to a program
	- Range of inputs very large
	- Intent determine if program of function hanldes abonormal inputs
- Can also use templates to generate classes of known problematic inputs
- LOOK ON SLIDES

## Writing Safe Program Code
- High level languages issues
- Security Issues:
	- Correct algorithm implementation
	- Correct machine instrucitons for algorithm
	- Valid manipulation of data

## COrrect Algorithm Implementation
- Issue of good program development technique
- Initial sequence numbers are too much prdfate
- LOOK ON SLIDES
- ANother variant
	- LOOKO N SLIDES

## Ensuring Machine Language Correspons to Algorithm 
- Issue is ignored by most programmers
- Requires comparing machine code with original source
- LOOKN ON SLIDES

## Correct Data INterpretation
- Bdata stoed as bits/bytes in 
- LOOK ON SLIDES

## Race Conditions
- Need snychronas threading
- Deadlock
	- Processes or threds wait  oin a resouce held by other
	- One or more programs has to be terminated

## Operatingj Systme iNteracition
- Prgrom exe tue 
- LOOK ON SLIDE}]
## Env0k
- LOOK ON SLIDES

- Road-Admistrator genius## 

## LOOK ON SLIDe MISSED ONE

## HAndling Program Output
Final component is programo utput
- May be stored for future use, sent over net, displayed
- May be binary or text
- FIlter output content
- Character set should b especified