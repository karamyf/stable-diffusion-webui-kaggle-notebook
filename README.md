# Stable Diffusion on Kaggle Tutorial

This tutorial demonstrates how to use Stable Diffusion on Kaggle, including its new built-in features and Dark theme. Stable Diffusion offers fast image editing capabilities, including a built-in cleaner option to remove objects from images.

## Prerequisites
- Kaggle account
- Ngrok account for hosting the Stable Diffusion web app

## Overview
Kaggle is a free alternative to Google Colab for running Stable Diffusion. Google has recently blocked the usage of Stable Diffusion with free Colab accounts, making Kaggle a viable alternative.

## Steps to Use Stable Diffusion on Kaggle
1. **Obtain Ngrok Token**
   - Sign up for a [Ngrok account](https://ngrok.com) and obtain your Ngrok API token.

2. **Configure the Notebook**
   - Replace the `xxxxxxxxxxxxxxxxxxxxxx` in `ngrok_token` with your Ngrok API token.

3. **Run the Notebook**
   - Run the notebook code.
   - The notebook will install dependencies, download models, upscalers, embeddings, and extensions needed for Stable Diffusion.

4. **Access Stable Diffusion**
   - After running the notebook, Stable Diffusion will be accessible through a local [URL](#).
   - Click on the Ngrok App URL to open Stable Diffusion in your web browser.

5. **Customize UI (Optional)**
   - Modify the UI configuration in the notebook to customize Stable Diffusion's appearance and functionality.

6. **Stop Session**
   - When you finish using Stable Diffusion, remember to stop the Kaggle session to conserve your GPU usage.

**Note:**  
- You have 30 hours per week of GPU usage in Kaggle. Use it responsibly and do not engage in any unethical activities.
