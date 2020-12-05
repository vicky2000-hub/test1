"""1.	Create a JSON of all object types and import the JSON"""

import json
json_file=open('C:\python projets\json.txt','r',encoding='utf-8')
movie= json.load(json_file)
json_file1=open('C:\python projets\json1.txt','w',encoding='utf-8')
json.dump(movie,json_file1)
json_file1.close()
json_file1=open('C:\python projets\json2.txt','w',encoding='utf-8')
json.dump(movie,json_file1,ensure_ascii=False)
json_file1.close()
text1="""{"titlr":"vicky"}"""
movie2=json.loads(text1)
print(movie2)
