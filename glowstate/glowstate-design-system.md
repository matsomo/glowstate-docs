# Glowstate — Visual Design System

## Core Identity

Glowstate visuals are clean, stylized anime environments focused on atmosphere, rhythm, and subtle motion.

They are:
- Calm but alive
- Structured and readable
- Designed for music immersion

They are not:
- Gritty or noisy
- Photorealistic or CGI
- Overly stylized or abstract
- Cluttered or chaotic

---

## Style Rules (Non-Negotiable)

- Clean linework
- Crisp, readable shapes
- Soft gradients with controlled transitions
- Minimal texture

Avoid:
- Gritty, noisy, or grainy textures
- Pixelated or low-fidelity rendering
- Painterly blur or muddy blending
- Photoreal or hyper-detailed CGI aesthetics

All visuals must feel intentional and designed, not generated.

---

## Composition Rules

- Wide format (16:9 preferred)
- Clear focal direction
- Strong use of depth:
  - Foreground
  - Midground
  - Background

- Natural asymmetry unless symmetry is intentional
- Leading lines should guide the eye through the scene

Do not alter composition unless explicitly requested.

---

## Environment Principles

- Environments must feel grounded and believable
- Maintain openness and breathable space
- Avoid overcrowding or emptiness

Urban environments:
- Clean, controlled surfaces
- Light wear is acceptable, not heavy grime

Natural environments:
- Simplified, readable forms
- No excessive detail noise

---

## Lighting Philosophy

- Soft, controlled lighting
- No harsh or overly dramatic contrast unless specified

Typical balance:
- Warm highlights (sunlight, lamps)
- Cool ambient tones (sky, shadows)

Lighting defines mood but should not overpower the scene.

---

## Motion Philosophy

Motion is subtle and implied, not explicit.

Use:
- Light shifts
- Soft reflections
- Environmental movement (wind, shadows)

Avoid:
- Strong motion blur
- Action-driven movement
- Static, lifeless scenes

---

# 🔧 AI Rendering Constraints (NEW — CRITICAL)

These rules define what the model can reliably render cleanly.

---

## Core Principle

👉 Clarity over complexity  
👉 Structure over detail  
👉 Controlled lighting over visual richness  

---

## Form Simplification Rules

- Use large, readable shapes instead of micro-detail
- Group complex elements into unified forms
- Avoid fine, high-frequency detail (leaves, textures, patterns)

Examples:
- Trees → clustered shapes, not individual leaves
- Crowds → grouped silhouettes, not micro-figures
- Surfaces → smooth shading, not texture simulation

---

## Detail Density Limits

Avoid:

- Dense foliage with visible micro-structure
- Overlapping small objects
- High-frequency patterns (grass, fabric noise, debris)

Preferred:

- Medium → large forms
- Clear separation between elements
- Controlled visual hierarchy

---

## Lighting Constraints

- Limit number of active light sources
- Avoid overlapping glow systems
- Keep light falloff smooth and continuous

Do NOT:
- Stack multiple glowing elements in the same area
- Create conflicting color lighting
- Use high-intensity neon across the entire scene

---

## Material Rules

Allowed:
- Smooth surfaces
- Soft gradients
- Clean shading

Avoid:
- Textured surfaces
- Grain
- “Detail for realism”

---

## Color Control

- Maintain balanced saturation
- Avoid full-scene neon intensity
- Use glow locally, not globally

---

# 🚫 Failure Patterns (NEW — MUST AVOID)

---

## 1. Gradient Break / “Bit-Crush”

**Symptoms:**
- Stepped color transitions
- Posterization
- Harsh banding

**Cause:**
- Over-saturated lighting
- Too many light sources
- Gradient complexity

**Fix:**
- Reduce contrast locally
- Simplify lighting interactions
- Use broader gradients

---

## 2. Foliage Speckling / Noise

**Symptoms:**
- Spotted leaf surfaces
- Grain-like patterns in trees
- Crunchy organic detail

**Cause:**
- Dense organic complexity
- Model approximating detail with noise

**Fix:**
- Simplify foliage into clusters
- Remove micro-detail instructions
- Increase shape readability

---

## 3. Texture Hallucination

**Symptoms:**
- Fake surface detail
- Noise where surfaces should be smooth
- Uncontrolled micro-variation

**Cause:**
- Model “filling space” with detail

**Fix:**
- Explicitly enforce smooth surfaces
- Remove references to texture
- Reduce visual density

---

## 4. Lighting Instability

**Symptoms:**
- Patchy illumination
- Inconsistent glow behavior
- Random brightness shifts

**Cause:**
- Too many emissive elements
- Conflicting light sources

**Fix:**
- Reduce number of lights
- Define clear lighting hierarchy

---

# ✅ Rendering Quality Check (NEW)

Reject any image that shows:

- Noisy or speckled surfaces
- Broken or stepped gradients
- Pixelated or low-fidelity rendering
- Overly complex or unreadable forms
- Lighting that feels chaotic or unstable

Accept only if:

- Gradients are smooth and controlled
- Shapes are clean and readable
- Lighting is cohesive and intentional
- Scene feels designed, not generated

---

## Do / Don’t

### Do
- Maintain clean, readable compositions
- Preserve structure and perspective
- Use depth and layering effectively
- Keep environments consistent with Glowstate identity
- Simplify forms for clarity

### Don’t
- Add unnecessary objects
- Introduce cliché props
- Break perspective or geometry
- Over-stylize or over-render
- Add micro-detail for realism
- Allow noise or texture artifacts

---

## Workflow

### Step 1 — Base Image
Select or generate a strong composition.

### Step 2 — Structural Cleanup
Fix:
- Perspective
- Geometry
- Object logic

### Step 3 — Style Alignment
Ensure:
- Clean anime style
- Smooth gradients
- Controlled lighting
- No texture artifacts

### Step 4 — Refinement
- Add subtle motion cues
- Polish lighting
- Remove noise and artifacts

---

## Iteration Rule

Every mistake must be added to the Failure Patterns section.

This prevents repetition and enforces system evolution.

---

## Guiding Principle

Glowstate is not about detail or realism.

It is about:
- Clarity
- Atmosphere
- Controlled motion

---

## Core Principle

👉 Clarity + Motion + Controlled Rendering = Glowstate
