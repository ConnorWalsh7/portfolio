---
layout: default
modal-id: 1
date: 2017-04-19
title: Sandbox Activity Manager
project: sandboxes
thumbnail: sandboxes-original.png
img: sandboxes-login.png
alt: image-alt
project-date: September 2016
---

# Summary
Sandbox Activity Manager was developed through Dalhousie's Community Outreach class that allows students to work on real software projects. This project was developed by a group of talented students over two semesters.   

My focus during this project was mostly on the website backend, developing the API, attendance tracking tool, automated reporter tool, as well as server deployment and maintenance 

This project consists of two components, a web application backend with RESTful API developed with Laravel for Sandbox managers to post content and manage users, and a hybrid Android and iOS app developed with Ionic for students to view the content and register for events.   
# Background
Nova Scotia Sandboxes are a provincial wide program to host collaborative workspaces at Nova Scotian universities and NSCC.
Each participating school has their own Sandbox run by a Sandbox manager.

Sandboxes act as a hub where students, mentors, and advisers can all work together to take innovative new ideas and bring them to life. 
Sandboxes also host various events for students and community members such as workshops, programming competitions, bootcamps, and more.

# Problem
Sandboxes are run independently from each other. Each Sandbox uses their own method of distribution for posting news and advertising events, such as school websites, email lists, flyers, or word of mouth. 

Sandbox managers also need a better way to track attendance at their events and organize data to generate reports for the government.

# Goals
The goal of the Sandbox Activity Manager was to create one platform for Sandbox managers to use to post news articles, 
create events, handle event registration, track attendance, and generate automated reports.  

Similarly for students, we created the Sandbox mobile app so students have one platform for all Sandbox content and a simple way to register for events.

# Administrator Backend
The administrator backend is built with <a href="https://laravel.com" target="_blank">Laravel</a>, a popular MVC framework using PHP.
The frontend is styled with <a href="http://materializecss.com" target="_blank">Materialize</a>, a design framework based on Google's Material Design. 

#### Dashboard
Tailored for each Sandbox manager showing their Sandboxes upcoming events, news articles, latest notes, and event statistics

<div class="row">
    <div class="col-lg-12">
        <div class="row">
            <a href="img/projects/sandboxes/sandboxes-dashboard.png" data-toggle="lightbox" data-title="Sandbox Dashboard" data-gallery="dashboard-gallery" class="col-lg-6">
                <img src="img/projects/sandboxes/sandboxes-dashboard.png" class="img-responsive">
            </a>
            <a href="img/projects/sandboxes/sandboxes-charts.png" data-toggle="lightbox" data-title="Sandbox Dashboard" data-gallery="dashboard-gallery" class="col-lg-6">
                <img src="img/projects/sandboxes/sandboxes-charts.png" class="img-responsive">
            </a>
        </div>
    </div>
</div>

#### News
Sandbox managers can post news articles to keep everyone up to date on the latest information or upcoming events

<div class="row">
    <div class="col-lg-4">
        <a href="img/projects/sandboxes/sandboxes-news-form-complete.png" data-toggle="lightbox" data-gallery="news" data-title="News Form">
            <img src="img/projects/sandboxes/sandboxes-news-form-complete.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-4">
        <a href="img/projects/sandboxes/sandboxes-news-filters.png" data-toggle="lightbox" data-gallery="news" data-title="News Filters">
            <img src="img/projects/sandboxes/sandboxes-news-filters.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-4">
        <a href="img/projects/sandboxes/sandboxes-news.png" data-toggle="lightbox" data-gallery="news" data-title="News Articles">
            <img src="img/projects/sandboxes/sandboxes-news.png" class="img-responsive">
        </a>
    </div>
</div>

#### Events
Manage events and allow students to register on their phones. Registrants are automatically added to the attendance list for each event

<div class="row">
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-event-form.png" data-toggle="lightbox" data-gallery="events" data-title="Event Form">
            <img src="img/projects/sandboxes/sandboxes-event-form.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-events.png" data-toggle="lightbox" data-gallery="events" data-title="Upcoming Events">
            <img src="img/projects/sandboxes/sandboxes-events.png" class="img-responsive">
        </a>
    </div>
