# Shell Variables
## Printing Variable
- Process: just echo the variable FLAG
- Flag: pwn.college{I6753Oi8UGYWbGVfV4gPeFDH8mt.ddTN1QDLzUjN0czW}
## Setting Variables
- Process: set the value of variable PWN as COLLEGE
- Flag: pwn.college{Y7EiVh4BozRtYclPeWgwaG6EXcR.dlTN1QDLzUjN0czW}
## Multi-Word Variables
- Process: Set the variable PWN as "COLLEGE YEAH"
- Flag: pwn.college{8EbGQEliH3vgkytG9k0SmBsasbC.dBjN1QDLzUjN0czW}
## Exporting Variables
- Process: Set the value of COLLEGE to PWN and then export the variable PWN setting its value COLLEGE and then run /challenge/run passing the variable PWN
- Flag: pwn.college{sTrpjY177bD8k1p7agQXAdNSxje.dJjN1QDLzUjN0czW}
## Printing Exported Variables
- Process: use env command to print all the exported variable set and grep the word FLAG
- Flag: pwn.college{Q3MHcTsvmMhmDMePTfIvvtKOVyP.dhTN1QDLzUjN0czW}
## Sorting Command Output
- Process: Store the output os /challenge/run to PWN and then read it
- Flag: pwn.college{cKo1F0qROhvghL8d5tug4s-SoNs.dVzN0UDLzUjN0czW}
## Reading Input
- Process: use read command to set COLLEGE as the value of PWN
- Flag: pwn.college{o39w5WlbkRYy57f__hT_JR-Zyn_.dhzN1QDLzUjN0czW}
## Reading Files
- Process: use read command to set the value of variable PWN as output of /challenge/run
- Flag: pwn.college{YG_-xTLob8u4hEHtfflCSFncAx0.dBjM4QDLzUjN0czW}
