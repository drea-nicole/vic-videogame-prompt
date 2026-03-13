# VIC Videogame Prompt

This repository contains a step-by-step guide for generating videogame-style scenes using AI prompting techniques. The process starts with creating static keyframes using Nano Bana Pro, then transitions to video generation with Veo3.1 by using these keyframes as reference images for start and end frames.

## Overview

The workflow involves three main phases:
1. **Keyframe Generation**: Using Nano Bana Pro to produce high-quality static images that serve as keyframes.
2. **Video Generation**: Converting the static keyframes into a smooth video sequence by treating them as start and end frame references.
3. **Editing**: Upscaling and exporting video files and bringing them to an external video editing tool. 

## Prerequisites

- Nano Bana Pro (or similar AI image generation tool)
- Veo3.1 (or similar Image-to-video generation tool)

- Reference images (uploaded in this repository under `/images/` or similar directory)
- Generated keyframes and video sequences ( uploaded in this repository under `/keyframes/` and `/videos/`)

## Step-by-Step Guide

### Step 1: Prepare Your Reference Images
- Gather or create initial reference images that capture the desired scene elements (characters, environments, lighting, etc.).
- These reference images are uploaded in the repository for consistency and reference.

### Step 2: Generate Static Keyframes with Nano Bana Pro
- Use detailed prompts to generate static keyframes. Focus on:
  - Character poses and expressions
  - Environmental details
  - Lighting and atmosphere
  - Composition and framing

- Generate multiple keyframes representing key moments in the scene (e.g., start pose, mid-action, end pose).
- Export the generated keyframes as high-resolution images.
- The generated keyframes are uploaded in this repository for reference.

### Step 3: Prepare for Video Generation
- Select keyframes to serve as the start and end frames for your video sequence.
- Ensure the keyframes have consistent style, lighting, and character continuity.

### Step 4: Generate Video from Images
- Use an image-to-video tool (e.g., Runway ML Gen-2,Veo 3.1, or similar).
- Upload your start frame keyframe as the initial image.
- Upload your end frame keyframe as the target or reference image.
- Craft a transition prompt that describes the motion between the frames:
  ```
  Smooth transition from [start frame description] to [end frame description], maintaining character consistency, fluid animation, videogame style
  ```
- Adjust parameters for duration, style, and quality as needed.
- Generate the video sequence.

### Step 5: Review and Edit Together
- Review the generated video for continuity and quality.
- If needed, regenerate with adjusted prompts or different keyframe selections.
- Upcale and export video segments to bring into editing software to stitch together sequences.

## Note on Editing
- Generated audio was detached and saved as an independent file. 
- Video files received a speed chnage to 1.8x. 
- Additional video/audio cuts and edits where made.

## Repository Contents

- `/keyframe.promt.md/`: Keyframe prompts used 
- `/images/`: Reference images used for prompting
- `/keyframes/`: Generated static keyframes from Nano Bana Pro
- `/videos/`: Generated video sequences
