# Expertise Area Development — 10 Minute Presentation Outline

14 slides in 10 minutes is roughly 40 seconds a slide. Bullets below are kept short and spoken-style on purpose, treat them as talking points to expand on out loud, not text to read off the slide.

All content is pulled from your existing portfolio pages (Vision & Identity, Expertise Areas, Future, project pages) and your coach's notes. Two flags before the outline:

- No source material exists anywhere in the portfolio for the **Arduino MIDI workshop (Jong Cultuur Eindhoven)**. I've left it as a placeholder on the Extracurricular slide rather than invent content, send me a couple of details and I'll fill it in.
- The **Expertise Areas Overview** slide is your visual to design, so I haven't written slide content for it, only a couple of suggested talking points for narrating it.

---

## 1. Vision

- Problem: digital music tools (screens, knobs, sliders) lost the embodied richness of playing a real instrument
- Deformable interfaces treat expression as continuous motion instead of discrete control
- My question: how can deformable interfaces enable musical expressivity?
- Two design principles: high-resolution sensing of fine motor skill, and entangling multiple sound parameters into one gesture
- Music as a safe testbed: insights can transfer to gaming, automotive, and beyond

## 2. Identity

- "A designer's designer": I design through making, first-person, rather than handing it off
- Roots in open-source 3D printing since my bachelor's, building and modifying my own printers
- Research through Design: I design through inquiry, not a fixed brief
- Growth point: the Preparation Project showed I can over-rely on solo making; the thesis pushed me to learn co-design
- Core belief: design and tools should be openly accessible, but shared thoughtfully (modular release, not blind open-sourcing)

## 3. M11 — Aqua-Morph

- First Master's project, applying the Material Driven Design (MDD) method
- Accessible method for 3D-printing hydrogel structures that self-actuate in water
- Two contributions: a Design Manual (FDM fabrication pipeline) and a Tangible Movement Library of shape-changing structures
- Published and presented at TEI '25 (ACM)

## 4. M12 — Greebling

- Texturing tool for Blender, made physical as a capacitive pressure-sensing MIDI interface
- Builds on existing HCI work: Capricate, HapticPrint, X-Hair
- Combined flexible and conductive filaments to sense touch, proximity, and pressure through 3D-printed texture
- First deep dive into the Pico-SDK / RP2040, programmed in C, for fast, responsive sensing
- Evaluated with creative users; demoed as a live musical interface

## 5. Isomorphic Hall-effect Keyboard

- Self-initiated project, "a summer project that got out of hand"
- MIDI keyboard with a hexagonal, isomorphic key layout
- Hall-effect switches give polyphonic aftertouch, every key sensed independently
- Built on RP2040 / C / MIDI, the same technical backbone as Greebling and Sonable
- Bridges directly into the hall-effect sensing approach used in Sonable and Tabula

## 6. M21 — Sonable

- Preparation project for the FMP: modular compliant mechanisms users can combine into their own DMI
- 3D hall-effect sensing per module detects bending, twisting, pressing, pulling
- Wrote my own SPI library for the MLX90395 sensor, first project requiring C++ and embedded OOP
- USB MIDI output for free parameter mapping in any DAW
- Same compliant-mechanism logic could extend to gaming controllers and automotive interfaces

## 7. FMP — Tabula

- Thesis question: how can deformable interfaces enable musical expressivity?
- Three design iterations, co-created with two expert electronic musicians
- Combines 3D-printed compliant mechanisms (foamed TPU, polypropylene) with hall-effect sensing
- Fabricated my own double-sided PCBs in KiCad for more complex circuits and sensors
- Finding: entangling two or more sound parameters into one multi-axis gesture grants expressivity through fine motor control and surprising sonic outcomes
- Thematic analysis of the co-creation sessions produced a working definition of "expressivity" in deformable DMI design, grounded in existing HCI research
- Beyond music: transfers to gaming and automotive/mobility contexts

## 8. Extracurricular

- Isomorphic Keyboard: hexagonal hall-effect MIDI keyboard with polyphonic aftertouch (previous slide)
- Studio Subwoofer: 250W sealed DSP subwoofer, designed around a simulated frequency response target (WinISD + Fusion 360)
- Arduino MIDI workshop, Jong Cultuur Eindhoven: co-hosted with Gion Berlijn; my prior MIDI controller work (Greebling, Isomorphic Keyboard, Sonable) prompted the invitation; three Arduino and MIDI novices each built a functional device, used live with TouchDesigner and Ableton Live
- Music production and DJing across Eindhoven, Tilburg, and Den Bosch: built a community that opened doors to DJ gigs, one-on-one Ableton lessons, workshop invitations, and ultimately the ability to recruit suitable participants for my FMP co-design process

