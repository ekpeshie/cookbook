# Mise cook-along

A cooking guide where every step comes with an animation, instructions and a timer.

## Prototype

`prototype/index.html` is a single-file, dependency-free prototype. Open it in a browser.

- **Search** with live suggestions that match dish names, cuisines, tags and ingredients.
- **Recipe page** showing ingredients that scale with servings, equipment, and a step overview grouped into Prep / Cook / Serve.
- **Cook-along mode**: an animated scene for each step (cutting styles, stove heat levels, sauté, boil, simmer, lid, flip, whisk, crack, rinse, blend, serve), a timer per step with a chime and auto-advance, and an "Up next" list.

Recipes live in the `RECIPES` array. Each step names a scene, for example
`{k:'cut', item:'tomato', style:'dice'}` or `{k:'stove', vessel:'pot', heat:'low', fx:'lid'}`,
so new recipes can reuse the same small set of animations.