</div>

#### Notes
Sandbox managers can leave notes on any users profile. Notes are private and only visible to the manager who posted them.

<div class="row">
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-profile-note.png" data-toggle="lightbox" data-gallery="notes" data-title="Notes">
            <img src="img/projects/sandboxes/sandboxes-profile-note.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-notes-table.png" data-toggle="lightbox" data-gallery="notes" data-title="Notes">
            <img src="img/projects/sandboxes/sandboxes-notes-table.png" class="img-responsive">
        </a>
    </div>
</div>

#### Attendance Tracker
Previously all attendance was done by pen and paper. 
Sandbox managers now have the ability to select an upcoming event and see all registered users.
From here they simply check their name off as they come into the event and their attendance is automatically tracked
<div class="row">
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-event-list.png" data-toggle="lightbox" data-gallery="attendance" data-title="Sandbox Attendance Tracker">
            <img src="img/projects/sandboxes/sandboxes-event-list.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-attendance-tracking.png" data-toggle="lightbox" data-gallery="attendance" data-title="Sandbox Attendance Tracker">
            <img src="img/projects/sandboxes/sandboxes-attendance-tracking.png" class="img-responsive">
        </a>
    </div>
</div>

#### Reporter Tool
The NSS Reporter Tool automatically takes the quantitative data Sandbox managers need to generate reports for the government and organizes it into a searchable, sortable, and exportable table.
Sandboxes need to record statistics such as how many users register for events vs how many attended, the school type of users, or gender.   

The NSS Reporter Tool also allows grouping of events based on different time frames such as searching an entire year, a specific semester, or year to date events.
All reports can be easily exported to an XLS document for use in Excel with the click of a button, making the reports easy to modify or send to others.

<div class="row">
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-reporter.png" data-toggle="lightbox" data-gallery="reporter" data-title="NSS Reporter Tool Event Statistics">
            <img src="img/projects/sandboxes/sandboxes-reporter.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-6">
        <a href="img/projects/sandboxes/sandboxes-reporter-user.png" data-toggle="lightbox" data-gallery="reporter" data-title="NSS Reporter Tool User Statistics">
            <img src="img/projects/sandboxes/sandboxes-reporter-user.png" class="img-responsive">
        </a>
    </div>
</div>


# App

The mobile application was developed with [Ionic](https://ionicframework.com/), 
a Framework that uses web languages to create native Android and iOS applications.

#### News

Students can view news posted by any Sandbox or filter to find news from a specific Sandbox. 
Students can share the news articles on Facebook or Twitter

<div class="row">
    <div class="col-lg-3 col-lg-offset-3">
        <a href="img/projects/sandboxes/app-news.png" data-toggle="lightbox" data-gallery="app-news" data-title="App News Feed">
            <img src="img/projects/sandboxes/app-news.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-3">
        <a href="img/projects/sandboxes/app-news-details.png" data-toggle="lightbox" data-gallery="app-news" data-title="App News Details">
            <img src="img/projects/sandboxes/app-news-details.png" class="img-responsive">
        </a>
    </div>
</div>


#### Events

Students will view events and register for events directly on the app. Students can keep track of their attended events on their profile page
<div class="row">
    <div class="col-lg-3 col-lg-offset-2">
        <a href="img/projects/sandboxes/app-event.png" data-toggle="lightbox" data-gallery="app-event" data-title="App Event Feed">
            <img src="img/projects/sandboxes/app-event.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-3">
        <a href="img/projects/sandboxes/app-event-details.png" data-toggle="lightbox" data-gallery="app-event" data-title="App Event Details">
            <img src="img/projects/sandboxes/app-event-details.png" class="img-responsive">
        </a>
    </div>
    <div class="col-lg-3">
        <a href="img/projects/sandboxes/app-event-details2.png" data-toggle="lightbox" data-gallery="app-event" data-title="App Event Details">
            <img src="img/projects/sandboxes/app-event-details2.png" class="img-responsive">
        </a>
    </div>
</div>