## Usage

- Create a .env file in the respective root directories of the project.

- Copy the following lines and specify appropriate values to corresponding lines.

```
PORT = 4000
NODE_ENV = DEVELOPMENT
DB_URI = mongodb+srv://<username>:<password>@mern.apqfp.mongodb.net/<collection-name>?retryWrites=true&
JWT_SECRET =
JWT_EXPIRES_TIME = 7d
COOKIE_EXPIRES_TIME = 7

CLOUDINARY_CLOUD_NAME =
CLOUDINARY_API_KEY =
CLOUDINARY_API_SECRET =

STRIPE_SECRET_KEY =
STRIPE_API_KEY =


SMTP_HOST = smtp.mailtrap.io
SMTP_PORT = 2525
SMTP_EMAIL =
SMTP_PASSWORD =
SMTP_FROM_EMAIL = noreply@shopit.com
SMTP_FROM_NAME = ShopIT
```

Install dependencies

```bash
npm install
cd frontend
npm install
```

### Run App

For running Server

```bash
npm run dev
```

For running Client

```bash
npm start
```

### Auth Routes

Admin Login

```
{
    "email": "admin01@shopit.com",
    "password": "123456"
}
```

Non-admin login

```
{
    "email": "user01@shopit.com",
    "password": "123456"
}
```
