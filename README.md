# flask_mega_tutorial
## Setup 
- Install python3
- Confirm `python3 --version`
- Create directory for the project `mkdir microblog && cd microblog`
- Create virtual environment `python3 -m venv venv`
- Activate (tell your system you want to use the virtual environment) `source venv/bin/activate`
- Install Flask `pip install flask`
- Confirm installation of Flask
    - `python`
    - `import flask`
    - Hit Enter (if no error is given, you're good to go)
- Create directory to host application `mkdir app`
---Do Some stuff here with creating files (refer to tutorial)---
- Install `pip install python-dotenv` to persist env variables

## Environment variables to set 
`export FLASK_APP=microblog.py`

## Run app 
`flask run`