# Powerful Text to Speech
This is an easy way to present your product and make your  website more attractive

### Installation

Optional: npm install content-reader


Easy to use.
add script and style sheet
```sh
<link rel="stylesheet" href="./app/src/css/text-to-speech.css">
<script src="./app/src/js/contentscript.js"></script>
```

Basic code example:
It needs an ID-tag to read the text area
```sh
<div id="yourId"> Your text or content  </div>
```
Create a button by using the OnClick function
button example:
```sh
<button type="button" onclick="speak(#yourId)"> Read this  </button> or
<div onclick="speak(#yourId)"> Read this  </div>
```
Create a button for change voice and control reading speed
```sh
<button data-toggle="modal" data-target="#play-setting"> Change voice </button> or
<div data-toggle="modal" data-target="#play-setting"> Change voice  </div>
```
