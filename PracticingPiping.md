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
