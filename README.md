data=[1, 6, 4, 2, 5, 7, 6, 9, 5, 3, 4, 5, 9, 10, 2, 4, 5, 3, 6];
n=len(data)
p=int(raw_input("enter the width of class interval: "));
a=max(data)
n=int(a/p)
for j in range(0,n):
	print ""
	l=p*(j+1)-1
	u=p*(j+1)
	print l,"-", u, 
	for i in data:
		if ( i in (l, u)):
			print "-",
			
		
