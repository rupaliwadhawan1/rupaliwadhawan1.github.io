---
date: 2021-01-05 05:20:35 +0300
title: Starbucks Voice-Ordering System
subtitle: NLP, Machine Learning and Frontend
image: /uploads/screenshot-2024-02-17-at-5-13-56-pm.png
---
**Approach**<br>The Starbucks voice ordering project is designed to revolutionize the way customers interact with the drive-thru kiosk. By integrating advanced Long Short-Term Memory Networks (LSTMs) into the system, the project leverages its superior ability to process and understand continuous speech. This is critical in accurately interpreting customer commands in a real-world environment. The LSTM's architecture, with its intricate system of gates, is adept at maintaining context over long sequences, thus ensuring that spoken sentences are recognized and correctly understood. This significantly enhances the user experience, enabling efficient and accurate voice-based ordering at Starbucks drive-thrus. The project architecture seamlessly integrates this technology with a Flask backend server, which effectively communicates with a database containing the menu to fulfill customer orders.

**Problem Solved**<br>Starbucks needs to tackle both cost savings and store expansion through drive-through stores. Utilizing machine learning to automate the voice ordering process within drive-throughs provides them a competitive advantage while strengthening the two priorities of cost savings and store expansion from their Triple Shot Reinvention Plan.

![](/uploads/picture1.png)

**Tools**

* speech\_recognition: For converting spoken words to text.
* gTTS (Google Text-to-Speech): For converting text into spoken audio files.
* pygame: For audio playback of spoken feedback to the user.
* Flask for the web app
* spacy: For advanced Natural Language Processing (NLP), used to parse and understand spoken orders.
* HTML/CSS/Javascript for the frontend application