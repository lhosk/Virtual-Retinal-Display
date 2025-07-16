# Virtual Retinal Display (VRD)

This project models a full optical system for a single-eye Virtual Retinal Display (VRD) using LightTools and supporting code. 

---

The system was modeled in LightTools with:
- Three laser sources (480, 532, 650 nm).
- Two dichroic mirrors to combine beams.
- A MEMS mirror system simulating a raster scanning pattern onto the retina.

The code was used to 
- Identify respective RGB screen absorption values to keep the total laser intensity under 1 mW.
- Convert images into spatial bins to extract RGB vectors and their intensities per region.
- Scale laser intensities based on the RGB balance of each bin for accurate color representation during scanning.
