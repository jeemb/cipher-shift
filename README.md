# _Cipher Shift Module App_

#### Drupal Custom Module Project 5.27.2017

#### By Jennifer Beem

## Description

This drupal-based project encrypts a phrase using the shift cipher method!

### Application Specifications

|Behavior|Input|Output|
|--------|-----|------|
|App changes letter value by "shift" value number | 1, right, "a"|"b"|
|Counting restarts at the end of the alphabet|2, right, "z"|"b"|
|No punctuation or space changes|"try this"|"usz uijt"|
|App only accepts positive integers for shift number|"-2"|error|
|App only accepts "left" or "right" for direction input|"middle"|error|
|App only accepts spaces and punctuations and letters|"~~~~heyyyyy"|error|


## Setup/Installation Requirements

* Clone this repository
* Navigate into repository
* Start MAMP server root in project root folder
* Import database from `db_backup` folder into MySQL servers
* Navigate to `localhost:8888` to visit app!

## Known Bugs

None known.

## Support and contact details

Feel free to contact me at: jenniferbeem@gmail.com if any questions come up!

## Technologies Used

* PHP/Drupal

### License

Copyright (c) 2017 Jennifer Beem
This software is licensed under the MIT license.
