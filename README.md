# Code Dispatcher Workflow for Alfred

## Overview

**Code Dispatcher** is an Alfred workflow designed to streamline your local development process. It allows you to quickly search for project folders inside a specified directory (default: `~/Sites`) and open them in your preferred code editor, Finder, or in your default browser using a custom TLD.

## Features

- **Search Folders**: Easily search for project folders within your designated directory.
- **Open in Code Editor**: Instantly open any project folder in your preferred code editor (default: Visual Studio Code).
- **Open in Finder**: Open the selected project folder directly in Finder.
- **Open in Browser**: Open the folder as a URL in your default web browser using a custom TLD (default: `.test`).

## Installation

1. Download the latest version from the [GitHub Releases page](https://github.com/graftechnology/alfred-code-dispatcher/releases).
2. Download and import the workflow into Alfred.
3. Configure your preferred settings in the Workflow Configuration section.

## Usage

Trigger the workflow by typing `code` followed by a space. Alfred will display a list of folders inside your configured directory. From there, you can:

- Press `Enter` to open the folder in your preferred code editor.
- Hold `Cmd` and press `Enter` to open the folder in Finder.
- Hold `Option` and press `Enter` to open the folder in your default web browser with the custom TLD.

## Customization

You can customize the workflow to suit your needs by modifying the following configuration options:

### Configuration Options

1. **Editor**:
   - Select your preferred code editor (default: Visual Studio Code).

2. **Directory**:
   - Specify the directory where your projects are located (default: `~/Sites`).

3. **TLD (Top-Level Domain)**:
   - Specify the custom TLD to be used when opening projects in the browser (default: `test`). For example, if the TLD is set to `test`, projects will open at `my-site.test`.

## Example

1. **Open a Project in VS Code**:
   - Type `code` in Alfred, select a project, and hit `Enter` to open the project in Visual Studio Code (or your preferred editor).

2. **Open a Project in Finder**:
   - Hold `Cmd` while selecting the project to open it in Finder.

3. **Open a Project in Browser**:
   - Hold `Option` while selecting the project to open `http://my-site.test` in your default web browser.

## Feedback

[Send us an email](https://graftechnology.com/contact/) with any feedback you have!

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. See the [LICENSE](https://github.com/graftechnology/alfred-code-dispatcher/blob/main/LICENSE) file for more details.

---

Created by [Graf Technology, LLC](https://graftechnology.com/).

### Restrictions
- You may not modify or redistribute modified versions of this project.
- This project may be used for personal or professional purposes, but it cannot be sold, resold, or used for any revenue-generating activities.
