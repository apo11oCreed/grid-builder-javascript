# Javascript Grid Builds

This repo holds a mechanism for admins to create CSS grid layouts. Using javascript for the most part, a form was created to accept admin-defined values to configure the subsequent grid table. The table, then, provides the means to add cells to the grid 'zone'. Instructions are provided at each step.

## Challenges include:

1. Creating start/restart options
2. Provide options to save current setting. In this case, 'post' is terminology used.
3. Add/remove rows and columns
4. Add error handling for when rows or columns do not conform to CSS grid specifications

## Enhancements to consider:

1. Include method to add by rows/columns, not just by cell
2. Add method to remove or 'undo' action
3. Add method for starting a new 'zone' with a different color to differentiate from other saved 'zones'
3. Create support for exporting layout HTML once completed