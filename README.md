# DIY-Spectrometer
Using easily available materials, we built a working, affordable spectroscope that could split light into its component wavelengths.   This project enables us to capture, process, and analyse the spectrum of light using Python-based tools for scientific study.Reading and processing images of spectra  using Python libraries (e.g., OpenCV, NumPy).
# 🔬 DIY Spectrometer

A low-cost, hands-on spectrometer built from cardboard, a webcam, and an old DVD — designed to split light into its component wavelengths and reveal the hidden spectra emitted or absorbed by everyday sources.

<img src="./assets/spectrum-diagram.png" width="450" alt="Light splitting into a visible spectrum through a diffraction grating" />

> **Mini Project — Engineering Physics (EN3BS16)**
> Medi-Caps University, Indore · Department of Physics
> Branch: CS | Section: P3 | Session: Jan 2025 – May 2025

---

## 📖 Overview

A DIY spectrometer is a low-cost, hands-on device that lets you explore the science of light and color. By splitting light into its component wavelengths, it reveals the hidden spectrum emitted or absorbed by various sources. Using simple materials — a cardboard box, a slit, a CD/DVD as a diffraction grating, and a smartphone or webcam — you can observe and record spectra from sunlight, LED bulbs, and more.

The core idea: an unknown beam of light is directed onto an optical element that splits it based on the wavelengths present. Each wavelength deviates by a different amount, so measuring that deviation reveals what wavelengths make up the light — and therefore something about its source, even if that source is millions of kilometers away.

Historically, scientists used prisms and a pivoting eyepiece to measure this angular deviation. Modern setups replace the prism with a **diffraction grating** and the eyepiece with an **electronic photoreceptor array** connected to a computer — which is exactly the approach this project takes.

---

## 🎯 Objectives

- Apply theoretical physics concepts to hands-on project work
- Develop innovative and creative problem-solving skills
- Practice effective collaboration as part of a team
- Strengthen communication and presentation abilities
- Gain experience budgeting and managing tasks within a timeline

---

## 🧰 Materials Required

| Material | Purpose |
|---|---|
| Cardboard | Enclosure body |
| Black chart paper | Internal light-blocking lining |
| Old DVD disk | Diffraction grating |
| Razor blades | Cutting slits and cardboard |
| Webcam | Light sensor / capture device |
| Glue | Assembly |
| Tape | Assembly / sealing light leaks |

<img src="./assets/build-materials.jpeg" width="500" alt="Materials and enclosure pieces used to build the spectrometer" />

---

## ⚙️ Principle of Working

The spectrometer works on the principle of **diffraction and dispersion of light**.

1. Light passes through a **narrow slit**, forming a thin beam.
2. The beam strikes a **diffraction grating** (a CD or DVD in this build).
3. The grating **bends and spreads the light into its component wavelengths** — diffraction.
4. Each wavelength (color) bends by a different amount, separating white light into a visible spectrum.

<img src="./assets/diffraction-diagram.png" width="500" alt="Diagram showing diffraction of light through a grating into a spectrum" />

---

## 🛠️ Build Process

**Sizing the enclosure** — measurements are taken from the webcam (height, width, lens height) so the box is built to fit it exactly:

- **Length:** 20–25 cm
- **Width:** 2 cm larger than the webcam
- **Height:** 1 cm taller than the webcam

**Assembly steps:**

1. **Overview of spectrophotometer theory** — understand diffraction/dispersion before building
2. **Gather materials** — see table above
3. **Cut the enclosure pieces** — trace all 6 faces onto cardboard using the dimensions, cut with a knife; add a cable slot on the rear face and a 2 cm × 1 cm slot on the front face at lens height
4. **Assemble the enclosure** — line all faces with black chart paper (glued and trimmed to the cardboard edges) to block stray light, then join the faces
5. **Cut the entrance slit** — a narrow slit on the front face to admit a thin beam of light
6. **Mount the diffraction grating** — position the DVD fragment at the correct angle inside the box
7. **Mount the camera** — align the webcam to capture the dispersed spectrum
8. **Test** — check for light leaks and a visible spectrum band
9. **Use analyzer software** — capture and process the spectrum on a computer
10. **Final result** — a working low-cost spectrometer

---

## 🌱 Applications

- **Education** — visualizing light spectra for teaching physics and chemistry
- **Environmental monitoring** — analyzing light pollution or LED bulb quality
- **Plant studies** — monitoring photosynthetically active radiation (PAR)
- **DIY lab projects** — calibrating lasers or LEDs

## ⚠️ Limitations

- Low resolution
- Calibration issues
- Limited sensitivity
- Narrow wavelength range
- Stray light and noise
- Inconsistent build quality
- Software limitations

## 🚀 Future Scope

- **Educational use** in schools and science outreach programs
- **Citizen science** — hobbyist environmental monitoring (e.g. detecting pollutants in light sources)
- **Upgrades** — smartphone, software, or Arduino/Raspberry Pi integration for digital spectrum analysis and data logging
- **Low-cost research** — spectral analysis in resource-limited biology, chemistry, or environmental science settings
- **Further innovation** — inspiring custom-built spectrometers with improved accuracy and functionality

---

## 👥 Team

| Name |
|---|---|
| Aditi Rohan | 
| Akshita Kushwaha | 
<img src="./assets/university-logo.jpeg" width="120" alt="Medi-Caps University logo" />

**Medi-Caps University, Indore** · Department of Physics
