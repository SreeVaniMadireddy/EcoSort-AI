# Proposed system architecture

**This is a future architecture proposal, not a claim that all blocks are implemented.**

```text
Camera / User Input
        |
        v
Image capture and preprocessing on Arm
        |
        v
Waste image classification model
        |
        v
Predicted category + confidence
        |
        v
Llama advisory component (planned)
using ExecuTorch on Arm
        |
        v
Text / voice / visual disposal guidance
        |
        v
User decision / future sorting mechanism

Optional future research:
FPGA + Verilog accelerator for selected
compute-intensive operations, after board selection.
```

## Current prototype
The current `index.html` implements manual category selection, rule-based disposal advice and browser text-to-speech. Image classification, Llama/ExecuTorch, Arm deployment, FPGA acceleration and physical sorting are not implemented in this version.
