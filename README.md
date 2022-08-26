# KhanomTan TTS v1.1

KhanomTan TTS (ขนมตาล) is an open-source Thai text-to-speech model that supports multilingual speakers such as Thai, English, and others.

KhanomTan TTS v1.1 is a YourTTS model trained on multilingual languages that supports Thai. We use Thai speech corpora, TSync 1* and TSync 2* [mbarnig/lb-de-fr-en-pt-12800-TTS-CORPUS](https://huggingface.co/datasets/mbarnig/lb-de-fr-en-pt-12800-TTS-CORPUS) to train the YourTTS model by using code from the 🐸 Coqui-TTS and remove the voice that have the license's problem (All voice that doesn't use CC-0 or public license) from model, so the model's license is apache-2.0.

Model: [https://huggingface.co/wannaphong/khanomtan-tts-v1.1](https://huggingface.co/wannaphong/khanomtan-tts-v1.1)

## Speakers
- Linda (English, female, [LJSpeech](https://keithito.com/LJ-Speech-Dataset/))
- Bernard (fr-fr, male, [m-ailabs](https://www.caito.de/2019/01/03/the-m-ailabs-speech-dataset/))
- Kerstin (x-de, female, [Rhasspy](https://github.com/rhasspy/dataset-voice-kerstin))
- Thorsten (x-de, male, [Thorsten](https://www.thorsten-voice.de/))

## Language
- th-th: Thai
- en: English
- fr-fr: French language
- pt-br: Portuguese
- x-de: Danish
- x-lb: Luxembourgish


*Note: Those are not complete corpus. We can access the public corpus only.
