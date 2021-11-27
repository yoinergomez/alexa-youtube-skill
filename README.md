# alexa youtube skill
Play audio from YouTube videos or play video if it's supported

## Unofficial YouTube skill for Alexa
This project is a fork from https://github.com/ndg63276/alexa-youtube

## Requirements
* Python 3
* Google account to create a YouTube API key
* Alexa account to create a skill
* Amazon AWS account to create a lambda with this repository


## Usage
This project required several settings to work successfully

* [Create YouTube API key and alexa skill](https://www.youtube.com/watch?v=aU1BmeJP3o8)
* Create .zip with these instructions
```sh
find . -type f -name *~ -exec rm -rf {} \;
find . -type d -name __pycache__ -exec rm -rf {} \;
find . -type f -name *.py[cod] -exec rm -rf {} \;
find . -type f -name *\$py.class -exec rm -rf {} \;
zip -r function.zip *
```
* Create a lambda function uploading the `.zip` file from previous step
