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
Sandbox Activity Manager was developed through Dalhousie's Community Outreach class that allows students to work on real software projects. 
This project consists of two components, a web application backend and API developed with Laravel, and a hybrid Android and iOS app developed with Ionic for consuming the content

# Background
Nova Scotia Sandboxes are a provincial wide program to host collaborative workspaces at Nova Scotian universities and NSCC.
Each participating school has their own Sandbox run by a Sandbox manager.
Sandboxes act as a hub where students, mentors, and advisers can all work together to take innovative new ideas and bring them to life. 
Sandboxes also host various events for students and community members such as workshops, programming competitions, interactive demonstrations, and more.

# Problem
Sandboxes are run independently from each other. Each Sandbox uses their own method of distribution for posting news and advertising events, such as school websites, email lists, flyers, or word of mouth. Sandbox managers also need a better way to track attendance at their events and organize data to generate reports.

# Goals
The goal of the Sandbox Activity Manager was to create one platform for Sandbox managers to use to post news articles, create events, handle event registration, track attendance, and generate automated reports.  

Similarly for the students, we created the Sandbox mobile app so students have one platform for every Sandbox. A single platform for viewing all Sandbox related content insures that students will not miss out on any news or events, and they can keep up to date with other Sandboxes other than their schools.

# Details

### Administrator Backend
The administrator backend is built with [Laravel](https://laravel.com/), a popular MVC framework based around PHP.
The frontend is styled with [Materialize](http://materializecss.com/), a design framework based on Google's Material Design. 

#### Dashboard
Tailored to each Sandbox manager showing their Sandboxes upcoming events, news articles, latest notes, and event statistics

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
