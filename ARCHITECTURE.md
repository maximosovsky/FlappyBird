# Architecture — FlappyBird

## Overview

FlappyBird — Unity WebGL билд Flappy Bird. Компилированная версия для веба.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Engine | Unity (WebGL export) |
| Runtime | WebAssembly |

## Project Structure

```
├── index.html       # Unity WebGL loader
├── Build/           # Compiled WASM + data
├── TemplateData/    # Unity template assets (CSS, icons)
└── LICENSE          # MIT
```

## Key Concepts

- **WebGL build** — скомпилированный билд, без исходников
- **TemplateData** — стандартный Unity WebGL template
