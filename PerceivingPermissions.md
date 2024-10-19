## Changing File Ownership 
Since I did not need to be the root user, I just chown'ed 
chown hacker /flag
cat /flag
pwn.college{sDxTZgn8Wz6AI01lovilXcE6cKN.dFTM2QDL3AjN0czW}

## Groups and Files
chgrp hacker /flag
 cat /flag 
pwn.college{YuUYjFrT8S4mfYiYbr8SQymQ_Po.dFzNyUDL3AjN0czW}

## Fun with Group Names
id
  chgrp grp17359 /flag
   cat /flag 
   read more about the id command at https://www.geeksforgeeks.org/id-command-in-linux-with-examples/
   pwn.college{8fBHIX2ZAvWnUAR4sZJ6x7yMtYE.dJzNyUDL3AjN0czW}

## Changing Permissions
Since I was an other user, I changed the permissions for other users to allow them to read the file 
   chmod o+r /flag
   cat /flag
   pwn.college{ILqhVP0hr6MbNCEFAM6d0S3j6km.dNzNyUDL3AjN0czW}

## Executable Files
First I gave the other users the ability to execute but when execution failed, I used the u+x arguement as I realised that I was the owner of the file
    chmod u+x /challenge/run
    /challenge/run
    pwn.college{w9XH1oGO1ILwfev4c0lkW6ADZ9C.dJTM2QDL3AjN0czW}

## Permission Tweaking Practice
   Solved all 8 rounds in first try to get the flag
   pwn.college{ARKfM2ooeXPoJyVs8LuvQJl15UD.dBTM2QDL3AjN0czW}

## Permission Setting Practice
   Solved all 8 rounds
   pwn.college{EPPEMFrunlunpH_VSrfCHmcvK9E.dNTM5QDL3AjN0czW}

## SUID Bit
   chmod u+s /challenge/getroot
   /challenge/getroot
   ~# cat /flag
   pwn.college{80095lUPT6-u2b4O-EcqCVx725C.dNTM2QDL3AjN0czW}
