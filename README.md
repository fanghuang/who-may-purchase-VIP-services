# Who may purchase VIP services?

## Introduction
There are millions of apps in the iOS AppStore and Google Play store. As an app provider, we need to identify people who may purchase VIP services. To figure this out we will try to learn from the download history of users. The goal is to see whether we can identify the users most likely to purchase VIP services, our golden users!

## Project
**Instructions:** 

In our training data, we will provide the probability of each user purchasing VIP services. Using this training data, your code should predict a user’s probability of purchasing VIP services with label=1 from other tags. After submitting your code, we will evaluate it based on normalized cross entropy.

**Fields:**
* appfile - the version of the news APP this user is using
* uid: unique ID to identity the user
* app: the kind of the news APP this user is using
* label: whether this user has purchased VIP service
* activity_time: the time when we logged while this user was using this APP
* category_id: a list of news categories the user has browsed. For example, 1 may stand for sports, 2 may stand for food, etc.

## Special Thanks
Special thanks to [bittiger](http://bittiger.io/) for providing the problem and the dataset.
