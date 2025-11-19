# DSPy as a framework for LLM-powered Design

## Getting Started
### API Keys
* Be sure to grab the API keys for whatever cloud-based providers you rely on.

* Add them into a `.env` file in your project root
    * Be sure to add `.env` to your `.gitignore` file so that your API keys are not tracked in your repository
* Using eg `python-dotenv` load in the `.env` keys and pull the appropriate ones for your LM setups.


### Signatures
* The simplest signature is `question -> answer : str` which takes as an input a question, and yields an answer.
* Build your own signatures that describe what you want the input and output to generally be.


### Modules
???