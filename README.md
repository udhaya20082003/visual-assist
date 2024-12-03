#####Visual Assist: Mobile Application for Visually Impaired Individuals

Visual Assist is a mobile application specifically designed to empower visually impaired individuals by leveraging advanced machine learning techniques. The app provides real-time object detection with positional audio feedback and optical character recognition (OCR) to extract critical text-based information, such as product prices and expiry dates.

Features

Cross-Platform Compatibility: Built with Flutter to run on both Android and iOS platforms.

Object Detection: Uses TensorFlow Lite and MobileNet for detecting objects and providing audio cues for their location.

Text Recognition (OCR): Extracts important textual information from images, such as product labels, prices, and expiry dates.

Modules

User Interface

Developed using Flutter and Dart with integration of Google TalkBack for accessibility.

Provides an intuitive interface with options for:

Start Object Detection

OCR Scan

Object Detection

Identifies objects in images or video streams and provides bounding box data along with confidence scores.

Audio cues indicate object positions (e.g., "left" or "right").

Powered by the MobileNet pre-trained model.

Optical Character Recognition (OCR)

Converts text in images into readable digital content.

Focuses on extracting essential details like product names, prices, and expiry dates.

Optimized to reduce computation by analyzing specific image regions.

This README provides an overview of Visual Assist, highlighting its features, modules, and purpose to aid visually impaired users through advanced technology.

