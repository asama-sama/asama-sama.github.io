---
layout: post
title:  "She's A Crowd"
date:   2023-01-19 12:00:00 +1100
categories: projects
---

# About

[She's A Crowd](shesacrowd.com) is a social enterprise to stop gender based violence. Traditional channels (eg. the police) are not suited to handle the nature of gender based violence and reports are often not acted on, or not reported at all. 

Working with She's A Crowd, I built a [platform](https://share.shesacrowd.com) to give a place where you can report incidents and give the location, what happened, what happened afterwards, and many other features of the incident, and if you feel comfortable, to share your story their as well. For many reporting, the experience of sharing your story on the platform is cathartic and empowering, and may be the first time that individual has ever told anybody. 

The goal of gathering this data is to use it to affect change by partnering with various community groups and organisations to identify problem areas. 

Currently the platform has received over 100,000 story submissions. None of the story descriptions themselves are publically available and users can choose to submit a story without it becoming publically available.

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