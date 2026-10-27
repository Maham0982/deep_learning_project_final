# VisionLab — Image Classification Project Showcase

A responsive static website for presenting an image-classification deep-learning project. It is separate from the TensorFlow/Flask inference app, so the showcase itself can be deployed on Vercel without installing TensorFlow.

## Files
- `index.html` — page structure and project information
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and local image preview
- `vercel.json` — minimal Vercel configuration

## Run locally
Open `index.html` in a browser, or use the VS Code Live Server extension.

## Deploy to Vercel
1. Push these files to your GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Use the project root as the Root Directory.
4. Choose **Other** as the framework preset if asked. No build command is needed; leave the output directory blank/default.
5. Deploy.

## Before submitting
Edit `index.html` and replace placeholder links for:
- Project report
- Presentation
- YouTube video
- LinkedIn post

The GitHub link currently points to `https://github.com/Maham0982/deep_learning_project`.

## Important model note
The supplied `main.py` source uses pretrained ResNet50 ImageNet weights and decodes ImageNet class predictions. This showcase does not claim that a custom dataset has been trained or evaluated. The image preview is front-end only; it does not run model inference. If your assignment requires custom training, provide your dataset, training script, saved model weights, and genuine evaluation results in the repository.
