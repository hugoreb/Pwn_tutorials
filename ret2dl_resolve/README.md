First, compile the file vuln.c with the following command :
gcc vuln.c -o vuln -fno-stack-protector -no-pie
It will disable Canary and PIE

When ?

ret2dl_resolve is a 
