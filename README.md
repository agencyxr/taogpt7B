# TAOGPT-7B

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contributors](#contributors)

## Introduction

TAOGPT-7B is an exciting project at the intersection of technology and the cutting-edge field of Tao Science. Tao Science is a relatively new and uncharted area of scientific exploration, which poses a unique challenge for Language Model Models (LLMs) like Mistral 7b. These models have been primarily trained on conventional data, and Tao Science's unexplored territory requires specific tuning to provide valuable insights and information.

In this project, we aim to address this challenge by fine-tuning Mistral 7b on data related to Tao Science. By doing so, we intend to make this LLM more adept at understanding and generating content in this novel field. To further enhance the performance and utility of TAOGPT-7B, we have implemented a Retrieval Augmentation pipeline. This pipeline ensures that the results are not only generated from the fine-tuned model but are also enriched through relevant information retrieval.

## Getting Started

To get started with TAOGPT-7B, you can fine-tune Mistral 7b on Tao Science related data and perform inference using the provided Colab notebooks. Click on the following links to access the respective notebooks:

- Fine-Tuning Mistral7b with TaoScience Dataset on Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agencyxr/taogpt7B/blob/main/finetuning.ipynb)
- Fine-Tuning Mistral7b- with TaoScience Dataset : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agencyxr/taogpt7B/blob/main/finetuning_instruct.ipynb)
- Inference on Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agencyxr/taogpt7B/blob/main/inference.ipynb)

## Project Structure

Taogpt7b is organized into several key components to facilitate fine-tuning, data preparation, and inference:

- **Data**:
  - `/unstructured`: Contains unstructured data in the form of PDFs related to Tao Science.
  - `/structured`: Houses datasets extracted from the provided PDFs.

- **Data Preparation**:
  - `dataprep.ipynb`: This notebook plays a crucial role in the project by converting unstructured data into a structured format. It also stores this data in a vector database for efficient retrieval and integration with the fine-tuned model.

- **Fine-Tuning**:
  - `finetuning.ipynb`: This notebook focuses on the supervised fine-tuning of Mistral 7b using the Tao Science data. The resulting model is then pushed to the model hub, making it readily accessible for inference and interaction.

- **Inference**:
  - `inference.ipynb`: In this notebook, you can test the fine-tuned model's capabilities with RAG (Retrieval-Augmented Generation) using Gradio to create an interactive user interface.

## Technologies Used

- **Language Model Model (LLM)**: Mistral 7b serves as the foundation of our project, fine-tuned to cater to the specific needs of Tao Science.

- **Langchain**: Langchain is used for orchestrating the various components of the project, ensuring seamless integration and flow.

- **Transformers Library**: This library provides the necessary tools for working with LLMs, including inference and fine-tuning.

- **Weaviate**: Weaviate is employed as the vector store for efficient data retrieval, enabling the retrieval augmentation pipeline.

- **Gradio**: Gradio is used to create a user-friendly and interactive interface for testing the fine-tuned model and engaging with Tao Science content.


## Contributing

We welcome contributions to Taogpt7b. If you'd like to contribute to the project, please read our [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

### Contributors
<a href="https://github.com/agencyxr/taogpt7B/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=agencyxr/taogpt7B" />
</a>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
