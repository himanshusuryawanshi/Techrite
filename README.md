# Techrite
Techrite is blog posting website built using Django that helps user to post, change and delete their post. It has a authentication for user login and logout.

***

## How to run on a Local Machine

1. Clone github repository to your Machine

```
git clone https://github.com/himanshusuryawanshi/Techrite.git
```

2. Create Virtual Environment

    * If you don't have virtualenv installed on local machine
    ```
    pip install virtualenv
    ```

    * Create Virtual Environment
    ```
    python -m virtualenv venv
    ```
    * Activate Virtual Environment
    ```
    .\venv\Scripts\activate
    ```

3. Install all dependencies in virtual environment

```
pip install -r requirements.txt
```

4. Run the Project
```
python manage.py runserver
```