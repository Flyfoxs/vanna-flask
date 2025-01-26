sudo apt-get update
sudo apt-get install unzip

wget https://codeload.github.com/Flyfoxs/vanna-flask/zip/refs/heads/main -O vanna.zip
unzip vanna.zip
cd /workspace/vanna-flask-main
python app.py

k port-forward chatubix-api-69767cf5c4-vpttw  5000:5001 -n data-tooling