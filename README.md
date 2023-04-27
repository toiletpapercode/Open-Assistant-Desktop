# Open Assistant Desktop

## <span style="color:red">This is a proposal and work in progress. This message will change once it is ready for use</span>

## Introduction

This will be a desktop application which allows you to interact with [Open Assistant](https://github.com/LAION-AI/Open-Assistant) chat models using your own hardware, on your own computer.

### <span style="color:orange">*No data will leave your computer*</span>

You may optionally choose to share feedback with Open Assistant, it is an Open Source initiative and simple thumbs up or down on responses will help the models improve.

If you want to help more: [Contribute to Open Assistant](https://github.com/LAION-AI/Open-Assistant/blob/main/CONTRIBUTING.md). You do not need to be a developer to help!


### What is Open Assistant?

https://github.com/LAION-AI/Open-Assistant

> Open Assistant is a project meant to give everyone access to a great chat based large language model. 
>
> We believe that by doing this we will create a revolution in innovation in language. In the same way that stable-diffusion helped the world make art and images in new ways we hope Open Assistant can help improve the world by improving language itself.

## Requirements

### GUI
- Windows 7 and above
- macOS 10.15 and above
- Debian (Ubuntu 18.04 and above or equivalent)
- Please see [Tauri Supported Platforms](https://github.com/tauri-apps/tauri#platforms) for more information

### Local chat

#### CPU

- Same as [GUI](#gui)
- Ram dependant on model used

#### GPU

  - Nvidia CUDA 11.7 and above (Linux, Windows)
  - Amd ROCm 5.4.2 and above (Linux only)
  - Metal (macOS 12.3+ with Apple Silicon or AMD GPUs)
  - GPU vram dependant on model used

## Installation


## Development

[Rust](https://github.com/rust-lang/rust)

### Local GUI

- [Tauri](https://github.com/tauri-apps/tauri)
- Modified Web UI from [Open Assistant Website](https://github.com/toiletpapercode/Open-Assistant/tree/main/website)

### Backend

- [Open Assistant compatible API](https://github.com/toiletpapercode/Open-Assistant/tree/main/backend)

### Model Inference

  - [rust-bert](https://github.com/toiletpapercode/rust-bert)
  - [tch-rs](https://github.com/toiletpapercode/tch-rs)
  - [LibTorch 1.13 / 2.0](https://pytorch.org/cppdocs/installing.html)

### Models 

- [Open Assistant](https://github.com/LAION-AI/Open-Assistant)