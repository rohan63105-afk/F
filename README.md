# MIT EECS Student Portal — Visual Refresh Final Pack

Static website package for GitHub + Vercel. Root index.html is the entry point.

Visual updates

•
Replaced the old hero image with a generated cinematic campus illustration inspired by MIT's iconic Great Dome and Killian Court.
•
Added the same campus image as the top-bar background.
•
Removed the V6 · STUDENT PROFILE pill and replaced it with a clickable student avatar. If a profile photo is saved in the same browser's local profile storage, it will appear here; otherwise initials show as a fallback.
•
Existing profile-photo upload/edit remains available in Student Profile.

Image note: Hero/topbar artwork is AI-generated campus-inspired art, not an official MIT photograph. Official MIT Media Library images are restricted to MIT-community use and require affiliation/permission for download/use.

Roadmap downloads

•
downloads/MIT_EECS_8_Semester_Course_Research_Plan.pdf
•
downloads/MIT_EECS_8_Semester_Course_Research_Presentation.pptx
•
downloads/EECS_Four_Year_Roadmap.png

Deploy

1.
Upload the contents of this ZIP to the root of a GitHub repository.
2.
Import that repository into Vercel.
3.
Framework Preset: Other; leave build command empty; Root Directory ./.
4.
Deploy.

Course pathway is a proposed self-study sequence, not an official MIT degree plan. Official OCW resource availability varies by course and is not fully verified across all entries.

Hero/Header image fix

The MIT-inspired dusk Great Dome artwork is now wired as a local asset in assets/hero.webp for both the hero section and top header. Use the ZIP package so relative image assets load. The standalone HTML has the image embedded.

