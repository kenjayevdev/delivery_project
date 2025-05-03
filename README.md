# Blog Site

🛠The following technologies were used in this project: Python, PostgreSQL (Libraries: FastAPI, pydantic, uvicorn, sqlalchemy, werkzeug, datetime)

🔹What's on the site:
Actions that can be performed with information:
- Add order (add)
- Edit order (Edit)
- Delete order (delete)
- Add product (add)
- Edit product (Edit)
- Delete product (delete)

Actions that can be performed with a user:
- Register user (SignUp)
- Log in user (LogIn)
- User can get API Key (Token)
- User can see all orders (Get User All Order)

Admin rights:
- Add product (Create Product)
- Edit product (Update Product)
- Delete product (Delete Product)
- Everything that can be done with a Product can be done on an order

## Setup

- run `git clone https://github.com/kenjayevdev/delivery_project.git` copy repositories
- run `cd delivery_project` accessing repositories
- run `python -m venv env` to create virtual environment
- run `env\Scripts\activate` to activate the env
- run `pip install -r requirements.txt` to install all required packages
- run `uvicorn main:app --reload`
