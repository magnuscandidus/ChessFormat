# ChessFormat
# cook your dish here
t=int(input())
while t:
    a,b=map(int,input().split())
    if((a+b)<3):
        print("1")
    elif(3<=(a+b)<=10):
        print("2")
    elif(11<=(a+b)<=60):
        print("3")
    else:
        print("4")
    t-=1
