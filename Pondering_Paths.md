# Pondering Paths
## The Root
- Process: to open a directory write its path example /cryptonite_taskphase_Harsh/filename
- Flag: pwn.college{AkVkYMYPH-ckL8eWoe26wnMVRk6.dhzN5QDLzUjN0czW}
## Program and Absolute Paths
- Process: to open a directory write its path example cryptonite_taskphase_Harsh/filename
- Flag: pwn.college{Y1bzOx4RWnLoCQzikzXth1K1V-z.dVDN1QDLzUjN0czW}
## Position thy self
- Process: use cd(change directory) which changes the current directory
- Flag: pwn.college{Isnl6zkM0JhyBZcQhBUvUzgjnpv.dZDN1QDLzUjN0czW}
## Position elsewhere
- Process: use cd(change directory) which changes the current directory
- Flag: pwn.college{4j9iW_brtTBXasppjbUhc_wycNc.ddDN1QDLzUjN0czW}
## Position yet Elsewhere
- Process: enter /challenge/run it will give you error and the actuat path then use that path to access flag
- Flag: pwn.college{cQQI_Fk_0qupwL-5X3GdL7wnri-.dhDN1QDLzUjN0czW}
## Implicit Relative Paths, from /
- Process: go to / directory and execute /challenge/run
- Flag: pwn.college{QDr7UaYGHjBePh6d2BtiyIzKgih.dlDN1QDLzUjN0czW}
## Explicit Relative Paths, from/
- Process: Go to / directory anf from there use that directory itself to go to /challenge/run
- Flag: pwn.college{0rDQZmFaUN4rSabBH06G4crZh9Y.dBTN1QDLzUjN0czW}
## Implicit Relative Paths
- Process: Use . to execute /challenge/run from the current directory
- Flag: pwn.college{cHS0cr3l1B-wGMXuKNIIDeLhhCi.dFTN1QDLzUjN0czW}
## Home Sweet Home
- Process: Use ~ this to access the path of current directory and pass an argument like "~/x" to /challenge/run
- Flag: pwn.college{wcjHC9fQjavNd_OO8LpR39TGzhe.dNzM4QDLzUjN0czW}
