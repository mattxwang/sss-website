---
layout: projects
title: Fair Chair
short: fairchair
permalink: /projects/fair-chair/
github: "malsf21/fair-chair"
img: "fair-chair-1.png"
creator: matthewwang
description: "Lorem Khaled Ipsum is a major key to success. Major key, don’t fall for the trap, stay focused."
---

# Fair Chair

[![Build Status](https://travis-ci.org/malsf21/fair-chair.svg?branch=master)](https://travis-ci.org/malsf21/fair-chair)

> Making chairing Model UN conferences easy and fair

Fair Chair is a desktop app that's designed to help chairs keep track of their committee, with a speaker timer, speaker list, and committee notes section. The goal of this app is to be projected on a screen, so all the delegates in the conference can always see what's happening.

*Note: If you want to use this for your conference, that's fine. But, please don't remove my name, or any parts of the bottom footer, from the app. Thanks!*

## Installation

Visit the [releases page](https://github.com/malsf21/fair-chair/releases) and download the `.zip` for your Operating System. Right now, Fair Chair is available for OSX and Linux.

## Tech Specs

Fair Chair uses [Electron](https://github.com/electron/electron) turn the HTML/CSS/JS into a desktop application.

Fair Chair uses [Bootstrap](https://github.com/twbs/bootstrap) as our CSS Framework, [jQuery](https://github.com/jquery/jquery) to do DOM manipulation, and [Font Awesome](https://github.com/FortAwesome/Font-Awesome) as an icon font toolkit.

## Development Setup

*Note: Development isn't working properly with travis right now, but you should be able to follow these steps to build it properly. Let me know if there are any problems, on our issue tracker!*

You'll need these things for development:

* Unix-based operating system (if you're running on Windows, find a unix shell and follow these steps)
* [node.js](https://nodejs.org) (we developed it on
* [npm](https://www.npmjs.com/)
* [Electron](https://github.com/electron/electron)

We'll assume you have node and npm installed.

First, clone this repository:

```

git clone https://github.com/malsf21/fair-chair.git

```

Get into the fair-chair directory:

```

cd fair-chair

```

Install our npm dependencies:

```

npm install

```

Then, start our app!

```

npm start

```

### Building a Distribution file

We'll use [Electron Packager](https://github.com/electron-userland/electron-packager) to help package our app. We assume you've done the above instructions.

Install electron-packager:

```

npm install electron-packager -g

```

Then, build for what platform you want. [Electron Packager](https://github.com/electron-userland/electron-packager) has documentation on how to customize your build options. Here's an example:

```

electron-packager ./ FairChair --platform=darwin --arch=x64

```

## Credits

Fair Chair was made by Matthew Wang (@malsf21) for the [Ontario Model United Nations Conference](https://omun.ca).
