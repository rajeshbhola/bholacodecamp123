---
layout: post
title: "Creating a simple Grails application"
description: "Learn how to build a modern blog using Jekyll and Tailwind CSS with step-by-step instructions"
date: 2024-12-01
author: Rajesh Bhola
categories: [web-development, tutorials]
tags: [grails]
image: https://images.unsplash.com/photo-1734375181552-cfa83d404033?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
featured: true
---

**Table of Contents**
- TOC
{:toc}
<br>

## Introduction

Creating a simple Grails application is a straight-forward process. Here’s a quick step-by-step guide to get you started. And this process is applicable for both VS Code and Intellij Ultimate Edition IDE.
<br>
<br>

## What is the Grails Framework

Grails is an open-source web application framework that uses Groovy, a dynamic programming language for the Java platform.
<br><br>

It is designed to simplify and accelerate web application development by providing a
**convention-over-configuration** approach, built on top of popular technologies like **Spring**, **Hibernate**, and **GSP**(Groovy Server Pages).
<br><br>
Grails is particularly useful for building scalable, enterprise-grade web applications with minimal configuration and boilerplate code, making it ideal for rapid application development.
<br>
<br>

## How to Install Grails

First, make sure you have Java Development Kit **(JDK)** installed on your system.
<br><br>
Next, download and install the **Grails Framework** from the official site or use a tool like **SDKMAN!** to manage your Grails installation.
<br><br>
**Install:** Download and install Grails -> [Go to Download Page](https://grails.org/download.html){:target="\_blank"}
<br>
<br>

## How to Set Up a New Project

Open a terminal or command prompt and
Run the following command to create a new Grails application:
<br>
{% highlight bash %}
grails create-app myapp
{% endhighlight %}
<br>
Replace "**myapp**" with the name you want for your application.
<br>
<br>

## Next Step
Move to the newly created project directory

{% highlight bash %}
cd myapp
{% endhighlight %}
<br>

## How to Run the Application

Start the Grails application with the following command
<br>
{% highlight bash %}
grails run-app
{% endhighlight %}
<br>
This will start the embedded server and you can access your application at **http://localhost:8080**.

Once the server is running, open your browser and go to **http://localhost:8080**. You should see the default Grails welcome page, indicating that your application is running successfully.
<br>
<br>

## How to Stop the Application

When you're done, you can stop the Grails server by pressing **CTRL + C** in the terminal where it's running.
<br>
<br>

## Demo
{% include video.html video="https://www.youtube.com/embed/fqFjuX4VZmU" %}


<br>

## Conclusion

You've successfully created and run a simple Grails application.
<br>
<br>

_happy coding!_