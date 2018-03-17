---
title: "Automating netSEC lab setup"
date: 2018-02-06T18:04:18-05:00
draft: true
---

## Helter Skelter

If you're like me, you spend your time spread across a number of different technologies, toolsets and subject matter. One week you find yourself setting up a full blown Windows Domain with endpoints logging to a centralized log correlation tool and the next week you are trying to wrap your head around how to automate malware analysis in the cloud.

## You practice how you play

Setting up a virtual lab can be painstaking. Ideally, you want multiple endpoints to simulate, well, multiple endpoints... It's no fun `moving laterally` between two Windows 7 VM's you setup with bogus default settings. 

Let's take our game to the next level and create a virtual netSEC lab that will provide us with the ability to simulate activity with a modest level of realism while not demanding an excessive amount of resources.

Unfortunately, unless we take the time to create scripts to automate the process, we will be stuck performing the same tedious and time consuming actions over and over again.

## Let's write a recipe

So let's walk through how to take the pain out of standing up a simple Windows Domain with a few of the necessary components a *Blue Teamer* needs to get any value out of them.


