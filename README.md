-- Used CNNs to identify simple emotions from multimodal data. Used softmax activation to find the confidence of each emotion.

-- Incorporated the Circumplex Model of Emotion (two axes of positivity/negativity and high intensity/low intensity) to map simple emotions to complex ones. Ex., [0.7 confidence sad]; [0.2 confidence anger]; [0.3 confidence calm]; [0.1, neutral], etc. == Regretful.

-- Fine-tuned an LLM to aid in crisis intervention and reduce miscommunication. Only a wrapper during the 24 hour hack.

-- When inputting audio/video/images, data is encrypted and only unencrypted for the moment it is used in the models.
