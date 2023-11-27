# Speech Recognition Project: Intent Detection

## Introduction

Intent detection is a crucial task in the field of natural language processing (NLP) and speech recognition. It involves identifying the underlying intention or purpose of a spoken or written statement. This task is particularly important in the development of voice assistants and other audio-based applications, as it allows the system to understand and respond appropriately to the user’s requests and commands.

## Project Goal

For this project, the focus will be on an intent detection problem: given an input audio sample, the goal is to predict both the action requested and the object that is affected by the action. This requires the development of a model that can not only understand the spoken words but also infer the intended actions and associated objects.

By successfully addressing this intent detection challenge, the project aims to contribute to the advancement of voice assistants and audio-based applications, enhancing their usability and providing users with a more satisfying and efficient experience.

## Proposed Approach
The proposed approach consists in extracting the mel-frequency cepstrum for each audio signal and split it into a specific number of chunks. Using the mean and resizing the different matrices to a common shape we were able to provide an input for two classification models. The proposed approach achieves good results and outperforms the baseline proposed for the project.

<img width="496" alt="Image_1" src="https://github.com/zari19/Intent-Detection-and-Speech-Recognition/assets/144258993/7d69c887-4869-46db-ba13-71121e7c1adc">
