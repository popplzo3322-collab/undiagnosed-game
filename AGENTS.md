# Case actions

- For every case, hide tests and treatments with unmet clinical or story prerequisites. Render them only once those conditions are satisfied. Use the same predicate in the click handler before spending AP.
- Once unlocked, an action can remain visible but disabled when AP or test slots are exhausted, or when the action has already been completed.
- Preserve intentionally selectable incorrect or premature actions when they drive a consequence. In CASE 007, insulin remains selectable before electrolyte correction.
- Verify initial visibility, unlocking, and the intended ending route when adding or changing a gated action.

## Shared clinical reference

- All cases load `case-reference.js`. Update that file when adding a case and confirm the diagnosis, relevant comorbidities, and plausible differential diagnoses are covered together by topic.
- Keep the reference available to all cases. Avoid case numbers, spoiler labels, and case-specific results or routes in its entries.
