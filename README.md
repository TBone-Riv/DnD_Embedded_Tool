# Application DnD Embedded Tool

A python web application combining different tools to facilitate playing virtual tabletop role-play games
(in particular Dungeons and Dragons v5) on a unique screen.

## Button reddy, press to roll.

This site embed [Roll20](https://www.roll20.net) and any charter sheet from
[D&D Beyond](https://www.dndbeyond.com) to make them accessible
from one screen. The web browser extension
[Beyond 20](https://github.com/kakaroto/Beyond20) by [Youness Alaoui](https://github.com/kakaroto)
is used to send rolls directly to the VTT.


## An academic project.
This repository one of the deliverable for the 13th project from the
Openclassrooms’s paths
 [“Développeur d'application - Python”](https://openclassrooms.com/fr/paths/68/projects/162/assignment)
.

The project, which is the final project of this parkour, is limited to 120h,
so some functionality will stay as "won't have" due to limited time.

## Setup.
This project uses a django framework.

After installing the requirements using pip install -r requirements.txt or by
author means, you can use the manage.py migrate then the manage.py
sample command before the runserver command to set up the website. 

If you wish to test the code you can do it using manage.py test followed by
the name of the app you want to test. The functional_tests contains the
functional test and only works on local wive an Edge web browser.
