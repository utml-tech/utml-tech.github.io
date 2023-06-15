---
author: pedro
header:
  actions:
    - label: YouTube
      url: "https://youtu.be/ztpWVZyim7k"
    - label: Transcription
      url: "assets/transcriptions/2023-06-09-stable-diffusion-lab.txt"
layout: single
tags:
  - labs
title: "Lab \#01: Stable Diffusion Web UI Introduction"
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/ztpWVZyim7k?start=120" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## TL;DR

We create an anime style dancing video using Stable Diffusion and Control Net.

## Topics

- Creation of a GitHub repository
- Discussion about the GitHub organization and utml.tech
- Mention of using Adobe Creative account and library computer for Adobe Express
- Slow performance of Firefly and Adobe Express
- Mention of having an email
- Creation of two repositories: websites and files
- Planning to add Tunga to the repositories
- Proposal of pair programming for better productivity in a team
- Instructions for downloading stable diffusion web UI, control net extension, and models
- Generation of multiple images from a video file
- Discussion on the benefits of Docker for isolated environments
- Setting up stable diffusion web UI on a remote server using VS Code and SSH
- Installation and configuration of dependencies and libraries
- Mention of using models from a website and downloading LoRa models
- Use of xformers library
- Custom file commands for convenience
- Testing stable diffusion web UI with a prompt
- The speaker expresses that the current setup is too much and needs to be reduced.
- They mention trying a vertical aspect ratio but it didn't work well, possibly due to improper configurations.
- The speaker decides to use 12 frames and wants the output to resemble the input image.
- There is a discussion about using batch processing and setting it to be local.
- They create an "images" folder and copy images into it.
- The speaker expresses frustration with the lack of information during the copying process.
- While the copying is in progress, they decide to download more files, particularly the OpenPose model.
- They discuss the purpose of OpenPose, which is for pose estimation and finding body positions.
- The speaker considers using OpenPose for depth and mentions SD15.
- They create an "outputs" folder and contemplate the need for certain files and configurations.
- The speaker realizes that Control-Net requires two units and explores the settings.
- There is a brief interruption where the UI is restarted and reloaded.
- They confirm that Control-Net now has four units and discuss the input directories for Control-Net and OpenPose.
- The speaker contemplates using Canny edge detection and seeks input on it.
- They mention the need for a prompt and decide to show OpenPose results to demonstrate it.
- The speaker discusses the limitations and possible alternatives to OpenPose.
- They generate the images and mention the time it will take.
- There is a discussion about the size of the output video and determining its dimensions.
- They mention the need to convert the frames and adjust the audio to match the video length.
- The speaker expresses the desire to automate the process of generating videos and discusses the challenges involved.
- They suggest creating a command-line interface and contemplate the necessary inputs and options.
- The speaker reflects on the potential of expanding the project and working on end-to-end video generation.
- They mention the possibility of using multiple GPUs and frame interpolation.
- The speaker mentions the presence of a watermark in the output and considers adding more features to the tool.
- There is a brief interruption to handle the code and create a README file.
- The speaker outlines the idea behind the project, including the CLI, input requirements, and conversion process.
- They mention the possibility of using the "Fire" library for creating the command-line interface.
- The transcription concludes with the speaker expressing the need to study and explore the implementation details.

Please note that some parts of the transcription were unclear or lacked context, so the bullet points may not capture the complete meaning or intention behind certain statements.
