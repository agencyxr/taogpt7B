# TaoGPT-7B

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Project Structure](#project-structure)
4. [Technologies Used](#technologies-used)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contributors](#contributors)

## Introduction
TaoGPT-7B is a pioneering project blending technology with the innovative field of Tao Science. The objective is to fine-tune the Mistral 7B Language Model (LLM) on Tao Science data to enhance its proficiency in this novel area. A Retrieval Augmentation pipeline is implemented to enrich outputs with relevant information.

## Getting Started
To start with TaoGPT-7B, follow these steps:
- Fine-tune Mistral 7B on Tao Science data.
- Utilize the Colab notebooks for training and inference.

### Notebooks:
- [Fine-Tuning Mistral 7B with TaoScience Dataset](https://colab.research.google.com/github/agencyxr/taogpt7B/blob/main/finetuning.ipynb)
- [Instructed Fine-Tuning of Mistral 7B with TaoScience Dataset](https://colab.research.google.com/github/agencyxr/taogpt7B/blob/main/finetuning_instruct.ipynb)
- [Inference with TaoGPT-7B on Google Colab](https://colab.research.google.com/github/agencyxr/taogpt7B/blob/main/inference.ipynb)

## Project Structure
The project is structured into several components:
- **Data**:
  - `/unstructured`: Contains PDFs and unstructured data on Tao Science.
  - `/structured`: Datasets derived from PDFs.

- **Data Preparation**:
  - `dataprep.ipynb`: Transforms unstructured data into a structured format.

- **Fine-Tuning**:
  - `finetuning.ipynb`: Focuses on the supervised fine-tuning of Mistral 7B using Tao Science datasets.

- **Inference**:
  - `inference.ipynb`: Tests the capabilities of the fine-tuned model using RAG and Gradio for user interaction.

## Technologies Used
TaoGPT-7B employs various technologies:
- **Mistral 7B (LLM)**: Central model, tailored for Tao Science.
- **Langchain**: Ensures seamless project component integration.
- **Transformers Library**: Provides LLM fine-tuning and inference tools.
- **Weaviate**: Manages efficient data retrieval.
- **Gradio**: Creates an interactive interface for model engagement.

## Contributing
Contributions to TaoGPT-7B are appreciated. For contribution guidelines, see [CONTRIBUTING.md](CONTRIBUTING.md).

### Contributors
For a list of contributors, visit:
<a href="https://github.com/agencyxr/taogpt7B/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=agencyxr/taogpt7B" />
</a>

## License
TaoGPT-7B is under the MIT License. See [LICENSE.md](LICENSE.md) for more details.

