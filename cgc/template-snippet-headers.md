# Skill: Header & Banner Snippets

Use these snippets for top-of-profile sections. 
**Constraint:** Match the overall color palette of the template.

## Full-Width Options (Banners)

### 1. Standard Full Width (1000px x 500px)
*Best for: Detailed artistic banners.*
```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="knowledge/graphics/headers/1000x500px-full-width-header.jpg" style="display:block;width:100%;height:auto;margin:0 auto;"/></li>


### 2. Full width header or banner 1000px/500px but using `object-fit`
Best for: When the image needs to fill a specific 300px height.
```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="knowledge/graphics/headers/1000x500px-full-width-header.jpg" style="display:block;width:100%;height:300px;margin:0 auto;object-fit:cover"/></li>



### 3. Full width header or banner 1000px/300px

```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="knowledge/graphics/headers/1000x300px-full-width-banner.jpg" style="display:block;width:100%;height:auto;margin:0 auto;"/></li>



### 4. Full width header or banner 1000px/150px

```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="knowledge/graphics/headers/1000x150px-full-width-banner.jpg" style="display:block;width:100%;height:auto;margin:0 auto;"/></li>

## Avatar & Profile Photo Options (Centered)

### 1. Header centered avatar 512px/512px square

```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="knowledge/graphics/headers/512x512-header-avatar.jpg" style="display:block;max-width:100%;width:300px;min-width:270px;height:auto;margin:0 auto;"/></li>



### 2. Header centered avatar 512px/512px round

```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><img src="knowledge/graphics/headers/512x512-header-avatar.jpg" style="display:block;max-width:100%;width:300px;min-width:270px;height:auto;margin:0 auto;border-radius:100% 100% 100% 100%"/></li>



### 3. Header centered avatar 512px/512px round, image is child element
Use this for a high-end, glowing look. Adjust border color to match theme.
```html
<li style="display:block;width:100%;height:auto;margin:0 auto;text-align:center;box-sizing:border-box;padding:0;list-style:none;"><i style="display:block;max-width:100%;width:300px;min-width:270px;height:auto;margin:0 auto;text-align:center;border-radius:100% 100% 100% 100%;font-style:none;box-shadow:0 0 12px #999;padding:1em;border:7px solid rgba(60%,40%,80%,.5);"><img src="knowledge/graphics/headers/512x512-header-avatar.jpg" style="display:block;max-width:100%;width:100%;min-width:200px;height:auto;margin:0 auto;border-radius:100% 100% 100% 100%"/></i></li>

---
*Update 2026*