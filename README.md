# Multilingual-Image-Caption-Generation-for-Visually-Impaired
This Git repository contains code for a project titled "Multilingual Image Caption Generation for Visually Impaired." The project focuses on generating descriptive captions for images to aid visually impaired individuals, with an additional feature of multilingual translation of these captions.

Key Components
Image Feature Extraction:
Utilizes the VGG16 pre-trained model to extract visual features from images, which are then used as inputs for generating captions.
Text Preprocessing:
Cleans and preprocesses text data associated with image captions. This includes converting text to lowercase, removing special characters, and adding start and end tokens to signify the beginning and end of a caption sequence.
Caption Tokenization:
Tokenizes cleaned captions and prepares the data for training the caption generation model.
Caption Generation Model:
Implements a deep learning model comprising an encoder-decoder architecture with LSTM layers. This model learns to associate image features with their corresponding descriptive captions.
Training and Evaluation:
Trains the caption generation model using image features and corresponding tokenized captions. Evaluates the model performance using BLEU (Bilingual Evaluation Understudy) scores to assess the quality of generated captions.
Multilingual Caption Translation:
Integrates text translation functionality using the translate library to convert captions into different languages, enhancing accessibility for non-English speakers.
Text-to-Speech (TTS) Conversion:
Implements text-to-speech conversion using gTTS (Google Text-to-Speech) to generate audio output of translated captions, facilitating auditory accessibility.
Usage:
Training the Model:
Utilize the provided data generator to train the caption generation model using extracted image features and tokenized captions.
Generating Captions:
Use the trained model to generate descriptive captions for new images.
Multilingual Translation:
Leverage the translation functionality to convert captions into various languages to enhance accessibility.
Audio Output:
Generate and play audio files containing spoken translations of image captions for improved accessibility.
