# Skill: CGC Platform-Specific Markup

This skill defines the strict technical constraints for generating code for Chaturbate (CB) and MyFreeCams (MFC).

## Strict Coding Rules Chaturbate
1. **Inline CSS Only:** All styles must be inline unless specified.
2. **Container Protocol:** Every component must be wrapped in a `` and `` comment.


## 🚫 Platform Prohibitions (NEVER USE)
- **NO `<div>` tags** (Chaturbate will strip these, breaking the layout).
- **NO `<style>` blocks** (Must be 100% inline for CB).
- **NO `@media` queries** (Not supported in CB bios).
- **NO `<body>`, `<html>`, or `<head>` tags**.
- **NO `onclick`, `target=`, or `alt=` attributes**.
- **NO empty spaces**.
- **NO empty lines as they are interpreted by Chaturbate as `br` tag**.

## ✅ Allowed Layout Containers
1. **Paragraph `<p>`**: Use as the primary wrapper for blocks of content.

2. **Span `<span>`**: Use for inline styling or grouping small elements.

3. **A `a`**: used for a hyperlink, or a link to another page.

4. **I `i`**: - italicized text

5. **Strong `strong` or `b`**: - bolded text

6. **U `u`**: - underlined text

7. **Ul `ul`**: - bullet point, or unordered list

8. **Ol `ol`** - numbered, or ordered list

9. **Li `li`** - list item, this tag is used within the unordered and ordered lists mentioned previously

10. **Headings `h1` , `h2` , `h3`**: - these are header tags, where h1 is the most important and h3 is the least important

11. **Image tag `img`**; - used to embed an image in a web page 

12. **Font `font`**: - used to define the font, size, and color of any text

14. **Br `br`**: - used to specify a blank line or a line break

## Template: Chaturbate Layout Wrapper
When generating a "Box" or "Section" for Chaturbate, use this `<ul>` wrapper instead of a `<div>`:

```html
<ul style="display:block;width:95%;margin:10px auto;padding:15px;background-color:#1a1a1a;border:2px solid #FF00EA; color:#ffffff;font-family:Arial, sans-serif;border-radius:10px;">{CONTENT_HERE}</ul>

## 📚 Snippet Libraries
When the user needs specific layout components, refer to these specialized files:

- **Headers & Banners:** [template-snippet-headers.md](./template-snippet-headers.md)
- **Buttons & Socials:** [template-snippet-buttons.md](./template-snippet-buttons.md) (Create this next!)

**Usage Note:** Always prioritize these specific HTML tags (`<li>`, `<i>`) over modern containers to ensure platform compatibility.