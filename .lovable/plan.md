

## Plan: Update Featured Work Section with Real Project Data

### Changes to `src/components/ProjectsSection.tsx`

Update the three project cards with real client details, links, and descriptions. Each card will open the client website in a new tab on click.

**Project 1 — The Melodic Mind Studio**
- Title: "The Melodic Mind Studio"
- Client: "The Melodic Mind"
- Link: `https://www.themelodicmind.com/studio`
- Description: Crafted a vibrant, animated UX design for an artist-based platform where followers can download and learn songs and tabs — delivering an energetic, immersive experience that keeps musicians engaged.
- Role: UX/UI Designer

**Project 2 — Maayari**
- Title: "Maayari"
- Client: "Maayari"
- Link: `https://maayari.com`
- Description: Designed a clean, professional, and minimal website focused on clarity and elegance — ensuring the brand's message comes through without distraction.
- Role: UX/UI Designer

**Project 3 — Paul Davids Guitar**
- Title: "Paul Davids Guitar"
- Client: "Paul Davids"
- Link: `https://pauldavidsguitar.com`
- Description: Created an intuitive, easy-to-navigate e-commerce website for a personalised guitar brand — making product discovery and purchasing effortless for customers.
- Role: UX/UI Designer

**Interaction**: Wrap each `Card` in an `<a>` tag with `href={project.link}`, `target="_blank"`, and `rel="noopener noreferrer"` so clicking routes users to the client website. Placeholder thumbnails (the numbered overlays) remain as-is. Deliverables/badges will be kept but updated to match each project's scope.

