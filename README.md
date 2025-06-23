# Challenge Overview

We present a large-scale automatic speech recognition (ASR) corpus for Kinyarwanda, The dataset was created by Digital Umuganda and made possible through funding from the Gates Foundation. The data spans five high-impact domains—Health, Government, Financial Services, Education, and Agriculture—to support robust ASR model development in both conversational and formal contexts.

The challenge is structured around three progressive tracks that cater to different resource and expertise levels:

Track A – Small – 500 hours of fully transcribed Kinyarwanda speech

Across these tracks, participants will build, fine‑tune, and evaluate state‑of‑the‑art speech‑to‑text systems that advance accessibility, innovation, and research. The event welcomes researchers, students, startups, and hobbyists worldwide.

# Solution

We finetune Whisper-Large using the provided supervised data. We focus on 95% quantiles of data. From EDA, we can see that:
- 95% of audio files lie between 10s and 30s
- 95% of audio files are related to a handful of speaker voices

Model currently ranked #10 out of 100's of submissions, challenge due in 2 weeks.
