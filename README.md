# SQLDebugTool
SQL Debug Tool

Used mainly with WebObjects SQL debug errors, but may be useful in other areas.  Web Objects includes bind values in the error stack.  Initially I struggled to find a way to transpose the `?` questions marks in the statement with their true value.  Then I wrote tool to do it for me.

It also prettifies the SQL output.  The full error stack can be pasted and only the SQL statement will be returned.

This tool allows you to paste a SQL debug notification into the input box below. 
When you press the 'Process' button, the tool will replace all '?' characters in the SQL statement with the corresponding binding values from the 'withBindings' section of the debug notification. It then formats the resulting SQL statement for readability.

Demo here:  https://jakemorgan.co.uk/projects/SQLDebugTool
