pipenv shell 

pipenv install

# Making migrations
python3 manage.py makemigrations
python3 manage.py migrate

Once the migrations are performed successfully, run the command to start the server on the localhost 
and go to the URL: http://127.0.0.1:8000/admin

<img width="1430" height="778" alt="image" src="https://github.com/user-attachments/assets/910fb6e2-8445-4e68-9070-2560a4501255" />

Add user token: 
<img width="1078" height="489" alt="image" src="https://github.com/user-attachments/assets/39cc220e-268d-4d13-a244-61b4727faf31" />


once open the API request client, Insomnia and perform the following actions:

Create a POST request to the URL: http://127.0.0.1:8000/api/ratings

<img width="983" height="768" alt="image" src="https://github.com/user-attachments/assets/3fb499fe-d487-4b67-a0ca-5136644ad947" />
<img width="1027" height="770" alt="image" src="https://github.com/user-attachments/assets/6b923376-eb60-4c9d-b315-99bc0b3493b2" />
<img width="999" height="500" alt="image" src="https://github.com/user-attachments/assets/19f63505-b8ec-4d6f-be58-5d9095d69ee3" />
<img width="1022" height="450" alt="image" src="https://github.com/user-attachments/assets/99629303-5774-4eae-9c28-de45802bcf7f" />
<img width="1022" height="411" alt="image" src="https://github.com/user-attachments/assets/6cca1903-f442-42e9-9800-cb0b9c2690c6" />
<img width="1162" height="485" alt="image" src="https://github.com/user-attachments/assets/18e4fa3e-b311-4847-a8ab-20bca5e5ec4d" />

Switch the screen and go back to the webpage on your browser with the URL: 
http://127.0.0.1:8000/api/ratings
