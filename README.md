# AI-powered meeting assistant app using Unbody and Appsmith

This repo demonstrates how to develop an AI meeting assistant app that processes video recordings from Google Meet, writes notes, captures action items, and generates summaries pf what was spoken. The app connects your [Google Drive](https://www.google.com/drive/) where all your Google Meet video recordings are saved and automatically captures meeting audio transcriptions and generates meeting notes with key points and action items in real-time. It also shows this data on [Appsmith](https://www.appsmith.com/) UI dashboard. [Unbody](https://unbody.io/) is used to retrieve meeting details such as video recordings or transcripts intelligently from Google Drive and deliver this information to query through GraphQL. Unbody uses LLMs to summarize key points from meetings, extract action items.

## One-click app showcase

Currently, the app is up and running on Appsmith Cloud. Navigate to this link to see the app:

https://app.appsmith.com/app/unbody-appsmith-graphql-showcase/report-6576eccbccfc99526bd6dbfc?branch=master

See how the app works:

![Unbody GraphQL Demo](/assets/Meeting%20Minutes%20Report%20v5.gif)

Read the following article to try out the project yourself:

[How to build a Google Meet AI assistant app in 10 minutes with Unbody & AppSmith](https://www.unbody.io/blog/gmeet-ai-assistant-appsmith)