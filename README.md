# SmartObjectInformationSystem
Use your YOLO models for real-time object information system supported with GeminiAI. 

Smart Object Information System

Smart Object Information System is a C# application that integrates YOLO object detection with a custom-built UI and AI-powered information retrieval.

Features

YOLO ONNX Support
Convert any YOLO model into ONNX format using my Gradio-based converter on Hugging Face Spaces
 and load it into the system for detection.

Custom Bounding Box Drawing
The system processes YOLO model outputs and draws bounding boxes directly on the camera feed using C# code (no external drawing libraries).

Multiple Functional Modes

Information: Provides detailed descriptions of detected objects.

Marketplace: Suggests product-related information for detected items.

Language: Offers language translation/learning support for detected objects.
These modes are powered by Gemini AI (API key configurable via settings).

Themes
Three UI themes are supported: Dark, Light, and Standard.

Camera Control
Choose any camera connected to your computer, pause/resume the feed, or take screenshots.

Image Saving
Save outputs in JPG or PNG format.

Technical Highlights

Implemented real-time detection pipeline with ONNX models in C#.

Developed custom bounding box rendering logic instead of relying on external libraries.

Used multi-threading for efficient video capture and detection.

Built a flexible UI with theme and mode switching.

Future Work

Add a mode where users can define and customize their own prompts.
