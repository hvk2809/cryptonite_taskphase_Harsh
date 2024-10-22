# Untangling Users
## Becoming Root with su
- Process: Become the root using su command and providing root password and then read flag
- Flag: pwn.college{Mnw8Gd5_PY3USi8pBbdE6kszw8r.dVTN0UDLzUjN0czW}
## Other Users with su
- Process: Become zardus user by passing it as argument to su command and then provide the password to access it and then execute /challenge/run
- Flag: pwn.college{IntZMuhvcTkQtNFDzoAmNArvsjF.dZTN0UDLzUjN0czW}
## Cracking Passwords
- Process: Use john command on /challenge/shadow-leak which is the leaked file of /etc/shadow which will run and give a password and then use that password to access zardus user to run /challenge/run
- Flag: pwn.college{M_lCDDrWl7BM3yOMXJnOcScbQjT.ddTN0UDLzUjN0czW}
## Using sudo
- Process: Use sudo command to read the flag as root as root has access to it.
- Flag: pwn.college{EFySJdq1JWW2aPQ4CRqDepj7YLl.dhTN0UDLzUjN0czW}
