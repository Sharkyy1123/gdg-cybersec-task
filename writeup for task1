# gdg-cybersec-task


#this is the write up for the first task assigned 

at first i checked whether the sha256 key matched with the file 
<img width="1122" height="63" alt="image" src="https://github.com/user-attachments/assets/cedf62a9-4ab1-4f8c-b181-86702a68cabd" />

then i was looking into what type of file this is, turns out it is 
<img width="1477" height="77" alt="image" src="https://github.com/user-attachments/assets/3ca42dac-9af9-4c52-9f96-c4cecc7ac7df" />


i then tried to view the readable contents of the file using a simple 'cat' command then started scrolling, thats when i noticed a weird function called
"def_nothing_important" in the file 


i used gdb then tried to disassemble the function and boom i got some thing 
<img width="1176" height="843" alt="image" src="https://github.com/user-attachments/assets/70d63977-ebf0-40a0-8227-bebd4873a5cc" />


using the hex values and ordering them in the right way we get the follwoing hex values (62 61 62 7e 55 34 40 5a 36 7d 75 69 35 34 71 60 61 5a 69 6a 69 78)

now if we look at the same image we can see an XOR (0x5) written 

bingo! i then put the value in cyberchef and used xor to it using the key 0x5 and got the flag ( gdg{P1E_3xpl01ted_lol} ) 

<img width="1847" height="906" alt="image" src="https://github.com/user-attachments/assets/14d43356-9025-488b-86c3-9e96bcd0579e" />

