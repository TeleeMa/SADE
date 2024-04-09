<div align="center">
<h3> An Examination of the Compositionality of Large Generative Vision-Language Models </h3>

[Teli Ma](https://teleema.github.io/)<sup>1</sup>, [Rong Li](https://rongli.tech/)<sup>1</sup>, [Junwei Liang](https://junweiliang.me/index.html)<sup>1, 2</sup>

<sup>1</sup> [AI Thrust, HKUST(GZ)](https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/information-hub/artificial-intelligence/), <sup>2</sup> [CSE, HKUST](https://cse.hkust.edu.hk/)

[[paper](https://arxiv.org/pdf/2308.10509.pdf)] [[homepage](https://teleema.github.io/projects/SADE/sade.html)]

</div>

## Abstract

With the success of Large Language Models (LLMs), many Generative Vision-Language Models (GVLMs) have been constructed via multimodal instruction tuning. However, the performance of GVLMs in multimodal compositional reasoning remains under-explored. In this paper, we examine both the evaluation metrics ( VisualGPTScore, etc.) and current benchmarks for evaluating the compositionality of GVLMs. We identify the syntactical bias in current benchmarks, which is exploited by the linguistic capability of GVLMs. The bias renders VisualGPTScore an insufficient metric for assessing GVLMs. To combat this, we first introduce a SyntaxBias Score, leveraging LLMs to quantify such bias for mitigation. A challenging new task is subsequently added to evaluate the robustness of GVLMs against inherent inclination toward syntactical correctness. Using the bias-mitigated datasets and the new task, we propose a novel benchmark, namely SyntActically DE-biased benchmark (SADE). Our study provides an unbiased benchmark for the compositionality of GVLMs, facilitating future research in this direction.


## Dataset Download

1. Download the [VG](https://drive.google.com/drive/folders/11dMtJByk7zmbQjV47PXVwfmakN3Gr5Ic), [VL-CheckList](https://github.com/om-ai-lab/VL-CheckList/blob/main/DATASETS.md), [COCO2014](https://cocodataset.org/#home), [Flickr30k](https://forms.illinois.edu/sec/229675), [Winoground](https://huggingface.co/datasets/facebook/winoground).

2. Download the positive and negative references of SADE from [here](https://drive.google.com/drive/folders/1TKFXHLIwetUPnD31gjgnMcll4wBJ1HaO?usp=sharing).

## License

MODE is released under the [MIT License](https://github.com/TeleeMa/MODE/blob/main/LICENSE).

## Citation

```bash
@article{ma2023examination,
  title={An Examination of the Compositionality of Large Generative Vision-Language Models},
  author={Ma, Teli and Li, Rong and Liang, Junwei},
  journal={arXiv preprint arXiv:2308.10509},
  year={2023}
}
```
