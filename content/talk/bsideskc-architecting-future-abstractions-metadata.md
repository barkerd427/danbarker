+++
date = "2017-05-20T00:00:00"
title = "Architecting the Future: Abstractions and Metadata"
abstract = "Kubernetes and Docker are two of the top open source projects, and they’re built around abstractions and metadata. These two concepts are the key to architecting in the future. Come with me as I dig a little deeper into these concepts within k8s and Docker and provide some examples from my own work."
abstract_short = ""
event = "BSidesKC"
event_url = "https://www.bsideskc.org"
location = "Kansas City, Missouri"

selected = false
math = true

url_pdf = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

Buy tickets now: [Attend BSidesKC](https://www.bsideskc.org/attendee/ "Attend BSidesKC")
<br />
Or become a sponsor: [Sponsor BSidesKC](https://drive.google.com/file/d/0B9HBYjWM2gT9MlAwSjZXS0RSamc/view "Sponsor BSidesKC")

This talk will explore these concepts within k8s and Docker as well as work I've done in my current role around continuous delivery pipelines. Attendees will leave with an appreciation for these two concepts and the tools necessary to begin architecting their systems similarly.

Abstractions and metadata are the future of architecture in systems engineering as they were before in software engineering. In many languages, there are abstractions and metadata. However, systems engineering has never adopted this view. Systems were always thought of as too unique for any standard abstractions. Now we've standardized the lower-level abstractions and we’re ready to build new system-level abstractions.

Docker has become the standard unit of processing, which has alleviated many of the diversity issues within systems. Docker did this with abstractions around networking, cpu, memory, and filesystems.

Kubernetes is now using Docker to create higher-level abstractions, but they've even abstracted away the runtime. Kubernetes uses concepts like PersistentVolumes, Routes, Services, and Deployments as abstractions.

My team has created an abstraction around continuous delivery pipelines that provides us more flexibility with underlying resources. It's a simple system based on certain abstractions and specific metadata. We've abstracted the build and deploy systems from the deployment pipeline model as well as accumulated metadata attributed to people, data, and pipelines to ensure security and compliance at scale.
