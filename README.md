# firstTypescriptCode

## Overview
This TypeScript project provides a way to manage and filter a list of persons, which includes both users and admins. It defines TypeScript interfaces for `User` and `Admin` types and implements a function to filter persons based on given criteria. The project also includes a utility function to log details of filtered persons.

## Features
- Defines `User` and `Admin` interfaces with distinct properties.
- Uses a `Person` type that can be either a `User` or an `Admin`.
- Stores a list of persons in an array.
- Implements a `filterPersons` function to filter persons based on given criteria.
- Provides a `logPerson` function to print person details in a readable format.

## Example Output in Code
The script filters and logs users and admins of age 23. 

Expected output:

Users of age 23:  
 &nbsp;- Kate Müller, 23, Astronaut  
 &nbsp;- Wilson, 23, Ball

Admins of age 23:  
 &nbsp;- Agent Smith, 23, Anti-virus engineer