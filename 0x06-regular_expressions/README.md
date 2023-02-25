# What I learned from this project  
At the end of this project you are expected to be able to explain to anyone, without the help of Google:  
---  

## REGEX  
I took a lot of notes down below.

## Each scripts and their output?**  
* Script 0 - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method.      
* Script 1 - Using the project instructions, create a Ruby script that accepts one argument and pass it to a regular expression matching method.    
* Script 2 - create a Ruby script that accepts one argument and pass it to a regular expression matching method.      
* Script 3 - create a Ruby script that accepts one argument and pass it to a regular expression matching method.    
* Script 4 - create a Ruby script that accepts one argument and pass it to a regular expression matching method.    
* Script 5 - create a Ruby script that accepts one argument and pass it to a regular expression matching method.      
* Script 6 - The regular expression must match a 10 digit phone number.      
* Script 7 - The regular expression must be only matching: capital letters.   
* Script 8 - This exercise was prepared for you by Guillaume Plessis, VP of Infrastructure at TextMe.      
* Script 9 - One way to get started in getting a Software Engineering job at LinkedIn is to solve their regex puzzle.  


#### Limitations of these projects:  
___

-Allowed editors: vi, vim, emacs  
-All your files will be interpreted on Ubuntu 14.04 LTS  
-All your files should end with a new line  
-A README.md file, at the root of the folder of the project, is mandatory  
-All your Bash script files must be executable  
-You are not allowed to use awk  
-Your Bash script must pass Shellcheck (version 0.3.3-1~ubuntu14.04.1 via apt-get) without any error  
-The first line of all your Bash scripts should be exactly #!/usr/bin/env bash  
-The second line of all your Bash scripts should be a comment explaining what is the script doing  


___


Regular expressions - basics  
Regular expressions - advanced  
Your best friend for this project is http://rubular.com/  
Understand a famous developer joke: “Use a regular expression against a problem: now you have 2 problems”  
Learn by doing with https://www.regexone.com/  
For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.  

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in beetween the //:  





Regex is an expression used regularly.  

We got repetition tokens, anchor tokens, character tokens, shortcut character tokens, the dot,   

Greedy tokens match as many repeats as possible. Lazy tokens match as few repeats as possible.  

Possessive quantifiers hold what was matched and forget the backtrack position.  

Greedy and backtracks: \*, +, ?, {m, n}  
Lazy and backtracks: \*?, +?, ??, {m,n}?  
Possessive and no backtrack: \*+, ++, ?+, {m,n}+  

Word boundaries! Alternations! Groups!  

Tips for regex:  
 Do not try to do everything in one uber-regex.  
 Use whitespace and comments  
 Use a regex tool  
 Regex are not parsers  


Why is regex useful?  
Extract info from text in code, files, spreadsheets, documents. Everything is a character.  
We write patterns to match a specific sequence (string). ACII can matcl all the english language and symbols but unicode can match all international text.  

\d is any digit from 0-9.  

. is the wildcard. to match a period you need \. cause yea.  

Include [specific characters] anything inside there will try and match.  

Exclude characters with [^unwanted].  

Character ranges: [0-6] matches from 0 to 6 and [^b-p] will exclude all b to p letters.  

\w is equal to [A-Za-z0-9\_].  

Repetition with {}. a{1, 3} will match the a character 1, 2 or 3 times. [xyz]{5} is 5 characters of xyz. .{2, 6} is any characters, 2 to 6.  

Kleene Star is 0 or more. Kleene Plus is 1 or more. \d\* means any number of digits but \d+ means at least 1 digit. a+ means one or more a's. [abc]+ means one or more abc character.  

\*. means zero or more of any character.  

Optional characters is ?. It will match zero or 1 of the preceding character or group.  
ab?c will match abc or ac. The b is optional. \? will give you a question mark.  

Whitespace is \_, \t, \n, and \r for windows. A \s will match any white space.  

^ is the start and $ is the end.  

Use () to group characters for furthur processing. You can nest groups for multiple capture groups.   

We can have conditional expressions like (cat | dog). Use piping or logical OR.  

TLDR: \d is digits, \w is all alphanums, \D is any not digits, \S is any not whitespace, \W is any nonalphanum so basically punctuation. \b is boundary.  
  
