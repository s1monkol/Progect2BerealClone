# Project 2 - BeReal Clone Pt. 1

Submitted by: **Semen Kolesnykov**

**BeReal Clone Pt. 1** is an iOS app that allows users to create an account, log in, and post images with captions to a shared feed. It mimics some of the core functionalities of the BeReal app, with backend support using Parse via Back4App.

Time spent: **~10 hours** spent in total

## Required Features

The following **required** functionality is completed:

- [x] Users see an app icon in the home screen and a styled launch screen.
- [x] User can register a new account
- [x] User can log in with newly created account
- [x] App has a feed of posts when user logs in
- [x] User can upload a new post which takes in a picture from photo library and an optional caption	
- [x] User is able to logout	

The following **optional** features are implemented:

- [x] Users can pull to refresh their feed and see a loading indicator
- [ ] Users can infinite-scroll in their feed to see past the 10 most recent photos
- [x] Users can see location and time of photo upload in the feed	
- [x] User stays logged in when app is closed and open again	

The following **additional** features are implemented:

- [x] Posts older than 24 hours are blurred until the user makes a new post
- [x] User can take a photo using the camera in addition to selecting from the library

## Walkthrough

⚠️ **Note:** The walkthrough is presented using Xcode screenshots instead of a simulator or video recording due to technical issues with running the iOS Simulator on the iMac in the FIU library. The app is fully functional and runs correctly on a physical device.

A full walkthrough with screenshots is available in the file:  
[`Semen_Kolesnykov_BeReal_Clone_Walkthrough.docx`](Semen_Kolesnykov_BeReal_Clone_Walkthrough.docx)

## Notes

- The main challenge was testing on a physical device due to lack of simulator support in the iMac environment.
- Initial Parse SDK integration required careful handling of async logic.
- Uploading and previewing images with `PHPickerViewController` and camera flow needed custom delegate handling.

## License

    Copyright 2025 Semen Kolesnykov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
