Egregore_1

Create a new folder
Inside the new folder, create a new folder
Download the zip file into the new folder
Extract the zip file into the folder
You should see 4 files and one folder
Create a file named “.env”
Add API keys into that file (content as follows, replace XXX and YYY with your keys)
ANTHROPIC_API_KEY=XXX
SERPAPI_API_KEY=YYY
Open a console in the parent folder
Make sure Python is installed
“python –version”
make sure it is python 3
Create the virtual environment
“python -m venv venv”
Activate the environment
“source venv/bin/activate” (Linux/Mac) or “venv\Scripts\activate” (Windows)
Install Flask (web server library)
“pip install Flask”
Install python libraries
“pip install python-dotenv langchain”
Instal NPM from https://nodejs.org/en
From the directory that extracted the zip file, start the web server
“flask run”
Open a second console and navigate to the nested ai-assistant-claude folder
Run the client code
“npm start”

Egregore_2

Simply submit a URL (of a product description) and it generates a product description.

# egregrore
