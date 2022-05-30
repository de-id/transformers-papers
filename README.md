# transformers-papers
Papers club from the AI team in D-ID  - this time transformers from attention to vision lectures are in Hebrew
מועדון קריאת מאמרים שלנו - כל ההרצאות בעיברית 

## 1: **Transformers are worth your attention** [Attention is all you need](https://arxiv.org/abs/1706.03762) 
<details>
  <summary>The paper that started it all, introduction to the basic concept & comparison to previous methods like RNN. The transformer here has both encoder & decoder layers creating a seq2seq model</summary>
  1. Speaker - @matan-feldman
  2. [Slides](url)
  3. [Recording](url) password: 
  4. Tl;dr
     * With some
     * Sub bullets
</details>


| Transformers are worth your attention | Attention is all you need | 2017 | <details><summary>read why</summary>The paper that started it all, introduction to the basic concept & comparison to previous methods like RNN. The transformer here has both encoder & decoder layers creating a seq2seq model</details> | Feldman | zoom (K%32MLKi) | slides |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Transformers tricks -  Positional Encoding, Layer Norm, Residual Connections. In code! | The annotated transformer | 2017 | Going into depth into the various tricks used to make transformers work. Implementing a trnasformer without them would lead to poor results  | x | x | x |
| Visualizing Attention | Visualizing Attention in Transformer-Based Language Representation Models On the Relationship between Self-Attention and Convolutional Layers  | 2017 | Attention is useful for explainability too, we can see what the network is using for the task. In this lecture we will exammine visualizations of this in NLP & vision | x | x | x |
| BERT | BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding | 2018 | This model from Google used only encoders & achived state of the art on many NLP tasks | Leon | zoom (LW$8fQ6f) | slides |
| GPT | Language Models are Few-Shot Learners | 2020 | This model from OpenAI used only decoders & achived state of the art text generation. Its authors first didn't release it becuase they said it is too dangerous. It is now the backbone of Github Co-Pilot | x | x | x |
| Wav2Vec U | Wav-to-vec U - Unsupervised Speech Recognition | 2021 | this unsupervised model from Facebook, is able to learn language representations. we use the supervised version in our A2K input | Feldman | zoom (p.qE+Q59) | slides |
| DETR for object detection & segmentations | End-to-End Object Detection with Transformers | 2020 | Taking transformers even further to other CV tasks in this paper the autors from FacebookAI combine CNN with transformers to reduce some of the human prio needed in designing object detection & segmentation models | Tal | zoom (17K%NSf3) | slides |
| ViT | An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale | 2020 | Treats the image as a sentence of 16x16 patches words. The model acheives SoTA in classiciation tasks with significant less compute. with supervision from large scale images datasets | Alon | zoom (ve1VHEM=) | slides |
| CLIP | Learning Transferable Visual Models From Natural Language Supervision | 2021 | OpenAI model that learns two encoders from images &text & via contrastive learning achive SoTA result on image classification while increasing dramatically the robustness over previous methods. Using internet scraped data instead of expesive annotated datasets. | Amitay | zoom (^a1!1BJf) | slides |
| Preceiver | Perceiver IO: A General Architecture for Structured Inputs & Outputs | 2021 | Preceivers models use cross-attention & learned latent dictionaries to work on many modalities by reducing the self attention complexity. The authors demostrate that the model produces baseline results on many tasks | Or | zoom (Ba9DQ&Ef) | slides |
| Dall-E2 & Imagen  | Hierarchical Text-Conditional Image Generation with CLIP Latents | 2022 | DALL·E 2 is a new AI system that can create realistic images and art from a description in natural language from OpenAI. The model uses CLIP embedding & diffusion models to generate images from a text description. Google DeepMind also came up with a competing model called Imagen that argues for superior quality | Tal | zoom () | slides |
