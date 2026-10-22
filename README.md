# Awesome-Image-Editing

# Top Image Editing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Raster Manipulation, Photo Retouching & Self-Hosted Creative Workflows*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Image Editing**. These tools enable photographers, designers, and artists to manipulate raster images—retouching photos, compositing layers, applying filters, and preparing assets for print or web—ranging from full professional suites to lightweight browser-based editors.

**Examples** include Adobe Photoshop, Affinity Photo, Canva, Photopea, GIMP, Krita, and Pinta (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription lock-in, and transparent image manipulation—ideal for photographers leaving Adobe's subscription model, designers wanting native Linux workflows, and anyone who believes creative tools should not require a monthly fee. The open-source landscape is anchored by **GIMP** (the veteran powerhouse with GIMP 3.0's non-destructive editing and new file format support), **Krita** (the artist's painting engine), and **PhotoGIMP** (a UI patch that makes GIMP feel like Photoshop), with **Pinta** serving beginners and **PhotoDemon** offering a portable Windows alternative.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Adobe Photoshop](https://www.adobe.com/products/photoshop.html)**  
  The industry standard for raster image editing. Generative Fill, neural filters, and comprehensive brush/selection engines. **Subscription-only**: ~$23/month for Photoshop alone . Proprietary, cloud-tied licensing.

- **[Affinity Photo](https://affinity.serif.com/photo/)**  
  Professional-grade photo editor with a one-time purchase model (no subscription). Strong RAW processing, focus stacking, and HDR merge. **Note**: Affinity has shifted toward a free model for some tiers; verify current licensing on the official site . Proprietary.

- **[Canva](https://www.canva.com/)**  
  Browser-based design platform with drag-and-drop templates, AI tools, and basic photo editing. Free tier with premium assets; Pro subscription for advanced features. Best for social media content and non-professional design workflows.

- **[Photopea](https://www.photopea.com/)**  
  **Browser-based Photoshop clone** with remarkable PSD compatibility. Free tier is ad-supported; premium removes ads. Runs entirely in the browser—no installation. Best for quick edits on machines without software installed, or for opening PSD files without Photoshop.

- **[Pixlr](https://pixlr.com/)**  
  Browser-based photo editor with AI-powered tools. Free tier with limited features; premium unlocks advanced tools. Best for quick, casual edits.

- **[Luminar Neo](https://skylum.com/luminar)**  
  AI-focused photo editor with sky replacement, relighting, and portrait enhancement. One-time purchase or subscription. Best for photographers who want creative AI transformations rather than manual retouching .

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
