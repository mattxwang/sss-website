---
layout: projects
title: Paleta
short: paleta
permalink: /projects/paleta/
github: "malsf21/paleta"
website: "https://matthewwang.me/paleta/"
img: "paleta-1.png"
creator: matthewwang
description: "Paleta is a set of style guides for UCC organisations and projects to make design easy."
---

![Paleta Full Logo](https://matthewwang.me/paleta/img/signature.png)

# [paleta](https://matthewwang.me/paleta/)

[![Build Status](https://travis-ci.org/malsf21/paleta.svg?branch=master)](https://travis-ci.org/malsf21/paleta)

Paleta is an online style guide for a few organisations that I have some sort of design role in. It provides information such as colour palettes, typography, or branding. Plus, it's modular, which means that you can use Paleta to make your own style guides. Awesome!

## Organizations

Currently, Paleta supports:
* [The World Affairs Conference](https://world.ac)
* [9651 Robotics](https://robotics.ucc.on.ca)

Paleta plans to support:
* [Convergence](https://convergence.today)
* [UCC Digital Media and Computer Science Club](https://dmcs.tech)
* [Ontario Model United Nations](https://omun.ca)
* [Student Server Space](https://github.com/studentserverspace/website)

## Setup

Paleta uses a script to perform setup (installing dependencies, moving a few files around, etc). In order to run the setup script, just run:

```
./setup.sh
```

After, you just need to serve the site. You should use:

```
./start.sh
```

On the contrary, if you want to build the site into the `_site` directory, run:

```
./build.sh
```

If you're having issues with running any `.sh` files, enter this in your terminal to make it executable:

```
chmod +x YOUR-FILE.sh
```

## Making a Style Guide

Coming soon!
