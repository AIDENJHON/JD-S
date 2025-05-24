pkg update

pkg upgrade -y

pkg install git

pkg install python -y

git clone https://github.com/AIDENJHON/JD-S.git

cd JD-S

git pull

pip install -r requirements.txt

python Main.py
