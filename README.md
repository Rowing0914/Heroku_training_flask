## Introduction
This is a demo project for playing with Heroku!
For simplicity, I am using quite simple Flask app, so if you would like to modify the code, it's totally fine! I mean, I would like to encourage to it.
But before, that I would recommend you to try following this project firstly!
Tnen convert it into your style later!

## Prerequiresites
Since I would like you to enjoy your life with Heroku and showing your achievement ASAP, I have skipped the explanaiton on the code, especially flask part.
So if it's needed, please familiarise yourself with Flask.

Flask Official Doc
http://flask.pocoo.org/docs/1.0/quickstart/


## Python Version
3.6.* or 2.7.*

## Agenda
1. What is Heroku?
2. Registration(Sign up)
3. Installation of CLI tool
4. Deployment

## 1. What is Heroku?
Heroku is a cloud platform that lets companies build, deliver, monitor and scale apps — we're the fastest way to go from idea to URL, bypassing all those infrastructure headaches.

## 2. Registration(Sign up)
Check this link and fill the blank.
https://signup.heroku.com/

## 3. Installation of CLI tool
Using the cli tool, we have an access to Heroku service from our terminal/CMD.
Link: https://devcenter.heroku.com/articles/heroku-cli
So pick one according to your machine.

## 4. Deployment
In this section, I will put some comment on between the line of the bash command,
so check them a bit carefully!

```bash
# first you need to login!
$ heroku login
# <outcome>
# Email: ??
# Password: ??
# Logged in as : your-user-name

# get this repo
$ git clone https://github.com/Rowing0914/Heroku_training_flask.git
# move to the directory
$ cd Heroku_training_flask
# test on the local machine!
$ python app.py
# Be sure that this works properly!
```

By now you should see the images below by hitting your localhost:5000
![im1](https://github.com/Rowing0914/Heroku_training_flask/blob/master/images/im1.png)

then, let's move on to deploy it!

```bash
# this will assign the domain_name to your app
$ heroku create
```
![im3](https://github.com/Rowing0914/Heroku_training_flask/blob/master/images/im3.png)

```bash
# deploy!!
$ git push heroku master
```

![im4](https://github.com/Rowing0914/Heroku_training_flask/blob/master/images/im4.png)

```bash
$ heroku open
```

DONE!

![im2](https://github.com/Rowing0914/Heroku_training_flask/blob/master/images/im2.png)

Thank you!