---
layout: cv
title: Antonio Bosak's CV
---
# Antonio Bosak
Software developer (backend)

<div id="webaddress">
<i class="fa-solid fa-envelope"></i>
<a href="mailto:toni.bosak@gmail.com">toni.bosak@gmail.com</a>
| <i class="fa-brands fa-linkedin"></i>
<a href="https://www.linkedin.com/in/antonio-bosak-6b9865136/">Antonio Bosak</a>
| <i class="fa-brands fa-github"></i>
<a href="https://github.com/toncek345">toncek345</a>
</div>


## Work experience

### Deliveroo
`01/05/2021 - 01/10/2022`

- Refactored websocket logic which resulted in 20% CPU usage decrese and decrease in disconnection
- Increased message throughput through redis
- Refactored tracing and logging across services
- Removing deprecated libs & business logic (db, library migration to DataDog, removed old routemaster logic)
- Participated in geosharding project
- Upgraded multiple PG DBs from 9.6 -> 11+
- Removed, updated, optimized a lot of legacy code

Tags:
- high scale
- golang
- backend
- ruby
- ruby on rails
- aurora/postgres
- terraform

### EPTI
`01/11/2020 - 01/05/2021`

My responsibility was maintenance of existing micro-services written in golang and adding new
features. Mainly I was responsible for fixing payment service and introduction to new payment
providers.

Tags:
- backend
- golang
- postgres

### Cinnamon Agency
`16/03/2020 – 1/11/2020`

For one of the clients my responsibility was consulting how to architect and write backend services
and writing backend services with devopsing on kubernetes. 

Tags: 
- backend
- golang
- postgres
- chi router
- docker
- devops
- kubernetes
- aws

<div class="page-break"></div>

### B2match
`01/05/2018 – 16/03/2020`

My responsibility was developing and maintaining backend services (main service, admin service
written in ruby and small redirector service for logging purpose) and monitoring unusual events
through GCP logging.

Summary:
- Fixing the CI/CD GitLab pipeline
- Prototyping some functionality using headless chrome
- Writing client consumable api
- Added ability for users to add their custom domain which was implemented through Let's Encrypt
- Maintaining administrator part (writing rake tasks, workers and migrations) 

Tags:
- solr
- golang
- gRPC
- chi router
- ruby
- ruby on rails
- sidekiq

### Side projects
`01/12/2017 - 01/05/2018`

- Retroreflection project for University of Zagreb Faculty of Transport and Traffic Sciences (React, Ruby, Devops)
- TotallyNotInstagram project for uploading pictures to only attended event through QR code (android)
- Izi do potpora project for listing EU projects for Zagreb city (Android)
- BronhoNote project for tagging lung bronchi in hospitals (JAVAFX)
- UNDP project for solar panel monitoring (C, GO)

### GoodCode
`01/04/2016 – 01/12/2017`

I was responsible for an internal MusicBox project which has 3 parts. Django (admin) part and golang
(streamer and player) part. I was mainly responsible for developing features on golang part but I
added small contributions to admin project (test fixing and sending email to client when player
connected or disconnected). 

Features added to streamer:
- buffering with smart "continue where left" 
- live stream support (through icy protocol) 
- song queuing ◦ various tests and benchmarks

The player part which was connected to streamer was developed for Raspberry Pi and it was written from scratch in C and then later rewritten in golang. 

Feature added to player: 
- buffering with smart continue when disconnected

<div class="page-break"></div>

### College demonstrator (VsiTe Zagreb)
`01/10/2015 – 01/02/2016`

Assistant during the laboratory practices in college in class programming methods and abstraction (C programming language).


<!-- ### Footer Last updated: May 2013 -->


