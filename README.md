# NER-Text-Making
The goal of this project is to evaluate your ability to generate high-quality Named Entity Recognition (NER) examples using AI. You will use the provided list of entity types and instructions to create 1,500 realistic and contextually accurate NER-tagged sentences.

## Installation

1. Clone the repository:
```bash
git clone [https://github.com/Devolved-AI/Athena_2_LLM_Evaluation.git](https://github.com/shuvo881/NER-Text-Making.git)
cd NER-Text-Making
```

3. Set up environment variables:

```bash
# Create a vertual enviroment
## for Mac and Linux
python -m venv venv

# Active the verual enviroment
## For Mac and Linux
source venv/bin/active
```

```bash
# Export your Open AI API secret key
export OPENAI_API_KEY=your_key_here
```

### Basic Usage

```bash
cd code
# run the main file:
python main.py
```


# File Structure

```bash
NER-Text-Making/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── input/
│   │   ├── Multiple_NER_Bengali_Dataset.csv
│   │
│   ├── output/
│   │   ├── Generated_NER_Examples.json
│
├── code/
│   └── main.ipynb
```

Main Project Files:
* README.md: Likely contains project documentation.
* requirements.txt: Contains Python dependencies for the project.
* main.ipynb: Main script for the project, found in the code/ directory.

Data Files:
* input: Contains original ‘Multiple_NER_Bengali_Dataset.csv’ dataset
* output: Contains ‘Generated_NER_Examples.json’ files that appear to have been processed.
