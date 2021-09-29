---
layout: post
title:  "Radio Stream to Spotify"
date:   2021-08-16 20:51:00 +0100
categories: projects
cover_image: "/assets/images/radio-stream-to-spotify-cover.png"
---
Radio stations tend to be good at collating a playlist for a specific genre or target audience. Monitoring these radio
stations creates very listenable playlists.

<a class="btn btn-primary" href="https://github.com/HaydenPWoods/radio-stream-to-spotify">Visit GitHub Repo 🔗</a>

"Radio Stream to Spotify" was an application designed to monitor the metadata of many different radio streams, find the
currently playing song on Spotify, and then add it to a specific playlist created for that station.

The application was written in Python 3, and utilises the [Tekore](https://pypi.org/project/tekore/) library for 
interfacing with the Spotify Web API. It is able to run indefinitely, and uses little resources.

I created this mainly to fulfill a personal need - I noticed that another Spotify user ([lerman01](https://open.spotify.com/user/lerman01?si=341773f6c14744f5))
had attempted a similar idea for Virgin Radio UK, and I wanted to extend it to more radio stations.

The program ran on a Raspberry Pi, monitoring a number of different UK radio stations and adding the songs to
respective playlists.
