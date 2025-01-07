---
title: Free Music Downloader
emoji: 🎵
colorFrom: blue
colorTo: purple
sdk: docker
app_port: 7860
short_description: AI service for searching and downloading the free music.
---

# jio-savan-music-downloader

This app will download Jio-Savan music.

-   **Github repository**: <https://github.com/DeepakPant93/jio-savan-music-downloader/>
-   **Documentation** <https://DeepakPant93.github.io/jio-savan-music-downloader/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

## Installation

1. Initialize the repository if it's your first time:

    ```bash
    cd jio-savan-music-downloader
    make init-repo
    ```

2. Install dependencies using Poetry:

    ```bash
    make bake-env
    ```

3. Run the FastAPI server:

    ```bash
    make run
    ```

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.
