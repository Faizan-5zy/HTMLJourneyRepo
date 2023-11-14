# HTML Audio Player Example

This project demonstrates the usage of the HTML `<audio>` element to embed an audio player in a web page.

## Description

The HTML `<audio>` element is used to include audio content on a webpage. This example provides a simple audio player with controls to play, pause, adjust volume, and more.

    <audio controls>: This is the main <audio> element. The controls attribute adds a set of controls (play, pause, volume, etc.) to the audio player, allowing users to interact with the audio.

    <source src="/sample1.mp3" type="audio/mp3">: The <source> element is used to specify alternative audio files in different formats. In this case, it provides two sources for the audio player. If the browser doesn't support the first format (audio/mp3), it falls back to the second format (audio/ogg). The src attribute specifies the path to the audio file.

    <source src="/sample2.mp3" type="audio/ogg">: Another <source> element providing an alternative audio file in a different format.

    Your browser does not support audio files.: This text will be displayed if the browser doesn't support the <audio> element or any of the specified audio formats.

The user can interact with the audio player through the controls provided, allowing them to play, pause, adjust volume, and more. The browser will automatically choose the first supported audio format from the provided <source> elements.

### Attributes

- `<audio controls>`: The main `<audio>` element with the `controls` attribute to provide playback controls.

- `<source>`: Specifies alternative audio files in different formats.

    - `src`: Path to the audio file.
    
    - `type`: MIME type of the audio file.

- The text "Your browser does not support audio files." is displayed if the browser doesn't support the `<audio>` element or any of the specified audio formats.
- 

## Important Note

Ensure that the audio files and paths are correctly specified and that your server configuration supports serving audio files with the specified MIME types.

