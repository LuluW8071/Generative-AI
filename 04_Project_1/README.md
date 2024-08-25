# MCQ-Generator

**MCQ-Generator** is a tool that generates multiple-choice questions (MCQs) based on a given twxt file or pdf file. It uses **Gemini 1.5 Flash** to generate MCQs with their respective answers. The generated MCQs are then saved in a csv file.

The notebooks folder contains a Jupyter Notebook that demonstrates how to use the MCQ-Generator tool. And, the src folder contains the source code of the MCQ-Generator tool wriiten in Python scripts from the notebook.

### Directory Structure

```
├── MCQ-Generator
│   ├── app.py                          # Main file    
│   ├── data.txt                        # Data file
│   ├── LICENSE.md                      # License file
│   ├── notebooks
│   │   ├── DeepLearning.csv
│   │   └── mcq_generation.ipynb        # Notebook file
│   ├── README.md                       # README file
│   ├── requirements.txt                # Requirements file
│   ├── response.json                   # Response file
│   ├── setup.py                        # Setup file
│   ├── src
│   │   ├── __init__.py     
│   │   └── mcq_generator               # Source code directory
│   │       ├── generate_mcq.py         # Source code file
│   │       ├── logger.py               # Logger file 
│   │       ├── prompts.py              # Prompt Template file
│   │       └── utils.py                # Utility file
│   └── test.py                         # Test file
```