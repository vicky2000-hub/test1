"""Create a JSON of all object types and import the JSON into a SQL Database"""

import pymongo

mongocon=pymongo.MongoClient("mongodb://localhost:27017")

mydb=mongocon["mydatabase"]

mycol = mydb["customers"]

mydoc={"name":"s.vignesh","department":"ECE"}

"""if you want to print your output in mongo server use this line"""
insertmy = mycol.insert_one(mydoc)

"""if you print your database output in python itself use this commend"""
x=mycol.find_one()
print(x)
