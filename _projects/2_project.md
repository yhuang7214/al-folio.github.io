---
layout: page
title: Event Finder App & Website
date: 2023-05-01
description: a full-stack project for searching daily events
img: assets/img/2/2-cover.png
# importance: 20
# category: work
giscus_comments: false
---

This full-stack project includes a **responsive web application** and an **Android app** for searching events using the _Ticketmaster API_.
The system includes features for searching, favoriting, and sharing events. It also integrates several APIs (Spotify, Google Maps, IPInfo) to enhance user experience.

---

**Technologies Used**

- [for *app*] Development Environment: Android Studio with Java.
- [for *website*] Frontend: Angular (with Bootstrap for responsive design).

- Backend: Node.js with Express framework.
- APIs: Ticketmaster, Spotify, Google Maps Geocoding, IPInfo...
- Cloud Deployment: Google Cloud Platform.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2/2-overview.png" title="system design overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    System Design Overview
</div>


**Implemented Features**

- Search Functionality
  - Dynamic search form with auto-detection of user location using _IPInfo_.
  - Show autocomplete options when typing.
  - Results displayed in a responsive tabular format with details like date, time, venue, and category.

- Event Details
  - Social sharing function.
  - Integrated _Spotify_ API to display artist popularity, followers, and top albums.
  - _Google Maps_ for venue visualization.

- Favorites Management
  - Ability to favorite/unfavorite events with real-time local storage updates.
  - Favorites list with trash functionality for removal.

- UI/UX
  - Responsive design for both web and mobile

- Error Handling
  - Robust handling of empty fields, API failures, and network issues with user-friendly messages.

- Cloud Deployment

Here's the demo for Android version.

<video width="780" height="400" controls>
    <source src="../../assets/img/2/2-demo_android.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Here's another demo for website version.

<video width="780" height="400" controls>
    <source src="../../assets/img/2/2-demo_website.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Backup for this two demo is on YouTube: [Android](https://youtu.be/Uyf8JRqRKHE) & [Website](https://youtu.be/qZaN8LAoHZM)
