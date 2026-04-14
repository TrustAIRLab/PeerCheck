# **PeerCheck**: Enhancing LLM-Generated Academic Reviews Towards Human-Level Quality

## Dataset Summary

**PeerCheck** is a framework for studying and improving the quality of LLM-generated academic peer reviews.

It contains both **human-written reviews** and **LLM-generated reviews** for the same research papers, enabling direct comparison between human and LLM-generated reviewers.

The dataset is used to support research on:
- LLM-generated peer review;
- Review quality evaluation;
- Human–LLM alignment in scientific assessment.

---

## Dataset Description

### Data Sources

The dataset is constructed from publicly available peer reviews collected from:

- ICLR 2024 / 2025
- NeurIPS 2024 (via OpenReview)

For each paper:
- Human-written reviews are collected;
- LLM-based reviews, including GPT-4o, Claude-3.7-Sonnet, and DeepSeek-V3, generate corresponding reviews.  

All data are processed to remove personal information and ensure quality.

---

## Limitations

- Focused on machine learning papers;  
- LLM-generated reviews may contain biases or inaccuracies; 
- Not intended to replace human peer review.

---

## Ethical Considerations

All data are collected from publicly available sources (OpenReview).  
Personal identifiers are removed or anonymized.
This study was reviewed and approved by the Ethics Review Board (No. 25-12-6) of our institution.

This dataset is intended **for research purposes only** and should not be used to automate real-world peer review decisions.

---
## Citation

If you use this dataset, please cite:

```bibtex
@article{peercheck2025,
  author={Zeyuan Chen and Ziqing Yang and Yihan Ma and Michael Backes and Yang Zhang},
  title= {{PeerCheck: Enhancing LLM-Generated Academic Reviews Towards Human-Level Quality}},
  booktitle = {{Findings of the Association for Computational Linguistics: ACL (ACL Findings)}},
  publisher = {ACL},
  year = {2026}
}
