# UA
Simple django app for unicode encoding and decoding of local languages.

## Installation

pip install django
pip install idna


## Approach
Simple django app for unicode encoding and decoding of local languages.

## Libraries

1. idna
2. django

## Target
To takevernacular language as input and accept and validate it.
Then after validation store it in the database.

## Implementation

Input is taken from the user (Input can contain any vernacular language)
A regular expression is defined to validate the input.
Then a  function is written to encode the inpu

## Issues during project
The encoding of email input was showing error because of "@" symbol so we had to slice and then 
encode and then concatenate the string to store in database.


Input is taken from the user (Input can contain any vernacular language)
A regular expression is defined to validate the input.
Then a  function is written to encode the inputs.Then the encoded input is stored in
the database.

At the time at displaying the details of user. The user encoded data is taken
from database and then decoded using idna and then displayed to user.
