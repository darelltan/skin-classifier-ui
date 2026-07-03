# Skin Condition Classifier — Frontend

React frontend for a CNN-based skin lesion classifier.

## Live Demo

**https://skin-classifier-ui.vercel.app**

## Features

- Drag-and-drop or click-to-upload image interface
- Real-time prediction with confidence scores for all 4 classes
- Grad-CAM heatmap showing which regions influenced the prediction
- Colour-coded results per condition
- Medical disclaimer

## Tech stack

- React 18
- Vite
- Axios
- Deployed on Vercel

## Connected services

- Backend API: https://renomaaaa-skin-classifier-api.hf.space
- Gradio demo: https://huggingface.co/spaces/renomaaaa/skin-classifier
- Backend repo: https://github.com/darelltan/skin-classifier-api

## Run locally

```bash
git clone https://github.com/darelltan/skin-classifier-ui
cd skin-classifier-ui
npm install
npm run dev
```

Update `src/App.jsx` line 4 to point to your local backend:
```js
const API = "http://localhost:8000";
```

## Disclaimer

This is a research prototype built for a student portfolio. Not for medical use.
