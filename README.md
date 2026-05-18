# Solar Box Dehydrator - CAD Files

This repository has all the CAD and STEP files for a vented solar box dehydrator we designed in SolidWorks. All the parts can be cut on a CNC router, which is how we made ours.

---

## Materials

| Part | Material |
|---|---|
| Structural panels (bottom, walls, top) | 1/4" Plywood |
| Front panel | Plexiglass (acrylic) |
| Vent covers | Stainless steel wire mesh (purchased separately) |

We used plywood for the structural parts because it's easy to cut and holds up well. The plexiglass front panel is angled to face the sun, letting sunlight in to heat the inside, which is what drives the dehydration process. Stainless steel wire mesh covers the air vents to keep insects out while still allowing airflow.

---

## Files

All parts are provided as STEP files (`.step`), which can be opened in essentially any CAD software including SolidWorks, Fusion 360, FreeCAD, and OnShape.

| File | Description |
|---|---|
| `0_ASSEMBLY.step` | Full assembly showing how all the parts fit together |
| `1_bottom.step` | Bottom panel |
| `2_back_wall.step` | Back wall |
| `3_top_panel.step` | Top panel |
| `4_side_wall_left.step` | Left side wall |
| `5_side_wall_right.step` | Right side wall |

We'd recommend opening `0_ASSEMBLY.step` first to get a feel for how everything fits together before diving into the individual parts.

Note: the plexiglass front panel and the stand were not CAD modeled. The plexiglass was cut directly in the CNC software, and the stand was built separately.

---

## Fabrication

### CNC Routing

All parts are designed to be cut on a CNC router. A few things worth knowing if you're making this yourself:

- For the plywood panels, a standard upcut or downcut spiral end mill works well. A downcut bit gives cleaner edges on the top surface.
- For the plexiglass panel, go slower and use a single-flute or O-flute bit. Plexiglass melts easily if the feed rate is too high.
- Use tabs or other workholding to keep parts from moving during cutting, especially the thinner wall panels.

### Assembly

The parts fit together as a wedge-shaped box. Check `0_ASSEMBLY.step` to see how everything goes together. The angled front face holds the plexiglass panel, which faces the sun to capture solar heat. The vented design lets air flow through the box, and stainless steel wire mesh over the vents keeps insects out. Panels were joined together primarily using L-brackets.

---

## Opening the Files

To open `.step` files:
- **SolidWorks**: File, then Open, then select the `.step` file
- **Fusion 360**: Upload to a project and open from the browser panel
- **FreeCAD**: File, then Import, then select the `.step` file (free and open source)
- **OnShape**: Import into a document (free, browser-based)

---

## License

Feel free to use, modify, and build on these designs. If you make improvements, we'd love to see them!