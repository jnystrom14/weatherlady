# WeatherCore Design Guidelines

## 🎨 Visual Style

* **Font**: Inter (clean, readable, modern-retro feel)
* **Primary Color**: `#227C9D` (classic blue)
* **Accent Color**: `#88C0A9` (vintage green)
* **Light Mode Backgrounds**: Soft whites, light grays
* **Dark Mode Backgrounds**: Deep navy, muted teal
* **UI Aesthetic**: Vintage NOAA/instrument panel vibe, clean card layouts

## 🧱 Layout Principles

* **Mobile-first** grid layout
* Consistent spacing and vertical rhythm
* Collapsible sections for content density (e.g., forecasts)
* Large tap targets and clear iconography for radar and AI tools
* Radar and alerts placed high in visual hierarchy on homepage

## ♿ Accessibility

* Sufficient contrast for both light and dark themes
* Semantic HTML and ARIA where needed
* Voice assistant fallback options for typed input
* Keyboard navigation supported throughout

## 📐 Page-Level Style Considerations

* **Homepage**: Hero section with quick-glance conditions, radar, and alerts. Emphasis on fast load and core info.
* **Radar Page**: Immersive, full-screen layout with layered overlays and animated time-slider.
* **Forecast Explorer**: Data-heavy page with graphs, toggles, and moon/sun visuals. Prioritize clarity.
* **AI Assistant**: Chat bubble format or clean voice input modal with subtle vintage microphone iconography.

## 🗣️ Brand Tone and Voice

* Warm, intelligent, lightly playful (e.g., “Might want an umbrella around 2pm”)
* Human-first responses from the AI assistant
* Avoid overly technical jargon unless user prompts it

## 🧾 Design Inspiration

* Vintage weather stations, NOAA charts
* Old aviation dashboards and analog radar monitors
* Subtle map textures or weather icons from the 1940s-60s
* Soft, natural color palette with restrained use of gradients
