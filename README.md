# Fast-API-Basic-project
Fast API Basic project

# Procedure to run app 

First create virtual env 
 
Conda create fastapi_env 

 

Install library 

Pip install fastapi 


Also install unicorn library 

pip install "unicorn[Standard]" 

Then go to the directory in which your python file is placed 

uvicorn main.py:app –reload 

 "main.py" is file name 

After loading this we get a port number , on which we get our interface 

http://127.0.0.1:8000 
