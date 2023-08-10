Email Validation via Regex
Regular Expressions (or regex for short) are tools used in computer programming in order to manipulate expression searching by using patterns in the text.

Summary
The regex for email validation (^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$) is a common regex used in order to validate an expression as an email address. In this project I will explain the different components of regex and how they work to validate what is and is not an email.

Table of Contents
Anchors
Quantifiers
OR Operator
Character Classes
Flags
Grouping and Capturing
Bracket Expressions
Greedy and Lazy Match
Boundaries
Back-references
Look-ahead and Look-behind
Regex Components
Anchors
"^" and "$" are used to mark the beginning "^" and end "$" of a regex. This ensures that we can correctly check the entirety of the pattern instead of only partial sections of it. In the regex above you can see that it starts and ends with those characters in this format /^...$/
Quantifiers
"+" is a quantifier that tells us that the preceding character must appear at least once (or more). for example in the regex above [a-z0-9_\.-]+ means the quantifer will check that those specified characters will show up one or more times.
OR Operator
the OR operator is not used in this regex
Character Classes
\d in this regex matches any digits, this means it will account for characters equivalent to "[0-9]". in this regex its used in this chunk ([\da-z\.-]+)
Flags
This regex doesn't explicitly use flags however they could be used for case sensitive matching such as 'i'.
Grouping and Capturing
parantheses '()' are used to group sections of the regex together. In this case it can be used to extract seperate parts of an email. It's used above 3 different times in ([a-z0-9_\.-]+) ,([\da-z\.-]+) , and ([a-z\.]{2,6}) 
Bracket Expressions
'[...]' bracket expressions for character class defining. It matches a given a given character the class. An example in the code is [a-z0-9_\.-].
Greedy and Lazy Match
this regex specifically uses greedy matching. This means that it will match the longest possible string.
Boundaries
bondaries are not used in this regex.
Back-references
back-references are not used in this regex.
Look-ahead and Look-behind
look-ahead and look-behind is not used in this regex.
Author
Hi im John! im a motivated Student striving for excellence in the field of web development, I am currently in the process of obtaining my certification in Full Stack Web Development.
Throughout my learning journey, I have acquired an extensive knowledge base in technologies predominantly focusing on the MERN stack - MongoDB, Express.js, React.js, and Node.js.
However, my technical expertise is not limited to these areas; I have a profound understanding of additional tools and languages such as Bootstrap, MySQL, NoSQL, and Progressive Web Applications (PWAs).
Furthermore, I am also familiar with programming languages such as Java and C++, and I am continually expanding my knowledge and skills to keep up with current trends and technologies.

When I'm not busy coding, I have a passion for all outdoor activities. I believe in maintaining a balanced lifestyle and find it important to spend a few hours a day outside, be it through hiking, fishing, swimming, etc. I am fortunate to have my Golden Retriever, Rosie, as my constant companion on these adventures.
As much as I may love the outdoors, I can always count on the fact that she will be that much more excited than I am to take a walk, or head down to the creek.