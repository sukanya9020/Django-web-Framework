  # Little Lemon App
Since databases are limited to local envoriment in this course, please enter your own database details, create users and tokens manually or through apis as decribed in the coursera's previous modules and then use the respective API where token authorization is required.

Following are the API URL
http://127.0.0.1:8000/restaurant/menu/       
http://127.0.0.1:8000/restaurant/menu/2/    
http://127.0.0.1:8000/restaurant/api-token-auth/ (POST METHOD)
http://127.0.0.1:8000/restaurant/booking/ 

http://127.0.0.1:8000/auth/users/   
http://127.0.0.1:8000/auth/users/me/
http://127.0.0.1:8000/auth/users/confirm/
http://127.0.0.1:8000/auth/users/resend_activation/
http://127.0.0.1:8000/auth/users/set_password/
http://127.0.0.1:8000/auth/users/reset_password/
http://127.0.0.1:8000/auth/users/reset_password_confirm/
http://127.0.0.1:8000/auth/users/set_username/
http://127.0.0.1:8000/auth/users/reset_username/
http://127.0.0.1:8000/auth/users/reset_username_confirm/

Djoser TOKEN:
http://127.0.0.1:8000/auth/token/login/

## Main Steps
1. **Create an environment:**![django8](https://github.com/johantbueno/Django-Meta-Assessment/assets/109690188/523f6198-1124-4588-b399-a0756d7c461c)
![django7](https://github.com/johantbueno/Django-Meta-Assessment/assets/109690188/a8175b1e-ce2f-47ac-8748-75aea560b6b6)
![django](https://github.com/johantbueno/Django-Meta-Assessment/assets/109690188/19a6f871-55cf-40fd-bac8-5b38c956de7a)


    **Windows:**
    ```
    python -m venv env
    ```
    **MacOS:**
    ```
    python3 -m venv env
    ```

2. **Environment activate:**

    **Windows:**
    ```
    .\env\Scripts\activate
    ```
    **MacOS:**
    ```
    source env/bin/activate
    ```

3. **Install Django:**

    **Windows:**
    ```
    pip install django
    ```
    **MacOS:**
    ```
    pip3 install django
    ```
    

    **Verify Django Version:**

    **Windows:**
    ```
