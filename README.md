# AutoLZ — Autonomous Landing Zone Detection (YOLOv5)

AutoLZ is a university team project where we built a small end-to-end system to help a programmable DJI drone land autonomously on a landing pad in a controlled environment using computer vision.

This project was completed by Aryan and team.
## What it does
- Uses the drone’s front camera feed
- Detects a landing pad using a YOLOv5 object detector
- Outputs a bounding box and confidence score
- Uses confidence and position to support a landing decision

---

## Model & Data
- Model: YOLOv5
- Training: trained from scratch
- Dataset: self-collected images of the landing pad
- Augmentation: rotation, flipping, and basic transformations
- Scale: ~4,000–5,000 images after augmentation

---

## Tech Stack
- Python
- PyTorch
- OpenCV

---

## Repository Structure

AutoLZ

↳training

↳inference

↳gui

↳data
    ↳ sample_images
   
↳results

↳ docs

↳ assets

↳ requirements.txt

↳ README.md

---

## Challenges
Building everything from scratch was the biggest challenge, as we started with limited knowledge and designed the full pipeline ourselves.

---

## Future Improvements
- Better robustness under lighting changes
- Reduced detection jitter
- Larger and more diverse dataset
- More structured landing control logic

---

## License
MIT
