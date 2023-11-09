# Speedreading with Large Language Models: Text Summarization in Python

## Objectives:
- Learn how to use LLMs in Python
- Learn how to summarize text using LLMs
- Learn how to perform text analysis tasks with LLMs

Large Language Models are on the rise! Are you wondering if you can somehow make them draw information from your own documents? What if you could ask it to summarize a large number of papers on a particular topic that you have gathered in your personal digital library? Or create a Q&A chat bot based on some existing documentation or manual? Wouldn’t it be cool if you could essentially have a conversation with one or more of your own documents?

In this session, we will demonstrate a few examples that let you do exactly this. We will use both OpenAI’s language models through their API, as well as an entirely local (and thus privacy-preserving) open source model. After this session, you will have a solid framework to adapt and to create your own applications!

This session is intended for users with basic knowledge of the Python programming language and the use of APIs. This session is therefore a perfect follow-up to [“Intro to Python”](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/intro-to-python) and [“Let there be Data! APIs in Python”](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/apis-in-python).

## Getting started

### Requirements

Some basic Python programming knowledge is required to fully understand the example code. Consider working through [Intro to Python](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/intro-to-python) and [Let there be Data! APIs in Python](https://git.dartmouth.edu/lib-digital-strategies/RDS/workshops/computational-tools/apis-in-python) prior to this workshop.

The requirements for the Python code can be installed using the following command:

```
pip install -r requirements.txt
```

### OpenAI API access

To get the most out of the examples, you will need an OpenAI API key. You can sign up for their API [here](https://openai.com/blog/openai-api).

> **Note**: OpenAI's API is a billed service that charges per input and output token (a token roughly corresponds to a 3/4 of a word). You can find their [pricing here](https://openai.com/pricing). The examples in this workshop use GPT 3.5. Running all the example code *once* costs less than 0.5 USD (as of November 2023). **Make sure you set appropriate usage limits in your OpenAI account to avoid surprise charges!**

Once you have obtained a key, create a new file `secrets.env` in the repository root. Add the following line to the file and save it:

```
OPENAI_API_KEY="<your_key_here>"
```

Replace everything between and including the `<>` with your own API key.


### Usage

The repo has the following structure:

- `ppt`: The slide deck used in the introduction
- `docs`: An empty placeholder folder used in the examples
- `notebooks`: Notebooks illustrating the main concepts discussed in this workshop


### Licensing

<table>
<tbody>
  <tr>
    <td style="padding:0px;border-width:0px;vertical-align:center">
    Instructional materials created by Simon Stone for Dartmouth College Library under <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons CC BY-NC 4.0 License</a>.
    </td>
    <td style="padding:0 0 0 1em;border-width:0px;vertical-align:center"><img alt="Creative Commons License" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></td>
  </tr>
</tbody>
</table>

Except where otherwise noted, the example programs are made available under the OSI-approved MIT license.