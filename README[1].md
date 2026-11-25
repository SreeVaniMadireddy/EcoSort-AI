# EcoSort AI – Smart Recycling & Waste Segregation Assistant
**Bharat AI-SoC Student Challenge 2026–27 | PS2 – Environment & Climate**

## Overview
EcoSort AI is an early-stage prototype that gives general waste-handling guidance. A user selects a category and the app displays collection advice. Browser text-to-speech can read the advice aloud.

## Implemented in this repository
- Responsive web interface.
- Six manually selected categories: plastic, paper, metal, glass, organic and e-waste.
- Category-specific guidance.
- Browser text-to-speech (support depends on browser).

## Not implemented yet
- Automatic image-based waste classification or trained AI model.
- Llama-family model integration.
- ExecuTorch inference or Arm-device deployment.
- Verilog/FPGA accelerator.
- Physical automatic sorting mechanism.

The current application is rule-based. Do not describe it as automatic AI image recognition.

## Run
1. Download/clone this repository.
2. Open `index.html` in Chrome, Edge or Firefox.
3. Select a category and click **Get segregation advice**.
4. Click **Read aloud**.

No external libraries are required.

## Future development
1. Add a labelled waste-image dataset and train/test an image classifier.
2. Report measured test accuracy and other evaluation metrics.
3. Integrate the required Llama-family advisory component using ExecuTorch on a supported Arm device.
4. Select compatible FPGA hardware before developing and testing Verilog acceleration.
5. Add a physical sorting mechanism only after safety testing.

## Team
Team members-N.Poornima
            M. Sree Vani
            K.Mounika
College-Vishnu Institute Of Technology
Department-ECE
Mentor details-B.V.V.Satyanarayana

