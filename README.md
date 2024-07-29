# ⏰ Scrumdinger App

[Read in Portuguese](https://github.com/francisdiasbr/Scrumdinger-app/blob/main/README.pt.md)

## ✨ About

Scrumdinger is an iOS app that helps teams manage their daily scrums. To help keep scrums short and focused, Scrumdinger uses visual and audio cues to indicate when and for how long each participant should speak. The app also displays a progress screen that shows the time remaining in the meeting and creates a transcript that users can refer to later.

With Scrumdinger you can:

- View the list of scheduled meetings on the main screen;
- Create new meetings: add all participants to a list, set the date and time of the meeting, choose a theme for the meeting, and view the meeting's history;
- Edit the meeting: change the title, duration, theme, and participants.

## ✨ Screens


| Meetings screen | Add a meeting screen |  Meeting details screen |
|:---------:|:---------:|:---------:|
| ![IMG_7924](https://github.com/user-attachments/assets/0cfc53b7-f6ce-4621-b510-2b7de87baa0d) | ![IMG_7934](https://github.com/user-attachments/assets/081ed4d9-7186-4762-b7ad-2173c26399b8) | ![IMG_7925](https://github.com/user-attachments/assets/d0b544f9-0a77-4e9a-862c-145c8fa8faf1) |

| Edit a meeting screen | Themes | Meeting screen |
|:---------:|:---------:|:---------:|
| ![IMG_7926](https://github.com/user-attachments/assets/e692c25e-fd86-4b8b-832e-4f256aa0b576) | ![IMG_7927](https://github.com/user-attachments/assets/2895ccf3-aef7-42a3-97d9-5f77d5e840fe) | ![IMG_7929](https://github.com/user-attachments/assets/9759e1bd-2d75-4f32-980f-6199e9ef1355) |


Here are the main screens of the application:

**Main Screen (Meetings Screen)**: On this screen, you can see all scheduled meetings, including details like the meeting name, number of participants, and the scheduled time, which will be equally divided among all participants.

**Add Meeting Screen**: This screen allows you to add a new meeting to the list of scheduled meetings.

**Meeting Details Screen**: Displays detailed information about the meeting, including attendees and meeting history.

**Edit Meeting Screen**: Allows editing of meeting information and attendees.

**Themes**: Choose from 16 different colors to visually represent your meeting.

**Meeting Screen**: Shows the meeting in progress, with a timer and sound cues.


## ✨ Features

#### Visual and Audio Cues
Visual Indicators: The app displays visual signals that indicate who should speak and for how long.
Audio Alerts: Sound alerts are used to signal the change of speakers and remind participants about the remaining time.

#### Progress Screen
The progress screen shows the total remaining time of the meeting and the time allocated for each participant.
It facilitates the visualization of the meeting's progress, helping to maintain focus and punctuality.

#### Transcription
The app generates a transcript of the meeting that can be referred to later.
Transcripts help record decisions, track actions, and provide a reference for future meetings.




## ✨ Project Structure
To implement Scrumdinger, we can follow a project structure that includes the following main components:

### Models
Scrum: Represents a daily scrum, containing details such as title, participants, and duration.
Participant: Represents each participant in the scrum, including name and allocated speaking time.

### Views
ProgressView: Displays the remaining time of the meeting and the time for each participant.
TranscriptionView: Displays the transcript of the meeting.

### ViewControllers
ScrumViewController: Controls the scrum logic, managing speaking time and switching between participants.
ProgressViewController: Controls the updating of the progress screen.
TranscriptionViewController: Manages the display and storage of the transcription.

### Visual and Audio Cues
Visual Cues: Implemented as animations or UI changes to indicate the current speaker.
Audio Cues: Implemented using AVFoundation to play alert sounds.











