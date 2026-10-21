 # Amharic Audio Quality Checker

​Final project for the Building AI course
​Summary
​The Amharic Audio Quality Checker is an AI-powered system designed to automatically evaluate the quality of Amharic speech recordings and their corresponding transcriptions. It identifies background noise, audio distortions, incomplete utterances, and transcription mismatches to assist reviewers and audio data platforms in maintaining high-quality datasets.
​Building AI course project
​Background
​In voice-recording and audio transcription workflows, human reviewers often spend significant time manually listening to audio files to verify quality. This process is time-consuming and prone to human inconsistency.
​This project solves three key problems:
​High volume of low-quality or noisy speech recordings submitted by users.
​Frequent mismatches between recorded audio and the provided script/transcription.
​Inefficient manual review processes for large Amharic speech datasets.
​As Amharic language AI technologies grow, having clean, accurately labeled speech data is essential. My motivation comes from seeing how automated quality checks can save reviewer time and improve dataset reliability.
​Data sources and AI techniques
​Data Sources
​Publicly available Amharic speech datasets (e.g., Common Voice Amharic).
​Synthetic audio samples with artificially added background noise (for training noise detection).
​Audio-text paired datasets for transcription accuracy alignment.
​AI Techniques
​Speech Feature Extraction: Extracting Mel-Frequency Cepstral Coefficients (MFCCs) and signal-to-noise ratio (SNR) to measure background noise.
​Automatic Speech Recognition (ASR): Utilizing pre-trained speech models (e.g., Wav2Vec2 or Whisper fine-tuned for Amharic) to align speech with transcribed text.
​Classification Models: Machine learning models (like Random Forest or Convolutional Neural Networks) to classify audio samples as "Pass", "Needs Review", or "Reject".
​How is it used?
​Upload: Audio contributors or platform users submit their Amharic audio recordings along with text transcripts.
​Automated Analysis: The AI checker runs background checks for noise levels, clipping, silence duration, and pronunciation alignment.
​Instant Feedback: The system assigns a quality score and flags specific issues (e.g., "High background noise at 0:05" or "Missing words in sentence").
​Reviewer Dashboard: Reviewers get a prioritized queue of flagged samples instead of having to review every single file manually.
​Users affected include audio platform contributors, language data reviewers, and researchers working on Amharic speech technology.
​Challenges
​Dialectal Variation: Variations in Amharic accents and regional dialects may falsely trigger alignment errors.
​Domain Limitations: The model does not fully replace human judgment for subtle emotional or context-specific speech nuances.
​Noisy Environments: Distinguishing between background noise and intentional background sounds remains challenging without clean training data.
​What next?
​Expand the system to support other Ethiopian local languages (such as Afaan Oromoo, Tigrinya, and Somali).
​Integrate a real-time recording interface that alerts users to noise while they are recording.
​Develop a lightweight mobile plugin for field audio collectors.
​Acknowledgments
​Building AI Course Team by Reaktor and the University of Helsinki.
​Mozilla Common Voice for open-source speech resources.
​Open-source speech recognition communities.
