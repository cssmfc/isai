# 📂 Master Resource Index & Knowledge Base
**Status:** ACTIVE | **Scope:** Full Repository | **Strictness:** High

## 🤖 Instructions for AI Agent {shape}
You are an expert UI/UX Designer. You have access to a deep directory of design assets and code snippets.
1. **No Skipping:** Do not skip information located in sub-directories.
2. **Context Matching:** Match the {user}'s request (e.g., "CB design") to the specific folder path provided below.
3. **Multi-File Synthesis:** If a design requires a graphic from one folder and a HTML snippet from another, combine them to create the final markup.

---

## 🗺️ Repository Structure & Knowledge Map

### 1. Camgirl Cloud Context (`./camgirl_cloud/`)
* **Purpose:** Core cloud infrastructure design and branding.
* **Resources:** Check `.md` files for branding guidelines and `/graphics/` for primary logos.

### 2. Chaturbate Design Assets (`./chaturbate/`)
* **Purpose:** Specific UI components for Chaturbate-themed templates.
* **Assets:** Contains specific `.html`, `.txt` and `.md` layouts optimized for this platform.
* **Instruction:** Read the `.md` inside this folder for platform-specific constraints.

### 3. Graphics Library (`./graphics/`)
* **Purpose:** Global image repository.
* **Usage:** Use the full Raw GitHub URL to include these in HTML `<img>` tags or where `background-image` url is needed.
* **Keywords:** Refer to image descriptions for "shiny," "round," "dark," or "light" attributes.

### 4. MFC (MyFreeCams) Assets (`./mfc/`)
* **SKIP** : - IGNORE PROTOCOLE this directory is not developed yet.
* **Purpose:** Layouts and graphics specifically for MFC profile designs.
* **Structure:** This folder is 3 layers deep. You MUST recurse through all sub-folders to find specific profile "skins."

---

## 🛠️ Global Component Catalog (Samples)

### [Graphic Asset 01] - Profile Header - Banner
![Banner](https://raw.githubusercontent.com/cssmfc/isai/main/knowledge/graphics/headers/1000x500px-full-width-header.jpg)
> **Metadata**
> * **Path:** `graphics/1000x500px-full-width-header.jpg`
> **Asset Intelligence**
> * **Specs:** 1000px/500px, jpg, transparency: no 
> * **Suggested Theme:** dark color scheme
> * **Admin Notes:** this is placeholder, user will change that on their own
> * **Keywords:** wide header, fully responsive wide banner, image wide, landscape orientation

```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="https://raw.githubusercontent.com/cssmfc/isai/main/knowledge/graphics/headers/1000x500px-full-width-header.jpg" style="display:block;width:100%;height:auto;margin:0 auto;"/></li>```

---


### [Code Snippet 01] - Base Layout
> **Path:** `chaturbate/codes/templates/template-1.md`
```html