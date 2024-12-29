# First Docker file

Step 1: Create python virtual environment to isolate packages 
Go to pwd, execute commands [help](https://fastapi.tiangolo.com/virtual-environments/)


>  ` python -m venv .venv `  
>  ` source .venv/bin/activate `  
> ` python -m pip install xyz `  

Step 2: docker build -t fastapi-demo .

Step 3: docker run with hostport