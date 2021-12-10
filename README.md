# Contributing Guidelines

A project is composed of two files: a Markdown file with headers, and an image. To add a new project to the ecosystem page, create both a new Markdown file in the projects directory and add a new image in the img directory.

!Important!: Should your Project already exist within this repo, refrain from creating a new Markdown file in the projects directory! Rather adapt your old one in a new PR. Same goes for changed images or Logos for your Project.

# Example File

```mdx
---
id: Scaleout
uri: https://www.scaleout.com
slug: Track your steps with Pebble Tracker to prove your activity and earn token rewards
logo: /assets/scaleout/logo.png
date: 2021-11-10
author: Big Data
previews:
  [
    /assets/scaleout/preview1.png,
    /assets/scaleout/preview2.png,
    /assets/scaleout/preview3.png,
  ]
data:
  {
    "appName": "Gravel",
    "appVersion": "v1.0.0+",
    "configName": "Common",
    "configVersion": "v1.0.0",
    "trusttreamTopic": "device/id/data",
    "dataChannel": 8183,
    "uploadPeriod": "30",
    "preciseGPS": false,
  }
---

Scaleout is a pioneering federated machine learning company, joining the IoTeX ecosystem to decentralize the machine learning value chain from data collection to model usage/access. As a first step, Scaleout will develop a protocol for contributor-owned machine learning models that will be trained with verifiable data from Pebble Tracker, allowing anyone to mine tokens by contributing their data to various models. The end goal is to develop an end-to-end solution for decentralized machine learning, including trusted collaboration, smart contract-based model governance, and on-chain serving of machine learning predictions.

Want to learn more? Join the discussion on IoTeX Forum
```
