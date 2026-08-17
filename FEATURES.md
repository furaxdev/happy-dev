# HappyDev — feature backlog

Brainstormed ideas, not commitments. Grouped so it's easy to pick off a batch.

## Make it stop looking/feeling like a VS Code fork

1. Custom About dialog (HappyDev name, version, build info, credits)
2. "Report Issue" flow points to our GitHub, not microsoft/vscode
3. Custom "What's New" / release notes page
4. Rebrand the "Restart to update" and update-flow dialog copy
5. Custom auto-updater pointed at our own GitHub Releases instead of Microsoft's endpoint
6. Custom crash / "not responding" dialog branding
7. Audit remaining telemetry/endpoint references in product.json
8. Rebrand extension marketplace empty-state / recommendation copy
9. Custom Dock icon behavior (bounce/badge on build errors, etc.)
10. Custom window title format (project · branch · HappyDev)
11. "About HappyDev" easter egg / command palette entry
12. Localize product strings to French as a first-class option

## Theming & visual polish

13. HappyDev Light theme (companion to the dark one)
14. HappyDev High Contrast theme
15. Custom file icon theme matching the palette
16. Custom product icon theme (recolor UI glyphs cyan/pink)
17. Rounded corners on hover cards / dropdowns / quick-pick via CSS
18. Scrollbar styling refinement
19. Minimap colors tuned to the theme
20. Find/replace widget restyle
21. Notification toast restyle
22. Status bar accent color for errors/debug state
23. Command palette restyle (Zed-inspired spacing/blur)
24. Breadcrumbs restyle (minimal, Zed-style)
25. Splash/boot screen tuned to the theme
26. Cursor + selection highlight color per theme

## Editor features

27. Bundle Vim mode, off by default, one-click enable
28. Bundle a formatter (Prettier) preconfigured
29. Auto dark/light switch based on system appearance
30. Better built-in Git graph / SCM visualization
31. Split-terminal presets (e.g. "2-up", "3-up" commands)
32. Zen mode preset tuned to HappyDev branding
33. Built-in TODO/FIXME highlighter
34. Markdown preview theme matching the palette
35. Custom Welcome walkthrough steps (HappyDev-specific, not the generic VS Code tour)
36. Recent projects list with folder previews on the Welcome page
37. Starter snippet library for common languages
38. Bracket-pair colorization tuned to the palette

## Product/ecosystem depth

39. Curated default extension recommendations (HappyDev pack)
40. "HappyDev Default" keybinding preset as an alternative to VS Code Default
41. In-app changelog viewer
42. Optional sound effects on save/error (subtle, off by default)
43. "Trust this workspace" dialog restyle
44. Share-snippet command (copies a shareable link/gist)
45. Discord Rich Presence integration (ties back to the original roadmap idea)
46. Windows build (currently macOS-only)
47. Linux build (currently macOS-only)
48. Code-signed + notarized macOS build (removes the Gatekeeper right-click-to-open step)
49. Auto-deploy the marketing site to Vercel on every push (currently manual)
50. Settings sync pointed at our own backend instead of Microsoft's (or just disabled cleanly)
51. Custom keyboard shortcut cheat-sheet reference (branded, printable)
52. Onboarding tooltip tour for first-time users (beyond the Welcome tab)
53. Built-in project templates ("New HappyDev project" starter kits)
54. Telemetry fully OFF by default with a clear one-line explanation, not just quietly rerouted
55. Auto-generated build info panel (commit hash, build date) in the About dialog

## Notes

- Items 1–12 matter most for "doesn't look like VS Code" — do those first.
- Windows/Linux builds (46, 47) are the biggest lift; everything else is small/medium.
- Signing + notarization (48) needs an Apple Developer account — flag before starting.
