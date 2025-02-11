# Gemini API: Animated Story Video Generation
https://github.com/user-attachments/assets/d8d85e34-b3bb-4d08-89d3-1af149633a86

This repository provides a Google Colab notebook that demonstrates how to create animated story videos by integrating multiple Google APIs and open source libraries. The notebook leverages:





- **Google Gemini API** to generate a structured story sequence.
- **Google Imagen API** to generate images for each scene.
- **Kokoro's KPipeline** to synthesize narration audio.
- **MoviePy** to combine the generated images and audio clips into a video.

## Features

- **Story Generation:** Generate a narrative with scene details such as image prompts, narration text, and character descriptions.
- **Image Generation:** Automatically create images for each scene based on a detailed prompt.
- **Audio Synthesis:** Convert narration text into audio using Kokoro's KPipeline.
- **Video Composition:** Combine images and audio clips to produce a full animated story video.
- **Automated Cleanup:** Remove temporary media files after video generation.

## Getting Started

### Prerequisites

- A valid [Google API key](https://cloud.google.com/) with access to the Gemini and Imagen APIs.
- Install the required Python packages. The notebook uses:
  - `google-generativeai`
  - `moviepy`
  - `Pillow`
  - `kokoro`
  - Other helper libraries (e.g., `soundfile`, `numpy`)

### Setting Up Your API Key in Colab

Before running the notebook, make sure to set your API key as a Colab Secret:
1. Go to **Tools → Command Palette → User secrets** in the Colab menu.
2. Click **Add a secret**.
3. Add the secret with the name `GOOGLE_API_KEY` and paste your API key in the value field.
4. Restart your Colab runtime if needed.

## Run in Google Colab

You can run the notebook directly in Google Colab by clicking the badge below:

[![Run in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1aO2MesYp6NKNIXcEdXhcuSQKvL9rb2Xn?usp=sharing)

## License

Licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to alter.

## Acknowledgements

- [Google Gemini API Documentation](https://ai.google.dev/gemini-api/docs/structured-outputs)
- [Imagen API Documentation](https://ai.google.dev)
- [Kokoro KPipeline](https://github.com/kokoro-ai)
- [MoviePy Documentation](https://zulko.github.io/moviepy/)

## Contact

If you have any questions or suggestions, please feel free to open an issue or submit a pull request.

Happy generating!
