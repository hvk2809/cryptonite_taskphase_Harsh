# Processes Jobs
## Listing Processes
- Process: In this use ps command along with -ef to check with /challenge file is running
- Flag: pwn.college{szxh7Onedo9_YwP529vWN7spBBR.dhzM4QDLzUjN0czW}
## Killing Processes
- Process: In this first find /challenge/run using the command ps -ef | grep /challenge/dont_run and then kill it
- Flag: pwn.college{Qa7hO65pHb1qsDyoCBvlHalnfC1.dJDN4QDLzUjN0czW}
## Inturupting Processes
- Process: Interreput the process using ^C
- Flag: pwn.college{8lZN3gl3wMUi_MXaZZ_SK2hDduU.dNDN4QDLzUjN0czW}
## Suspending Processes
- Process: first run /challenge/run and then suspend it using ^Z and then again run it
- Flag: pwn.college{EXB5ZYE35N4GWGyjtQVt-scWiCL.dVDN4QDLzUjN0czW}
## Resuming Processes
- Process: first suspend the process usinf ^Z and then resume it using command fg
- Flag: pwn.college{4HU7SEYHNSdd82FsackSneVHq6l.dZDN4QDLzUjN0czW}
## Backgrounding Processes
- Process: First 'run' and then suspend the process and then use command bg to run it in background and then make a copy of it
- Flag: pwn.college{wgWiVR17dlv0kiUxO5lTfIrj3kW.ddDN4QDLzUjN0czW}
## Foregrounding Processes:
- Process: First suspend the process then background the process and then foreground the process
- Flag: pwn.college{0hXcryVhAGHS8_aHTWfDvHSv_Jj.dhDN4QDLzUjN0czW}
## Starting Background Process
- Process: background the process using &
- Flag: pwn.college{4F9lvdiFUktJt6JflLhLlbJcLgv.dlDN4QDLzUjN0czW}
## Processes Exit Codes:
- Process: first run /challenge/get-code which will give error and then read the error using $? and then pass the error to /challenge/submit-code
- Flag: pwn.college{UdG8bPSOlggVsEfupGm8IrJI5Q0.dljN4UDLzUjN0czW}
