---
title:
layout: page
---

<a rel="me" style="display:none;" href="https://mastodon.social/@tekknolagi">Mastodon</a>

# Lydia Krifka-Dobes  

I’m Lydia Krifka-Dobes—I work with [Samir Timajchi](https://samirtmajchi.com) as a computer-artist.  
- *Computer:* (99% open source software and hardware, 1% other)  
- *Artist:* (51% sound and 49% other mediums)  

---

## Studies and Background  

- *Studies at* [Institute of Sonology](https://www.sonology.org/)  
- *Gap Year at* Conservator Evangelicky Academy  
- *High School* at Beethoven Gymnasium  
- *Studied at* [School for Poetic Computation](https://sfpc.io/)  
- *Based in* Den Haag and Berlin  
- *Born in* Austin, Texas  

---

```javascript
system_boot = {
   artist: "lydia_krifka-dobes",
   location: "berlin",
   status: "exploring_the_glitch",
   focus: ["sound", "identity", "technology"],
   collaborators: ["humans", "machines", "systems"]
}
```
## About

I write about experimental music, art-technology hybrids, and the poetics of code. Collaborate with me! I’m always open to new projects and opportunities.

You can email me at opensourcereartwork@gmail.com if you want to discuss art, technology, identity, or anything in between. I’m happy to engage in mind-expanding conversations!

## Current Research

## Research Projects Overview  

Our work operates at the intersection of *thermal-acoustic interaction, **language preservation through computational methods, and **deep fake transformation* using advanced machine learning pipelines.

---

## 1. Temperature & Sound Research  

### Overview  
At the intersection of physiological response and artistic expression, this research explores how temperature changes affect our perception and experience of sound.  

---

### Sauna Project Development  
Collaborating with [Borealis Festival](https://borealisfestival.no/) in Bergen, we're pioneering new approaches to immersive sound experiences in extreme temperature environments.  

*Key Components:*  
- Full-scale sauna installations  
- Cold water immersion environments  
- Temperature gradient zones for performance  
- Real-time acoustic monitoring systems  

---

### CHILLER Technology Integration  
The [NYU CHILLER sensor](https://engineering.nyu.edu/) enables unprecedented tracking of audience physiological responses, opening new possibilities for interactive performance.  

*Technical Specifications:*  
- 20mm x 20mm polymer construction  
- High-precision skin texture monitoring  
- Real-time piloerection detection  
- Multiple sensor array capability  

---

### Goosebumps Research  
- Studying the relationship between temperature changes and sensory responses.  
- Combining ASMR sounds, brass registers, and rapid thermal shifts.  
- Exploring the potential of wind machines to induce shivers in localized zones (e.g., eyes and sinus areas).  

---

### Insights from Correspondence  

*Subjectivity of Goosebumps:*  
- Responses to sonic or temperature stimuli vary widely between individuals.  

*Rapid Temperature Changes:*  
- Goosebumps are more likely to occur with sudden shifts rather than at specific thresholds.  

*Relevant Works and Practices:*  
- [The Flicker](https://en.wikipedia.org/wiki/The_Flicker) by Tony Conrad  
- [Philippe Rahm's Convection Spaces](http://www.philipperahm.com/data/convection.html)  
- Native American sweat lodge practices, which inspired early [SWANS](https://en.wikipedia.org/wiki/Swans_(band)) performances  
- Sensory installations by [Olafur Eliasson](https://en.wikipedia.org/wiki/Olafur_Eliasson)  

---

## 2. Language Preservation Project  

### Overview  
This project documents and analyzes the acoustic diversity of human languages through high-fidelity recordings, computational analysis, and creative reinterpretation.  

---

### Framework Structure  

Our archive centers on [The Oak and the Reed](https://en.wikipedia.org/wiki/The_Oak_and_the_Reed) fable, chosen for its rich phonetic content and narrative structure.  

*Recording Architecture:*  
- 12 parallel sentences with identical semantic content  
- 24-bit/96kHz audio capture  
- Controlled recording environments  
- Multiple takes per speaker  
- Ambient noise profiling  
- Room impulse response measurements  

---

### Language Collection  

We are working with 21 languages across multiple language families, including endangered ones:  

- *Austronesian:*  
  - [Indonesian](https://en.wikipedia.org/wiki/Indonesian_language)  
  - [Malagasy](https://en.wikipedia.org/wiki/Malagasy_language)  
  - [Samoan](https://en.wikipedia.org/wiki/Samoan_language)  

- *Caucasian:*  
  - [Abkhazian](https://en.wikipedia.org/wiki/Abkhaz_language)  

- *Language Isolates:*  
  - [Basque](https://en.wikipedia.org/wiki/Basque_language)  

- *Germanic:*  
  - [Bavarian](https://en.wikipedia.org/wiki/Bavarian_language)  

- *Creole Languages:*  
  - [Bislama](https://en.wikipedia.org/wiki/Bislama_language)  
  - [Rodriguan Creole](https://en.wikipedia.org/wiki/Rodriguan_Creole_language)  

- *Endangered Pacific Languages:*  
  - [Daakie](https://en.wikipedia.org/wiki/Daakaka_language)  

- *African Languages:*  
  - [Hausa](https://en.wikipedia.org/wiki/Hausa_language)  
  - [Khoekhoe](https://en.wikipedia.org/wiki/Khoekhoe_language)  
  - [Yoruba](https://en.wikipedia.org/wiki/Yoruba_language)  

- *Asian Languages:*  
  - [Malayalam](https://en.wikipedia.org/wiki/Malayalam_language)  
  - [Vietnamese](https://en.wikipedia.org/wiki/Vietnamese_language)  

- *Mayan Family:*  
  - [Yucatec Maya](https://en.wikipedia.org/wiki/Yucatec_Maya_language)  

---

### Technical Implementation  

*Segmentation Pipeline:*  
- Using [WhisperAI](https://github.com/openai/whisper) for sentence-level segmentation.  
- Phonetic alignment with [Web-MAUS](https://clarin.phonetik.uni-muenchen.de/BASWebServices/interface/WebMAUS).  

*Naming Conventions:*  
[LANG]-[SENT]-[WORD]-[SYLL]-[PHON]-[SAMPA].wav
Example: ABKH-3-4-2-3-O.wav
*Phonetic Analysis Tools:*  
- Vowel space mapping  
- Consonant cluster analysis  
- Prosodic feature extraction  
- Tonal pattern recognition  

---

### Main Composition  

Inspired by Trevor Wishart’s [Globalalia](https://www.youtube.com/watch?v=DWkxPP6Ndng), the main composition reimagines the Aesop fable through:  
- Strong, rigid oak tree: low sonority (voiceless stops)  
- Weak, flexible reeds: high sonority (vowels)  
- Water and wind as dynamic, sonic elements  

---

## 3. Deep Fake Transformation Project  

### Overview  

This project reimagines deep fake technology as an artistic tool for interactive, real-time data morphing across mediums like audio and video.  

---

### Binary Search Trees & Granular Synthesis  

*Concept:*  
- *Binary Search Trees (BST):* Organize data into sorted nodes based on comparisons.  
- *Granular Synthesis:* Breaks audio into tiny "grains" for micro-level manipulation.  

*Applications:*  
- Sorting audio by *frequency centroid* or *RMS value*.  
- Organizing video data by *brightness* or *edge sharpness*.  
- Morphing data between mediums in real time.  

---

### Procedure  

1. *Audio Transformation:*  
   - Sorting samples by pitch or amplitude.  
   - Creating evolving sonic landscapes.  

2. *Visual Transformation:*  
   - Sorting pixels by color intensity or spatial frequency.  
   - Dynamic texture generation.  

3. *Interactive Control:*  
   - Multi-touch interfaces for real-time manipulation.  
   - OSC and MIDI integration for external device control.  

---

### Technical Challenges  

*Processing Large Datasets:*  
- Efficient real-time analysis of audio and video.  
- Integration of OpenCV for computer vision tasks.  

*Creative Opportunities:*  
- Combining granular synthesis with dynamic particle systems.  
- Leveraging Perlin noise for generative meshes.  

---

### Ethical Considerations  

*Consent & Transparency:*  
- Explicit consent for data usage in deep fake creation.  
- Ensuring viewers understand the artificial nature of the work.  

*Artistic Responsibility:*  
- Using deep fake technology to provoke critical thought on *identity, **authenticity, and **perception* rather than deception.  

---

## Contact  

For collaboration inquiries, reach out at [opensourcereartwork@gmail.com](mailto:opensourcereartwork@gmail.com).