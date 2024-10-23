# ChangeLog
Change log for TextGenerator

## 2.0.0 - Oct 23, 2024
- update PHP version, update dependencies, improve code quality
- Add a reproducable random function "reprandom"

## 1.7.0 - June 3, 2020
- Remove recursive regex and recursive sort in template compilation step
- Add test testImbricatedFunctions()
- Fix unit tests

## 1.6.0 - February 11, 2020
- Other text functions now returns '[empty]' instead of ''

## 1.5.0 - February 11, 2020
- ProbabilityRandomFunction and RandomFunction now returns '[empty]' instead of '' if there is no valid choices as arguments.

## 1.4.0 - February 11, 2020
- ExprFunction now returns [empty] if the expression thrown an Error or an Exception.

## 1.3.0 - February 9, 2020
- Add "replace" filter

## 1.2.1 - December 10, 2018
- Fix reset sortedStatementsStack within TextGenerator::compile()

## 1.2.0 - June 4, 2018
- Update phpunit and expression-language versions

## 1.1.1 - November 11, 2017
- Replace strtolower() call to mb_strtolower() within LoopFunction 

## 1.1.0 - March 31, 2017
- Add rmna function
- Prevent filters to be called on empty values
- Prevent 'number' filter to be called on non-numeric values

## 1.0.2 - March 14, 2017
- Add u modifier to preg_replace_callback() call

## 1.0.1 - March 13, 2017
- Allow to load dependency expression-language 2.x or 3.x

## 1.0.0 - March 8, 2017
- Add coalesce function
- Handle properly UTF-8 characters
- Remove whitespaces around variable name in set function

## 0.4.0 - September 12, 2016
- Sort the function calls tree from left to right and from bottom to up
- Add 'substring' filter to FilterFunction
- Fix error when a filter doesn't exist
- Fix set function when the variable name contains another existing variable name
- Return an error in date filter is used with a wrong format

## 0.3.0 - September 05, 2016

- Add new #choose{} function
- Add new #prandom{} function
- Add new #expr{} function
- Allow variables assignment through #set{} function
- Update statements execution order to allow variables assignment
- Use the special caracter '@' for tags in every cases
- Allow text to be indented with ';;'

## 0.2.0 - June 01, 2016

- Misc typo fixes

## 0.1.0 - April 18, 2016

- Initial version
