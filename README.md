
## Project Overview
This project is an integration of web development and the very emerging technology, Machine Learning. This Project aims to provide summarized documentation of a video that are too long to be watched. Today education is more dependent on online sources rather than the offline source, and no one has much time to spent on lecture videos that are too long to watch. So, to resolve this, there should be a tool which can provide a summarization of the video and therefor save time.

## Problem and Solution Statement
Enormous number of video recordings are being created and shared on the YouTube throughout the day. It becomes really difficult to spend time in watching such videos which may have a longer duration than expected and sometimes our efforts may become futile if we aren’t able to find relevant information out of it. Summarizing transcripts of such videos will allows us to quickly look out for the important patterns in the video and helps us to save time and efforts to go through the whole content of the video.

## Implementation strategy
So basically, it will be a chrome extension, having an option to copy to current URL of the video being selected. After providing the link, it will access the transcript of the particular audio using the YouTube transcript API and then the transcript will be provided to a machine learning model will in return provide the summarized text of the transcript. The summarized text would be downloadable by the user.







## Features

- Multiple Langauage Support (Hindi,English,Gujarati,Braille)
- Runtime Text to Speech Conversion (English language Only)
- Get Transcripts of videos of any length.
- Get Summarization of video of any language.
- Downloadable Transcripts.


## Installation


```

1. To run the API, you need to set up a **Virtual Environment**. Go into *youtube-transcript-summarizer-api* folder, open command prompt and paste the following command.
```
python -m venv venv
```

2. Now that you got a Virtual Environment created, it's time to install all the **dependencies**. Use the following command.   
```
pip install -r requirements.txt
```
3. Now it's time to run the **API**.
```
python app.py
```
4. Now the API is set up to provide the response. Its time to start with **frontend**.
```
cd ..
cd youtube-transcript-summarizer-frontend
```
5. Install all the required **node modules**.
```
npm install
```
6. You are all set to run the frontend.
```
npm start
```

- [@Aditya_Ojha](https://github.com/ojhaadityaa)
