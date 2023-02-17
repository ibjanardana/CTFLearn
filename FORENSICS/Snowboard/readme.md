Category: Forensics
Difficulty: Easy


- Snowboard


Description

Find the flag in the jpeg file. Good Luck!

https://ctflearn.com/challenge/download/934


Answer : 

1. first step use tools forensics, i prefer online tools like : https://29a.ch/photo-forensics/#strings

2. open file link above with the tools and u get the exif data :

CTFlearn{CTFIsEasy!!!}
Q1RGbGVhcm57U2tpQmFuZmZ9Cg==

as we see u got 2 string first the fake flag " CTFlearn{CTFIsEasy!!!} ", and the second string base64 code

3. decode Q1RGbGVhcm57U2tpQmFuZmZ9Cg== with base64 decode tools and u got the real flag.


flag : CTFlearn{SkiBanff}