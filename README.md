# LLM Question and Answer

## Overview

LLM Question and Answer is a project aimed at providing a streamlined interface for querying language models (LLMs) to
generate responses to questions. This project demonstrates how to utilize both proprietary and open-source LLMs for
answering questions based on given prompts.

## Proprietary LLM from OpenAI

The first part of the project demonstrates the usage of a proprietary LLM provided by OpenAI. Users need to set their
OpenAI API key in the environment variable `OPENAI_API_KEY`. After setting the API key, the script initializes the LLM
and sends a query prompt to generate a response.

### Usage

1. Set the OpenAI API key in the environment variable `OPENAI_API_KEY`.
2. Run the script.

## Open-source LLM hosted on Hugging Face

The second part of the project showcases the usage of an open-source LLM hosted on Hugging Face's model hub. Users need
to install the required library and set the Hugging Face API token in the environment
variable `HUGGINGFACEHUB_API_TOKEN`. After that, the script initializes the LLM using the desired repository ID and
sends a query prompt to generate a response.

### Usage

1. Install the `huggingface-hub` library.
2. Set the Hugging Face API token in the environment variable `HUGGINGFACEHUB_API_TOKEN`.
3. Run the script.

## Conclusion

The LLM Question and Answer project provides a convenient interface for utilizing both proprietary and open-source
language models to generate responses to user queries. Users can seamlessly interact with LLMs to obtain accurate and
informative answers to their questions.



------------

**Running Jupyter Notebook:**

To launch the Jupyter Notebook server, use the following command:

```bash
jupyter notebook
```

(Note: Use Control-C to stop the server)

---

**Installing Dependencies:**

Ensure that the required dependencies are installed by running the following commands:

```bash
pip install -r requirements.txt
python -m pip install jupyter
```

---

**Memory Profiling:**

To profile the memory usage, decorate your Python script with `@memory_profiler.profile` and run the following command:

```bash
python -m memory_profiler main.py
```

---

**Line Profiling:**

For line-level profiling, use the `line_profiler_pycharm` package. Decorate your Python script with `@profile` and
execute the following command:

```bash
python -m line_profiler main.py.lprof > results.txt
```

Make sure to replace `main.py` with the appropriate filename.