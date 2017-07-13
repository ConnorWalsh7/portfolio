---
layout: default
modal-id: 4
date: 2017-07-11
title: Let's Schedule
project: lets-schedule
thumbnail: lets-schedule-home-scaled.png
img: lets-schedule-home.png
alt: lets-schedule-logo
---

# Summary
Let's Schedule automates the process of finding group availability by automatically looking through each group members existing calendars to highlight ideal meeting times everyone has in common.
This eliminates the need for back and forth "when is everyone free?" discussion and does not require any users to manually input availability. 

Let's Schedule is under active development and subject to change as development continues

Let's Schedule is currently compatible with Google Calendar and Microsoft based calendars (Outlook, Exchange, Office365, etc).

Please visit <a href="https://www.lets-schedule.com" target="_blank">Let's Schedule</a> to try out an early version of the application 

# Problem
Scheduling group meetings can be time consuming when trying to plan around everyone's schedules. 
The current tools available still leave much to be desired. 
They are either not suited for groups of people or they require users to manually fill out availability which leaves you waiting on others

# Solution
I created an application that automatically looks through group members calendars and finds the mutual availability.
Let's Schedule allows you to search for available meeting times over a date range (ex: Look for a 60 minute window next week between 10am and 4pm) to provide the most possibilities for ideal meeting times



# Technical Details
Let's Schedule is built with Ruby on Rails, a powerful MVC framework. The front end is styled with Bootstrap. The project is hosted on Heroku 

The application leverages the Oauth 2.0 protocol for authentication and allows users to use this application with their existing Google or Microsoft accounts

Calendar interactions are done through Google's and Microsoft's API's using the same Oauth authentication methods