## 9. Expertise Areas Overview (visual)

This is your diagram to build. Two optional talking points for narrating it, straight from your coach's notes:

- Suggested throughline: technical, MDD-driven exploration (T&R + C&A) → growing want for societal impact (U&S) → realized and tested through live performance and DMI design (B&E) → backed by deepening MDC skills throughout
- T&R and C&A as your intertwined core, MDC as the technical backbone enabling both, U&S and B&E as where the work meets people, users, and industry

## 10. Technology and Realization

- Making is the core of how I design: hands-on with 3D printing since my bachelor's, deepened across every MSc project
- Material range: TPU (standard, 95A, foamed), polypropylene, hydrogel, conductive filament
- From single-material prints to embedded circuits: double-sided PCBs designed in KiCad (Tabula)
- Years of hands-on material testing built real insight into the haptic, interactive qualities each material offers a user (→ U&S)

## 11. Creativity and Aesthetics

- Inseparable from T&R: I look for the design opportunity in a fabrication constraint, not the limit
- Pushing back on the stigma that 3D printing is "just prototyping," through functionally and aesthetically considered design
- Interactive Materiality trained me to read material qualities as interaction cues
- A second creative practice: sound design, from playing instruments since my teens to producing electronic music (The Sound of Smart Things)
- MDD applied repeatedly (Aqua-Morph, CDR, UME) built a deep, transferable understanding of TPU's material parameters

## 12. Math, Data and Computing

- Shifted from desktop software in my bachelor's (Java, Processing, Python) to embedded/microcontroller work in the master's, for the responsiveness music interfaces need
- Pico-SDK / RP2040 in C (Greebling), then C++ embedded OOP and a custom SPI library for the MLX90395 sensor (Sonable)
- Deliberately avoid LLMs for under-documented embedded work, they slow me down more than they help
- Also explored outside embedded devices: DUIET turned my bass guitar into a MIDI controller via ArUco markers
- This technical fluency is what lets me iterate quickly on design concepts (→ T&R, C&A)

## 13. User and Society

- Growth area this semester: in my bachelor's I was usually the technician, rarely running user tests myself
- For the FMP, I ran my own co-design process with two expert musicians who aren't designers
- Active membership in the Eindhoven/Tilburg/Den Bosch music communities gave me a first-person, insider understanding of the user group I design for — and directly enabled recruiting the right FMP participants
- E-Lab / 3D-Print Farm role taught me to manage stakeholder expectations: people assume FDM can do everything, or nothing, the real value is in finding the middle ground
- Reconciling two identities: the musician and the designer in me turned out to be deeply intertwined
- Thematic analysis of the co-design sessions produced a definition of "expressivity" I can explain to non-academics too

## 14. Business and Entrepreneurship

- Tabula isn't for sale yet, it's a design research artifact, though multiple musicians have already asked to buy one
- I sell my vision through how the work is shown: prototyping skill makes demos look effortless and museum-quality, which reads as state of the art
- Networking through exhibitions: TEI '25 (Aqua-Morph) and Dutch Design Week build visibility and connections in both academic and design communities
- Networking through music: DJing and producing across Eindhoven, Tilburg, and Den Bosch built a community that opened doors to DJ gigs, Ableton lessons, workshop invitations, and recruiting the right participants for my FMP co-design process
- I'm a confident, ad hoc presenter, a skill built up through the master's
- Already giving MIDI controller masterclasses, a direct extension of my MDC development
- Strategy: started from technical, MDD-driven material samples; now aiming for societal impact through live performance and introducing technical interfaces to wider audiences
- Building visibility through my own compositions and live sets, plus synth/modular events like Dutch Modular Fest

## 15. Future

- Ruling out academia for now, despite the CDR track, nine years of school is enough for a while
- Job direction: roles using T&R/MDC strengths for prototyping and production (e.g. CAD FDM specialist, like my E-Lab role), with enough variety to stay engaged
- Music interface industry is small and niche (Arturia, Intuitive Instruments, Expressive E, Dato), plan to keep building this work and my network through live performances in my free time
- Near-term: Dutch Design Week for Tabula, building a more robust, week-durable version to widen exposure
