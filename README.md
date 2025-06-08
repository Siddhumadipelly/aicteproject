# aicteproject
Hey

My name is Siddharthamadipelly
About My Project
Universal Object Analyzer
Overview

In many real-world scenarios, identifying objects with accurate semantic detail—such as color, shape, category, and weight—remains a challenge for AI systems.
Existing object detection solutions typically focus on object localization and classification but lack multi-dimensional descriptive capabilities. This limits their usability in domains like assistive technology for visually impaired users, robotics, and context-aware AI applications.

The Universal Object Analyzer addresses this gap by integrating multiple AI components into a single, real-time, multimodal object analysis pipeline.
Solution Pipeline

    🟢 YOLOv8
    Detects and localizes objects in real time using bounding boxes.

    🟣 CLIP (Contrastive Language-Image Pretraining)
    Performs zero-shot classification to identify objects from a set of candidate labels.

    🟡 KMeans Clustering
    Detects the object’s dominant color.

    🟠 OpenCV
    Analyzes the object’s geometric shape through contour detection.

    🔵 Estimated Weight Lookup
    Retrieves an estimated weight from a predefined lookup table based on the identified object.

    🔊 gTTS (Google Text-to-Speech)
    Converts the object description into audio output.

    🌐 Gradio Web Interface
    Provides an intuitive web-based interface allowing users to upload or capture images and view both text and audio descriptions of detected objects.

Features

    Real-time object detection and precise localization using YOLOv8
    Zero-shot object classification powered by the CLIP model
    Dominant color extraction utilizing KMeans clustering algorithm
    Geometric shape analysis through OpenCV contour detection
    Estimated object weight calculation based on a predefined lookup table
    Audio output of object descriptions implemented with Google Text-to-Speech (gTTS)
    Intuitive and user-friendly web interface built with Gradio, supporting both local and cloud deployment

Applications

    Assistive Technology for visually impaired users
    Robotics and human-robot interaction
    Smart devices and home automation
    Interactive AI agents
    Educational tools
