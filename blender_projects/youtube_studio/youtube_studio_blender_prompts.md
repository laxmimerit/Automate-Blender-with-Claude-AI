# YouTube Creator Studio — Blender Prompts

A complete log of every prompt used to build a cinematic YouTube creator studio desk setup from scratch in Blender using Claude + MCP.

---

## Scene Setup

**1. Clear the scene**
```
clear the scene
```

**2. Invoke the blender-assembly skill and describe the full setup**
```
/blender-assembly

Create a modern YouTube creator studio with a large desk, dual monitors, RGB lighting, microphone setup, gaming chair, LED strips, and cinematic room lighting.
```

---

## Geometry Fixes & Rebuilds

**3. Fix proportions and alignment**
```
Fix the proportions and alignment of all objects in the scene. Make the desk, chair, monitors, and accessories look realistic and properly scaled relative to each other.
```

**4. Full rebuild from scratch**
```
Delete the entire existing scene except the camera and lights. Rebuild the setup completely from scratch with clean geometry and correct real-world proportions.
```

**5. Delete all meshes (clean slate)**
```
Delete every mesh object in the scene. Keep only the camera and lights. Do not create any environment, room, floor, walls, or additional objects.
```

---

## Building the Scene Object by Object

**6. Floor**
```
Create a simple flat dark floor plane below the scene. Do not create walls, room, ceiling, or any extra environment elements.
```

**7. Desk**
```
Create only a modern rectangular wooden desk in the center of the scene with black metal legs. Use realistic proportions. Do not create any other objects.
```

**8. Refine the desk**
```
Refine the desk geometry with smooth edges, proper thickness, realistic materials, and clean modern styling. Only modify the desk.
```

**9. Left monitor**
```
Create one realistic 27-inch monitor on the left side of the desk with a thin bezel and modern stand. Do not create anything else.
```

**10. Right monitor**
```
Create a second matching monitor on the right side of the desk aligned symmetrically with the first monitor.
```

**11. Keyboard**
```
Create a modern black keyboard placed naturally in front of the monitors. Do not create additional accessories.
```

**12. Keyboard realism fix**
```
keyboard does not look good. it is not realistic. make it realistic and place it in front of monitors.
```

**13. Gaming chair**
```
Create a realistic ergonomic black gaming chair facing the desk with proper proportions and clean geometry.
```

**14. Move chair to correct side**
```
put chair to other side of the desk.
```

**15. Fix chair orientation**
```
fix the chair direction. it must be facing desk side
```

**16. Mouse**
```
Create a realistic mouse beside the keyboard with proper scale and placement.
```

**17. Microphone**
```
Create a modern desktop microphone near the monitors suitable for a YouTube creator setup.
```

**18. Fix chair legs**
```
fix the chair legs. do not touch anything else.
```

---

## Lighting & Atmosphere

**19. RGB accent lighting**
```
Add subtle blue and purple RGB accent lighting to the scene. Do not modify object geometry.
```

---

## Camera & Rendering

**20. Cinematic camera**
```
Position the camera for a cinematic three-quarter view of the entire setup with balanced composition and depth of field.
```

**21. Render quality**
```
Improve realism using better materials, reflections, soft shadows, ambient occlusion, and cinematic rendering quality. Do not add new objects.
```

---

## Tips for Reproducing This Scene

- Use `/blender-assembly` at the start to invoke the skill for correct geometry techniques
- Build objects **one at a time** — each prompt adds a single element
- When geometry looks wrong, prefer **"delete and rebuild"** over patching
- Always specify **"do not create anything else"** to keep focus on one object
- Use **"do not touch anything else"** when fixing specific parts (e.g. chair legs)
- Real-world dimensions in the prompts (27-inch, TKL keyboard, 130mm mic) produce better results than vague descriptions

---

## Object Inventory

| Object | Prompt # |
|---|---|
| Floor plane | 6 |
| Wooden desk + metal legs | 7–8 |
| Left monitor (27", stand) | 9 |
| Right monitor (mirrored) | 10 |
| TKL keyboard (86 keycaps) | 11–12 |
| Gaming chair (ergonomic) | 13–15 |
| Gaming mouse | 16 |
| Desktop condenser microphone | 17 |
| Chair leg fix | 18 |
| RGB blue/purple lighting (13 lights) | 19 |
| Cinematic camera (50mm, f/4 DoF) | 20 |
| Material & render quality pass | 21 |
