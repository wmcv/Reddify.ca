# reddify.ca

**An automated short-form content platform that transforms a topic into a complete Reddit-style story video.**

[Live product](https://reddify.ca)

> This repository contains public product and technical documentation for reddify.ca. The production source code and deployment configuration are maintained privately.

reddify.ca helps creators produce short-form story videos without manually scripting, narrating, editing, and publishing every post.

A user provides a topic and content preferences. The platform coordinates a series of AI and media-processing stages to generate the script, voiceover, visual composition, and final video.

The product reached **50+ active subscribers** and approximately **$10K in annual recurring revenue**.

---

## What reddify.ca does

- Turns a topic into a structured short-form story
- Generates scripts using AI-assisted content pipelines
- Produces automated voiceovers
- Renders vertical videos for short-form platforms
- Supports reusable templates and content styles
- Coordinates long-running generation tasks asynchronously
- Tracks subscriptions and payments through Stripe
- Stores projects, generated assets, and processing state
- Reduces the manual work required to create repeatable content

---

## How it works

A generation request moves through a sequence of independent processing stages:

```text
Topic
  ↓
Content research and planning
  ↓
Script generation
  ↓
Voiceover generation
  ↓
Visual and media selection
  ↓
Video composition
  ↓
Rendering
  ↓
Completed short-form video
