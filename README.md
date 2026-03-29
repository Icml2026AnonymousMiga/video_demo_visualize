# MIGA: Video Demo Visualization

This repository provides visualization demos for the paper **"Enhancing Train-Free Infinite-Frame Generation for Consistent Long Videos"** (submitted to ICML 2026). It contains generated long video samples along with an interactive web page for browsing and playing the results.

## File Structure

| File | Description |
|------|-------------|
| `index.html` | Interactive project page with video demos, abstract, and method overview. Supports tab-based video switching with auto-play. |
| `prompts.txt` | Text prompts used to generate the three demo videos. |
| `1_iron_man.mp4` | Generated video: Iron Man soaring through a cloud-filled sky. |
| `2_sea_turtle.mp4` | Generated video: A sea turtle gliding through a colorful coral reef. |
| `3_corge_dog.mp4` | Generated video: A fluffy Corgi dog trotting across a green lawn. |
| `method_tta.png` | Illustration of the Two-Stage Alignment (TTA) mechanism. |
| `method_dce.png` | Illustration of the Dual Consistency Enhancement (DCE) mechanism. |
| `.gitignore` | Git ignore rules for `.claude/` and `.netlify/` directories. |
