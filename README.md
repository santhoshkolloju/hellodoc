# hellodoc
Semantic search engine with support for pdf


<b>hello doc</b> is a sematic search built on top of python stack and huggingface transformers library.
This is not a completely automated end to end solution currently,but planning to built a full fledged application in fututre.

<h1>Steps to use this solution.</h1>
<pre>
Step1:
Install Elastic search, Mongodb , Django, djongo(python conector for mongodb)
start elastic search
start mongodb
elastic search should be running on default port 9200
mongodb will should be running on default port 27017

once installed 
cd src/server/
python manage.py makemigrations
python manage.py runmigrations
python mange.py createsuperuser
This step creates a super user for you which can be used during th login.
python manage.py runserver
http://localhost:8000/ will redirect to the login page.
Now login with credetials you created earlier.
</pre>
<pre>
Step2:
Click on the folder icon on left panel.
Create a Folder space for you to upload the documents.
Once created upload the documents there 

</pre>

https://github.com/santhoshkolloju/hellodoc/edit/master/README.md
