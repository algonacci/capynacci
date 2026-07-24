# QA Checklist for Capynacci Illustrations

## Must Pass Checklist

- [ ] **16:9 Aspect Ratio**: Is the image in horizontal 16:9 format?
- [ ] **Pure White Canvas**: Is the background pure white (`#FFFFFF`) with zero texture/gradients?
- [ ] **Capynacci Present & Colored**: Is Capynacci featured with warm golden-brown fur, smart round glasses, and navy tech hoodie?
- [ ] **Active Role**: Is Capynacci actively performing the core technical action (not just standing as passive decoration)?
- [ ] **Minimalist Diagram**: Is the background diagram drawn with clean black hand-drawn line art?
- [ ] **Abundant White Space**: Does the canvas have at least ~35%-40% blank white space?
- [ ] **Sparse Handwritten Annotations**: Are there 3-5 short handwritten English labels (8 max)?
- [ ] **Restrained Colors**:
  - Orange: Main data flow / prediction path
  - Red: Loss / error / bottleneck / key result
  - Blue: Weights adjustment / system state notes
  - Black: Main line art & annotations

## Failure Signals (Requires Regeneration or Local Editing)

- ❌ Top-left corner has category headers like "Workflow", "System Architecture", or "Roadmap".
- ❌ Capynacci is rendered in pure black silhouette without colors or outfit.
- ❌ Capynacci looks like a generic vector sticker or childish meme.
- ❌ The diagram looks like a formal corporate PowerPoint slide or rigid CAD schematic.
- ❌ Long paragraphs of explanatory text appear inside the image.
- ❌ Background is dark, gray, textured, or gradient-filled.
- ❌ Illegible or misspelled handwritten annotations.
