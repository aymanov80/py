def pgdc(N1,N2):
   
    while N1>N2 :
        N1-=N2
        print('le pgdc est:',N1)
    
    while N2>N1 :
        N2-=N1
        print('le pgdc est:',N2)

N1=int(input('enter N1:'))
N2=int(input('enter N2:'))   
print(pgdc(N1,N2))
