cat /etc/passwd | less | grep  --invert-match "^#" | sed -n "n;p" | cut -d : -f 1 | rev  | sed -n '$FT_LINE1,$FT_LINE2 p' | xargs 
