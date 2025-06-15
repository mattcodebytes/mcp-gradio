---
title: Sentiment Mcp
emoji: 💻
colorFrom: yellow
colorTo: indigo
sdk: gradio
sdk_version: 5.34.0
app_file: app.py
pinned: false
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

## Activate your virtual environment
```mcp-sentiment\venv\Scripts\activate.bat``` 

## Command to push to multiple repos
- set a second remote in git

```for %r in (origin hf) do git push %r main```

## Login to Huggingface
First go into console and generate a new token, then use it to login
```huggingface-cli login```
## Activate your virtual environment
```mcp-sentiment\venv\Scripts\activate.bat``` 

## Command to push to multiple repos
```for %r in (origin hf) do git push %r main```