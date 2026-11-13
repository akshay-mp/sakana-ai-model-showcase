Create a complete, playable HTML browser game called
“THE ANCESTOR’S JOURNAL.”

It is a single-player Indian adventure about an inherited journal, a dangerous
journey through a monsoon forest, a hidden mountain treasury, and the struggle
to escape with its gold.

The result must be a game with a beginning, playable challenges, checkpoints,
a conclusion, and replay. It should work on desktop and mobile browsers.

CREATIVE DIRECTION

Set the game in a fictional, present-day Indian landscape inspired by the
Western Ghats during the monsoon. The mood should combine mystery, survival,
exploration, and treasure-hunting adventure.

Use Tumbbad as a reference for atmosphere and Indiana Jones as a reference for
the feeling of adventure. Create an original story, locations, characters,
dialogue, music, and visual identity. Do not copy characters, scenes, logos,
or artwork from either reference.

The protagonist is an Indian adventurer who receives an ancestor’s journal.
Keep the protagonist unnamed unless a name is needed for dialogue. The
ancestor’s identity and the true origin of the treasure should remain
mysterious.

The forest hunters are a fictional hostile faction. They must not be presented
as, named after, or visually associated with a real Indian tribe or community.
Their threat can be communicated through dialogue, abandoned belongings,
footsteps, and pursuit. Keep violence non-graphic.

VISUAL DIRECTION

Make the world feel like a lush, dangerous forest rather than a flat green
plane. Prioritize atmosphere, readable gameplay, and consistent art.

- Dense trees with layered foliage, roots, vines, ferns, and wet ground.
- A narrow stream, muddy paths, scattered stones, mist, and light filtering
  through the canopy.
- A large sacred tree with a subtle, otherworldly glow.
- An old freight wagon, a remote railway station, and monsoon scenery.
- Mountain paths, broken steps, moss-covered stonework, and a hidden treasury.
- A recognizably human Indian protagonist with practical travel clothes,
  a journal, and a satchel.
- Clear silhouettes and enough light for the player to understand hazards.

Use realistic or semi-realistic visuals where technically practical. If full
3D is too demanding for a browser implementation, use an attractive 2.5D or
layered illustrated approach with depth, movement, lighting, and parallax.
Avoid blank backgrounds and unfinished placeholder boxes.

STORY AND GAMEPLAY

PROLOGUE — THE PARCEL

The game opens in a rainy Indian city. An old parcel arrives at the
protagonist’s home. Inside is an ancestor’s journal: worn, damp pages, a
hand-drawn route, an illustration of a great branching tree, and notes about
gold hidden beneath a mountain.

The journal says:

“Beyond the station stands a sacred tree that holds its own light. The goods
train will pass it without stopping. That is where you must leave the train.”

The protagonist decides to follow the route.

Present the prologue as illustrated journal pages or short cinematic panels.
Allow the player to turn pages, inspect the tree illustration, and skip the
introduction. The journal remains available throughout the game.

CHAPTER 1 — THE ROAD OUT OF THE CITY

A night bus takes the protagonist beyond the city. Rain streaks the windows
as buildings give way to hills and forest.

At a freight yard, the protagonist boards a moving goods train carrying
secured cargo. A visible sign makes it clear that passengers are prohibited.

Show this journey through a short playable or cinematic transition. Preserve
the order: journal, bus, then goods train.

CHAPTER 2 — THE TRAIN THAT DOES NOT STOP

The player travels inside an open or partly open goods wagon. The train passes
a small remote station named Devrai Halt without stopping.

As the landscape moves past, the player must watch for the sacred glowing
tree shown in the journal. Give the player enough time and a clear cue to
recognize it.

When the tree comes into view, the player must jump from the moving wagon.
The jump is a deliberate decision based on the journal and the landmark.

If the player misses the opportunity, return them to a nearby train
checkpoint and allow an immediate retry.

Do not introduce a derailment, rockfall, emergency stop, or passenger train.

CHAPTER 3 — THE TREE THAT HOLDS THE LIGHT

The protagonist lands near the enormous sacred tree. The goods train
disappears into the night.

The tree resembles the journal’s drawing. Its roots carry a mark matching a
symbol in the book. The protagonist can inspect the mark and read the next
clue:

“Follow the water. Where it disappears beneath the mountain, look for the
steps.”

