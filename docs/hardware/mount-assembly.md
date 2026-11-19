# Mount Assembly

Use this page as your step-by-step build checklist.

---

## Mount reference images

<div style="display: flex; gap: 18px; justify-content: center; margin: 22px 0;" markdown="1">

<figure style="margin: 0; flex: 1; text-align: center;" markdown="1">
![Mount structure](../assets/mount_hardware_1.png){ style="border-radius: 10px; box-shadow: 0 6px 14px rgba(0,0,0,0.35); width: 100%;" }
<figcaption style="opacity: 0.75; margin-top: 10px;">Mount structure</figcaption>
</figure>

<figure style="margin: 0; flex: 1; text-align: center;" markdown="1">
![Phone holder detail](../assets/mount_hardware_2.png){ style="border-radius: 10px; box-shadow: 0 6px 14px rgba(0,0,0,0.35); width: 100%;" }
<figcaption style="opacity: 0.75; margin-top: 10px;">Phone holder detail</figcaption>
</figure>

</div>

---

## CAD files

Download the mount model and print it before assembly (see [Printing](printing.md) for settings).

| File | Format | Size | Use |
|------|--------|------|-----|
| [drone_mount.stp](../assets/cad/drone_mount.stp){ download } | STEP (AP214) | 2.4 MB | Open in Fusion 360, SolidWorks, FreeCAD, Onshape to edit or export STL |

!!! tip
    Most slicers cannot open STEP directly. Export to STL/3MF from your CAD tool first.

---

## Assembly steps

1. **Dry-fit**
   - Phone inserts smoothly
   - No force required

2. **Install fasteners / inserts (if used)**
   - Do not overtighten into plastic

3. **Add straps/velcro**
   - Straps should not cover camera/IMU areas

4. **Vibration damping (optional)**
   - Add pads only where they do not allow “wobble”

---

## Mount QA checklist

- [ ] Phone is centered and stable
- [ ] Camera view is clear
- [ ] No contact with moving parts
- [ ] No sharp edges / abrasion points
