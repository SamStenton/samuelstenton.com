---
title: Hosting your static site using Azure DevOps and Blob Storage
date: "2019-12-29T22:12:03.284Z"
description: "Host "
---

Been putting off rebooting the blog for quite some time. Renewing this domain for the third consecutive year without anything on it finaly gave me the push I needed to do something about it. 

What better first post than one explaining how the site is hosted. As my recent experience with Elanco has been with Azure, it makes sense to build and host this site on there. I plan on 
using the following services from Azure. 

**Azure DevOps**

Will pull the site code from GitHub, run `gatsby build` and then send the output to Blob storage.


**Blob Storage**

Holds the static site files and allows acess to them from the a the internet.


**Content Delivery Network**

Adds a super fast content delivery backend but most importantly allows me to connect my personal domain to the site.

## Prerequisites

This post assumes that you have access to Azure, Azure DevOps and have created a Gatsby (or similar) site sitting in GitHub. 

## Azure Setup

## DevOps Pipeline