---
layout: post
title:  "Radio Stream to Spotify"
date:   2021-08-16 20:51:00 +0100
categories: projects
cover_image: "/assets/images/radio-stream-to-spotify-cover.png"
---
Radio stations tend to be good at collating a playlist for a specific genre or target audience. Monitoring these radio
stations tends to create very listenable playlists.

<a class="btn btn-primary" href="https://github.com/HaydenPWoods/radio-stream-to-spotify">Visit GitHub Repo 🔗</a>

"Radio Stream to Spotify" is an application designed to monitor the metadata of many different radio streams, find the
currently playing song on Spotify, and then add it to a specific playlist created for that station.

The application has been written in Python 3, and utilises the [Tekore](https://pypi.org/project/tekore/) library for 
interfacing with the Spotify Web API. It is able to run indefinitely, and uses little resources.

I created this mainly to fulfill a personal need - I noticed that another Spotify user ([lerman01](https://open.spotify.com/user/lerman01?si=341773f6c14744f5))
had attempted a similar idea for Virgin Radio UK, and I wanted to extend it to more radio stations. I like the playlists
on Radio X and Kiss, but I don't always feel like listening to the DJs (and the adverts..!) 

I have the program running on a Raspberry Pi, monitoring a number of different UK radio stations and pushing the songs
to public Spotify playlists. Many people must find these useful - my most popular playlist by far is Radio X with 700+
followers.

<iframe src="https://open.spotify.com/embed/playlist/1hy8UACNKGHQq6nyCHXZZN" width="100%" height="450" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

Current radio stations being monitored include:

<table class="table">
<tr>
<td>Absolute Radio</td>
<td>Absolute Radio 00s</td>
<td>Absolute Radio 10s</td>
</tr>
<tr>
<td>"Begins with a C"</td>
<td>Gold</td>
<td>Greatest Hits Radio</td>
</tr>
<tr>
<td>Heart</td>
<td>Hits Radio</td>
<td>Jazz FM</td>
</tr>
<tr>
<td>Kiss</td>
<td>Kisstory</td>
<td>Kiss Fresh</td>
</tr>
<tr>
<td>Magic</td>
<td>Planet Rock</td>
<td>Radio X</td>
</tr>
<tr>
<td>Smooth Radio</td>
<td>Union JACK Dance</td>
<td>Union JACK Radio</td>
</tr>
<tr>
<td>Virgin Radio Anthems</td>
<td>Virgin Radio Chilled</td>
<td>Virgin Radio Groove</td>
</tr>
<tr>
<td>Virgin Radio UK</td>
</tr>
</table>