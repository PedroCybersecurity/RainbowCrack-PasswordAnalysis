# RainbowCrack Password Analysis

## Overview
This repository contains the solutions and scripts for Lab 2.5.5 from TestOut CyberDefense Pro's English 2.0 course. The lab focuses on analyzing passwords using Rainbow Tables to ensure they meet specific requirements.

## Lab Tasks
- Determine the rainbowcrack charset that includes all the characters required for the company's password requirements.
- Create md5 and sha1 rainbow tables using rtgen.
- Sort the rainbow tables using rtsort.
- Analyze the passwords using rcrack.

## Password Requirements
- Password length: Eight or more characters
- At least one upper and one lowercase letter
- At least one special character: !, ", #, $, %, &, _, ', *, or @
- All passwords are encrypted using md5 or sha1 hash algorithms

## Instructions
1. Determine the charset by viewing the `/usr/share/rainbowcrack/charset.txt` file using the `cat` command.
2. Create md5 and sha1 rainbow tables using `rtgen`.
3. Sort the rainbow tables using `rtsort`.
4. Analyze the passwords using `rcrack`.

## Lab Report
- Time Spent: 11:39
- Score: 9/9 (100%)

## Questions
- Q1: Which charset supports the company's password requirements? (Your answer: ascii-32-95)
- Q2: What is the password for hash 202cb962ac59075b964b07152d234b70? (Your answer: lmnop)
- Q3: What is the password for hash 400238780e6c41f8f790161e6ed4df3b? (Your answer: S3cur3Dev!ce)
- Q4: What is the password for hash 89BF04763BF91C9EE2DDBE23D7B5C730BDD41FF2? (Your answer: DisneyL@nd3)
- Q5: Which of the passwords found do not meet the company's password policy? (Your answer: lmnop)

Feel free to use this repository as a reference for your portfolio on GitHub.
