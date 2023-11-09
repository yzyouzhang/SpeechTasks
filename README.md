# SpeechTasks
This is a list of speech tasks and datasets, which can provide training data for Generative AI, AIGC, AI model training, intelligent speech tool development, and speech applications.

## Tasks

|Task|DataSets|Input Mode|Output Mode|Modeling Target|Level|Description|
| :-----|:----- |:----- |:----- |:----- |:----- |:----- |
|Accent Classification|[AccentDB Extended Dataset](https://accentdb.org)|Audio|Label|Classification|Accent|Accent classification involves the recognition and classification of specific speech accents.The task involves the recognition and classification of specific speech accents. The possible answers include American, Australian, Bangla, British, Indian, Malayalam, Odiya, Telugu, or Welsh. The objective is to correctly identify these accents based on the given speech samples, contributing to a system's ability to understand and interact with various speakers.|
|Dialogue Act Classification|[DailyTalk Dataset](https://github.com/keonlee9420/DailyTalk)|Audio|Label|Classification|Act|Dialogue act classification aims to identify the primary purpose or function of an utterance within its dialogue context.The aim of this task is to identify the action in the audio. The possible answers could be *question*, *inform*, *directive*, or *commissive*. These identification tasks are important, as dialogue acts are central to understanding human conversation and dialogue-based AI system communication.|
|Dialogue Act Pairing |[DailyTalk Dataset](https://github.com/keonlee9420/DailyTalk)|Audio, Label|Binary Label|Binary Classification|Act|Dialogue act pairing involves assessing the congruence of dialogue acts—that is, whether a response dialogue act is appropriate given a query dialogue act. The objective is to determine whether a given dialogue act pairing is congruent or not. The answer could either be true or false. Being able to accurately judge the appropriateness of dialogue acts is key for a universal speech model to understand and participate in human conversations effectively.|
|Dialogue Emotion Classification |[DailyTalk Dataset](https://github.com/keonlee9420/DailyTalk)|Audio|Label|Classification|Emotion|Dialogue emotion classification is a task that assesses an AI model's ability to identify the most suitable emotion in a given dialogue extract. The main goal of this task is to correctly identify the communicated emotion in an audio clip. Possible answers include anger, disgust, fear, sadness, happiness, surprise, or no emotion. It is an evaluation of the model's capacity to interpret and distinguish emotions conveyed through speech, accounting both for linguistic content and paralinguistic indicators.|
|Emotion Recognition |[Multimodal EmotionLines Dataset](https://affective-meld.github.io/)|Audio|Label|Classification|Emotion|Emotion recognition aims to identify the most appropriate emotional category for a given utterance.Recognizing the emotion expressed in an utterance can be quite challenging. While we can sometimes identify emotion from the linguistic content alone, the more important factors often lie in paralinguistic features — like pitch, rhythm, and other prosodic elements. For a universal speech model, understanding these paralinguistic features is crucial, as they distinguish speech from mere text in a significant manner.|
|Enhancement Detection |[LibriTTS-TestClean](https://huggingface.co/datasets/DynamicSuperb/EnhancementDetection_LibriTTS-TestClean_WHAM)|Audio|Binary Label|Binary Classification|Acoustic|Enhancement detection is a task focused on determining whether a given audio has been created or modified by a speech enhancement model. The objective of enhancement detection is to ascertain if an audio file has been created or altered by a speech enhancement model. The expected answer is either yes or no. The task poses a challenging problem because the speech model must not only process the content of the speech but also detect minute modifications that might indicate enhancement. |
|HowFarAreYou  |[3DSpeaker Dataset](https://github.com/alibaba-damo-academy/3D-Speaker)|Audio|Scalar|Regression|Acoustic|The HowFarAreYou task aims to determine the distance of the speaker from the source of sound. The task's goal is to ascertain the approximate distance of a speaker, based on the provided audio or speech. The task's response could be an exact value, such as 0.4m, 2.0m, or 4.0m, indicating the speaker's distance from the sound source. Gauging the speaker's distance provides insights into the audio's spatial characteristics, which forms a crucial aspect of auditory scene analysis. |
|Intent Classification  |[FluentSpeechCommands Dataset](https://fluent.ai/fluent-speech-commands-a-dataset-for-spoken-language-understanding-research/)|Audio|Sequence Label|Classification|Intent|Intent classification aims to identify the actionable item behind a spoken message. The objective of this task is to understand and categorize the intent performed by a spoken message. The recognized actions can vary, including activate, bring, change language, deactivate, decrease, or increase. Identifying the intent accurately is pivotal for building reliable speech-based applications and interfaces. We categorize this task into three types: Action, Location, and Object.|
|Language Identification |[VoxForge Dataset](https://www.voxforge.org/)|Audio|Label|Classification|Language|Language Identification task is aimed to determine the language spoken in a given speech recording. The main goal of this task is to identify the language spoken in a specific speech recording. This is an essential part of speech processing, as it facilitates the understanding and translations for different languages. The language spoken could be German, English, Spanish, Italian, Russian, or French.|
|MultiSpeaker Detection |[LibriSpeech-TestClean Dataset](http://www.openslr.org/12/),[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)|Audio|Binary Label|Binary Classification|Speaker|MultiSpeaker Detection aims to analyze the speech audio to determine whether there is more than one speaker present in it. The core objective of this task is to analyze the speech audio for the presence of more than one speaker. It is crucial for a universal speech model to detect this as the presence of multiple speakers can alter the context and understanding of the spoken content.|

