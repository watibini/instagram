# INSTAGRAM

This is Photo Gallery built in python that allows users to view and share their favorite Photos.

## Author name

[David Watibini Makhanu](https://github.com)

## Project Description

This application allows users to view and share there favorite photos with the capabilites of following profiles of those individuals who interests them.

## Technologies Used

Python 3.6

Django 1.11

## Application requirements

1. Ensure you have Python3.6 installed in your computer. you can download it by running this command

`$ sudo apt-get update sudo apt-get install python3.6.`

2. Ensure you have PiP installed in your computer, you can download it by running this command:

`$ python get-pip.py`

3. set up a virtual environment using the following command;

`$ python3.6 -m venv --without-pip virtual`

4. Run the following command to install all your dependencies in your local computer;

`$ pip install -r requirements.txt`

## Project setup instruction/ installations


1. From the repository, click + in the global sidebar and select Clone this repository .

2.  Copy the clone command.

3.  From a terminal window, change to the local directory where you want to clone your repository.

or just use this

`$ git clone https://github.com/watibini/instagram.git`

4. Run this command to open the app

`$ python3.6 manage.py runserver`


## BDD

| Behavior        | Result |
| ------------- |:----:|
| user loads the page | all favorite images are displayed |
| User clicks on the profile icon | Profile details of the current user is loaded |
| User clicks on edit profile | Profile forms are displayed |
| user searches for an image category  | user is re-directed to the searched term with relevant images displayed |
| User clicks on images on the profile page | A modol pops up and the image details and the image are displayed |

## TDD

-To test the app, run this commands in the terminal;

`$ python3.6 manage.py test.py instagram`


## Live link

Use this link to see the web-page

(<https://watibini.github.io/instagram/>)

## Contact Information

Email-(watimakhanu@gmail.com)

Github user name -Watibini

## License

MIT License

Copyright (c) [2019] [David Watibini Makhanu]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
