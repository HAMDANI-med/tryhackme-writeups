# Lo-Fi Challenge 

## Room Info

Platform: TryHackMe
Difficulty: Easy
Category: Web Exploitation
Focus: Local File Inclusion (LFI), Directory Traversal

## Objectives
Identify and exploit a Local File Inclusion vulnerability
Access sensitive files using path traversal
Capture the flag

## Exploitation

I began by visiting the target website: http://machine_ip/
After navigating through different pages, I noticed that the URL structure included a page parameter: http://machine_ip/?page=relax.php
![Page parameter](touver LFI.png)

