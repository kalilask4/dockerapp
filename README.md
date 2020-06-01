virtualenv --python=python3.7 venv
source venv/bin/activate
pip install -r requirements.txt
sudo apt  install docker-compose
sudo docker-compose build
sudo docker-compose up