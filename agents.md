# UI/UX Designer Harness

## Project Overview
This project is a dedicated harness for designing amazing UI/UX for mobile devices. It is strictly confined to generating and refining UI/UX designs using the Stitch MCP toolset.

The final mobile applications will be built externally using **React** and **Capacitor**. Therefore, all designs produced here should be optimized for mobile-first, native-feeling experiences that align with mobile development standards.

## Project Organization Rules
To maintain a clean and scalable repository for multiple UI/UX designs, follow these structural rules:
1. **New App Ideas**: When a new project or app idea is provided, create a dedicated project folder in the root directory (e.g., `/app-name`).
2. **File Placement**: All design files, generated UI code, and specific design system guidelines for that app must be stored exclusively inside its dedicated folder. 
3. **No Root Clutter**: Avoid creating individual component or screen files directly in the root directory. Keep the root reserved for global configurations and this `agents.md` guideline.

## Tools & UI Generation
- **Stitch MCP**: We use the Stitch MCP server to generate and refine UI components. Always leverage the Stitch toolset when creating new visual interfaces or layouts.
- **Mobile Focus**: Ensure all generated designs are responsive, touch-friendly, and maintain a mobile-first approach.

## Stitch Organization & Naming Conventions
To ensure smooth navigation and maintainability when generating designs via Stitch, adhere to the following conventions:
- **Ordered Pages**: Number your screens sequentially to reflect the logical user journey or app flow (e.g., `01-onboarding`, `02-login`, `03-home`).
- **Section Grouping**: For apps with distinct functional areas, use a structured section prefix (e.g., `auth-01-login`, `auth-02-signup`, `settings-01-profile`).
- **File Naming**: Use `kebab-case` for all page and asset file names (e.g., `user-profile.tsx`, `hero-background.png`). Avoid spaces, uppercase letters, or underscores.
- **Asset Management**: Name assets clearly, prefixing them by type or section for easy filtering (e.g., `icon-nav-home.svg`, `img-onboarding-bg.png`).
