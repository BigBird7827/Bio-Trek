# Bio-Trek

**Bio-Trek** is a Star Trek–themed biography browser. It lets you explore character and actor biographies from across the Star Trek universe through a clean, card-based web interface, using structured JSON data and custom portrait images.

---

## What Bio-Trek Does

- **Browse Star Trek series**

  Switch between multiple Star Trek series (such as *The Original Series*, *The Next Generation*, *Deep Space Nine*, *Voyager*, and others) from a dedicated series menu. Each series presents its own set of crew cards and portraits.

- **Explore character biographies**

- **What is included**
Bio-Trek displays character and actor biographies for TOS, TNG, DS9, VOY, ENT, DIS, PIC and SNW

** What is not included**
Bio-Trek does not display biographies for TAS, LD or PRO. There are currently no plans to include animated series in the future.

  View crew-focused biographies that cover:
  - Origins and background
  - Career in Starfleet or equivalent service
  - Key missions, relationships, and story arcs
  - Notable episodes or milestones in that character’s history  

- **Explore actor biographies**

  Alongside each character, Bio-Trek highlights the actor who portrayed them. Actor bios can include:
  - Brief personal and professional background
  - Star Trek–specific roles and contributions
  - Other notable work, when relevant

- **Card-based character gallery**

  Each character is represented as a visual “card” with:
  - A portrait image (all images are AI generated)
  - Character name and role/title
  - Actor name
  Cards are organized in responsive rows so you can quickly scan a series’ ensemble at a glance.

- **Linked character ↔ actor views**

  From the same interface, you can move between:
  - A character’s in-universe biography
  - The corresponding actor’s real-world biography  
  This allows you to treat Bio-Trek as both an in-universe reference and an actor-focused guide.

- **JSON-driven bio library**

  Biographies are stored in structured JSON files grouped by series (for example, TOS and TNG), making it possible to:
  - Maintain consistent formatting across characters and actors
  - Expand the collection with additional entries and series over time
  - Reuse the same data in other Star Trek fan tools or visualizations

---

## Repository Contents

This repository is intended as a self-contained, static web project and biography library. It typically includes:

- `index.html` – the main Bio-Trek browser page with series selection and card-based biography browsing.
- `Biographies/` – JSON biography collections (e.g., TOS crew and actor bios, with room for TNG and beyond).
- `Crew/` and related folders – structured data for individual crew and actor entries, used to build combined biography files.
- `Images/` – portrait images for characters and, where appropriate, actors, sized for the on-page cards.

You can host the project via GitHub Pages or any static web server to make the biography browser available as a simple website.

---

## Project Goals

Bio-Trek is designed to be:

- **A reference library** for Star Trek characters and actors, with clearly separated in-universe and real-world sections.
- **Expandable** so additional series, characters, and actors can be added over time.
- **Simple to host** as a static site that can be shared with other fans.

- **Under Construction** - Bio-Trek is a work in progress. TOS, TNG and DS9 are complete. We are currently working on VOY and ENT, and they will be available soon.

- **NOTE:** All images, character and actor biogrophies are AI generated.

---

## Legal Notice

Bio-Trek is an **unofficial, fan-made project** created solely for entertainment and educational purposes. It is **non-commercial** and is not endorsed by, sponsored by, or affiliated with Paramount Global, CBS Studios, or any other rights holders.

**Star Trek**, including all related names, characters, images, logos, and other elements, are trademarks and/or copyrighted materials of their respective owners. All such intellectual property remains the property of those owners.

No copyright infringement is intended. This project uses references to Star Trek and its characters under principles commonly associated with fair use in the context of non-commercial fan works.
