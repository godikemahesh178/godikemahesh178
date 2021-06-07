


def lcount():
  #ask user to input starting year of leaf year list
    start=int(input("enter starting year>"))
  #ask user to input ending year of leaf year
    end=int(input("enter ending year>"))
    print("here is your leaf year list 👇")
    print("*"*10)
  #we have to range start to end
    for x in range(start,end):
  #set (x℅4==0) for 4 table from 0
        if (x%4==0):
            print(">",x)
  #if user enter start>end it will print this
    if start == end or start > end:
        print("There are no leaf years between",start,"&",end)
   
    print("thank you")
    print("*"*10)
  #while loop for repeat user input
    while"True":
        lcount()
#calling function
lcount()        
