
# CLAWS & CO. 🐾

### Your nails. Your canvas.

Claws & Co. is a creative nail-design studio built for nail artists, press-on creators, and anyone who wants to design their next set before making it.

The goal is simple:

**Make designing nails feel as fun as playing a dress-up game — while giving professionals the control of a real design studio.**

---

## ✨ What is Claws & Co.?

Claws & Co. combines a playful 3D nail-design experience with professional creative tools and AI assistance.

The core experience is a rotatable 3D hand where users can:

- Select individual nails
- Experiment with nail shapes and lengths
- Apply colors, finishes, patterns, and decorations
- Build designs layer by layer
- Import visual references
- Use AI to modify designs through natural language
- Save and export finished sets

The 3D hand is the canvas.

The user is the designer.

AI is the copilot.

---

## 🎨 Core Products

### Claws Studio

The main 3D nail-design workspace.

Users can interact directly with a 3D hand and design each nail individually.

### Claws AI

An AI design copilot that understands natural-language instructions.

For example:

> "Make the tips thin and leopard print."

> "Add chrome to the middle finger."

> "Make this more Y2K."

AI converts these instructions into structured, editable design changes rather than replacing the entire design with an image.

### Size Claws

A professional nail-sizing utility designed around a nail technician's own tip sizing system.

The goal is to help technicians translate measurements into their own inventory and sizing guide.

### Claws Press

A future workflow for turning designs into press-on sets and client-ready design sheets.

---

## 🐾 Seasonal Collections

Claws & Co. will support limited-time visual collections and themes.

For example:

- Gothic Halloween
- Black Cat
- Vampire
- Dark Academia
- Chrome
- Y2K
- Holiday collections

These collections can introduce new hand appearances, materials, nail finishes, decorations, and visual assets without changing the core design system.

---

## 🧠 Product Philosophy

Claws & Co. is being built around three principles:

**1. Design first**

The creative experience comes before AI.

**2. AI should assist, not replace**

AI should modify and extend a user's design while keeping the result editable.

**3. Everything should remain structured**

A nail design is represented as structured data rather than a single generated image.

This makes individual nail editing, undo/redo, layers, exporting, and future automation possible.

---

## 🛠️ Tech Stack

- Next.js
- TypeScript
- React
- Tailwind CSS
- Three.js
- WebGL
- AI APIs
- Vitest
- AWS (planned)

---

## 🚧 Project Status

**Early development — Claws Studio MVP**

The first milestone is a functional 3D nail-design experience.

Current development priorities:

- [ ] Project foundation
- [ ] 3D hand viewer
- [ ] Hand rotation and interaction
- [ ] Individual nail selection
- [ ] Nail shape controls
- [ ] Nail length controls
- [ ] Color and finish system
- [ ] Structured design state
- [ ] Design layers
- [ ] AI design copilot
- [ ] Reference image analysis
- [ ] Size Claws
- [ ] Export / client design sheet
- [ ] Seasonal collections

---

## 🏗️ Architecture Direction

The 3D hand acts as the visual canvas.

Design actions modify a structured nail-design state:

```text
User
  ↓
Design Studio
  ↓
Structured Nail Design
  ↓
3D Renderer
  ↓
Interactive Hand
