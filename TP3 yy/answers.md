# TP 3 – Questions

## (a)
`left to right direction` changes the diagram layout so that elements are arranged from left to right instead of the default top-to-bottom direction. The arrow in `Customer --> Withdraw` indicates a directed association in the drawing. Chapter 3 uses an ordinary association line between an actor and a use case, without an arrowhead.

## (b)
PlantUML renders the reversed `extend` relationship but does not necessarily detect that its UML meaning is incorrect. A modeling tool checks and renders the written notation and may report syntax errors; it does not automatically guarantee that the model expresses the correct requirements or semantics.

## (c)
**Advantages:** diagrams are described as text, so they are easy to edit and compare; automatic layout saves time and keeps diagrams consistently arranged.

**Drawbacks:** automatic layout may not place elements exactly as desired; complex diagrams can become crowded and may need direction hints or manual adjustments.

## (d)
PlantUML is text-based: editing is quick, changes are easy to track with Git, and diagrams can be regenerated. A graphical tool such as Modelio offers palette-based editing and more direct visual positioning. PlantUML layout is automatic, while graphical tools offer more manual control. Consistency in PlantUML can be maintained by editing the text source; in a graphical tool it depends more on the modeling environment and user actions.

## (e)
Keeping models in the same repository as the code makes the diagrams versioned with the implementation, allows changes to be reviewed through Git, preserves the history of design decisions, and helps keep documentation synchronized with the software.
