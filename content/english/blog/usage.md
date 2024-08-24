---
title: "Usage"
date: 2024-08-24T09:47:04+08:00
description: "This is meta description"
# save as draft
draft: false
---


# WeEat Android Client

## Description

The WeEat Android client is designed to interact with the WeEat backend to provide a user experience for managing food-related activities.

## Features

- Seamless integration with the WeEat backend REST API.
- Display food information and recommendations.
- Support for audio input and output for enhanced interaction.
- Image and video analysis for food recognition.

## Prerequisites

- Android Studio 4.2 or later.
- Android SDK with appropriate API levels.
- Internet permission for communicating with the backend.

## Installation

1. Clone the project repository.
2. Open the project in Android Studio.
3. Sync the project with Gradle to resolve dependencies.

## Usage

1. Launch the application on your Android device or emulator.

2. Obtain the API endpoint URL of the WeEat backend. This can be configured in the application's `setting` fragment, you can find it in the settings tab and modify the `Default host url` field and `Default user info` field.

<div style="text-align: center;">
    <img src="../settings.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">Settings</p>
</div>

1. Navigate at the bottom to the chats page and interact with llm via `text/image/voice` in the chats tab, you can press the bottom button to switch the input method.

<div style="text-align: center;">
    <img src="../llm.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">LLM</p>
</div>

1. Navigate at the bottom to the chats page and start a cooking clock in the clocks tab.

<div style="text-align: center;">
    <img src="../clock.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">Clock</p>
</div>

5. Navigate at the bottom to the chats page and handling your recipes in the recipes tab.

<div style="text-align: center;">
    <img src="../recipe.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">Recipe</p>
</div>

1. Navigate at the bottom to the overview page and check your stats.

<div style="text-align: center;">
    <img src="../overview.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">Overview</p>
</div>

7. Navigate at the bottom to the storage page and you can check if your stored food is expired or add new food.

<div style="text-align: center;">
    <img src="../storage_insert.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">Storage Insert</p>
</div>

8. Navigate at the bottom to the timeline page and view a timeline of food eaten this week before it expired.

<div style="text-align: center;">
    <img src="../timeline.jpg" alt="Alt text" width="300"  />
    <p style="margin-top: 10px; font-style: italic;">Timeline</p>
</div>

## Known Issues

- Some older Android devices may experience performance issues due to the complexity of image and video analysis.
- Network connectivity issues may affect the reliability of communicating with the backend.

## Contributing

If you wish to contribute to the WeEat Android client, please follow these steps:

1. Fork the repository => [WeEat](https://github.com/Renaissance0412/WeEat).
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure they are properly tested.
4. Submit a pull request with a clear description of your changes.