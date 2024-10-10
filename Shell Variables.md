### Printing Variables 
echo $FLAG
pwn.college{wLZcsxb6i7b1A7Rw_wLpFW0S8V5.ddTN1QDL3AjN0czW}

### Setting Variables
PWN=COLLEGE
pwn.college{cwFZEizOHLbnslj4hODHwLR9I-E.dlTN1QDL3AjN0czW}

### Multi-word variables 
PWN="COLLEGE YEAH"
pwn.college{kPVyfludczJdj7QelyX6Kzzcv9v.dBjN1QDL3AjN0czW}

### Exporting Variables 
PWN=COLLEGE
COLLEGE=PWN
export PWN
sh
sh$ /challenge/run
pwn.college{Yn-ERf--Z8ih264ZLHiIbJcdUxj.dJjN1QDL3AjN0czW}


### Printing Exported Variables
env
pwn.college{oc6vcJWitV6iDXgywHpAnL8rlaK.dhTN1QDL3AjN0czW}

### Storing Command Output
PWN=$(/challenge/run)
echo $PWN
pwn.college{M_CsfyuSmHSbWMbr8DUh5zlTF31.dVzN0UDL3AjN0czW}

### Reading Input
read -p "INPUT: " PWN
INPUT: COLLEGE
pwn.college{waFSTsFaba7oZmhKrzJbCtX0UCY.dhzN1QDL3AjN0czW}

### Reading Files
read PWN < /challenge/read_me
pwn.college{ERZoby34CeREKfdLpQfrbWVSF7s.dBjM4QDL3AjN0czW}
