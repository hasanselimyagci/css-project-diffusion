# Imagined Recollections: Exploring Memories of Forced Labor through AI-Generated Imagery

<p align="center">
    <img src="https://github.com/hasanselimyagci/css-project-diffusion/blob/main/overview.png">
  </p>

With the recent developments in generative forms of Artificial Intelligence (AI), it is vital to rethink our interaction with history, atrocities and memorialization. The digital media has already transformed the accessibility of memories through web archives of images, interviews and evidences. In this project, using the interview data available on digital Forced Labor archives, we investigated the capabilities of diffusion models to generate memory guided visual representations. Despite the limits of the model, the results showed promising results which potentially can help past atrocities be more accessible to young people and consequently increase awareness towards current labor exploitation and other rights and justice issues.

## Motivation

* Remembering mass atrocities and the importance of images for communicating the past
* Transformation in memorialization practices with technology and making the mass atrocity memories more accessible to young people
* Identifying influence of temporal, political and situational factors on narratives of atrocities
* Assessing capabilities of state-of-the-art AI models creating distorted images of reality

## Overivew 

Utilizing Generative AI models to construct visual representations of forced labor victims’ memories.

## Technical Aspects

For text analysis part, 
* Keyphrase and descriptive phrases extraction utilizing PoS tagging token classifier models

For image generation,
* Pretrained Stable Diffusion model for Text-to-Image (Further experiments with Image-to-Image model)
* Leveraging GPT model to generate better prompts given extracted keyphrases
* Prompt weighing and negative prompts to improve quality of images
* Further improving aesthetics and prompt-image alignment with implementing RL approaches

## Discussion and Findings

* Paucity of available data distorts the representation
* AI can promote false information concerning atrocities and enable propaganda
* Lack of ‘empathy’ in models can lead to feeling-ignoring content
* Training diffusion models are computationally expensive
* Remembering forced labor can help reflecting ideas to current rights and justice issues concerning labor exploitation
* AI can empower individuals who want to contribute to memorialization practices with limitless creativity (although limited through explicit list of banned prompts)
* Models trained on different language texts help us understand different narratives among cultures and memory politics


## References

[Interview Archive](https://archiv.zwangsarbeit-archiv.de/ "Forced Labor 1939-1945 Memory and History")
