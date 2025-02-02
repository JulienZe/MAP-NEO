# MAP-NEO: A fully open-sourced Large Language Model
<div align="center">
    <p>
    <b>MAP-NEO</b> is a <b>fully open-sourced</b> Large Language Model that includes the pretraining data, a data processing pipeline (<b>Matrix</b>), pretraining scripts, and alignment code. It is trained from scratch on 4.5T English and Chinese tokens, exhibiting performance comparable to LLaMA2 7B. The MAP-Neo model delivers proprietary-model-like performance in challenging tasks such as reasoning, mathematics, and coding, outperforming its peers of similar size. For research purposes, we aim to achieve full transparency in the LLM training process. To this end, we have made a comprehensive release of MAP-Neo, including the final and intermediate checkpoints, a self-trained tokenizer, the pre-training corpus, and an efficient, stable optimized pre-training codebase. 
    </p>
    <p>
    <img src="figure/map-neo-bold.jpg" alt="SLAM-LLM Logo" style="width: 200px; height: auto;">
    </p>
    <p>
    </p>
 <div align="center">
 <a href="https://github.com/multimodal-art-projection/MAP-NEO" target="_blank">
    <img alt="Homepage" src="figure/map-logo-c.svg" style="width: auto; height: 20px;"/>
</a>
  <a href="https://github.com/multimodal-art-projection/MAP-NEO"><img src="https://img.shields.io/badge/HomePage-MAP%20NEO-orange" alt="version"></a>
  <a href="https://huggingface.co/collections/m-a-p/neo-models-66395a5c9662bb58d5d70f04" target="_blank">
    <img alt="Hugging Face" src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-MAP%20NEO-ffc107?color=ffc107&logoColor=white" />
  </a>

</div>
  <a href="https://discord.com/invite/qeRsjRdRHf" target="_blank">
    <img alt="Discord" src="https://img.shields.io/badge/Discord-MAP%20NEO-7289da?logo=discord&logoColor=white&color=7289da" />
  </a>
  <a href="figure/Wechat_QR.jpg" target="_blank">
    <img alt="Wechat" src="https://img.shields.io/badge/WeChat-MAP%20NEO-brightgreen?logo=wechat&logoColor=white" />
  </a>
  <a href="https://twitter.com/GeZhang86038849/status/1788874345927889203" target="_blank">
    <img alt="Twitter Follow" src="https://img.shields.io/badge/Twitter-MAP%20NEO-lightgrey?logo=x&logoColor=white" />
  </a>
    <a href="https://github.com/multimodal-art-projection/MAP-NEO"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="mit"></a>
</div>


## Evaluation Results
### MAP-NEO 7B Base

We evaluate MAP-NEO 7B on various benchmarks, as shown in the following.

<p align="center">
<img src="figure/base_eval_results.jpg" alt="table" width="50%">
</p>


## Model & DATA Downloads

We are pleased to announce the public release of the MAP-NEO 7B, including base models and a serious of intermedia checkpoints. This release aims to support a broader and more diverse range of research within academic and commercial communities. Please **note** that the use of this model is subject to the terms outlined in [License section](#license). Commercial usage is permitted under these terms.  

### Huggingface

|         Model         |                                 Download                                 |
|:---------------------:|:-----------------------------------------------------------------------:|
| MAP-NEO 7B Base       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_7b)  |
| MAP-NEO 7B intermedia       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_7b_intermediate)  |
| MAP-NEO 7B decay       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_7b_decay)  |
| MAP-NEO 2B Base       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_2b_general)  |
| MAP-NEO scalinglaw 980M       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_scalinglaw_980M)  |
| MAP-NEO scalinglaw 460M       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_scalinglaw_460M)  |
| MAP-NEO scalinglaw 250M       | 🤗 [HuggingFace](https://huggingface.co/m-a-p/neo_scalinglaw_250M)  |
| MAP-NEO DATA Matrix   | 🤗 [HuggingFace](https://huggingface.co/datasets/m-a-p/Matrix)  |
## License
This code repository is licensed under the MIT License. 

## Contact


For further communications, please scan the following WeChat and Discord QR code:

<table>
  <tr>
    <td>WeChat </td>
    <td>Discord </td>
  </tr>
  <tr>
    <td><img src="figure/Wechat_QR.jpg" alt="WeChat QR Code" width="200"/></td>
    <td><img src="figure/discord.jpg" alt="Discord QR Code" width="200"/></td>
  </tr>
</table>
