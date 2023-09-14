# MODEL MERGING FOR SPEAKER INTERPOLATION IN SPEECH SYNTHESIS

**Paper**: [arxiv]()  
**Authors**: Masato Murata, Koichi Miyazaki, Tomoki Koriyama  
**Affiliation**: CyberAgent, Inc., Japan  

**Abstract**: A model merging method in generative tasks, which simply averages parameters from two base models, has attracted attention because of its simpleness and capability to generate intermediate features. 
In this study, we apply the model-merging method to text-to-speech (TTS) for speaker interpolation, which generates a speaker with an intermediate attribute (i.e., mid-attribute). 
This method is easily applicable without additional training, as it utilizes only two single-speaker base models, regardless of the model architecture. 
To investigate the effect of the base model training strategies, we conduct objective and subjective evaluations of the output of the merged model derived from two base models trained with various training strategies, such as initialization with shared/individual parameters and optimization from scratch/pretrained models. 
Our experimental results show that only the merged model of two models fine-tuned from the same pretrained model (fine-tuning-based merging) can generate speech with mid-attribute speaker characteristics without significant deterioration. 
We also found that the parameters of both the merged and base models are distributed in a close position in parameter space, indicating that this is the reason for the success of the model merging speaker interpolation. 
Moreover, we investigated the robustness of model merging using diverse base speaker combinations.

## Speech Samples
