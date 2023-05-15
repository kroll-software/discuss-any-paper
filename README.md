# Discuss Any Paper

Let your LLM discuss any paper or book. Great for brainstorming ideas and to get a glance.

Works locally with open-source models, no API keys needed. Uses [LangChain](https://github.com/hwchase17/langchain), so that each component could be easily replaced. Runs on CPU with most GGML models.
</br>

# Installation:

1. Clone this repository
2. Install the requirements: *pip install -r requirements.txt*
3. You may also have to install the tesseract OCR package to read PDF-files: *sudo apt install -y tesseract-ocr*
4. Download a ggml-model, e.g. [*gpt4-x-vicuna-13B.ggml.q4_2.bin*](https://huggingface.co/TheBloke/gpt4-x-vicuna-13B-GGML)
5. Copy the file *.env.example* to *.env*
6. Edit the model-path and other preferences in the file *.env*
7. Copy one ore more documents (papers or books, *.pdf and *.txt files are supported) to the ./docs folder
8. Also edit the objective in .env (typically "Discuss *paper title*")
</br>

Then run *python discuss.py*

Outputs are stored as text files under ./outputs

Have fun!
</br>
