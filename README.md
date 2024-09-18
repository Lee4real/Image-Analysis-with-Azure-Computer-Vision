# Image Analysis with Azure Computer Vision

This project uses Azure's Computer Vision service to analyze images.

## Setup

1. Install dependencies:

   ```
   pip install python-dotenv azure-ai-vision
   ```

2. Set up environment variables:
   Create a `.env` file in the project root with:
   ```
   AI_SERVICE_ENDPOINT=https://your-endpoint.cognitiveservices.azure.com/
   AI_SERVICE_KEY=your-api-key
   ```

## Usage

Run the script with an image file as an argument:

```
python image-analysis.py images/street.jpg
```

This will analyze the image and save the results.
# Image-Analysis-with-Azure-Computer-Vision
