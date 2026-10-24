# Awesome-3D-Material-Digitization-Capture

## Top 3D Material Digitization & Capture Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Photo-to-PBR Conversion, Procedural Material Authoring & Self-Hosted Texture Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Material Digitization & Capture**. These tools transform photographs, scans, and procedural inputs into game-ready PBR materials—albedo, normal, roughness, metallic, ambient occlusion, and height maps—ranging from AI-assisted commercial suites to lightweight open-source converters.



**Examples** include Adobe Substance 3D Sampler, InstaMAT, Materialize, AwesomeBump, and Material Maker (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription fees, and controlling the texture pipeline. The open-source landscape is anchored by **Materialize** (the long-standing image-to-PBR converter with a slider-driven workflow and live 3D preview), **AwesomeBump** (the GPU-accelerated normal/height/specular generator), and **Material Maker** (the node-based procedural authoring tool built on Godot), with **ComfyUI-SuperPBR** and **TextureForge** serving AI-assisted and browser-based needs respectively.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Adobe Substance 3D Sampler](https://www.adobe.com/products/substance3d/apps/sampler.html)** | Photo-to-material capture with AI-assisted delighting, tiling, and PBR map generation, bundled in Adobe's Substance ecosystem. | **Substance 3D Texturing plan**: ~$24.99/month (annual prepaid ~$249.99/year), includes Sampler, Designer, and Painter . **Full Collection**: ~$60/month . | **30-day free trial** via Adobe account . No permanent free tier for the application itself. |

| **[Quixel Mixer](https://quixel.com/mixer)** | **Discontinued.** Final version 2023.1 released free, runs offline indefinitely, no further updates or support . | **Free** (final version, requires Epic Games account) . | **Fully free** final version with 800+ built-in assets, but **no online library access** and no future updates . |

| **[InstaMAT](https://www.instamat.com/)** | Material authoring and texturing tool positioned as a Substance alternative, with layer-based painting and node workflows. | **Pioneer license**: **Free** for indie artists/studios earning under **$100,000/year**, usable on commercial projects with attribution . Paid tiers available for larger organizations. | **Free Pioneer license** (revenue < $100k/year, attribution required). Native Linux support included . |

| **[Crazybump](https://www.crazybump.com/)** | Normal map and texture generation from photos. Shareware with a free evaluation. | **$49** shareware license (version 1.22) . | **Free trial** available; continued use requires purchase. |

| **[Bitmap2Material](https://store.steampowered.com/)** | Allegorithmic's (now Adobe) image-to-PBR tool. **Legacy product**—largely superseded by Substance Sampler. | **N/A** on Steam as of 2026; historical lowest recorded price ~$33.49 . | **No current free tier**. Legacy licenses may persist. |

| **[MindTex 2](https://store.steampowered.com/app/441770/MindTex_2/)** | Normal map generation utility for game developers and 3D professionals. | **$19.99** on Steam (frequent discounts, e.g., $5.99 during sales) . | **No free tier**. Paid Steam license only. |

| **[Knald](https://www.knaldtech.com/)** | GPU-accelerated normal/height/AO map generator. | **Freelancer License**: non-commercial use. **Studio License**: commercial use (quote-based) . | **Freelancer License** available (non-commercial only). Commercial use requires Studio license. |

| **[ShaderMap Pro](https://shadermap.com/)** | Map generation suite converting diffuse/displacement/normal sources into full PBR sets. | Pricing not published in search results. Contact vendor. | Not specified in available results. |

| **[Substance Alchemist](https://www.adobe.com/)** | **Legacy name**—Substance Alchemist was renamed to **Substance 3D Sampler** and is no longer a separate product. | See Adobe Substance 3D Sampler above. | See Adobe Substance 3D Sampler above. |



## Open-Source GitHub Projects



- **[Materialize](https://github.com/BoundingBoxSoftware/Materialize)** [![GitHub Stars](https://img.shields.io/github/stars/BoundingBoxSoftware/Materialize?style=social&color=white)](https://github.com/BoundingBoxSoftware/Materialize/stargazers)  

  **The long-standing image-to-PBR converter.** Free, open-source (GPL-3.0), and still widely used nearly a decade after its 2018 release . **Workflow**: import a source image, step through map generation with a slider-based interface, preview results in real-time on a 3D model in the viewport, and export standard PBR texture maps . **Features**: seamless tiling, clipboard automation via XML commands, and support for generating the full PBR suite from a single image . **Status**: ~1,460 GitHub stars, updated recently (2 months ago as of the source date) . Best for artists wanting a straightforward, free tool for photo-to-material conversion without subscriptions or AI dependencies.



- **[AwesomeBump](https://github.com/kmkolasinski/AwesomeBump)** [![GitHub Stars](https://img.shields.io/github/stars/kmkolasinski/AwesomeBump?style=social&color=white)](https://github.com/kmkolasinski/AwesomeBump/stargazers)  

  **The GPU-accelerated map generator.** Written in C++ with Qt, designed to generate normal, height, specular, and ambient occlusion textures from a single image—positioned as an alternative to the GIMP plugin Insane Bump . **Performance**: image processing is done **99% on GPU**, so the program runs very fast and all parameters can be changed in real time . Best for users wanting a fast, open-source tool for map generation with immediate visual feedback.



- **[Material Maker](https://github.com/RodZill4/material-maker)** [![GitHub Stars](https://img.shields.io/github/stars/RodZill4/material-maker?style=social&color=white)](https://github.com/RodZill4/material-maker/stargazers)  

  **The node-based procedural authoring tool.** Built on the Godot engine, it provides a visual graph interface for authoring complex surface properties and textures through connected functional nodes . **Features**: procedural texture generation, 3D painting directly onto geometry, and a material exporter that converts authored data into formats compatible with external 3D software and game engines . Best for technical artists and teams wanting a free, procedural alternative to Substance Designer's node-graph workflow.



- **[ComfyUI-SuperPBR](https://github.com/Hullabalo/ComfyUI-SuperPBR)** [![GitHub Stars](https://img.shields.io/github/stars/Hullabalo/ComfyUI-SuperPBR?style=social&color=white)](https://github.com/Hullabalo/ComfyUI-SuperPBR/stargazers)  

  **The AI-assisted PBR decomposition suite.** ComfyUI nodes for the **Base SuperMat** model (ICCV 2025)—a Stable Diffusion 2.1 UNet finetuned as a single-step feed-forward network . **Workflow**: one pass over a rendered object produces **albedo** and **ORM** (occlusion/roughness/metallic) maps, with tile split/stitch nodes for images larger than 512px . **Use case**: reconstructing PBR materials from existing renders or photos using AI rather than manual slider tuning. Best for users already in the ComfyUI ecosystem wanting AI-powered material extraction.



- **[TextureForge](https://github.com/yedp123/Yedp-Texture-Forge)** [![GitHub Stars](https://img.shields.io/github/stars/yedp123/Yedp-Texture-Forge?style=social&color=white)](https://github.com/yedp123/Yedp-Texture-Forge/stargazers)  

  **The zero-install browser tool.** Single-file HTML/React application that runs entirely client-side—drop in an image and generate Normal, Roughness, Ambient Occlusion, Height, Metallic, and Opacity maps . **Features**: smart tiling, manual clone stamp, direct normal painting, real-time 3D preview (plane/cube/sphere with HDRI lighting), and one-click ZIP export . **Caveat**: marked **Experimental**; AI features require optional API keys but core PBR generation works without them . Best for quick material prototyping without installing anything.



### Additional Strong Open-Source Options



- **ArmorPaint / ArmorTools** — Open-source PBR texture painting suite with GPU-accelerated texture baking and node-based material editing, plus AI-assisted map generation from text prompts . Best for users wanting Substance Painter-like painting with open-source licensing.

- **Dream Textures** — Stable Diffusion integration for Blender, enabling AI-generated textures and concept art directly within the 3D environment . Best for Blender users wanting generative texture creation in their existing workflow.

- **pbr-renderer (PBR Material Studio)** — WebGL 2.0 real-time PBR material authoring tool with Cook-Torrance BRDF, 10 material presets, and JSON export . Best for learning PBR principles and quick material previews in the browser.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Quixel Mixer is discontinued**: the final version (2023.1) is free and runs offline indefinitely, but receives no updates, has no online library access, and no product support . Do not select for new projects requiring active development.

- **Bitmap2Material and Substance Alchemist are legacy names**: Bitmap2Material has been superseded by Adobe's Substance 3D Sampler ecosystem; Substance Alchemist was renamed to Sampler. Verify you're pursuing the current product before budgeting.

- **Free tiers vary in commercial usability**: InstaMAT's Pioneer license is free only for studios under $100k/year revenue (attribution required) ; Knald's Freelancer license is non-commercial only ; Adobe's trial is 30 days with no permanent free tier .

- **AI-assisted tools are experimental**: ComfyUI-SuperPBR and TextureForge are promising but newer; validate output quality against your specific material types before relying on them for production pipelines.



---



**Made for 3D artists, technical artists, and game developers building PBR material pipelines.**  

Let's make material digitization more open, accessible, and self-hostable.
