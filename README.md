# SincerityTool4Email
An generative AI tool to check how sincere is your received email. Sincerity Index - how little the email used Generative AI and how much human effort is put in.

Sincerity from one man to another takes human effort.  With digital bots and Generative AI, sincerity in digital communications like email is questionable.  

Sincerity tool is a simple email content checker aim to rate the author sincerity.  

**Method:**
* Program based on user inputs on received email content
* Based on the email text content, using Gen AI to derive the email intent and Gen AI generate another 5 pesudo emails content
* Compare all the pesudo emails with original received email and compute the sincerity index
* Sincerity index = closer 1, likely not generated by Gen AI

**Note:**
* This project is still in experimental phase.  Hence, sincerity index accurancy is questionable.

Best run in Google's [Colab](https://colab.research.google.com/).

Demo video of this code can be found [here](https://youtu.be/OkGQ4uS4Wz4).

This project is based on Google's Gemini - [Gemini API: Quickstart with Python](https://ai.google.dev/tutorials/python_quickstart) and [Document Similarity with Examples in Python](https://www.linkedin.com/pulse/document-similarity-examples-python-rany-elhousieny-phd%E1%B4%AC%E1%B4%AE%E1%B4%B0-0i5lc/)
