# GAI_2_ImageGeneration_byte

AVIP 2026 — Generative AI, Task 2: Image Generation with Pretrained Models

## Project overview

This repository contains 30 image outputs generated from 30 diverse prompts, prompt-to-image example reports, inference notes, and a short qualitative failure analysis.

## Repository contents

- `prompts.txt` — the 30 prompts and their corresponding output filenames.
- `generated_images/` — 30 generated image files, named to match the prompts.
- `inference_notes.txt` — platform, model identification, and workflow notes.
- `failure_analysis.txt` — qualitative failure/limitation review (under 200 words).
- `image_manifest.csv` — image filenames and prompt mapping.
- `examples/` — five prompt-to-image examples with captions describing visible strengths or possible artefacts.

## Generation platform and model

- **Platform/interface:** Google Flow (web interface).
- **Model selected by the user:** Nano Banana 2.
- **Model family:** Google's Gemini image-generation model family. Google's documentation identifies Nano Banana 2 as Gemini 3.1 Flash Image. The API model ID documented for API usage is `gemini-3.1-flash-image`; this project was generated in Flow's user interface, not through a direct API request.
- **API version / request code:** Not applicable; images were generated through the Flow interface. No API calls, API version, seeds, or other internal generation parameters were recorded.
- **Official model overview:** https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/
- **Google Flow:** https://labs.google/fx/tools/flow
- **Google Flow Help and safety guidance:** https://support.google.com/flow/answer/16353333
- **Applicable Google Terms of Service:** https://www.about.google/policies/terms/
- **Gemini image-generation documentation (model mapping):** https://ai.google.dev/gemini-api/docs/image-generation

Nano Banana 2 is a hosted model, not a locally downloaded checkpoint. The links above are official documentation and terms, not an open-weight model license.

## Safety and prompt policy statement

The prompts in this project were designed around ordinary landscapes, fantasy environments, illustration, architecture, product concepts, science visualizations, and still-life subjects. They intentionally avoid requests for copyrighted characters, named living artists' styles, personal data, and sensitive content. Prompts ask for no brand logos and generally no text/watermarks where appropriate. Google Flow applies platform safety policies and protections; this project did not independently configure or measure its internal safety filters. Outputs should still be reviewed before public use.

## Prompt-to-image examples

See `examples/` for five examples. Each file records a prompt, the matching image filename, and a qualitative note about visible quality or potential limitations. These are visual observations, not a claim that every possible artefact was exhaustively tested.

## Limitations and reproducibility

The images are JPEG outputs exported from the Flow interface. Exact generation timestamps, seeds, internal settings, and a machine-readable request/response log were not provided. The project therefore documents the known workflow accurately without claiming API-level reproducibility. The five example captions and failure analysis are qualitative.
