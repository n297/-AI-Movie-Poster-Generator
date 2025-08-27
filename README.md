🎬 AI Movie Poster Generator
This project generates AI-designed movie posters using textual descriptions (e.g., title, actors, director, synopsis).
It is a proof-of-concept that demonstrates how machine learning and generative AI can create visually compelling movie posters.

📂 Dataset
For this demo, used a small synthetic dataset of 10 movies.
Each entry includes:

Movie Title

Main Actors

Director

Genre

Synopsis


🛠 Tech Stack
Python 3.10+

PyTorch (for deep learning)

Diffusers (Hugging Face Stable Diffusion)

TorchVision (image transforms)

Pillow (image processing)

Hugging Face Transformers (for text encoding)


🚀 How It Works

Reads movie metadata from the dataset.

Converts text (actors, plot, genre) into a descriptive prompt.

Uses Stable Diffusion to generate a high-resolution poster (up to 4K).

Optionally adds text overlays (title, credits).


⚠ Limitations

Faces and fine details may not be perfect due to AI model limitations.

Small dataset means the model is not fully fine-tuned.

Text on posters may have spelling inconsistencies.
