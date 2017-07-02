Mobile Money Transactor
============

[![Build Status](https://travis-ci.org/Elbertbiggs360/mobile-money-transactor.svg?branch=master)](https://travis-ci.org/Elbertbiggs360/mobile-money-transactor)
[![Coverage Status](https://coveralls.io/repos/github/Elbertbiggs360/mobile-money-transactor/badge.svg?branch=master)](https://coveralls.io/github/Elbertbiggs360/mobile-money-transactor?branch=master)
[![Code Health](https://landscape.io/github/Elbertbiggs360/mobile-money-transactor/master/landscape.svg?style=flat)](https://landscape.io/github/Elbertbiggs360/mobile-money-transactor/master)
[![Code Climate](https://codeclimate.com/github/Elbertbiggs360/mobile-money-transactor/badges/gpa.svg)](https://codeclimate.com/github/Elbertbiggs360/mobile-money-transactor)
[![Issue Count](https://codeclimate.com/github/Elbertbiggs360/mobile-money-transactor/badges/issue_count.svg)](https://codeclimate.com/github/Elbertbiggs360/mobile-money-transactor)


This is a python application using SQLAlchemy and Flask 
to create a REST API backend to be used to compute commissions and float values
for agents of mobile money services

## Demo
You can request a demo at https://serveway.co.ug/contact/

You can also test the API demo hosted at https://mmtool.herokuapp.com in Postman
Use a request to the url with extension 
- GET `/branches` to get a list of the available mm branches
- GET `/rates` to get a list of the transaction rates

---

## Features
- Modem Dialer
- Automated USSD data collection (via modem dialer)
- Local Usage
- Cloud Sync when connectivity available
- Other awesome features yet to be implemented


## Setup
- Clone this repo to your desktop and cd into the directory created
- Run `python install -r requirements.txt` to install all the dependencies.

---

## Usage
After you clone this repo to your desktop and the dependencies are installed, you can run  `python mobile-money-transactor` to start the application. You will then be able to access it in the terminal as displayed

---

## License
>You can check out the full license [here](https://github.com/elbertbiggs360/mobile-money-transactor/blob/master/LICENSE)

![MIT License](https://github.com/elbertbiggs360/mobile-money-transactor/blob/master/mit.png)
This project is licensed under the terms of the **MIT** license.