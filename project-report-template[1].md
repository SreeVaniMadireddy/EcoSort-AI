# ECO SORT AI
## Smart Recycling and Waste Segregation Assistant
**Bharat AI-SoC Student Challenge 2026–27**  
**Problem Statement 2 – Environment & Climate**

**Team:** [Enter team name]  
**Members:** [Enter all names]  
**College / Department:** [Enter details]  
**Faculty mentor:** [Enter details, or state unavailable if the form permits]

## Abstract
EcoSort AI is an early-stage software prototype for a smart recycling and waste segregation assistant. The current version allows users to select a waste category and view general handling and disposal guidance. It also provides browser-based text-to-speech. The current implementation is rule-based and relies on user selection. Automatic image recognition, Llama inference using ExecuTorch, Arm deployment and FPGA acceleration are not implemented in this version.

## 1. Introduction
Improper waste segregation can contaminate recyclable materials. Users may be unsure whether an item belongs in dry recycling, wet waste or a special collection stream. EcoSort AI aims to make basic guidance easier to access.

## 2. Problem statement
The selected challenge concerns a smart recycling and waste segregation assistant. This prototype addresses the user guidance and interface portion of the problem.

## 3. Objectives
- Provide a simple interface for selecting common waste categories.
- Display handling and collection guidance.
- Provide voice output where supported.
- Establish a foundation for future AI and hardware integration.

## 4. Proposed solution
The current prototype supports plastic, paper, metal, glass, organic/food waste and electronic waste. When a user selects a category, the app displays a suggested collection stream, handling guidance and a next step.

## 5. System architecture
Refer to `architecture.md`. The current implementation includes category selection, rule-based guidance and browser text-to-speech. AI image classification, Llama/ExecuTorch, Arm deployment and FPGA acceleration are future work.

## 6. Hardware and software
**Hardware actually used:** [List only devices actually used, e.g. laptop.]  
**Software:** HTML, CSS, JavaScript and a modern web browser.

## 7. Methodology
1. User opens the web application.
2. User selects a waste category.
3. JavaScript retrieves the matching guidance.
4. The application displays collection and handling recommendations.
5. User can activate browser text-to-speech.

## 8. Results
Fill this table only after testing.

| Test | Expected result | Actual result |
|---|---|---|
| Plastic selection | Plastic guidance appears | [Fill] |
| Paper selection | Paper guidance appears | [Fill] |
| Metal selection | Metal guidance appears | [Fill] |
| Glass selection | Glass safety guidance appears | [Fill] |
| Organic selection | Organic guidance appears | [Fill] |
| E-waste selection | Authorized collection guidance appears | [Fill] |
| Voice output | Browser reads advice | [Fill] |

No AI accuracy, model latency, FPGA utilization or power values are reported because those components have not been implemented and measured.

## 9. Hardware utilization and optimization
This version is a browser-based software prototype and does not use an FPGA accelerator. FPGA resource utilization, timing, power and RTL performance measurements are therefore unavailable. Future work may investigate a suitable Arm platform and FPGA board.

## 10. Limitations
- Category is selected manually.
- No image classification is performed.
- Guidance is general and local rules may differ.
- Llama, ExecuTorch and Arm inference are not implemented.
- Verilog, FPGA acceleration and physical sorting are not implemented.

## 11. Future scope
- Add image capture and a trained classifier.
- Evaluate the classifier on a labelled test set.
- Integrate a Llama-family model using ExecuTorch on a supported Arm device.
- Select compatible FPGA hardware and investigate RTL acceleration.
- Add a safely tested physical sorting mechanism.

## 12. Conclusion
EcoSort AI currently demonstrates a basic waste guidance application with manual category selection and voice output. It provides a foundation for further development. The main AI, Arm/ExecuTorch and FPGA components remain future work.

## References
[Add only sources actually consulted.]
