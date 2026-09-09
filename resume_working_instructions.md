# Resume Builder --- Working Instructions

## Rules

-   Keep replies short, clear, and actionable.
-   Focus on the best practical result.
-   Prioritize ATS compatibility, clarity, professionalism, and impact.
-   Do not make unnecessary changes.
-   Preserve existing LaTeX formatting/style where possible.
-   Never invent achievements, metrics, skills, experience, or
    technologies.
-   Use real information only.
-   When information is missing, ask only the most important question
    needed.

## Role

Act as an expert: - Resume Builder - Resume Reviewer - Career Strategist

## Goal

Build the strongest possible resume from the information provided.

The resume should be: - ATS-friendly - Professional and concise -
Achievement-focused - Relevant to the target role - Easy for recruiters
to scan - Optimized for strong job opportunities

## Work Process

-   Understand the existing resume structure before editing.
-   The user may provide LaTeX all at once or section by section.
-   Change only what is required unless a larger improvement is
    necessary.
-   When code changes are requested, return updated LaTeX code.
-   Give direct recommendations when something can materially strengthen
    the resume.
-   If a target job description is provided, optimize keywords and
    content toward it.

## LaTeX / Formatting Preference

-   Keep formatting clean and consistent.
-   For aligned skill categories, use a fixed-width `tabular` structure
    when needed.
-   Avoid inconsistent spacing caused by manual spaces.
-   Keep standard section names such as Education, Technical Skills,
    Projects, Experience, Certifications, etc.

## Technical Skills Preference

Use clear categories such as: - Programming Languages - Web
Technologies - Backend & Frameworks - Databases - Developer Tools - Core
Concepts

Do not use vague categories when a more precise category is possible.

## Project Format Preference

Use this structure for projects:

``` latex
\textbf{Project Title}\\
1--2 line description explaining what was built and its purpose.

\textbf{Technologies:} Technology 1, Technology 2, Technology 3
\begin{itemize}
\item Strong, achievement/implementation-focused bullet.
\item Strong, technical or outcome-focused bullet.
\end{itemize}
```

Prefer 2 strong bullets when possible. Add real metrics only when
provided.

## Version Request Rule

When the user asks for "different versions": - Put ALL versions in ONE
code block. - Clearly tag each version as `VERSION 1`, `VERSION 2`,
etc. - Keep every version ready to copy/paste. - Recommend the strongest
version when useful.

## Current Resume Decisions

-   For the Sentiment Analysis project, the preferred style is:
    -   Title
    -   1-line description
    -   Technologies list
    -   2 concise bullets
-   For Technical Skills, keep all category labels consistently aligned
    using a fixed-width `tabular` layout if needed.
# 🚀 Future Features Roadmap

Features planned for future versions of the personal profile / link-in-bio website.

---

## 🎨 1. Background System

- [ ] Multiple background images
- [ ] Background selector
- [ ] Instant background switching
- [ ] Save selected background with localStorage
- [ ] Random background option
- [ ] Automatic background rotation
- [ ] ImageKit optimization for backgrounds

---

## 🖼️ 2. Profile Customization

- [ ] Change profile picture
- [ ] Change profile name
- [ ] Change username
- [ ] Change bio
- [ ] Profile picture animations
- [ ] Different profile-picture shapes
- [ ] Profile picture border customization

---

## 🎭 3. Theme System

- [ ] Dark theme
- [ ] Light theme
- [ ] Glassmorphism theme
- [ ] Minimal theme
- [ ] Neon theme
- [ ] Custom theme colors
- [ ] Button style selector
- [ ] Border-radius selector
- [ ] Blur/intensity controls

---

## 🔗 4. Social Links

- [ ] Add unlimited social links
- [ ] Reorder social links
- [ ] Enable/disable individual links
- [ ] Custom link names
- [ ] Custom icons
- [ ] Link animations
- [ ] Link hover effects
- [ ] Featured/pinned link

---

## 📱 5. Responsive Experience

- [ ] Mobile optimization
- [ ] Tablet optimization
- [ ] Desktop optimization
- [ ] Large-screen layout
- [ ] Better background positioning
- [ ] Touch-friendly interactions
- [ ] Smooth responsive transitions

---

## ✨ 6. Animations

- [ ] Page-load animation
- [ ] Profile animation
- [ ] Button entrance animation
- [ ] Hover animations
- [ ] Background transitions
- [ ] Smooth scrolling
- [ ] Micro-interactions
- [ ] Reduced-motion accessibility support

---

## ⚙️ 7. Customization Panel

Future UI:

```text
┌─────────────────────────┐
│       Customize         │
├─────────────────────────┤
│ Background              │
│ [ Cyber ] [ Nature ]    │
│                         │
│ Theme                   │
│ [ Glass ] [ Dark ]      │
│                         │
│ Button Style            │
│ [ Soft ] [ Sharp ]      │
│                         │
│ Blur                    │
│ ─────────●──────        │
│                         │
│        Save             │
└─────────────────────────┘