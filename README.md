# Amplify Fusion Speech API using Mistral Speech and Transcribe Services

An Amplify Fusion Speech REST API that leverages [Mistral speech and transcribe services](https://mistral.ai/solutions/speech/).

It has two main POST methods:

/transcribe - transcribes MP3 or WAV audio to text. Audio is uploaded using multipart/form-data
/speech - turns text into MP3 or WAV audio returned as Base64 encoded string. Voice can be configured

The API leverage Amplify Fusion Mistral Transcribe and Speech connectors

Also included is a sample web app for testing the APIs

## Getting Started

* Import Fusion project in Manager
* Configure connectors
* Activate the API