Let the player explore briefly, then follow a stream into the forest.

CHAPTER 4 — THE FOREST

The stream winds through dense trees, roots, rocks, and mist. Along the way,
the protagonist discovers signs of earlier travellers: a torn satchel, a
broken lantern, disturbed ground, and scattered belongings.

The trail approaches a hidden camp. From concealment, the player sees members
of a hostile fictional group and hears enough to understand that the
travellers are in danger. Avoid graphic imagery.

A lookout spots the protagonist at an exposed crossing. The hunters begin
pursuit.

CHAPTER 5 — THE CHASE AND ROOT HOLLOW

The player must run along a readable escape route beside the stream.

Include a small number of clear obstacles:

- Vault or jump over a fallen trunk.
- Navigate around forest obstacles.
- Reach a large rock and break the hunters’ line of sight.
- Find and enter a hollow beneath massive roots.

The hunters should not automatically give up the instant the player enters
the hollow in full view. The player must first break sight, then remain
concealed while the hunters search nearby.

Communicate the danger through footsteps, lantern light, sound, and a clear
on-screen state such as “HUNTERS SEARCHING.” If discovered or caught, return
the player to a nearby checkpoint without losing all progress.

When the search ends, the footsteps fade. A rear opening leads to a screened
water channel. The player follows it uphill.

CHAPTER 6 — THE HIDDEN STEPS

The stream vanishes beneath a stone shelf. Moss-covered steps match the
journal’s clue.

This is a brief safe moment. Let the player reopen the journal, observe the
mountain, and prepare for the ascent. Save a checkpoint.

CHAPTER 7 — THE MOUNTAIN PASSAGE

The player climbs a short mountain route toward the hidden treasury.

Include a clear traversal challenge: broken steps or a gap between ledges
that the player must jump. A failed jump returns the player to a nearby
checkpoint.

The passage should feel ancient and water-worn, with carved stone, roots,
mist, and distant glimpses of the forest below.

CHAPTER 8 — THE TREASURY

The player reaches a small chamber hidden inside the mountain. Warm light
reveals stone pillars, a moving stone mechanism, and several gold caches.

The entrance to the treasure is protected by a timed stone shutter. Make its
motion visible and understandable. Provide a safe area where the player can
watch its rhythm before crossing.

After passing the shutter, the player collects the gold. Show the amount
carried on screen. Gold is not counted as successfully recovered until the
player escapes.

The chamber’s final route is blocked by an old water gate. Let the player
interact with its latch to open the way out.

CHAPTER 9 — ESCAPE

The protagonist leaves the treasury through the newly opened route and
follows a stone ledge toward daylight. Build tension with sound, movement,
and environmental atmosphere without adding an unexplained collapse or
arbitrary failure.

At the end of the route, dawn appears over the mountains and forest. The
protagonist escapes with the collected gold and the ancestor’s journal.

Show a completion screen with:

- “EXPEDITION COMPLETE”
- Gold carried out of the mountain
- A brief closing line: “The forest keeps its secrets. This gold is yours to
  carry home.”
- A replay button

The mystery of the sacred tree, the ancestor, and the treasure’s origin
remains open for a future chapter.

GAME SYSTEMS

- Give the player clear objectives and contextual interaction prompts.
- Include keyboard controls and touch controls for movement, jump, hide,
  interaction, journal, and pause.
- Include a pause menu and a readable journal containing discovered clues.
- Use checkpoints after the train jump, before the chase, at the hidden
  steps, and near the treasury.
- Make retries quick and restore the correct objective and game state.
- Ensure collected gold is not duplicated on checkpoint retry.
- Show a clear start menu and a completion screen.
- Add adjustable sound or a mute button.
- Respect reduced-motion preferences where practical.
- Make text legible and buttons usable on mobile screens.

IMPLEMENTATION

Build the experience with HTML, CSS, and JavaScript. Use a browser-compatible
rendering approach appropriate to the chosen visual style, such as Canvas,
WebGL, or Three.js. Organize the code clearly so scenes, input, story,
checkpoints, and game state can be extended later.

Deliver the actual runnable implementation and any required assets, along
with concise instructions for starting it locally. Make the complete story
playable from beginning to end; do not deliver only a landing page, a static
story synopsis, or disconnected visual mockups.

If an asset or feature cannot be completed, state that clearly rather than
claiming it is implemented.
