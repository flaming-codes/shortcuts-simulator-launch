<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/11635736/165845954-35d547f4-a99c-446c-b311-0b8172a85062.png" /></p>

<h3 align="center"><a align="center" href="https://www.icloud.com/shortcuts/14430ea52e5640d6bf5b6caf48d4df4e" aria-label="Link to shortcut">Shortcuts Simulator Launch</a></h3>
<h5 align="center">Launch a simulator on macOS with two clicks</h5>

<br/>
<br/>
<br/>

## About

This 'repo' contains the link to a completely editable **Shortcut** for macOS' **Shortcuts**-app. It allows you launch any simulator on your device w/o opening the terminal every time. This is super handy for my use case (testing web apps on various devices), so I thought it might help you, too!

Why is there no code in this repo? That's b/c Apple doesn't allow a real export of Shortcuts, only links to their locations where they're stored.

## Prerequisites

- macOS 12 or higher
- Xcode is installed and has been started at least once
- the `xcrun simctl` command has to be available on your device (should be after Xcode install)

## Usage

Simply import the Shortcut [from this iCloud-link](https://www.icloud.com/shortcuts/14430ea52e5640d6bf5b6caf48d4df4e). That's it! You can also run the shortcut from the Menu Bar. The Shortcut will check the simulators on your device, parse them into a list and then starts the one you selected.

Of course you can edit/duplicat the Shortcut once imported. By adding a simple second Javascript execution you could, for instance, only show iPads or Watches.

## Privacy

This automation uses JavaScript to parse the terminal's raw output as input. You don't need to run it as admin. No data other than the terminal's inital output of available simulators is used.

## Screenshots

| Description | Image |
| --- | --- |
| Overview | ![Screenshot 2022-04-28 at 22 57 52](https://user-images.githubusercontent.com/11635736/165845471-09c8e386-4eae-493f-ae57-b658f269116d.png) |
| Pinned to Menu Bar | ![Screenshot 2022-04-28 at 22 59 00](https://user-images.githubusercontent.com/11635736/165845555-e4b26c67-7f5c-43f8-afb3-2b27c85ebba1.png) |
