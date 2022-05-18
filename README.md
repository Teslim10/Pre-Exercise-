# Pre-Exercise-
My pre Exercise 
#using the request module to write a code that gets to print the HTML source code of a webpage from the internet 
import requests
x = requests. get("https://w3schools.com/python/demopage.htm")
print(x. text)
#code to plot a scatter plot graph using the matplotlib library. 
from matplotlib import pyplot as plt
x = [5,10,15,20,25]
y = [96, 83,78,60,52,30]
plt.scatter(x,y)
plt.show
#code to create a student database using the mysqlconnector
import mysql. connector
mydb = mysql. connector. connect(
   host = "localhost", 
   user = "my username", 
   password = "my password" 
) 
mycursor = mydb.cursor()
mycursor.execute("CREATE DATABASE studentdatabase")
OR
import sqlite3
conn = sqlite3. connect ("test.db")
print("opened studentdatabase successfully") 



 
