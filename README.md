# Awesome-Image-Editing

## Top Image Editing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Raster Manipulation, Photo Retouching & Self-Hosted Creative Workflows*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Image Editing**. These tools enable photographers, designers, and artists to manipulate raster images—retouching photos, compositing layers, applying filters, and preparing assets for print or web—ranging from full professional suites to lightweight browser-based editors.



**Examples** include Adobe Photoshop, Affinity Photo, Canva, Photopea, GIMP, Krita, and Pinta (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription lock-in, and transparent image manipulation—ideal for photographers leaving Adobe's subscription model, designers wanting native Linux workflows, and anyone who believes creative tools should not require a monthly fee. The open-source landscape is anchored by **GIMP** (the veteran powerhouse with GIMP 3.0's non-destructive editing and new file format support), **Krita** (the artist's painting engine), and **PhotoGIMP** (a UI patch that makes GIMP feel like Photoshop), with **Pinta** serving beginners and **PhotoDemon** offering a portable Windows alternative.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global photo editing software market was valued at approximately $1.15B to $1.2B in 2024 (projected between $1.2B and $14B+ depending on inclusion of broader digital content and generative creation suites) and is forecast to expand at an 8–10% CAGR through 2030. The industry displays a highly concentrated, winner-take-most dynamic in the professional and enterprise creative tier dominated by Adobe, while showing moderate fragmentation across prosumer, browser-based, and mobile casual content creation segments led by Canva and various niche innovators.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Starting Tier Pricing | Free Tier Limits / Free Trial | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Photoshop](https://www.adobe.com/products/photoshop.html)** | ~$146.5B Market Cap / $23.8B Revenue (Adobe FY25) | $22.99/mo (annual commitment) or $19.99/mo (Photography plan) | 7-day free trial with full feature access (requires payment info; auto-renews unless canceled) | Industry standard for professional raster image editing, layer compositing, and generative AI features. |
| **[Canva](https://www.canva.com/)** | $42B Valuation / ~$3.5B ARR (2025) | $15.00/mo or $120.00/yr ($10/mo billed annually) for Canva Pro | Free-for-life tier with 5 GB storage, ~1.6M templates; limited to basic exports (no background remover, magic resize, or transparent PNGs) | Browser-based design and visual communication platform with drag-and-drop templates and AI tools. |
| **[Affinity Photo](https://affinity.serif.com/photo/)** | ~$380M Acquisition by Canva (2024) | Free core suite (Canva Pro from $15/mo for integrated AI features) | Free-for-life core application access via free Canva account login; optional paid Canva subscription for cloud AI features | Professional raster editing, RAW development, and layered compositing suite without subscription fees for core tools. |
| **[Skylum Luminar Neo](https://skylum.com/luminar)** | ~$55M–$60M Implied Valuation / ~$18M ARR | $9.95/mo (billed annually at $119/yr) or $14.95/mo monthly | 7-day free trial covering core application and AI tools (watermark/resolution restrictions may apply to exports) | AI-centric photo editor featuring generative tools, sky replacement, relighting, and portrait enhancement. |
| **[Pixlr](https://pixlr.com/)** | ~$9.1M Revenue (Subsidiary of Inmagine Group) | $1.99/mo (Plus Plan, billed annually at $23.88/yr) or $2.49/mo | Free-for-life tier with ad-supported interface, limited to ~3 saves per day and 20 starter AI credits | Browser-based photo editor providing quick raster manipulation, templates, and lightweight AI utilities. |
| **[Photopea](https://www.photopea.com/)** | Bootstrapped solo venture / ~$2M+ Annual Revenue | $5.00/mo (Single User Premium) or $15.00/quarter | Free-for-life tier with full tool access and no watermarks; includes sidebar ads and 0.5 GB PeaDrive cloud storage limit | Web-based Photoshop clone offering deep PSD/PSB compatibility, full layer controls, and zero software installation. |

## Open-Source GitHub Projects



- **[GIMP](https://github.com/GNOME/gimp)**  

  **The veteran open-source image editor.** **GIMP 3.0** (released March 2025) is the biggest update in years: **non-destructive editing** for most filters, improved PSD export with layer and metadata preservation, support for JPEG XL, ICNS, and BC7 DDS formats, better text tools with non-destructive outlines, and multi-layer selection . **Trade-offs**: the UI remains idiosyncratic and requires relearning if you're coming from Photoshop; some workflows (like adjustment layers) still lag behind commercial tools. Best for users who want a full-featured editor without subscriptions and are willing to invest time in learning its way of working.



- **[PhotoGIMP](https://github.com/Diolinux/PhotoGIMP)**  

  **The Photoshop-to-GIMP bridge.** A patch (not a fork) that transforms GIMP's interface into a Photoshop-like layout: single-column toolbar on the left, tool options and layers on the right, **Photoshop keyboard shortcuts** (Ctrl+T to transform, Ctrl+D to deselect), and a dark theme with simplified icons . **Requires GIMP 3.0+** and that you run GIMP once before applying the patch. **Caveat**: GIMP updates may overwrite the patch, requiring reapplication . Best for Photoshop users who want to try GIMP without fighting muscle memory—it's the single most effective on-ramp to open-source image editing.



- **[Krita](https://github.com/KDE/krita)**  

  **The artist's editor.** A powerful digital painting application with a serious brush engine, layered editing, masks, vector tools, and animation timeline . **Not a Photoshop replacement for photo retouching**—Krita is built for drawing and painting from scratch. Best for illustrators, concept artists, and anyone whose work leans more artistic than photographic.



- **[Pinta](https://github.com/PintaProject/Pinta)**  

  **The beginner-friendly editor.** Deliberately simple: layers, selection tools, color adjustments, filters, gradients, and brushes, all laid out predictably . Originally a Paint.NET alternative for Linux/macOS. **Not suitable for professional workflows**, but perfect for everyday edits, screenshots, and basic designs. Best for users who find GIMP intimidating and just need to crop, annotate, and adjust.



- **[PhotoDemon](https://github.com/tannerhelland/PhotoDemon)**  

  **The portable Windows alternative.** Free, open-source, fully portable (no installation), with non-destructive layers, masks, wide color depth support, and **better PSD handling than most open-source tools including GIMP** . Batch processing and a streamlined interface. Best for Windows users who want professional-level features without installation or subscription.



- **[Bitmappery](https://github.com/igorski/bitmappery)**  

  **The browser-based minimal editor.** Self-hosted, web-based, non-destructive with layers, masking, filters, selections, and PSD imports . Runs on any device with a browser. Best for users who want a privacy-focused, zero-install editor for essential edits.



### Additional Strong Open-Source Options



- **Graphite** — Browser-based progressive web app with hybrid vector-raster editing and a node graph for non-destructive procedural workflows. In alpha but already impressive . Best for designers wanting a modern, Affinity-like vector tool.

- **Scribus** — Desktop publishing for print layouts (brochures, newsletters, magazines). Not an image editor per se, but essential for print workflows that require layout . Best for print designers needing an InDesign alternative.

- **PhotoSplice** — Rust-based editor built on PhotoCraft, focused on **1:1 native PSD/PSB compatibility** and classic Photoshop (CS6) feel. GPU-optimized, no Electron . Best for users who need flawless PSD round-tripping with Photoshop.

- **Frameworks for building custom systems**: Start with **GIMP + PhotoGIMP** for a Photoshop-like experience. Use **Krita** for painting and illustration. Use **Pinta** for quick edits and **PhotoDemon** for portable Windows work. For print layout, add **Scribus**. For PSD compatibility without Adobe, evaluate **PhotoSplice**.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **PhotoGIMP is a patch, not a separate application**: it modifies GIMP's configuration files and requires GIMP 3.0+. Updates to GIMP may overwrite the patch, requiring reinstallation .

- **GIMP 3.0 is a major release**: some third-party plugins and scripts written for GIMP 2.10 may not work without updates. Verify plugin compatibility before migrating critical workflows .

- **"Photoshop clone" claims vary**: Photopea is genuinely browser-based with PSD support; PhotoCraft/ArtCraft is an early-stage AI-assisted reverse-engineering project with subscription-gated AI features . Evaluate maturity before relying on any tool for production work.



---



**Made for photographers, designers, artists, and anyone who believes creative tools should not require a subscription.**  

Let's make image editing more open, accessible, and Photoshop-familiar.
