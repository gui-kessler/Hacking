___ 
### FFUF

___ 
### WFUZZ
#### Instalacao
- `sudo apt install wfuzz`
#### Diretorios
- `wfuzz -c -w wordlist.txt -u http://exemplo.com/FUZZ --hc 404`
#### Subdominios
- Virtual host: `wfuzz -c -w wordlist.txt -u https://<IP_DO_SERVIDOR> -H "Host: FUZZ.dominio.com" --hc 404 --hw 18`