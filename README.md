# Job Application Tasks

This repository contains solution to all the tasks which were given to me as a part of the job application process.

## 01. Real-Time Transcription

The file ```[HuggingFace] Afiniti Task - Real-time Transcription.ipynb``` contains the code to the task given by Afiniti. The task was to create a system which would first perform speech to text STT on potentially an infinite stream of audio. No file saving was allowed; we could not take parts of the audio, save them and load for processing. We used the ```whisper-tiny``` model from the HuggingFace library for this task.

The second part of the task was to perform evaluation of the STT system. The evaluation was to be done on the basis of the WER (Word Error Rate), MER (Match Error Rate), and WIL (Word Information Lost). The evaluation was to be done on the basis of the ground truth and the output of the STT system.

The third part of the task was to use a query to search for answers in the transcript. The query was to be given in the form of a sentence. We used a question answering model to perform this task. The model used was the ```distilbert-base-uncased-distilled-squad``` model from the HuggingFace library.
