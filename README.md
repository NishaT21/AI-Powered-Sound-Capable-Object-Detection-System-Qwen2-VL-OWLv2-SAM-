# AI-Powered-Sound-Capable-Object-Detection-System-Qwen2-VL-OWLv2-SAM-
A vision language powered detection pipeline that analyzes images to identify and localize objects capable of producing sound. The system integrates Qwen2-VL for semantic scene reasoning, OWLv2 for text-guided object detection, and SAM for precise segmentation.

## System Workflow

<p align="center">
  <img src="Flowchart_workflow_mermaid_diagram.png" width="800"/>
</p>

## Limitations
- Qwen2-VL may return invalid JSON.
- OWLv2 accuracy depends on text prompt quality.
- High GPU memory requirement (7B model).
- Quantization reduces memory but may affect accuracy.
- Not optimized for real-time inference.

## 🧪 How to Run

### 1️⃣ Google Colab Setup (Recommended)

1. Open `AI_PoweredSoundCapableObjectDetection.ipynb` in **Google Colab**
2. Navigate to:  
   **Runtime → Change runtime type → Select GPU**
3. Run all cells sequentially (Cell 1 → Cell 9)
4. Choose an input mode (Webcam or Static Image)
