---
title: Boats Animator
repository: https://github.com/charlielee/boats-animator
version: 0.11.1
layout: page
permalink: boats-animator/
redirect_from:
- boatsanimator/
- animator/

hero_cover: true
hero_img: assets/boats-animator/ba-0-11-0-screenshot-1.png
hero_text: A free open-source stop motion animation program.
hero_button_text: Download Boats Animator
hero_button_link: "#downloads"
hero_social: true
hero_social_github: https://github.com/charlielee/boats-animator
hero_social_docs: https://boatsanimator.readthedocs.io/

home_description: >
  An open-source stop motion animation program created using Electron.
  Home to an active community and over 20,000 downloads.
home_image: assets/boats-animator/ba-0-11-0-screenshot-1.png
home_call_to_action_text: Learn More
home_call_to_action_icon: fa-arrow-right
home_call_to_action_url: /boats-animator
home_technologies:
- Electron
- JavaScript
- Node.js
---
# Introduction

**Boats Animator** is a free and open-source stop motion animation program for Windows, macOS and Linux. Its intuitive interface caters to animators of all levels and offers many powerful features. The program has been open sourced under the GNU General Public License and contributions are welcome to the project's active [GitHub repository]({{ page.repository }}).

![Screenshot of Boats Animator](../assets/boats-animator/ba-0-11-0-screenshot-1.png)

# Features

## Instant Playback

![Playback](../assets/boats-animator/playback.png) Instantly preview your captured frames with Boats Animator. Unlike other programs, there is no need to wait for the frames to process.

## Onion Skinning

![Onion skinning](../assets/boats-animator/onion-skin.png) This professional feature helps keep your animations smooth by showing you a translucent version of the last image captured.

## High resolution and multi device support

![Capture options](../assets/boats-animator/capture-options.png) Boats Animator supports high resolution frame capture, including 1080p and beyond! It's also simple to switch between multiple connected devices for multi-camera shots.

## For Windows, macOS and Linux

![Cross platform](../assets/boats-animator/cross-platform.png) Boats Animator is built with [web technologies](https://www.electronjs.org/) which means it runs equally well on all major desktop operating systems.

## Open Source

![GitHub logo](../assets/boats-animator/github-logo.png) With an open-source code base, new features are always being added to Boats Animator by people **just like you**. [Your suggestions]({{ page.repository }}/issues) and contributions improve Boats Animator for everyone.

# Downloads

| Windows | macOS | Linux |
| - | - | - |
| [Boats Animator {{ page.version }} Setup.exe]({{ page.repository }}/releases/download/v{{ page.version }}/boats-animator-{{ page.version }}-win-setup.exe) | [Boats Animator {{ page.version }}.dmg]({{ page.repository }}/releases/download/v{{ page.version }}/boats-animator-{{ page.version }}-macos.dmg) | [Boats Animator {{ page.version }}.deb]({{ page.repository }}/releases/download/v{{ page.version }}/boats-animator-{{ page.version }}-linux.deb) |

### Other

<ul class="plainlist">
  <li><a href="{{ page.repository }}/releases">Other downloads and release information</a></li>
  <li><a href="https://boatsanimator.readthedocs.io/en/stable/introduction/system-requirements/">System requirements</a></li>
  <li><a href="https://boatsanimator.readthedocs.io/">Documentation</a></li>
  <li><a href="{{ page.repository }}">GitHub Repository</a></li>
</ul>

# User Testimonials

Here's what people think of Boats Animator! All of the photos below were taken by the users themselves.

## Bert Loos

[https://www.youtube.com/tehbertl](https://www.youtube.com/tehbertl)

*"It's very user-friendly, fast, and has a minimal design that keeps me focused on animating. I also like that it's able to utilize the maximum resolution my webcam outputs..."*

![BertL](../assets/boats-animator/user-submissions/bertl1.jpg)

## Shelby Pritchard

[https://www.youtube.com/user/pritchardstudios](https://www.youtube.com/user/pritchardstudios)

*"I use it for brickfilming, Lego stop-motion animation, and love that it is a free capture program that allows easy preview, camera selection, and most importantly, 1080p capture."*

![Pritchard](../assets/boats-animator/user-submissions/pritchard1.jpg)

## Catalin Chelariu - Softpedia

[https://www.softpedia.com/get/Multimedia/Video/Other-VIDEO-Tools/Boats-Animator.shtml](https://www.softpedia.com/get/Multimedia/Video/Other-VIDEO-Tools/Boats-Animator.shtml)

*"On the whole, this program looks very promising, and we were mostly impressed by its intuitive, novice-friendly design. Once the missing features are implemented, this will be an excellent alternative to overly complex or expensive stop-motion animation tools."*

## Ryan

*"I love the onion skinning... ...I'm glad I found this as it's something that still being worked on!"*

## Owen Garcia

*"I make brickfilms (Lego stop motion movies) and Boats Animator is perfect for it. I love that it has onion skinning, grid overlay, and 1920x1080 support. Boats Animator is great and I think anyone, pro or beginner, should use this wonderful program."*

![Garcia](../assets/boats-animator/user-submissions/garcia1.jpg)

# Recent News
{% capture get_category %}{{ page.category }}{% endcapture %}
{% for post in site.categories["Boats Animator"] limit:3 %}
<article class="item">
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <h4>{{ post.date | date: "%-d %B %Y" }}</h4>
  <p>{{ post.excerpt }}</p>
</article>
{% endfor %}

<a href="/category/boats-animator" class="button">More posts</a>
