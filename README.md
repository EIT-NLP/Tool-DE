# Tool-DE

<p align="center">
  <a href="https://arxiv.org/abs/2510.22670"><img src="https://img.shields.io/badge/Paper-arXiv-b31b1b.svg"></a>
  <a href="https://opensource.org/licenses/Apache-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-green.svg"></a>
  <a href="#code-coming-soon"><img src="https://img.shields.io/badge/Code-Coming%20Soon-orange.svg"></a>
  <a href="#models-coming-soon"><img src="https://img.shields.io/badge/Models-Coming%20Soon-blue.svg"></a>
</p>


## 📖 Introduction
Tool-DE is a new benchmark and framework that enhances tool retrieval by systematically enriching tool documentation using Large Language Models (LLMs).
Existing benchmarks (e.g., ToolBench, ToolACE, ToolRet) reveal a key bottleneck — incomplete and inconsistent tool documentation hinders retrieval quality.

<div align="center">
  <img src="assets/heatmap.png" alt="Visual Layer Analysis" width="80%">
  <p><em> Figure 1: Incomplete field coverage across the 35 tool-use datasets. </em></p>
</div>

To address this, Tool-DE introduces an LLM-driven document expansion pipeline that generates structured fields such as function_description, when_to_use, limitations, and tags.
We further release two models built upon this data:
- Tool-Embed – a dense retriever trained on 50k expanded documents
- Tool-Rank – an LLM-based reranker trained on 200k pairs

Tool-DE achieves new state-of-the-art results on both ToolRet and its own benchmark, setting a foundation for data-centric tool retrieval research.

## ✅ TODO List
- [ ] Release training & evaluation code
- [ ] Release benchmarks and models
- [ ] Release training datasets
- [ ] Provide documentation & usage examples

## 📚 Citation
```bibtex
@misc{lu2025tool-de,
      title={Tools are under-documented: Simple Document Expansion Boosts Tool Retrieval}, 
      author={Xuan Lu and Haohang Huang and Rui Meng and Yaohui Jin and Wenjun Zeng and Xiaoyu Shen},
      year={2025},
      eprint={2510.22670},
      archivePrefix={arXiv},
      primaryClass={cs.IR},
      url={https://arxiv.org/abs/2510.22670}, 
}
```
