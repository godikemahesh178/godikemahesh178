


def lcount():
  
    start=int(input("enter starting year>"))
  
    end=int(input("enter ending year>"))
    print("here is your leaf year list 👇")
    print("*"*10)
  
    for x in range(start,end):
  
        if (x%4==0):
            print(">",x)
  
    if start == end or start > end:
        print("There are no leaf years between",start,"&",end)
   
    print("thank you")
    print("*"*10)
    while"True":
        lcount()

lcount()        
