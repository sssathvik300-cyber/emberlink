# 🔥 Ember: Team Pulse

**Ember: Team Pulse** is a real-time team engagement and mood-tracking platform that replaces traditional delayed pulse surveys with a live, interactive workspace. Teams can visualize collective energy, mood, and alignment instantly through dynamic profile orbs, responsive team spaces, and fluid real-time interactions.

## ✨ Features

### Interactive Team Spaces

* Team members appear as draggable profile orbs within dedicated team boundaries.
* Users belonging to multiple teams are automatically represented in each team space.
* Real-time boundary clamping prevents profiles from leaving their assigned team area.
* Smooth visual organization with intelligent orb positioning.

### Fluid Physics & Live Feedback

* Spring-based animations create natural movement during workspace changes.
* Automatic profile reflow when team boundaries expand or shrink.
* Collision detection prevents overlapping profiles.
* Dynamic boundary glow provides visual feedback when profiles approach team limits.

### Contextual User Experience

* Click any orb to view an inline profile card.
* Expandable team badges display all teams a member belongs to.
* Click-outside dismissal keeps the interface clean and distraction-free.
* Responsive interactions across desktop and mobile devices.

### Multi-Room Collaboration

Manage multiple workspaces through a unified room system:

* Join existing rooms
* Search rooms using a 4-letter room code
* Create new rooms instantly
* Seamless room switching and onboarding

## ⚙️ Technical Highlights

### Real-Time Interactive Architecture

* Live synchronized workspace updates
* Physics-driven orb movement and positioning
* Team-aware collision and boundary management

### Server-Side Rendering (SSR)

* Fully rendered HTML delivered on initial load
* Improved SEO and discoverability
* Better social sharing previews
* Enhanced performance and accessibility

### Accessibility & Responsive Design

* Semantic HTML structure
* Accessible interactive controls
* Mobile-first responsive layout
* Structured metadata and JSON-LD support

## 🛠 Configuration

Key interaction settings can be adjusted in:

```bash
src/routes/room.tsx
```

### REFLOW_SPRING

Controls animation behavior when profiles reposition after boundary size changes.

* Stiffness
* Damping
* Reflow responsiveness

### BOUNDARY_WARN_AT

Defines the distance threshold for activating the team boundary glow effect.

* Higher values trigger feedback earlier
* Lower values require closer proximity to the boundary

## 🚀 Vision

Ember transforms team sentiment from a periodic survey into a living, shared experience. Instead of waiting weeks for engagement data, teams can understand energy, mood, and alignment in real time through a collaborative visual workspace.
