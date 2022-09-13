# Requirements

- Number: 1
- Statement: Software must Record a video
- Evaluation Method: Starting a recording and having a video saved when finished recording
- Dependency: None
- Priority: Essential
- Requirement revision history: 

-  Number: 2
- Statement: Must be able to ask user for authentication
- Evaluation Method: A prompt for authentication is presented during relevant actions
- Dependency: None
- Priority: Essential
- Requirement revision history: 

- Number: 3
- Statement: Software must run on android devices
- Evaluation Method: Testing using android emulator
- Dependency: None
- Priority: Essential
- Requirement revision history: 

- Number: 4
- Statement: Must have a video gallery
- Evaluation Method: Testing on Android. Videos can be selected, viewed, and deleted.
- Dependency: recording
- Priority: Essential
- Requirement revision history: 

- Number: 5
- Statement: Records while screen is off/device is locked
- Evaluation Method: Testing on Android.
- Dependency: recording, authentication
- Priority: high
- Requirement revision history: 

- Number: 6
- Statement: auto backup video to the cloud while recording
- Evaluation Method: Testing on Android. Test with some cloud storage service.
- Dependency: Recording, Gallery
- Priority: high
- Requirement revision history: 

- Number: 7
- Statement: watermark/authenticate video 
- Evaluation Method: Testing recordings and analyzing videos
- Dependency: recording, gallery
- Priority: (Assign a priority to this requirement: essential, high, middle, low, or if time permits.)
- Requirement revision history: 