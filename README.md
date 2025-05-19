## Overview

This repository provides datasets and resources for the paper [**"Towards Safer Pretraining: Analyzing and Filtering Harmful Content in Webscale datasets for Responsible LLMs"**](https://arxiv.org/pdf/2505.02009). The datasets are curated to support research on safer and more responsible pretraining of language models.

For now, we open source a sample (50 samples) of our datasets (TTP-Eval & HAVOC). We will share the entire sets soon.

## Folder Structure

```
TowardsSaferPretraining/
├── data/
│   ├── [README.md]/
│   ├── [HAVOC]/
│   └── [TTP-Eval]/
├── prompts/
│   └── [HAVOC]/
│   └── [TTP]/
├── LICENSE
└── README.md
```

- **data/**: Contains the datasets used in the paper.
- **prompts/**: Includes prompts used for creating TTP and HAVOC.
- **LICENSE**: License information for the datasets and code.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/themendu/TowardsSaferPretraining.git
    cd TowardsSaferPretraining
    ```
2. Review the `data/README.md` for dataset details and usage instructions.
3. Use the prompts folder in case you need to evaluate TTP. The prompts are styled in Open AI's ChatML Format.
4. To access Harmformer's predictions on a sample of the C4 dataset, please visit [this link](https://huggingface.co/datasets/themendu/SafeC4Sample).

## License

See the [LICENSE](./LICENSE) file for details.

## Contact

For questions or contributions, please open an issue or contact the maintainers.