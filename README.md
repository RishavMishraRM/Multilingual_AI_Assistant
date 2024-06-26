# Multilingual Assistant

1. Used python to create program
2. installed the gemini libs
3. used the gemini API key
4. streamlit to execute frontend
5. Google speech lib

# How to run?

### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# Finally run the following command
streamlit run app.py
```

Now,

```bash
open up localhost:
```

### Techstack Used:

- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s
