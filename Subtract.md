# Subtract

## Scenario: Subtraction of two positive numbers

Given: Calculator is turned on

When: Type "positive number",
and then enter "minus" operator,
and Type "positive number",
and press "equals".

Then: I get "subtracted number" as the result.

## Scenario: Subtraction of two negative numbers

Given: Calculator is turned on

When: Type "negative number",
and then enter "minus" operator,
and Type "negative number",
and press "equals".

Then: I get "subtracted number" as the result.

## Scenario: Subtraction of fractions

Given: Calculator is turned on

When: Type " fraction number",
and then enter "minus" operator,
and enter second "fraction point",
and press "equals".

Then: Display "subtracted number" as the result.

## Scenario: Subtraction of positive and negative number

Given: Calculator is turned on

When: Type "positive number or negative number",
and then enter "subtract" operator,
and Type "negative number or
positive number", and press "equals".

Then: I get "subtracted number" as the result.

## Scenario: Subtraction of decimals

Given: Calculator is turned on

When: Enter first "decimal point number",
and then enter "minus" operator,
and enter second "decimal point",
and press "equals".

Then: Display "subtracted number" as the result.

## Scenario: Typing operator more than once

Given: Calculator is turned on

When: Type "number", and then enter "plus" operator,
and Type any "operator", and press "equal"

Then: Prefer the first operator and
display "subtracted number"
as the result.

## Scenario: Subtraction of more than 2 numbers

Given: Calculator is turned on

When: Enter first "number", and
enter "minus" operator,
and then enter second "number",
and press "equal" then again
press "minus" operator, then type
third "number", then press "equal".

Then: I get result as first number minus
third number and second number and see
the final "subtracted number" as result.

## Scenario: Subtraction of numbers where the result goes out of range

Given: Calculator is turned on

When: Type "number/large size number",
and then enter "minus" operator,
and Type "number/large size number",
and press "equals".

Then: I get the result within range.

## Scenario: 6+* as an input

Given: Calculator is turned on

When: Type "6", and then enter "plus" operator,
and enter "star" operator, and press "equals".

Then: Prefer the first operator
and wait for next input.

## Scenario: Identity operation

Given: Calculator is turned on

When: Type first "number", and then
enter "minus" operator,
and press "equals".

Then: Use "Identity element" as a
second input and add
this with first number. I get
"subtracted number" as the result.

## Scenario: Converse operation

Given: Calculator is turned on

When: Type first "number", and then
enter "minus" operator,
and then Type "second" number,
and press "equals".

Then: I get "subtracted number" as the result.
