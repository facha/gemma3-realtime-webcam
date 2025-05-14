# Fork of SmolVLM real-time camera demo
with some minimal changes to run with Gemma3 on Ollama

![demo](./demo.png)

This repository is a simple demo for how to use Ollama with Gemma3 to get real-time object detection

## How to setup

1. Install [Ollama](https://ollama.com/download)
2. Run `OLLAMA_ORIGINS='*' ollama serve`
3. Download Gemma3 `ollama pull gemma3`  
4. Open `index.html`
5. Optionally change the instruction (for example, make it returns JSON)
6. Click on "Start" and enjoy
