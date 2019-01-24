# Writing Viruses For Fun Not Profit

Took the commuity pledge 

What is a virus? 
    * infection mechanism 
    * payload
    * trigger

How are viruses detected
    * spread detection
    * analysis detetion 
    * stealing resources

Escaping detection
    * detection system, look for patterns
    * adapt evolve
    * obsfuscate
    * encrypt
    * act benign
    * lay dormant
    * take it slow

let's write a virus

presenter is doing it in php

## step1

opens all files with .php
adds "<?php //FILE INFECTED ?>" 

quiet output when the virus runs
quiet when the user runs infected files as well 

## step2

## step3

scamble the main text on the file system 

## step4

don't infect more than once to keep entropy and reduce errors/file sizes
check if the file is already infected 

## example of a vulerable server 

gallery image webpage 

overwrote the jpeg headers with their php script, uploaded the image to a gallery and was able to infect as per the php script earlier 

uploaded a script that overwrite index page of the website to a 301 redirect, successfully taking over the whole domain pointing it to where ever they please

## payload ideas

DDoS 
taking over domains
json with different flags to do whatever you want based on a flag you send

## why? 

Think different, think security 


