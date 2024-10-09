# LLM Evaluation guidebook

Links prefixed by ⭐ are links I enjoyed and recommend reading.

## How to read this guide
- **Beginner user**
  If you don't know anything about the topic, you should read the  `Basics` sections in each chapter, and explore the sections that interest you. 
  You'll also find explanations to support you about important LLM topics in `General knowledge`: for example, how model inference works and what tokenization is.
- **Advanced user**
  The more practical sections are the `Tips and Tricks` ones, and `Troubleshooting` chapter. 
  You can likely skip all `Basics` sections and the `General knowlege` chapter.

## Table of contents

### Intro
I'll add this section later, but if you want an intro on the topic, you can read this [blog](https://huggingface.co/blog/clefourrier/llm-evaluation) on how and why we do evaluation!

### Automatic benchmarks
- [Basics](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Automated%20benchmarks/Basics.md)
- [Designing your automatic evaluation](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Automated%20benchmarks/Designing%20your%20automatic%20evaluation.md)
- [Some evaluation datasets](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Automated%20benchmarks/Some%20evaluation%20datasets.md)
- [Tips and tricks](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Automated%20benchmarks/Tips%20and%20tricks.md)

### Human evaluation
- [Basics](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Human%20evaluation/Basics.md)
- [Using human annotators](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Human%20evaluation/Using%20human%20annotators.md)

### LLM-as-a-judge
- [Basics](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Model%20as%20a%20judge/Basics.md)
- [Getting a Judge-LLM](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Model%20as%20a%20judge/Getting%20a%20Judge-LLM.md)
- [Designing your evaluation prompt](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Model%20as%20a%20judge/Designing%20your%20evaluation%20prompt.md)
- [Evaluating your evaluator](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Model%20as%20a%20judge/Evaluating%20your%20evaluator.md)
- [Tips and tricks](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Model%20as%20a%20judge/Tips%20and%20tricks.md)

### General knowledge
These are mostly beginner guides to LLM basics, but will still contain some tips and cool references! 
If you're a advanced user, I suggest skimming to the `Going further` sections.
- [Model inference and evaluation](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/General%20knowledge/Model%20inference%20and%20evaluation.md)
- [Tokenization](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/General%20knowledge/Tokenization.md)

### Troubleshooting
The most densely practical part of this guide. 
- [Troubleshooting inference](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Troubleshooting/Troubleshooting%20inference.md)
- [Troubleshooting reproducibility](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/Troubleshooting/Troubleshooting%20reproducibility.md)

## Planned next articles
- contents/Automated benchmarks/Metrics -> Description of automatic metrics
- contents/Introduction: Why do we need to do evaluation?
- contents/Troubleshooting/Troubleshooting ranking: Why comparing models is hard

## Resources
Links I like
- [About evaluation](https://github.com/huggingface/evaluation-guidebook/blob/main/resources/About%20evaluation.md)
- [About NLP](https://github.com/huggingface/evaluation-guidebook/blob/main/resources/About%20NLP.md)

## Thanks
This guide has been heavily inspired by the [ML Engineering Guidebook](https://github.com/stas00/ml-engineering) by Stas Bekman! Thanks for this cool resource!

Many thanks also to all the people who inspired this guide through discussions either at events or online, notably and not limited to Moritz Hardt (Max Planck Institute), Luca Soldaini, Kyle Lo and Ian Magnusson (Allen AI), Ludwig Schmidt (Anthropic), Max Bartolo (Cohere), Kai Wu (Meta), Swyx and Alessio Fanelli (Latent Space Podcast), Hailey Schoelkopf (EleutherAI), as well as people at Hugging Face, like Lewis Tunstall, Omar Sanseviero, Arthur Zucker, Hynek Kydlíček, Guilherme Penedo and Thom Wolf, without forgetting of course the evaluation team with Nathan Habib and Alina Lozovskaya.

## Citation
@misc{fourrier2024evaluation,
  author = {Fourrier, Clémentine},
  title = {LLM Evaluation Guidebook},
  year = {2024},
  journal = {GitHub repository},
  url = {https://github.com/huggingface/evaluation-guidebook)
}
