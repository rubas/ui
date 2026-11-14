---
"@ui-sdk/core": patch
---

`bindDrag`, and every drag built on it, captures the pointer only once it moves past `dragThreshold`. A click on a button inside the dragged element, like a handle in a Transfer or Reorder item, reaches the button.
