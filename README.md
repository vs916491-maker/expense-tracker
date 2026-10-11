# Expense Tracker

A simple personal expense tracker that runs entirely in your browser. It is a single file, `index.html`, with no installs, frameworks or server needed.

## What it does

- **Add an expense** with a date, an amount in ₹, a category (Food, Travel, Bills, Shopping, Other) and a short note.
- **See all expenses** in a list, newest first, each with a **Delete** button.
- **Filter by category** using the dropdown above the list; it also shows how many expenses match and their subtotal.
- **See the total spent this month** at the top of the page.
- **Keeps your data** in your browser (`localStorage`), so it is still there after a refresh or restart.

## How to use

1. Open `index.html` in any modern browser (double-click it).
2. Fill in the form and press **Add expense**.
3. Press **Delete** next to an expense to remove it.

## Notes

- Data is stored only in the browser you use. It is not sent anywhere, and a different browser or device starts empty.
- Clearing your browser's site data will erase your expenses.
- The layout adapts to phone screens.
