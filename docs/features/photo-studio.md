# Photo Studio

Photo Studio is a dedicated tab for AI-powered image tools. It combines cloud AI models (DALL-E 3, gpt-image-1) with on-device Apple Vision capabilities.

## Features

### 1. AI Image Generation

Create images from text descriptions using DALL-E 3.

- Tap **Generate** and type a prompt: "a watercolor painting of a mountain lake at sunset"
- Choose a size (square, landscape, or portrait)
- The generated image appears in the app and can be saved to your photo library

**Geek mode:** `/photo generate a watercolor landscape`

### 2. AI Photo Editing

Edit existing photos using natural language instructions, powered by gpt-image-1.

- Select a photo from your library
- Describe what you want changed: "remove the person in the background" or "make the sky more dramatic"
- The AI returns an edited version

**Geek mode:** `/photo edit make the colors more vibrant`

### 3. Describe Image

Get an AI-generated description of any photo using your active LLM provider's vision capabilities.

- Select a photo and tap **Describe**
- The AI analyzes the image and returns a detailed text description
- Useful for accessibility, cataloging, or understanding photo contents

**Geek mode:** `/photo describe`

### 4. AI Enhance

Automatically improve photo quality using AI-suggested adjustments applied through Core Image.

- Select a photo and tap **Enhance**
- The LLM analyzes the image and suggests brightness, contrast, saturation, and sharpness adjustments
- Adjustments are applied using Core Image filters (CIColorControls, CISharpenLuminance)

**Geek mode:** `/photo enhance`

### 5. Background Removal

Remove the background from any photo using Apple Vision, entirely on-device.

- Select a photo and tap **Remove Background**
- Uses `VNGenerateForegroundInstanceMaskRequest` to isolate the subject
- Returns a PNG with a transparent background

**Geek mode:** `/photo bg`

### 6. Add Watermark

Overlay semi-transparent text on a photo using Core Image. Select a photo, tap **Watermark**, and type your text.

**Geek mode:** `/photo watermark "Your Text Here"`

### 7. Remove Watermark

Blur out a watermark region on a photo. A scaled Gaussian blur covers the area, with the radius adapting to image resolution.

**Geek mode:** `/photo remove`

### 8. OCR / Extract Text

Extract text from photos using Apple Vision's on-device OCR.

- Select a photo and tap **OCR**
- Uses `VNRecognizeTextRequest` in accurate mode
- Extracted text can be copied to clipboard

**Geek mode:** `/photo ocr`

### 9. Resize Image

Resize photos while preserving aspect ratio. Enter a target width or height and the image scales proportionally.

**Geek mode:** `/photo resize 1024`

## Requirements

- **DALL-E 3 / gpt-image-1 features** (generate, edit, enhance, describe): Require an OpenAI API key configured in Settings > LLM Providers.
- **On-device features** (background removal, OCR, watermark, resize): No API key needed. Work offline.

## Tips

- Generated and edited images can be saved to your photo library with the share button.
- Background removal works best with clear foreground subjects.
- OCR supports multiple languages and works on documents, screenshots, and handwritten text.
- Enhance is non-destructive -- your original photo is never modified.

## Related

- [Geek Mode Commands](geek-mode.md) -- All `/photo` subcommands
- [Getting Started](../guides/getting-started.md) -- Setting up an LLM provider
