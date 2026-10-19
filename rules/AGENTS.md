# monday.com in Antigravity

Antigravity does not render MCP UI widgets. When working with monday.com tools, do not call the display
widgets `show-chart`, `show-table`, `show-battery` or `show-assign`. Treat them as unavailable: where a
skill gives a fallback for a missing or failed widget, follow it; otherwise present results as plain text
or markdown tables.
