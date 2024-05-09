# RAG-Powered Search and QA

## Introduction

This proof-of-concept project explores the use of Retrieval-Augmented Generation (RAG) to customize information delivery systems tailored to the specific needs of different user groups within an organization. By leveraging advanced AI techniques, the system dynamically adapts its responses to suit marketing and research teams, ensuring stylistic and contextual relevance.

## Goals

- To develop and demonstrate a proof-of-concept for an adaptive RAG system that tailors responses according to user personas.
- To assess the impact of various configurations of retrieval systems and language models on the response quality for distinct personas.
- To optimize system performance through extensive testing and customization of system parameters.

## Dataset

This project utilizes a multi-source dataset comprising arXiv papers, GitHub repositories, and Wikipedia entries. Gold standard validation data is provided to benchmark the system's response quality against high-quality human-generated responses.

## Methodology

1. **System Architecture**: The system uses a flexible RAG architecture that integrates retrieval and generation capabilities, underpinned by the LangChain library.
2. **Customization and Testing**: Offers deep customization of retrieval and language model settings, tailored for either marketing or research needs.
3. **Evaluation**: Applies BLEURT and qualitative evaluation to rigorously evaluate the system, ensuring responses meet the set quality standards.

## Results

The results affirm the capability of the adaptive RAG system to significantly enhance the relevance and quality of responses across different user personas. Particularly, research-oriented configurations have been shown to outperform their marketing counterparts, highlighting the effectiveness of the tailored system components.

## Usage

To utilize this project on Google Colab:
1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/) and sign in with your Google account.
2. **Upload Notebooks**: Upload the Jupyter notebooks from the `notebooks/` directory of this repository to your Google Colab session.
3. **Install Dependencies**: Run the `pip install` commands to install the required dependencies

## Future Work
Further developments might include exploring additional data sources for even more tailored responses, integrating more advanced language models, and expanding the customization options for different industries or departments within an organization.

## Project Organization

    ├── LICENSE
    ├── README.md
    ├── data
    │    ├── final               <- Final results of all experiments, consolidated and cleaned
    │    ├── interim             <- Results from hyperparameter tuning experiments
    │    └── raw                 <- Gold standard validation data
    ├── notebooks
    │    └── Adaptive-RAG.ipynb  <- Jupyter notebook used to generate report
    ├── reports
    │    ├── figures             <- Figures used to generate report
    │    └── Adaptive-RAG.ipynb  <- Final report
    └── models                   <- Configuration files of model variants

