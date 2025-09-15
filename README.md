# MoodScan--Tracks-mood-from-journal-entries-

Mood Tracker — Sentiment Analysis on Long-Form Text

Using Machine Learning + NLP to Understand Emotions Over Time

-Introduction-

I began tracking my mood to observe how daily choices and life events impacted me over time. Through this process, I discovered how vital it is to have a clear and accurate picture of emotional patterns — especially when reflecting on long-form journal entries.

This project is a result of that insight. I built a sentiment analysis tool using a Naive Bayes machine learning model, then extended its capability with Natural Language Processing (NLP) to better interpret and analyze long-form, nuanced text like journal entries.

-How It Works-

This application processes user-generated text and predicts the emotional sentiment. There are two versions of the model:

predict_emotion(x, nv_model)
The original Naive Bayes model used to analyze shorter, more direct input.

large_text_emotion()
A modified version designed to handle and interpret longer, more complex text. It breaks down the input, extracts meaningful features, and maps sentiment trends more effectively.

-To Use-

Change the Path
Make sure to modify the pathname in your script to correctly point to the training dataset you're using.

Run the Prediction

Use predict_emotion(x, nv_model) for basic sentiment predictions.

Use large_text_emotion() to analyze and interpret long-form text entries (like journal logs, essays, or conversations).

-Reflection-

While building this project, I quickly realized the challenges involved in using machine learning to classify human emotions — especially within long-form text. A single label or word often isn’t enough to capture the emotional complexity within a journal entry.

That led me to focus less on binary sentiment classification, and more on mapping the emotional journey within a piece of writing. The goal isn’t just to say “this is happy” or “this is sad,” but to recognize the nuances and shifts in feeling, allowing for more meaningful mood tracking over time.
