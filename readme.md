# Natours Application

Built using modern technologies: node.js, express, mongoDB, mongoose

You should have mongoDB local db installed, create a database named natours

Also you should create a config.env file with the following properties

NODE_ENV=production|development
PORT=PORT, default is 3000
DATABASE_LOCAL=mongodb://localhost:port/natours

JWT_SECRET=secret
JWT_EXPIRES_IN=quantity of days like 90d
JWT_COOKIE_EXPIRES_IN=quantity of days like 90

EMAIL_FROM=email from which sengrid should send notifications

SENDGRID_USERNAME=sendgrid username
SENDGRID_PASSWORD=sendgrid password

EMAIL_PORT=email port
EMAIL_HOST=email host

EMAIL_USERNAME=email username
EMAIL_PASSWORD=email password

STRIPE_SECRET_KEY=stripe secret key
STRIPE_WEBHOOK_SECRET=stripe webhook secret
