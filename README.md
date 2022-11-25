# hunger-captain-carey-frontendpart
# Hunger Captain    
This is an online food menu service of a restaurant. These days, when you visit a restaurant, you often use the QR code to load the PDF of the menu. It has no image and is not easy to select items. So we created the menu app where you can see food images with the needed information and select your items easily. During such unprecedented time and social distancing, online menu card technology is a boon!   
# Check out [API LIVE DEMO]()!!
# Tech used
* Frontend : React & Redux
* Backend : Django

# 2. Backend setting
# cd backend Python -m venv env (For Mac) source env/bin/activate (For Windows) env/Scripts\activate pip install -r requirements.txt python manage.py makemigrations python manage.py migrate python manage.py runserver
Open http://127.0.0.1:8000/   
To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
# 3. Frontend setting   
cd frontend npm install npm start
Open http://127.0.0.1:3000/
