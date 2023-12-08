DialogFlowtter is a package that helps you to build integrations with DialogFlow easier and faster.

    Authenticate with Google Auth Json
    Get an authenticated http client so you can talk with your DialogFlow agent
    Get access to all DialogFlow responses and models easily
    Inspect what values a DialogFlow response could have


## Features

This package is fully supported in Android, iOS and Web. We have plans on testing and adding support for Windows, Linux and MacOS as this platforms mature in the Flutter SDK.

## Getting started

Every time you instanciate DialogFlowtter, the class creates an authenticated http client, with the credentials obtained from the DialogFlow Auth JSON.

## Usage

 `/example`

```dart
 
  IconButton(
    color: Colors.white,
    icon: Icon(Icons.send),
    onPressed: () {
      sendMessage(_controller.text);
      _controller.clear();
      },
  ),

```

## Additional information

    Add support for null safety
    Add support for cards, images, etc.
    Memory, file and remote auth JSON
    Secure DialogFlow auth JSON
    Support audio queries
    Add a catalog of supported languages
    Add direct access to common used attributes
    Support use of custom HTTP Client

