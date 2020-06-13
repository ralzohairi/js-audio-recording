# Audio Recording Demo using JavaScript and HTML
This project demonstrates the usage of a user-defined audio recording API in a website. The implementation is based on the explained audio recording API here[insert here]. The following is a screenshot of the demo's view.

<img src="https://github.com/ralzohairi/audio-recording-in-js/blob/master/images/main-view.png?raw=true"  width="600">


## Key Features
1. Audio Recording. <br/>
2. Stopping the Audio Recording, where the maximum recording duration is 1 hour. <br/>
3. Listening to the recorded audio played back once recording has stopped. <br/>
4. Canceling the Audio Recording. <br/>

## Getting Started
1. Clone the project. <br/>
2. Open index.html in your favorite browser, where now you can start enjoying the demo! <br/>

## Use Cases
* ### Starting the Audio Recording

To start the audio recording, the microphone icon must be clicked. Once the icon is clicked, the audio recording should get started, that is if the user grants permission and if no error has occurred.

 When the recording starts, the elapsed recording time is displayed alongside two buttons that allow stopping and canceling the ongoing audio recording. 

The following GIF image demonstrates starting the audio recording.<br/>  

![alt text](https://github.com/ralzohairi/audio-recording-in-js/blob/master/images/audio-recording-start.gif?raw=true)

* ### Stopping the Audio Recording

To stop the ongoing audio recording, the stop button should be clicked. Once the audio recording has successfully stopped, the audio is played back to the user.

The following GIF image demonstrates stopping the audio recording.<br/> 

![alt text](https://github.com/ralzohairi/audio-recording-in-js/blob/master/images/stoping-audio-recording.gif?raw=true)

* ### Cancelling the Audio Recording
To cancel the ongoing audio recording, the cancel button should be clicked.
The following GIF image demonstrates stopping the audio recording.<br/> 

![alt text](https://github.com/ralzohairi/audio-recording-in-js/blob/master/images/canceling-audio-recording.gif?raw=true)

* ### Starting the Audio Recording in a Browser that does not support the Audio Recording API
When the user attempts to start an audio recording in a browser that does not support the audio recording API, a message box will be displayed for the user to inform him why they cannot use the audio recording feature.

The following GIF image shows the message box displayed to the user.<br/> 

![alt text](https://github.com/ralzohairi/audio-recording-in-js/blob/master/images/audio-recording-not-supported.gif?raw=true)
