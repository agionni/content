---
title: 'Offline Transcription'
description: 'Speech-to-text processing that runs on local models instead of a hosted API.'
date: 2026-05-20
author: 'Aldo Giovanni'
---

# Offline Transcription

## Definition

Offline transcription is the process of converting speech into text with a
model that runs locally on the same machine or workspace where the audio file is
processed. The audio does not need to be uploaded to a hosted speech-to-text
API.

## Context and Usage

Engineering teams use offline transcription when recordings contain sensitive
customer calls, internal demos, unreleased product details, or regulated data.
It is also useful when a workflow must keep working without internet access or
when a team wants predictable cost for large batches of recordings.

Offline transcription still needs model files, CPU or GPU resources, and a
review step. The tradeoff is direct control over the execution environment and
data path.
