llm-project
LLM application to generate Mobile UI Designs.


Project Description

The **Mobile UI Design Generator** is an innovative application that utilizes  Large Language Model (LLM)  Stable diffusion model and a computer vision model to create mobile user interface designs based on user input. By providing a descriptive query, users can generate unique UI designs tailored to their specifications. 

Imported modules required (requirement.txt)
changed the running time to T5 to load faster

This repository contains a Python project that generates mobile UI designs based on user input using a combination of Stable Diffusion, Gradio for web interface, and transformers for natural language processing. It runs on CUDA-enabled GPUs for efficient computation.

## Features

- Generate mobile UI designs based on text descriptions
- Use **Gradio** for an easy-to-use web interface
- Integrate **Stable Diffusion** for generating UI images
- Supports **CUDA** for GPU acceleration

iface.launch(auth=["admin", "password"])
in login page username = "admin"
password = "password"
