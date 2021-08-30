---
layout: post
title:  "Placements Management Web App"
date:   2021-08-17 19:14:00 +0100
categories: projects
cover_image: "/assets/images/pmwa/pmwa-cover.png"
---
The Informatics department at the University of Leicester uses a "paper-based" system for managing placements. This
project replaced this with a custom web application, designed to support the needs of all the different groups of people
involved with managing placements.

<a class="btn btn-primary" href="https://github.com/HaydenPWoods/placements-management-web-app">Visit GitHub Repo 🔗</a>

<div id="pmwa-carousel" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="4" aria-label="Slide 5"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="5" aria-label="Slide 6"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="6" aria-label="Slide 7"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="7" aria-label="Slide 8"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="8" aria-label="Slide 9"></button>
    <button type="button" data-bs-target="#pmwa-carousel" data-bs-slide-to="9" aria-label="Slide 10"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/images/pmwa/pmwa-login-and-registration.png" class="d-block w-100 border-radius-15" alt="Registration form">
      <div class="carousel-caption d-none d-md-block">
        <h5>Registration Form</h5>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-placements-list.png" class="d-block w-100 border-radius-15" alt="Placements list">
      <div class="carousel-caption d-none d-md-block">
        <h5>Placements List</h5>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-placement.png" class="d-block w-100 border-radius-15" alt="Individual placement page">
      <div class="carousel-caption d-none d-md-block">
        <h5>Individual Placement Page</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-provider.png" class="d-block w-100 border-radius-15" alt="Individual provider page">
      <div class="carousel-caption d-none d-md-block">
        <h5>Individual Provider Page</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-tutor-visits-suggested.png" class="d-block w-100 border-radius-15" alt="Tutor's suggested visits">
      <div class="carousel-caption d-none d-sm-block">
        <h5>Tutor's Suggested Visits</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-message-chain.png" class="d-block w-100 border-radius-15" alt="Messaging">
      <div class="carousel-caption d-none d-md-block">
        <h5>Messaging</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-received-email.png" class="d-block w-100 border-radius-15" alt="Email notifications">
      <div class="carousel-caption d-none d-md-block">
        <h5>Email Notifications</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-send-email.png" class="d-block w-100 border-radius-15" alt="Send group email">
      <div class="carousel-caption d-none d-md-block">
        <h5>Send Group Email</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-log.png" class="d-block w-100 border-radius-15" alt="Activity log">
      <div class="carousel-caption d-none d-md-block">
        <h5>Activity Log</h5>
      </div>
    </div>
  <div class="carousel-item">
      <img src="/assets/images/pmwa/pmwa-stats-and-exports.png" class="d-block w-100 border-radius-15" alt="Stats and exports">
      <div class="carousel-caption d-none d-md-block">
        <h5>Stats & Exports</h5>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#pmwa-carousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#pmwa-carousel" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<br/>

The Placements Management Web App is a Spring (Java) application designed for my final year project at the University of
Leicester. Fully accessible through the web interface, it is designed to meet the needs of many different user groups:

* Students would use the application to find (and apply for) placements, submit placements they have found outside the
  system for approval, and check-in using the system whilst the placement is ongoing.
* Tutors would manage placement matters related to their tutees, whilst they are applying for and out on placement.
* Members of placement providers would have the ability to list their placements on the system, and make them open for
  applications by students. Applications can be personally approved and managed.
* Administrators would oversee the whole system, and have reasonable control over activities and day-to-day operations.
* Graduates would be able to login to the application, and check the state of their account as a former student - seeing
  information related to placements they were on, for example.

Given the needs of all these users, and the inherent requirements of the placements processes, a strong set of features 
were developed, which included:

* Login and Registration
* User Management
* Creating and Managing "Authorisation Requests", Providers, and Placements
* Applying for Placements
* Document / File Uploads
* Scheduling Placement Visits
* Searching Placements and Authorisation Requests
* Messaging
* Email Notifications (and Web Notifications for messages)
* Activity Logging
* Statistics and Export Creation
* Graduate Records

Data is stored in a MySQL database. Various APIs, services, and libraries are utilised to achieve the full feature set. This
includes:

* Google Maps API - for geocoding addresses of providers and showing these on maps, and for working out the distance
  between placements when generating the tutor's suggested visits list (using the Distance Matrix API.)
* Firebase Cloud Messaging - for near instant receiving of messages sent through the application, and for sending web
  notifications to the user when a new message is received while away from the application, using a registered service
  worker.
* Bootstrap 4 - for a fully responsive design. Where appropriate, a two-column layout is used on desktop, collapsing
  down to one column for smaller screen widths.
* jQuery - for dynamic page content. Used for sending AJAX calls to the server to allow for immediate field
  validation (for example, when checking if a username or email has been taken by another user of the application). Also
  used for generating page elements without requiring a reload (for example, when a user selects files for upload,
  generating form fields to add a description for each of these files.)
