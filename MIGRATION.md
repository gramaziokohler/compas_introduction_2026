# 2026 adaptation

Sources:

- COMPAS Introduction 2025: `0d0ba952a9758a15403dcf8ffac98e8656eec316`.
- Coding Architecture HS26: `f5c4e0d871fccfa2b2a6f340b9ed44eb9af7599f`.

Copied the introduction files without source Git history. Retained all examples, exercise starters and solutions, Python modules, roadmap images, and the MIT license.

Renamed HS25 assets to HS26 and updated their links and embedded document names. Updated embedded Python scripts in all nine Grasshopper archives from `mas-2526` to the reference environment `ca-hs26`. Standardized Rhino COMPAS directives to `>=2.15.1` (Rhino treats commas as package separators), with `>=2.15.1,<3` in the VS Code requirements, including Draw and solution components, so geometry producers and consumers use the same environment. Preserved component IDs, connections, input settings, canvas layouts, and lesson algorithms.

The matching anatomy scripts are identical in both source repositories. The matching Grasshopper Python basics and VS Code scripts differ only in their environment directive; those changes are applied here. Kept the original geometry-based hello-world example, 3D grids, and compact brick-wall exercise rather than introducing the semester course's additional assignments.

Copied the HS26 VS Code requirements, setup scripts, external example module, and cross-platform setup workflow. Removed the unused `compas_viewer` dependency as in HS26. Fixed the roadmap's missing thumbnail link to use the included image. The existing slides link is explicitly labeled as a 2025 reference because no replacement introduction slide deck was supplied.

## Validation

All nine saved Grasshopper definitions reopen in Rhino 8.35 and solve with no runtime errors through LAMCP using installed COMPAS 2.15.1. The 3D grids produce geometry; the brick-wall solution produces 320 bricks at its saved inputs. Component IDs, wire sources, and input/output counts match the 2025 archives. All embedded and standalone Python scripts parse, the shell setup script passes `bash -n`, and all local Markdown links resolve. The Windows setup script is copied unchanged from HS26 and has not been executed locally.
