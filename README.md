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
A logged off user can search for books and look for the details of the interested books. When the above user tries to make a purchase, the user is redirected to sign-in page.

https://user-images.githubusercontent.com/24699564/134438041-adc04a7e-5319-4fb4-bc65-a450ea61b8d1.mp4

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
