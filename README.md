mkdir Fastapi-demo
cd Fastapi-demo
code .

// Open VSCODE terminal

python3 -m venv venv
source venv/bin/activate

pip install fastapi uvicorn[standard] 
pip freeze > requirements.txt

touch app.py
