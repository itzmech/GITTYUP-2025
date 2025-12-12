# PROMPT FOR GENERATING index.html and style.css

## copy paste this prompt in chatgpt and take the html generated and paste it in index.html and style.css

Generate a complete tech portfolio website for a Computer Science student, with two separate files:

index.html – full HTML structure

style.css – all styling (no Tailwind, no Bootstrap, pure CSS)

``` prompt
# Role
You are an expert Senior Frontend Engineer and UI/UX Designer. Your task is to build a high-performance, responsive personal portfolio website using **only** HTML and CSS.

# Context & User Data
Please populate the site with the following details. If a field is empty, use a professional placeholder.

**Personal Details:**
- Full Name: {{Ansh}}}
- Role/Title: {{Owner}} (e.g., "Systems Engineer")
- Tagline: {{life is messed up
}}
- Location: {{Amravati}}

**Education:**
- University: {{VIT-AP}}
- Degree: {{right now in core branch}}
- Grad Year: {{2029}}

**Technical Skills:**
- Languages: {{python}}
- Tools/Platforms: {{vs code}}
- Core Concepts: {{git-hub}}

**Projects (Highlight 2-3):**
1. {{PROJECT_1_NAME}}: {{PROJECT_1_DESC}}
2. {{PROJECT_2_NAME}}: {{PROJECT_2_DESC}}
3. {{PROJECT_3_NAME}}: {{PROJECT_3_DESC}}

**Interests:**
- Hobbies: {{HOBBIES}}
- Soft Skills: {{SOFT_SKILLS}}

**Links:**
- GitHub: {{GITHUB_URL}}
- LinkedIn: {{LINKEDIN_URL}}
- Email: {{EMAIL_ADDRESS}}

# Design Requirements
1. **Theme:** Dark mode default. Use a "Hacker/Terminal" aesthetic (e.g., dark gray backgrounds, neon accent colors).
2. **Typography:** Use distinct monospaced fonts for headers.
3. **Responsiveness:** Must look perfect on mobile and desktop.
4. **Layout:** Single-page scrolling design with a sticky navigation bar.

# Technical Constraints
- **File Structure:** You must provide exactly **two** files:
  1. `index.html`
  2. `style.css`
- **No External Libraries:** Do not use Bootstrap, Tailwind, or external JS frameworks. Use vanilla CSS (Flexbox/Grid).
- **JavaScript:** If any interactivity is needed (like a mobile menu toggle), write the JavaScript strictly **inside a `<script>` tag at the bottom of the HTML file**. Do not create a separate .js file.

# Output Instructions
Please generate the full code for these two files below.

## File 1: index.html
- Should link to `style.css`.
- Should contain semantic HTML5 tags (<header>, <main>, <section>, <footer>).
- Should contain the embedded JS for the mobile menu or simple animations.

## File 2: style.css
- Should contain all styling, variables for colors, and media queries for responsiveness.
```
