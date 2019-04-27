## Last Week's Accomplishments

> Last week, I finished implementing object port selection in the Selection Tool class. Previously, object ports \
> could not be selected, and now, when a selection box is drawn around a port, it is added to the array of \
> selected components, and it is rendered with the selection shadow too. The hard part about this was that \
> wire ports are not IOobjects, so they couldn't be selected the same way that all other components get \
> selected. All new methods had to be written to handle the selection of ports. Also, the port selection is not \
> always valid (for example, when a non-port component is already selected, we don't want to select any ports). 
> There were several similar edge cases I had to consider in implementation. \

## This Week's Plan

> This week, I have chosen another feature from the issue list to implement. I will work on the Copy and Paste \
> functions to copy circuits to the user's clipboard. I will have to do this by saving the selected group as XML \
> to the clipboard. This will also have do be an undoable action.\

## Anything Blocking?

> I have no idea how to implement copy and paste. I took on the issue hoping it would be a learning \
> experience, but I don't really know how the user's clipboard will interact with the code, and the user's \
> circuits.\

## Notes

> NA\
