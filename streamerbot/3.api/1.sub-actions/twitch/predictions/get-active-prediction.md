---
title: Get Active Prediction
description: Check if a prediction is currently active and unlocked
version: 0.2.5
variables:
  - name: active
    type: bool
    description: Indicator whether an active prediction is running (and not locked yet)
    value: True
  - name: prediction.Id
    type: string
    description: Twitch's internal id for the prediction
  - name: prediction.CreatedAt
    type: DateTime
    description: The timestamp that the prediction was created
    value: 8/4/2023 10:56:06 AM
  - name: prediction.Title
    type: string
    description: The title of the prediction
    value: My prediction title
  - name: prediction.PredictionWindow
    type: number
    description: The duration of the prediction
    value: 300
  - name: prediction.outcome#.id
    type: string
    description: The id for this outcome
  - name: prediction.outcome#.title
    type: string
    description: The title for this outcome
    value: Outcome 1
  - name: prediction.outcome#.users
    type: number
    description: How many users voted for this outcome
    value: 20
  - name: prediction.outcome#.points
    type: number
    description: The amount of channel points used for this outcome
    value: 1200
  - name: prediction.outcome#.color
    type: string
    description: In capital letters the color name for this outcome
    value: BLUE
---