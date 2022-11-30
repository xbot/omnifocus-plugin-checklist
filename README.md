# omnifocus-plugin-checklist
Make OmniFocus as a checklist App.

![screenshot](assets/screenshot-01.gif)

## Features

- Maintain multiple checklist templates.
- Create a checklist in a single or multiple projects by selecting a pre-built template.
- Notes, Parallel and 'Complete with last action' properties and tags from the template are preserved while creating a checklist.

## Quick Start Guide

### Installation

Clone the repo and link it in the Automation Configuration dialog in OmniFocus, or add it as a git submodule to the default plugin folder of OmniFocus. I recommend the latter for an easier synchronization with other devices.

```shell
cd ~/Library/Mobile Documents/iCloud~com~omnigroup~OmniFocus/Documents/Plug-Ins

git init

git submodule add https://github.com/xbot/omnifocus-plugin-checklist.git checklist

# For updating:
git submodule update --remote --recursive
```

### Usage

- Create a folder for checklist templates.
- Create as many projects as you want under that folder, each project is considered as a checklist template.
- Set the folder as the template folder in the plugin's preferences dialog. (Click the menu item while holding the `Ctrl` key)
- Select an ordinary project and trigger the plugin action, then choose a template in the dropdown list and press the `Create` button.
