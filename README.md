# WordlistsWithCrunch

Overview: In this repository i'll be covering what crunch is, my experience using it, and my thoughts on the tool.

What is crunch? 
Crunch is a tool used for password generation which helps with creating custom wordlists based on user specified criteria. This can include character sets, a minimum and maximum amount character length, and specific patterns. The wordlists created are mostly used in brute force attacks, crunch can be used with other tools such as John the Ripper and Hydra. 

My experience using crunch: I used crunch in my homelab to create a custom wordlist in order to crack my own WPA2 encryption. For my wordlist I had to create 2, The first wordlist was broad and included numbers 0-9, and all letters if im not mistaken. I knew what the password was but I just wanted to see if the password would be found when I ran the crunch against the wordlist, long story short the password wasn't found. For the second wordlist I had specify only numbers (because my password had only numbers) and other crunch commands such as -t, the password was found, so I need to work on improving my wordlist generation skills.

My thoughts on crunch: I like the tool crunch, even though I ran into a roadblock with generating the wordlist on my part, I still enjoyed using this tool.

Check out my hands on that covers how I make a custom wordlist and run it against crunch when it becomes available.
