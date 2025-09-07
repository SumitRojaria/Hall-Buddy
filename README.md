# Hall-Buddy
How to run the software locally?

Make sure you have python and pip installed in your system.
Clone the repository-

git clone https://github.com/mridul-g/HallBuddy
Run following commands to start the backend server-

cd HallBuddy_Website
pip install -r requirements.txt
python manage.py collectstatic
Use following commands to run the server locally :

python manage.py makemigrations
python manage.py migrate
python manage.py runserver
Go on the localhost web address :http://127.0.0.1:8000/ which must have been printed on the terminal.
