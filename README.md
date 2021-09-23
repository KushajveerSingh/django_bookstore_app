# Genlib
This repository contains an implementation of an online-bookstore-system built using the [Django](https://www.djangoproject.com/) framework. I worked on the following aspects of the project
- Backend implementation
- Database creation and handling
- Frontend and backend integration

The frontend development (HTML, CSS, JavaScript) was handled by [Vipul Shinde](https://github.com/vipul-shinde) and [ManushGH](https://github.com/ManushGH).

## Table of Contents
- [Website working](#website-working)
    - [Logged off user](#logged-off-user)
- [Requirements](#requirements)
- [License](#license)

## Website working

### Logged off user
A logged off user can search for books and look for the details of the interested books. When the user tries to make a purchase, the user is redirected to the sign-in page.

https://github.com/KushajveerSingh/genlib/blob/main/videos/logged_off_user.mp4

### Sign-up process
To sign up, the user has to provide personal information and optionally, provide address and payment information. After a user has provided the required information, an email is sent to the user with a link to activate the account. Clicking the link activate's the account and redirect's the user to the homepage.

If the user has not activated the account, then the user would be treated as a logged-off user and when the user tries to sign-in, an error message, "Please activate your account" would be shown.

### Editing profile
You can do the following
- Edit personal information
- Edit address information
- Add/Remove payment cards. A maximum of three cards can be stored in the system. All the card information is stored encrypted

When you click "save changes" the information is updated in the database and an email is sent to the user w

## Requirements
The website was built using the following versions of the main libraries
- python = 3.9.7
- Django = 3.2.7

Download python using [Miniconda](https://docs.conda.io/en/latest/miniconda.html) and then install [Django](https://www.djangoproject.com/) using the following command

```
python3 -m pip install Django==3.2.7 django-cryptography==1.0
```

## License
[Apache License v2](LICENSE)