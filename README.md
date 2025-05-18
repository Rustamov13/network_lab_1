# network_lab_1

![alt text](https://raw.githubusercontent.com/Rustamov13/network_lab_1/main/lab1.png)  

## TCP ESTABLISHED Connections Count

This repository shows how to count the number of **ESTABLISHED** TCP connections on your system using a single command.

## Example

The screenshot below runs the command on Windows and shows the result (`33`):

![ESTABLISHED Count](https://raw.githubusercontent.com/Rustamov13/network_lab_1/main/lab1.png)

```text
C:\Users\New_User> netstat -n | find /c "ESTABLISHED"
33



