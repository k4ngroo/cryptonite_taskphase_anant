## Becoming root with su
  su
  password: hack-the-planet
  pwn.college{46Twq1ywrrv1fsaW0Hq8bI255mL.dVTN0UDL3AjN0czW}

## Other Users with su
  su zardus
  pwn.college{UYL84jPVuSFt6rCPlqgBJKYkIrj.dZTN0UDL3AjN0czW}

## Cracking Passwords
  Used John the ripper to crack the passowrd, read more about it on the provided website
  john /challenge/shadow-leak
  john /challenge/shadow-leak --show
  su zardus
  /challenge/run
  pwn.college{8UtTxfaBGjSfAgKpqrVArbdMrHd.ddTN0UDL3AjN0czW}

## Using Sudo
  sudo /challenge/run (Not the correct answer)
  sudo cat /flag
  pwn.college{g1jmkv-UPfBxnl_A2td84p_AxNX.dhTN0UDL3AjN0czW}
