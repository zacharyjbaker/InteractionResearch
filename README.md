# Interaction: Movement of handheld controllers

Example 1: Spellcasting Duel -- Trace spellcasting glyphs with your wand (your controller) faster than your opponent, to counter their spells and attack back.

![IMG_8333 3](https://github.com/user-attachments/assets/c50369c2-0b1d-4844-9887-a4fe6eb4685b)

Example 2: Fishing -- Catch fish from a boat, moving your fishing rod counter to your catch's movement to exhaust the fish and finish the catch

![IMG_8333 2](https://github.com/user-attachments/assets/54118dc1-784b-4c2f-bf3d-16ef5ee65e8a)

Example 3: One Shot Roulette Defend against waves of enemies, with a caveat: Everytime you successfully shoot or slash with your weapon, your weapon shifts into a new one.

![IMG_8334](https://github.com/user-attachments/assets/a9335ae6-3f82-4c7e-a908-dae16d23f11d)


# Implementation Summary

I ended up implementing three versions of the spellcasting idea, with each way using the motion of the controller (and triggers) to cast different spells:
1. Tracing a glyph using the staff as a brush. The player would have to connect nodes via a line in a specific order, directed by their spellbook and the on-key musical notes that would play if they traced in the correct order.
2. Swiping in a series of specific directions. The player would see a series of arrows on their spellbook, and would have to swipe the controller in the same series of directions as shown on their book.
3. Aiming a fireball at targets: The player would have to shoot fireballs conjured from their staff into their targets--flaming rings.

Following my test in-class, the main feedback I got was that the position of staff in the VR space (especially for drawing and swiping) was somewhat disjointed from the position of the hand controller in real space, and that the method of casting the spells was a bit confusing. I did expect that most peoples favorite minigame was tracing the glyph as that was also my favorite (and most fun to program). I think the spell-tracing interaction is also the most expandable to a larger game, with more spells, features, etc.

# Test Questions

Pre-test
1. What kind of VR games or experiences are you familiar with?
2. What is your primary method of interfacing with games (controllers, M&K, touchscreen, VR, etc.)
3. What possible features come to mind that focus on the flexibility of VR controller movement?

Post-test
1. What was your favorite of the three spellcasting minigames?
2. Which minigame best utilized the unique capabilities of VR?
3. What would be a fitting expansion of the interactions in this research project?

### Test 1:

Pre
1. Expiration FPS games
2. Controller
3. Shooting, aiming, climbing, traversal

Post
1. Drew a glyph, liked fire effects
2. Drawing a glyph, arrows had potential but needed guidance
3. Exploration, at different checkpoints with magical puzzles

### Test 2:

Pre
1. None
2. mouse and keys
3. sword

Post
1. Drawing
2. Drawing
3. Puzzle game, opening arcane locks. Spell duel

### Test 3:

Pre
1. None
2. mouse and keys
3. Beat Saber

Post
1. Flamethrower
2. Swiping
3. More spells! and patterns. go through spellbook pages

### Test 4:

Pre
1. Played beat Saber
2. Desktop pc
3. Rod/handle/staff
   
Post
1. Drawing
2. First one
3. more intersction with spellbook, flipping

### Test 5:

Pre
1. Superhot, steamvr
2. Mouse and keys
3. Being able to move your hand, range of movement

Post
1. fire circle
2. First one ability to draw
3. More refinement of control and alignment of controller object. Hand holding the staff

### Test 6:

Pre
1. Yes
2. Controller
3. Triggering

Post
1. Dont do it, when coerced
2. Controllers

### Test 7:

Pre
1. Fire circles
2. All feel samey, circles graphical output
3. Time based interaction, competition, racing to complete, build up a spell recipe. A lot of gestures

Post
1. A little bit. Superhot
2. Mouse and keys
3. Gun and drawing

### Test 8:

Pre
1. Drawing runes, fire particles
2. Fire one is most power fantasy
3. Rune drawing expansion

Post
1. Sweeping
2. Rod is a bit disjointed
3. Make tracing onto spellbook to put into world.


