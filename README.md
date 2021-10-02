# test
#Rectangle_module
import circle
import rectangle
choice = 0
ch = "y"
while (ch=="y")
  print("MENU")
  print("1.Area of the circle")
  print("2.Circumferance of a circle")
  print("3.Area of a rectangle")
  print("4.Perimeter of a rectangle")
  print("5.Quit")
  choice= int(input("Enter your choice:"))
  if (choice==1):
    radius=int(input("Enter radius of the circle:"))
    print("The area is",circle.area(radius))
  elif(choice==2):
    radius=int(input("Enter radius of the circle:"))
    print("The circumferance is",circle.circumference(radius))
  elif(choice==3):
    width=int(input("Enter width of the rectangle:"))
    length=int(input("Enter length of the rectangle:"))
    print("The area is",rectangle.area(width,length))
  elif(choice==4):
    width=int(input("Enter width of the rectangle:"))
    length=int(input("Enter length of the rectangle:"))
    print("The perimeter is",rectangle.perimeter(width,length))
  elif(choice==5):
    print("Exiting the program...")
  else:
    print("Error")
  
  
  
    
  
