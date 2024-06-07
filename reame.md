python3 -m venv ./venv
source ./venv/bin/activate // deactivate
pip3 install -U pip
pip3 install 'rasa[spacy]'
python3 -m spacy download pt_core_news_md
wget -c https://raw.githubusercontent.com/RasaHQ/rasa/main/.gitignore
pip install --upgrade pip