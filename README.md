# AIOracle

AIOracle is a collection of very simple scripts and tools for querying OpenAI's APIs, enabling you to tap into its vast knowledge base and extract valuable insights and information. With AIOracle, you can easily access OpenAI's language models, text generators, and other powerful tools to analyze text, generate natural language, and more.

This repository contains sample code and tutorials to help you get started with querying OpenAI, as well as more advanced scripts for building custom applications and workflows. Whether you're a data scientist, developer, or researcher, AIOracle provides the tools you need to unlock the full potential of OpenAI's APIs.

## Getting Started

To your OpenAI API key as an environment variable. You can do this by running the following command in your terminal or command prompt:

1) Open Terminal.
2) Type `nano ~/.bashrc` to edit your bashrc file.
3) Add the line `export OPENAI_API_KEY="<your-api-key>"` to the bottom of the file.
4) Press ctrl + o to save the file.
5) Press ctrl + x to exit nano.
6) Type `source ~/.bashrc` to reload your bashrc file.
7) To check if it has been set: `echo $OPENAI_API_KEY`

To set in your local conda env instead:
`conda env config vars set OPENAI_API_KEY="<your-api-key>"`