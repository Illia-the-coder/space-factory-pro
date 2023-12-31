---
title: Space Factory Pro
emoji: 🏭🦙
colorFrom: purple
colorTo: indigo
sdk: docker
pinned: false
app_port: 7860
license: llama2
---

Generate Hugging Face Spaces using CodeLlama 34b

# Examples

## Local prompt examples

```
http://localhost:7860/?prompt=A%20simple%20page%20to%20compute%20the%20BMI%20(use%20SI%20units)
```

# Installation
## Building and run without Docker

```bash
nvm use
npm i
npm run start
```

## Building and running with Docker

```bash
npm run docker
```

This script is a shortcut executing the following commands:

```bash
docker build -t space-factory .
docker run -it -p 7860:7860 space-factory
```