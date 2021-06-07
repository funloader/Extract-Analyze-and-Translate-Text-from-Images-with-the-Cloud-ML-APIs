## Extract-Analyze-and-Translate-Text-from-Images-with-the-Cloud-ML-APIs-Add-to-favorites-Help
The Cloud Vision API's text detection method to make use of Optical Character Recognition (OCR) to extract text from images. Then we'll learn how to translate that text with the Translation API and analyze it with the Natural Language API
* Creating a Vision API request and calling the API with curl

* Using the text detection (OCR) method of the Vision API

* Using the Translation API to translate text from your image

* Using the Natural Language API to analyze the text

* Create an API Key

## Create your Vision API request
In your Cloud Shell environment, create an ocr-request.json files, then add the code below to the file, replacing my-bucket-name with the name of the bucket you created. You can create the file using one of your preferred command line editors (nano, vim, emacs) or click the pencil icon to open the code editor in Cloud Shell:

* Add the ocr-request.json file

## Sending text from the image to the Translation API
The Translation API can translate text into 100+ languages. It can also detect the language of the input text. To translate the French text into English, all you need to do is pass the text and the language code for the target language (en-US) to the Translation API.

* First, create a translation-request.json file

## Analyzing the image's text with the Natural Language API
The Natural Language API helps us understand text by extracting entities, analyzing sentiment and syntax, and classifying text into categories. Use the analyzeEntities method to see what entities the Natural Language API can find in the text from your image.

* To set up the API request, create a nl-request.json file
