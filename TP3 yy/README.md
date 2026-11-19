# TP 3 – Use Case Diagrams with PlantUML

This folder contains the PlantUML source files and written deliverables for TP 3.

## Files
- `atm.puml` – Part A, first PlantUML diagram.
- `use-cases.puml` – Part B, library use-case diagram.
- `register-loan-activity.puml` – Part C, activity diagram for registering a loan.
- `register-return.md` – Part D, fully dressed description of UC-07.
- `register-return-activity.puml` – Part D, activity diagram for registering a return.
- `answers.md` – answers to questions (a) to (e).

## Open in VS Code
1. Extract this ZIP file.
2. Open the extracted `TP3_Library_UML` folder in Visual Studio Code.
3. Install the **PlantUML** extension.
4. Open any `.puml` file.
5. Use the PlantUML preview command from the Command Palette (or the extension's preview shortcut).

PlantUML requires Java. For use-case diagrams, Graphviz is recommended. If Graphviz is unavailable, add `!pragma layout smetana` immediately after `@startuml` in the relevant file.

## Export diagrams
Open a `.puml` file and use the PlantUML extension's export command to export it as PNG or SVG. The TP asks for PNG and SVG/image exports to be placed with the source files in `docs/uml`.

## Git deliverable (Part E)
From the TP 2 repository, create `docs/uml`, copy these files and the exported diagram images into it, then commit. To inspect the requested textual change, rename `Register a loan` to `Lend copies` in `use-cases.puml`, run `git diff`, and commit. A PNG is a binary file, so `git diff` normally cannot show its visual change as readable text.
