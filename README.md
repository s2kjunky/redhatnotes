# redhatnotes
*******************************************************************************************************************
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

*******************************************************************************************************************

esc key to escape the insert mode
(shift):wq
(shift):q!   but will not save edit

v for visual mode 
y yank the text to the buffer (not delete)
p paste teh text 

i for insert
h for hangback
j for jump down
k for kick up
l for leap forward

x for single character deletion

*******************************************************************************************************************
