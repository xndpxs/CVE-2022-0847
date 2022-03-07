# CVE-2022-0847
Vulnerability in the Linux kernel since 5.8 which allows overwriting data in arbitrary read-only files. This leads to privilege escalation because unprivileged processes can inject code into root processes.
<br>
To compile: `gcc poc.c -o poc`
<br>
`Usage: ./poc TARGETFILE OFFSET DATA`
<br>
Author and more info: https://dirtypipe.cm4all.com/
