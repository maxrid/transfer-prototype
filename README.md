# Transfer prototype

A small banking prototype for a live demo: a designer fixes a UI bug in code, opens a pull request, and another designer reviews and merges it.

Open `index.html` in a browser. Look at the "Confirm transfer" button. The design system says main actions use the primary colour; this one is using the danger colour, so the most important button on the screen looks like a warning.

The fix is one line in `src/transfer.css`. The colour roles are defined in `src/tokens.css`.

Northwind Bank is fictional. All names, accounts and amounts are made up.
