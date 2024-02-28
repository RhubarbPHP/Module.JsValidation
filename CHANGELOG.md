# Changelog

### 2.0.0

Fixed: Issue where validations were calling validationCompleted() regardless of whether it had been called already, 
which was causing contact form emails in NiJobfinder to send twice. This reverts the previous change made in V1.1.5.

### 1.1.7

Added:  Ability to clear triggers

### 1.1.6

Fixed:  Email validation now trims for IE 10/11 support

### 1.1.5

Fixed:  Fixed issue with ajax callbacks as checks causing doubling of require messages

Fixed:  Fixed issue with -is-missing and -is-required showing on validation even when not required.

### 1.1.4

Added:  Support for sources that return an array - empty array is considered as no value.

### 1.1.3

Added:  Support for requireWhen to support conditional requirements

### 1.1.2

Fixed:	Validations not set to 'required' where still be tested if they had no value

### 1.1.1

Added:  Check Has Value function

### 1.1.0

Added:  Changelog
Added:  Regex validator
