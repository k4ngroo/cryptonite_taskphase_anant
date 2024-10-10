# Practicing Piping

### Redirecting Output
followed the instructions

### Redirecting More Output
followed the instructions

### Appending the output
used >> instead of > to append file instead of overwriting

### Redirecting errors
redirected the output to myflag file and error to instructions file

### Redirecting input
Redirected output of echo to PWN file and redirected PWN file as an aruguement for /challenge/run

### Grepping Stored Results 
Grepped pwn.college in data to find the flag
Used geeksforgeeks to revise on Grep

### Grepping Live Output
Grepped /challenge/run using the pipe (|) operator

### Grepping errors
changed stderr to stdout using >& operator and grepped it using |
Used the resources provided in the dojo to do extra reading on the operator

### Duplicating piped data with tee
Took me an ungodly amount of time
Piped the data using tee to a different file
catted the file to get the secret arguement
ran the /challenge/pwn with the secret arguement to get the key pwn.college{MVXcgzIsIlL2bCV5OnLduzi7mSm.dFjM5QDL3AjN0czW}

### Writing to multiple programs
Took me an ungodly amount of time yet again
Duplicated the output to input using tee >()
pwn.college{E4YXxE2AvvOv32RRLvEG_a3Bduf.dBDO0UDL3AjN0czW}

### Split-Piping with stderr and stdout
VERY VERY DIFFICULT
I can't stress the difficulty enough 
used the command /challenge/hack > >/challenge/planet 2> >/challenge/the
pwn.college{0S61ZYy_Z3VVfpXwrZJccXZN5mY.dFDNwYDL3AjN0czW}


