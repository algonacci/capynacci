---
name: capynacci-illustrations
description: Plan, generate, and edit Capynacci-style body illustrations for English articles, posts, blogs, and Notion documents. Use when the user explicitly mentions Capynacci or requests article illustration strategy, shot lists, generation, or edits starring Capynacci — an Applied AI Researcher & Tech Founder Capybara with warm golden-brown fur, dark navy tech hoodie, smart round glasses, and running shoes, set against a pure white background with minimalist black line-art diagrams and sparse colored English annotations.
---

# Capynacci Quirky Body Illustrations

## Core Positioning

Design and generate 16:9 horizontal body text illustrations for articles and technical posts. The goal is not to create generic commercial vector illustrations or formal PPT slides, but to turn key AI/systems judgments, processes, architectures, or conceptual metaphors into clean, quirky, highly readable hand-drawn explanatory images.

The visual IP is **"Capynacci"**: a warm golden-brown capybara wearing a dark navy tech hoodie, smart round glasses, and athletic running shoes. Capynacci represents an Applied AI Researcher, Tech Founder (Braincore Research Labs), and endurance athlete who is seriously, calmly, and slightly bizarrely solving complex system problems. Capynacci must participate in the core conceptual action of the image, not just stand aside as decoration.

## Read These References First

Read them as needed for the task:

- `references/style-dna.md`: Visual style DNA, colors, text rules, and taboos.
- `references/capynacci-ip.md`: Capynacci IP appearance, personality, outfit, action library, and taboos.
- `references/composition-patterns.md`: Structure types, original metaphor methods, and anti-copying rules.
- `references/prompt-template.md`: Single image generation prompt template & image edit prompts.
- `references/qa-checklist.md`: Post-generation inspection and iteration rules.

## Workflow

### 1. Digest the Main Text

Read the main text, article draft, Notion page, Markdown file, or prompt provided by the user. Extract:
- Core technical/business viewpoint
- Cognitive transition points
- Content suitable for visual explanation
- Content suitable for pure text (no image needed)

Prioritize "cognitive anchors" such as: AI model pipelines, input-output loops, before-and-after comparisons, R&D to product translation, architecture bottlenecks, handoff paths, common pitfalls.

### 2. Provide Illustration Strategy First

If the user requests strategy or shot lists, provide a breakdown. For each image write:
- Position (after which section)
- Theme of the image
- Core technical meaning
- Structure type
- What Capynacci is doing in the image
- Suggested elements
- Suggested English handwritten annotations

Default to 3-6 images for standard articles.

### 3. Generate Single Images

Use the available raster image-generation capability (e.g. `generate_image`) to generate each image individually.

The prompt must enforce:
- 16:9 horizontal English article illustration format
- Pure white background (no gradients, shadows, paper texture)
- Minimalist black hand-drawn line art for background technical diagrams
- Capynacci as a fully colored main character (warm golden-brown fur, dark navy tech hoodie, round glasses, running shoes)
- Target 3-5 sparse handwritten English annotations (8 max)
- Generous white space (~40%-60% subject occupancy)
- Prohibit PPT slides, vector clipart, cute children's cartoons, and top-left titles

### 4. Check and Iterate

After generation, verify against `references/qa-checklist.md`:
- Capynacci must perform the core conceptual action
- Background must be pure white
- No top-left category titles ("Workflow", "System Architecture")
- Annotations must be sparse, short, and legible

### 5. Save and Deliver

Save or copy the final images to:

```text
assets/<article-slug>-illustrations/
```

Name them sequentially:

```text
01-topic-name.png
02-topic-name.png
```

## Output Tone

Outputs should be concise, professional, and clear. State the number of images generated, their purpose, save paths, and key visual highlights.
