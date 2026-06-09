# Frontend Design Reference

Use this reference when a task involves frontend layout, UI polish, visual hierarchy, interaction design, or a user-facing web experience.

## Product Fit

- Match the interface to the product domain instead of applying a generic landing-page style.
- Prefer dense, calm, scannable layouts for operational tools such as CRM, SaaS, admin, and workflow systems.
- Prefer richer visual atmosphere only when the product is editorial, portfolio, playful, consumer, game-like, or brand-led.
- Build the actual usable interface first. Do not make a marketing landing page unless the user asks for one.

## Layout

- Keep primary workflows visible and reachable without decorative detours.
- Use clear page structure: navigation, workspace, detail panels, toolbars, and status areas should have distinct roles.
- Avoid cards inside cards. Use cards for repeated items, modals, or truly framed tools.
- Give fixed-format controls stable dimensions so hover states, dynamic labels, counters, and icons do not shift the layout.
- Check mobile and desktop widths for text overflow, overlapping controls, and cramped actions.

## Components

- Use established project components before inventing new UI primitives.
- Use icons for common actions when available: save, download, edit, delete, undo, redo, search, filter, zoom, add, close.
- Use tooltips for icon-only controls whose meaning may not be obvious.
- Use segmented controls for mutually exclusive modes.
- Use switches or checkboxes for binary settings.
- Use sliders, steppers, or numeric inputs for numeric values.
- Use menus or selects for option sets.
- Use tabs only when the views are peers and switching should preserve context.

## Visual Style

- Avoid one-note palettes dominated by a single hue family.
- Keep border radii restrained unless the product's design system says otherwise.
- Do not use decorative gradient blobs, bokeh, or random orb backgrounds.
- Use typography scale deliberately: reserve hero-sized text for true hero areas, and keep panels and dashboards compact.
- Do not use negative letter spacing.
- Do not scale font size directly with viewport width.

## Assets

- Use real or generated bitmap imagery when a website needs visual assets.
- For product, place, portfolio, or object-focused pages, show the actual subject in the first viewport.
- Avoid dark, blurred, cropped, stock-like, or purely atmospheric images when the user needs to inspect the subject.
- For games or 3D work, verify that canvas or rendered assets are visible, framed correctly, and interactive.

## Accessibility And States

- Preserve keyboard access for controls and workflows.
- Include loading, empty, disabled, hover, focus, error, and success states where the workflow needs them.
- Keep button labels short and action-oriented.
- Make destructive actions explicit and recoverable when possible.
- Ensure color is not the only carrier of meaning.

## Verification

- Run the project's formatting, linting, type-checking, and build commands when available.
- For visual work, inspect the result in browser screenshots at desktop and mobile widths when tooling is available.
- Check that text fits, controls do not overlap, and the first viewport communicates the product or workflow clearly.
