# Youtube-Transcript-Summarizer
Just provide the link to the youtube video on colab and download its summary.
For a UI experience I've provided jupyter code also (which doesn't includes summarization code)

Algorithm :
1. Extract transcript using ytapi
2. Summarize the transcript using pipelines.
3. Translate the summary into various dialecs using google translator
4. Audio output using gTTS
5. For UI I've used tkinter
