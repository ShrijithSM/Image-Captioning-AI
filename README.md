

# Image Captioning AI

This project is an AI-powered image captioning web application that automatically generates natural language descriptions for uploaded images. Built with Gradio and the BLIP (Bootstrapping Language-Image Pre-training) model, it provides an intuitive interface for users to get accurate and descriptive captions for their images.

## Live Demo

Try out the live demo: [Image Captioning AI on Hugging Face Spaces](https://huggingface.co/spaces/Xsparkm/Image-Captioning-AI)


## Features

- 🖼️ **Simple Image Upload**: Drag and drop or click to upload any image
- 🤖 **Advanced AI Model**: Uses BLIP model from Salesforce for accurate image understanding
- 📝 **Instant Captions**: Generates natural language descriptions in real-time
- 🌐 **Web Interface**: User-friendly interface built with Gradio
- 🚀 **Fast Processing**: Efficient image processing and caption generation

## Example Screenshot

![Image Captioning Example](assets/image01.png)

## Technology Stack

- **Frontend**: Gradio (Web Interface)
- **Backend**: Python
- **AI Model**: BLIP (Salesforce/blip-image-captioning-base)
- **Libraries**: 
  - transformers (Hugging Face)
  - PyTorch
  - Pillow
  - NumPy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ShrijithSM/Image-Captioning-AI.git
cd Image-Captioning-AI
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python app.py
```

2. Open your web browser and navigate to the local URL shown in the terminal (typically http://127.0.0.1:7860)

3. Upload an image using the interface

4. The AI model will process the image and generate a caption automatically

## Requirements

The following dependencies are required to run the project:

- gradio==4.44.0
- pillow==10.4.0
- torch>=2.0.0
- transformers==4.38.2
- requests>=2.31.0
- numpy>=1.24.0

## How It Works

1. **Image Upload**: User uploads an image through the Gradio interface
2. **Image Processing**: The image is preprocessed to meet the BLIP model's input requirements
3. **Caption Generation**: The BLIP model analyzes the image and generates a descriptive caption
4. **Display**: The caption is displayed alongside the uploaded image

## Deployment

The project is deployed on Hugging Face Spaces, providing free and accessible hosting for the application. You can access it at [https://huggingface.co/spaces/Xsparkm/Image-Captioning-AI](https://huggingface.co/spaces/Xsparkm/Image-Captioning-AI)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Salesforce for the BLIP model
- Hugging Face for the transformers library and Spaces hosting
- Gradio team for the excellent web interface framework
