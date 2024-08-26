# Palindrome Checker DApp

## Overview

This decentralized application (DApp) checks if a given string is a palindrome. A palindrome is a string that reads the same forwards and backwards.

## Features

- Converts hexadecimal data to objects and vice versa.
- Checks if a string is a palindrome.
- Tracks the number of operations and users.
- Provides endpoints for reporting and inspecting state.

## Functions

- **`hex2Object(hex)`**: Converts a hexadecimal string to a JSON object.
- **`obj2Hex(obj)`**: Converts a JSON object to a hexadecimal string.
- **`isPalindrome(str)`**: Checks if a string is a palindrome.

## Endpoints

- **`/advance`**: Handles requests to check if a string is a palindrome. Accepts input in hexadecimal format and responds with the result in hexadecimal.
- **`/inspect`**: Provides inspection data including the list of users and the total number of operations.

