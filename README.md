<h1 align="center">
  Sia
</h1>

_<p align="center">Your open-source privacy preserving personal assistant.</p>_

---

## 👋 Introduction

**Sia** is an **open-source personal assistant** who can live **on your server or local system**.

She **does stuff** when you **ask her for**.

You can **talk to her** and she can **talk to you**.
You can also **text her** and she can also **text you**.
If you want to, Sia can communicate with you by being **offline to protect your privacy**.

### **Click the following link for demo video** : [**Demo Video**](https://drive.google.com/file/d/1F2UxkAHYUbh--oqtS100vYYFTnUx4QKl/view?usp=sharing)

### Azure technologies used

> 1. **Azure text-to-speech** : With the help of text-to-speech feature of the Speech service, which is part of Azure Cognitive Services. Sia is able to interact with us by converting text into humanlike synthesized speech.
>
>    With the help of nodejs npm package : `npm i microsoft-cognitiveservices-speech-sdk`.We can synthesize speech using text or string to a .wav file in the location that we specified.
>
>    The text-to-speech feature in the Azure Speech service supports more than 270 voices and more than 110 languages and variants.
>
>    Currently, Sia is using `en-US-AmberNeural` voice.
>
> 2. **Azure speech-to-text** : _(Not yet integrated, still under development)_

### Why?

> 1. If you are a developer (or not), you may want to build many things that could help in your daily life.
>    Instead of building a dedicated project for each of those ideas, Sia can help you with his
>    packages/modules (skills) structure.
> 2. With this generic structure, everyone can create their own modules and share them with others.
>    Therefore there is only one core (to rule them all).
> 3. Sia uses AI concepts, which is cool.
> 4. Privacy matters, you can configure Sia to talk with her offline. You can already text with her without any third party services.
> 5. Open source is great.

### What is this repository for?

> This repository contains the following nodes of Sia:
>
> - The server
> - The packages/modules
> - The web app
> - The hotword node

### What is Sia able to do?

> Today, the most interesting part is about her core and the way she can scale up. She is pretty young but can easily scale to have new features (packages/modules).

Sounds cool right?

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) >= 16
- [npm](https://npmjs.com/) >= 8
- [Python](https://www.python.org/downloads/) >= 3
- [Pipenv](https://docs.pipenv.org) >= 2020.11.15
- Supported OSes: Linux, macOS and Windows

### Installation

```sh
# Clone the repository (stable branch)
git clone -b master https://github.com/varunsrivatsa/Sia.git sia


# Go to the project root
cd sia

# Install
npm install
```

### Usage

```sh
# Check the setup went well
npm run check

# Build
npm run build

# Run
npm start

# Go to http://localhost:1337
# Hooray! Sia is running
```

**Sia needs open source to live**, the more modules she has, the more skillful she becomes.

## ☁️ Try with a Single-Click

Gitpod will automatically setup an environment and run an instance for you.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/NXture/Sia)

## 📝 License

[MIT License](https://github.com/NXture/Sia/blob/main/LICENSE.md)

Copyright (c) 2021-present, Varun Srivatsa <varunsrivatsa27@gmail.com>
