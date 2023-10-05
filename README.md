# An Extended Study of Human-like Behavior under Adversarial Training
Paul Gavrikov, Janis Keuper, Margret Keuper

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Presented at: Art of Robustness Workshop @ CVPR 2023

[Paper](https://openaccess.thecvf.com/content/CVPR2023W/AML/html/Gavrikov_An_Extended_Study_of_Human-Like_Behavior_Under_Adversarial_Training_CVPRW_2023_paper.html) | [ArXiv](http://arxiv.org/abs/2303.12669)


Abstract: *Neural networks have a number of shortcomings. Amongst the severest ones is the sensitivity to distribution shifts which allows models to be easily fooled into wrong predictions by small perturbations to inputs that are often imperceivable to humans and do not have to carry semantic meaning. Adversarial training poses a partial solution to address this issue by training models on worst-case perturbations. Yet, recent work has also pointed out that the reasoning in neural networks is different from humans. Humans identify objects by shape, while neural nets mainly employ texture cues. Exemplarily, a model trained on photographs will likely fail to generalize to datasets containing sketches. Interestingly, it was also shown that adversarial training seems to favorably increase the shift toward shape bias. In this work, we revisit this observation and provide an extensive analysis of this effect on various architectures, the common L2- and Linf-training, and Transformer-based models. Further, we provide a possible explanation for this phenomenon from a frequency perspective.*


[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

<!-- ![Hero Image]() -->


## Citation 

If you find our work useful in your research, please consider citing:

```
@InProceedings{Gavrikov_2023_CVPR,
    author    = {Gavrikov, Paul and Keuper, Janis and Keuper, Margret},
    title     = {An Extended Study of Human-Like Behavior Under Adversarial Training},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2023},
    pages     = {2360-2367}
}
```

### Legal
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].
