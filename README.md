
x=1
print(x+1)

print("welcome to rubios ")
x=input("enter cost of the product ")
d=int(x)
result=0.9*d
print("After 10% discount",result)
###############################################
# IF condition
print("namaskaram")
c=input("enter your value ")
d=int(c)
print(d+2)

if(d==20):
          print("u are dumb")
if(d==10):
 print("welcome asshole")

if(d==23):
     print("jessie pinkman")
###########################################
# FOR LOOP
for i in range(3):
   print("astala vistha baby")

for i in range(5) :
     print(9*i)

for i in range(4):
    print(10+i)

answer=10
for i in range(100):
    answer=answer+i
    print("first", i ,"numbers added gives", answer)

t=input("choose the table")
c=int(t)
for i in range(10):
    print(c,"X",i,"=",c*i)
#################################################
    # WHILE LOOP
print("hello there....welome to jessy clinic")
x=1
z=2
while(z==2):
    print("token number",x,"please comein")
    z=input("continue(0/2) ? ")
    z=int(z)
    x=x+1
print("we are closed for the day...thanks visiting jessy cinic")
#######################################################
#lists
room=("praveen","arun","geetha","seetha")
print(room)
# you want show these names in an order use loop concepts
for people in room:
    print(people)
#append method : if want modify the exiting tuple to list for use append method.Note:the type should me "list" only.
# if it is in "tuple" you can not modify if you want to modify tuple change into type as list
t=list(room)
t.append("srinu") #now srinu can be added into room
print(t)

room=("praveen","arun","geetha","seetha")
print(room)
t=room
while(t==room):
    print(t)
    break # it will stop from continuty of printing
#++++++++++++++++++++++++++++++++++++++++++++++++++++++++++====
home=("mom","dad","brother","sister")
print(len(home)) 
for i in home:
    print(i)
print(home[1]) # you want to print specific item from the group/list use this command
print(home)
x=list(home)
x.insert(2,"granny") # you want add any thing in specific place use INSERT method
for i in x:
    print(i)

t=x.count("mom")
print(t,x)

for i in range(len(home)):
    print(home[i])
    
numbers=(1,13,7,24,27,29,34,52,42,27,16,81,73,42,55,98,68)
t=list(numbers)
t.sort() # sort method will arrange items in ascending order
t.reverse() # reverse method will arrange the items in descending order
print(t)
#################### SLICING #############################################
classroom=["rajesh","suresh","ramesh","naresh","ganesh","mahesh","sarvesh",]  
for i in classroom:
    print(i)
classroom.insert(1,"python")    
classroom.append("spider")
print(classroom)
print(len(classroom))
print(classroom.count("spider"))# displays count for spider in list i.e 1 in this case
print(classroom[3:8]) #you divide the items where to where,
print(classroom[:]) # if you wont specify anything itwill show the default
################# GAMING Kaki Cheruvu ##################################
for i in range(51):
  if(i%2==0 and i%3==0): # please define combination staement first.
         print(str(i)+"= out")
  else: #make sure it should be in the same line where if defined.
   if(i%2==0):
        print(str(i)+"= kaki")
  else:
    if(i%3==0):
        print(str(i)+ "= cheruvu")
    else:
        print(str(i))
# you can define entire code with #def method and type name(range) given below
def kakicheruvu(r):
 for i in range(1,r):
  if(i%2==0 and i%3==0): # please define combination staement first.
         print(str(i)+"= out")
  else: #make sure it should be in the same line where if defined.
   if(i%2==0):
        print(str(i)+"= kaki")
   else:
    if(i%3==0):
        print(str(i)+ "= cheruvu")
    else:
        print(str(i))  

kakicheruvu(51) # you cann simply run this syntax.output will come

#############################################################################
# to import system config values
import platform
print(platform.machine())
print(platform.version())
print(platform.platform())
print(platform.uname())
print(platform.system())
print(platform.processor())
print(platform.architecture())
print(platform._node())
import psutil
print(psutil.cpu_percent())
print(psutil.virtual_memory())
print(psutil.disk_usage)
print(psutil.MACOS)
