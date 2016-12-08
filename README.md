# CIS602-Ass2 


This is the link to the my docker file

https://hub.docker.com/r/dkumar2/tb-wf/


This docker file contain two images with tag "parameterized" and "nigeria"

# Nigeria tag Image

This image will calculate the average of number of Tuberculosis cases per 100000 people in Nigeria.

# Parameterized tag Image

This image will calculate the average of number of Tuberculosis cases per 100000 people in any country, but we have to assign the country name in the list. 


## Steps to pull the Tagged Images from docker hub how to run these images

# 1. You have to pull these images using this command

``
docker pull dkumar2/tb-wf
``

Make sure both the images are pulled to your local repository, if you want to download both images one by one you can use following commands

# Pull Image with Nigeria Text
``
dokcer pull dkumar2/tb-wf:nigeria
``
# Pull Image with Parameterized Tag

``
dokcer pull dkumar2/tb-wf:parameterized country=Albania
``
# 2. Now you can run both of the images using these commands

``
docker run dkumar2/tb-wf:nigeria
``

``
docker run dkumar2/tb-wf:parameterized country=Afghanistan
``



