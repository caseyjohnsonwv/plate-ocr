# plate-ocr

Just playing with license plate OCR. License plates are cool because they're structured, yet each design is so drastically different. It's a really interesting engineering problem.


## Methodology
1. Use a fine-tuned image recognition model to detect a license plate in an image.
2. Crop the image down to just the plate.
3. Pass the cropped image to OCR to extract all possible texts.

## Potential Improvements
- Stringify OCR outputs and give them to an LLM to infer state, expiration, etc
- Use a stronger OCR engine like Tessaract
