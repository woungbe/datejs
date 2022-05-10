# datejs
this is sample date for golang 


I do not want to look up the date method every time 
So, I made a function that I use often.


1.format
 types := yyyy-mm-dd , yyyy-mm-dd hh:ii:ss 
 t1 := new Date => string 
 
 Format(types, t1) string 
 

2. diff 
DiffDate(string, string) => int 
=> date - date => second 

AddDate(string, int) => time.Time 
=> date + day 

AddSecond(string, int) => time.Time 
=> date + second =>  

