---
layout: post
title:  "About Folder Queue Manager (FQM)"
date:   2020-03-25 21:12:01 +0300
categories: Code Science
---

Folder Queue Manager - FQM is a simple software for adhoc Directory Monitoring, command executing and folder copying/moving software for small tasks. This software is written for adhoc needs of a physics research group LRG. With the Covid-19 outbreak, Laboratory went to all remote-work. However, there were some computational codes needed to run on lab computers. However, because of Teamviewer type of remote connection softwares and Reverse SSH were not working on the lab computers, there was a need of this small software. It is best used with Google Drive (GD), Dropbox type of cloud file management tools.

With this code, you can use your GD or Dropbox as a queue for your computation tool. Program checks a folder (likely in GD or Dropbox Folder). When finds a file (likely a Python script), it copies to a temp folder (likely a local folder). Then, it executes the file. When the execution of command finishes, it zips all results and put it to another folder (again likely a GD or Dropbox folder). Therefore, without using any other tools, you can use you Cloud file space as a computation queue. It can be used in many computers you need.

We believe, in a days like these, many people may need this kind of software. Therefore, we publish it freely as quick as possible (First release: Mar 25,2020). Code is very primitive in the of this post published. However, it is easy to recompile for your needs.
