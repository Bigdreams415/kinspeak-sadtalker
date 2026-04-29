# kinspeak-sadtalker

## Setup and run

This repo vendors SadTalker under SadTalker/. Follow the upstream instructions for your OS:

- Installation and usage: see SadTalker/README.md
- FAQs and troubleshooting: see SadTalker/docs/FAQ.md

Quick start (macOS/Linux):

```bash
cd SadTalker
conda create -n sadtalker python=3.8
conda activate sadtalker
pip install -r requirements.txt
python inference.py --driven_audio examples/driven_audio/bus_chinese.wav --source_image examples/source_image/art_1.png
```
