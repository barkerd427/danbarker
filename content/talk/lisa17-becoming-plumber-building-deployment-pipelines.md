+++
date = "2017-11-01T00:00:00"
title = "Becoming a Plumber: Building Deployment Pipelines"
abstract = "A core part of our IT transformation program is the implementation of deployment pipelines for every application. Attendees will learn how to build abstract pipelines that will allow multiple types of applications to fit the same basic pipeline structure. This has been a big win for injecting change and updating legacy applications."
abstract_short = ""
event = "LISA17"
event_url = "https://www.usenix.org/conference/lisa17"
location = "San Francisco, CA"

selected = false
math = true

url_pdf = "https://drive.google.com/uc?export=download&id=0B88WpFWKRdpYQTExZGFlMUQwSkE"
url_slides = "https://www.slideshare.net/DanielBarker4/becoming-a-plumber-building-deployment-pipelines-lisa17"
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

<iframe src="//www.slideshare.net/slideshow/embed_code/key/wC7bottiYo2ufL" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/DanielBarker4/becoming-a-plumber-building-deployment-pipelines-lisa17" title="Becoming A Plumber: Building Deployment Pipelines - LISA17" target="_blank">Becoming A Plumber: Building Deployment Pipelines - LISA17</a> </strong> from <strong><a href="https://www.slideshare.net/DanielBarker4" target="_blank">Daniel Barker</a></strong> </div>

A core part of our IT transformation program is the implementation of deployment pipelines for every application. Attendees will learn how to build abstract pipelines that will allow multiple types of applications to fit the same basic pipeline structure. This has been a big win for injecting change and updating legacy applications.

In large enterprises, there are a lot of moving parts to manage. Our company has historically acted as many individual companies, but we have pivoted toward a model where we can still maintain independence but leverage efficiencies of scale. My team was formed to help create a new platform for all our applications. We work with the business units and the rest of the IT organization to ensure everyone is aligning with our overall strategy.

We are building out a PaaS system using Kubernetes and Docker. Those are cool buzzwords, but the most important part is the deployment pipeline system. We’ve discovered how crucial it is to have every application in a deployment pipeline that can be easily managed centrally. In the past, it was nearly impossible to inject any kind of change into the deployment path when a new corporate policy or government regulation came out.

We’re now able to pivot applications from VMs, to Docker containers, to the public cloud. We’re also able to inject changes into our pipelines through our pipeline abstractions that our applications now use. Making an update just requires a change in the core pipeline model and then rebuilding all the dependent pipeline descriptions.
