# redhatnotes

cat file1 file2 file3 > combined
echo "new line" >> combined  
find /etc/su*
find /etc/su* >output 2>errors
find /etc/su* >output 2>/dev/null

ls -l /usr/bin | less

ls  | wc -l
ls  | wc -l > how-many

ls -l | mail -s subject student
mail
tty
ls -l | tee /dev/pst/0 | mail -s subject student



