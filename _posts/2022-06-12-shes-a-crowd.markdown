---
layout: post
title:  "She's A Crowd"
description: "A platform to report gender based violence"
date:   2022-06-12 12:00:00 +1100
categories: projects
---

# About

[She's A Crowd](shesacrowd.com) is a social enterprise to stop gender based violence. Traditional channels (eg. the police) are not suited to handle the nature of gender based violence and reports are often not acted on, or not reported at all. 

Working with She's A Crowd, I built a [platform](https://share.shesacrowd.com) to give a place where you can report incidents and give the location, what happened, what happened afterwards, and many other features of the incident, and if you feel comfortable, to share your story their as well. For many reporting, the experience of sharing your story on the platform is cathartic and empowering, and may be the first time that individual has ever told anybody. 

The goal of gathering this data is to use it to affect change by partnering with various community groups and organisations to identify problem areas. 

Currently the platform has received over 100,000 story submissions. None of the story descriptions themselves are publically available and users can choose to submit a story without it becoming publically available.

It was a pleasure to work with Zoë and the rest of the team at She's A Crowd. Being a part of this project opened my eyes up to the subtle and not so subtle ways women are harassed and how unfortunately common this experience is.

![map](/assets/images/sac/map.png)

![survey](/assets/images/sac/whathappened.png)

![stats](/assets/images/sac/stats.png)

## Admin Portal

The app features a portal as well where admins can go and edit stories, or remove them entirely. For privacy reasons, all stories must be processed through this portal and have any identifying information removed before being made to third parties.

![portal](/assets/images/sac/portal.png)

# Technologies used

## Frontend

* React/Typescript
* Mapbox

## Backend

* Node.js/Typescript
* Express
* Docker
* Jest (tests)
* Redis
* Postgres

## Cloud services

* AWS RDS
* AWS Elasticache
* AWS ECS
* AWS cloudfront

## Apis

* PTV
* Auth0