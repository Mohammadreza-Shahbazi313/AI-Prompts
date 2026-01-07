# 🔄 Image to JSON Prompt Generator

This is a powerful utility prompt designed for **Reverse Engineering** images.

If you have found an image online and want to recreate its style, lighting, or composition using AI, this tool is for you. It instructs a Multimodal AI (like ChatGPT-4o, Gemini 1.5, or Claude 3.5) to analyze the image and output a **structured JSON file**.

## 🚀 How to Use

1.  **Download/Select** the reference image you want to analyze.
2.  **Upload** the image to an AI Chatbot that supports vision (e.g., ChatGPT 4).
3.  **Copy** the prompt text from [`prompt.md`](./prompt.md).
4.  **Paste** the prompt alongside the image and hit send.
5.  **Result**: You will get a precise JSON block describing the subject, lighting, camera settings, and style. You can then feed this data back into image generators.

## 📦 Output Format

The AI will generate a strict JSON object containing:
*   `subject_description`
*   `lighting_parameters`
*   `camera_settings` (Lens, Aperture, etc.)
*   `artistic_style`
*   `negative_prompt`

