# AI Design Skill Brief — research dashboard

> Build-ready design skill brief for Claude Code
> Tool: **Claude Code**
> Save this as a markdown file in your project and reference it in Claude Code to match this design language.

---

## Overall Read

Minimalist, Functional, Analytical. The interface conveys a Informative and Calm, with a hint of playful branding through the penguin motif. mood. Type: app.

## Layout Archetype

Dashboard Layout with Fixed Sidebar and Content Cards. A three-column grid at the highest level: 1) a fixed-width left navigation sidebar, 2) a main content area containing stacked data cards, and 3) a large interactive map. The top header spans the width of the main content and map areas.. Density: Medium, balancing detailed data within cards with generous outer spacing between cards and layout regions. This allows for scanability without overwhelming the user..

## Information Flow

Primary navigation is vertical on the left. Global search and utility actions occupy the top horizontal space. The main content flows vertically within a card-stacking structure on the left of the main content area, while a large, persistent map occupies the right.

## Spacing Rhythm

A consistent 16px base unit appears to be used for padding within cards, and for the vertical and horizontal gaps between cards. Larger margins (e.g., 32px or more) separate major layout blocks like the sidebar from the main content, and the header from the content below it.. Section separation: Sections are primarily separated by the distinct boundaries of cards and containers, which use subtle shadows and increased white space. Clear, bold headings also delineate different data sections within the cards..

## Navigation Behavior

Fixed Left Sidebar and Top Global Header. Visibility: Always visible (persistent sidebar and top header).. Depth: Primary navigation is a single level (e.g., Home, Insights, Data Analysis). Utility actions in the header (user profile, notifications, app menu) suggest secondary functions or settings accessed via dropdowns or modals.. Utility actions: Top right of the global header (user profile, notifications, app menu). Search is centrally located in the top header..

## Card & Surface Treatment

Surfaces: Cards use solid white backgrounds, providing a clean canvas for data display. Slight shadows enhance their presence.. Borders: Consistent 8px border-radius applied to all principal cards, search inputs, and interactive elements, creating a soft and modern aesthetic.. Shadows: Subtle, soft, single-layer box-shadows are applied to cards to lift them slightly off the background, providing a sense of depth and separation without feeling heavy.. Container separation: Cards are the primary containers, separated by consistent vertical and horizontal white space (e.g., 16px). Shadows further reinforce their individual boundaries..

## Component Recurrence

- Data visualization cards (line charts, bar charts, calendar grids)
- Navigation links (icon + text)
- Search input field
- User avatar/dropdown
- Notification icon
- Application menu icon
- Map controls (zoom, position display)

Recurrence: High recurrence of card components and navigation links. The top header components (search, user, notifications) are globally recurrent.. Consistency: Very high. All cards follow the same border-radius, shadow, and internal padding. Navigation links maintain consistent styling for active/inactive states. Icons are consistently styled. This ensures a unified user experience..

## CTA Hierarchy

Primary: No explicit 'primary' CTA button is immediately visible in the current view of the dashboard. Most actions are driven by navigation clicks or data exploration.. Secondary: Implicit CTAs are navigation links (e.g., 'Insights' is currently active/selected). Text-based links within cards (e.g., 'Map Settings', 'Collapse') serve as secondary actions, often paired with an icon.. Frequency: Low to medium. The interface is more focused on information display and exploration than on forcing immediate actions. CTAs appear contextually within relevant data cards or as part of the navigation.. Emphasis: Emphasis is placed on contextual actions (e.g., 'Map Settings' dropdown) and navigation. The lack of prominent, brightly colored buttons suggests a calm, exploratory interface rather than an action-driven one..

## Information Density

Medium, with a balance between detailed data presentation within cards and ample white space separating distinct information blocks.

## Typography System

Humanist Sans-serif. Headings: Bold, varied font sizes (e.g., 80 bpm is very large, 'Heart Rate Analysis' is smaller) to create a strong perceptual hierarchy. All headings are left-aligned.. Body: Regular weight, legible sizes for data labels and descriptive text. Utilizes a slightly lighter gray for secondary information to reduce visual clutter.. Hierarchy strength: Strong due to clear size and weight variations, effective color contrast against backgrounds, and consistent left alignment..

## Color Strategy

Monochromatic (grays, whites) with functional accents (blue, red, green).. Accent behavior: Used for active states (blue for ‘Insights’), warnings/alerts/specific data categories (red for ‘Alerts’ and some map markers/graph lines), and positive indicators/other data categories (green for check-ups and other map markers). Accents are used sparingly to guide the eye and convey meaning.. Contrast: High contrast between text and background for readability (dark text on light surfaces). Mid-range contrast is used for secondary information (lighter gray text). Accent colors provide strong contrast against the neutral palette to draw attention..

## Interaction Style

Click-based navigation and data exploration. Hover states are implied for interactive elements (buttons, links).. Hover feedback: Not directly visible in a static screenshot, but a subtle change in background color or text/icon color is expected for elements like navigation items or buttons.. Motion intensity: Presumed low. Dashboards typically rely on subtle transitions and animations for data updates or navigation, rather than elaborate, high-intensity motion..

## Data Visualization

Yes. Chart style: Clean, line graphs with distinct colors for data series, bar charts with solid fills, and a heatmap-style calendar. The map uses custom icon markers (penguins) and color-coded triangular indicators.. Data density: Medium to High within individual charts, but presented in digestible chunks within cards. Labels and legends are concise to avoid clutter..

## Build Guidance

Data dashboards, monitoring systems, analytical platforms, educational applications, and interfaces requiring clear, structured information display.

## Avoid

Highly artistic or abstract applications, interfaces requiring a very high frequency of complex user interactions, or designs needing to convey an extremely vibrant or aggressive brand personality.

## Do Not Copy

Do not reproduce the exact layout, brand identity, or copy from the source design.
Use the extracted design language only as inspiration for creating a new interface.
