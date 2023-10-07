# BigDL-LLM Portable Executable For Windows: User Guide

This portable executable includes everything you need to run LLM (except models). Please refer to How to use section to get started.

## 13B model running on an Intel 11-Gen Core PC (real-time screen capture)

<p align="left">
            <img src=https://llm-assets.readthedocs.io/en/latest/_images/one-click-installer-screen-capture.gif width='80%' />

</p>

## Verified Models

- ChatGLM2-6b
- Baichuan-13B-Chat
- Baichuan2-7B-Chat
- internlm-chat-7b-8k
- Llama-2-7b-chat-hf

## How to use

1. Download the model to your computer. Please ensure there is a file named `config.json` in the model folder, otherwise the script won't work.

   ![](https://llm-assets.readthedocs.io/en/latest/_images/one-click-installer-user-guide-step1.png)

2. Run `chat.bat` in Terminal and input the path of the model (e.g. `path\to\model`, note that there's no slash at the end of the path).

   ![](https://llm-assets.readthedocs.io/en/latest/_images/one-click-installer-user-guide-step2.png)

3. Press Enter and wait until model finishes loading. Then enjoy chatting with the model!
4. If you want to stop chatting, just input `stop` and the model will stop running.

   ![](https://llm-assets.readthedocs.io/en/latest/_images/one-click-installer-user-guide-step34.png)