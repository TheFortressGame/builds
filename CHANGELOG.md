# The Fortress - changelog

Cumulative per-build release notes, newest first. REGENERATED from the
release bodies by .github/scripts/repair_release_notes.py on every
publish - do not edit by hand.

## v0.0.28-P4208

- The pace reads the WEEK's position, and ahead of the clock HALTS the refactor (Nathan's rule)
- The refactor pace is derived from the account meters - paced to a bit under 1/7th of the week a day, released on the last day, and it names a swap when the accounts diverge
- The nightly log is UTF-8 throughout - PowerShell 5.1's Tee-Object -Append wrote UTF-16 into it
- 'TECH-LEAD: BLOCK lifted' is a lift, not a new block (#6200 was held by its own lift line)
- The club and axe wear their icons' colours - a palette read off the icon, applied by one fixed path
- Weapons face the way he faces - the grip socket pins the head side, not just the haft; the axe is the hatchet
- The live hero is permanent - the LIVE toggle is gone
- A fresh HUD window is placed at its final font and chrome, so the Character run no longer floats into the Log *(fix attempt - still being verified)*
- The Builder tab's open Filter row wraps at phone width instead of pushing the screen off the right edge *(fix attempt - still being verified)*
- Nathan's P4169 pass - thick walls, straight pieces, hearth-stone room, a door and outside faces, the exit square

Behind the scenes:
- Say it once - the five lines are the only place that states what waits on Nathan, and nothing above them repeats it
- Interior rule 15 - one geometry change per interior PR (GEOMETRY-EXEMPT)
- Slice 2 - surprised_by findings, the nightly (journeys + personas, new findings to the standing issue), task installer, Daily Brief line
- V51 - two more parked UX questions (scroll cue, the Defend run's 4 px) (#6147, #6182)
- A lane row's identity is owned by the pin registry - never write the repo copy over the deployed one
- Interior rule 8 mechanized - a static-gates scan fails a PR that adds hand-drawing to a script that writes an image (ART-SCRIPT-EXEMPT to declare)
- The structure numbers reach Nathan daily, and a lane he does not open routes its asks through the console
- Story-canon and stat-engine bases locked; hero-base drawn live (Nathan 2026-09-24)
- 'which wall a decor piece stands against' - MapData.decor_wall_side (#5962, #6189)
- The cottage's code and test comments name interior stages by NAME, not number
- Round props stand on a drawn 2:1 base ellipse - rule 14 in the prop validator
- A wall piece's side is one declared field on its decor entry, read by both renderers
- The daily Claude Code update retries past EBUSY, files an issue when it gives up, and the self-check's window narrows to one day; Stat Wiring moves to account B
- The eyes test (scripted prefix + before/after judge), expectation_met findings, the completionist persona (#6147 slice 1b)
- Progression's done_when in Nathan's 10:53 AM words - his flow is playthrough and feedback, the outline is the lane's playtest map; GUI choice confirmed
- Interior Stage 4 - when the whole-room edit can't change a surface, per-surface Codex paintings under conditions (#6183, Nathan 2026-09-24)
- Two lanes minted PAUSED - Progression and Stat Wiring, Nathan's words as goal and done_when (2026-09-24 10:32 AM)
- V50 - more UX questions from the simulated player's harvest, parked in OPEN DESIGN QUESTIONS (never posted)
- The cottage's 17 functional mistakes become interior rules - pipeline doc table, blockout checklist, cottage-layout 'never' (Nathan 2026-09-24 9:50 AM)
- Interior pipeline gains Stage 2 MOCKUP - many whole-room Codex mockups, Nathan picks, the pick sets positions and the skin's reference (Nathan 2026-09-24 9:49 AM)
- The protagonist's in-world appearance, in Nathan's words - nondescript, short brown hair; silhouette rule scoped to portraits/cutscenes

## v0.0.28-P4176

- The bar's PANEL button is a toggle that opens and closes the full panel (#6140, #5907 brief #10 PR A) *(fix attempt - still being verified)*
- The live hero's weapons are the body author's own pack at real lengths - sword, club stand-in, axe, spear

Behind the scenes:
- V49 - the simulated player's first harvest's UX questions parked in OPEN DESIGN QUESTIONS (never posted)
- The player's hands and eyes - a command channel in the capture driver and a blind observe/act agent loop (#6147 slice 1)
- The entity tabs build their stat rows through the base, and the pool getters fold into _tab_entity() (#5907 brief #9b)
- Cottage-layout lock's skin_is follows the Stage 3 furniture rule - lifted from the room painting
- Hero-weapons never is a list and names its gate - the lane prompt stamp printed it letter by letter

## v0.0.28-P4169

- The cottage hearth, wardrobe and washstand from the pre-spike painting, blocks grown to them
- Skins for the live hero - wears B (villager) by default
- The stone floor and walls, cut from Nathan's picked room onto the grid

Behind the scenes:
- Interior Stage 3 furniture is lifted from the room's own painting; prespike_pieces.md is the style anchor (Nathan 2026-09-23)
- Send-to-lane.ps1 - any chat reaches any chat on either account; the routing rule had no cross-account path
- Skin palettes are data - <name>.palette.json beside each LiveSkin; skin_hero.py is the one fixed tool that applies them
- How a character skin is made - Nathan describes, Codex writes the palette as data, one fixed tool applies it (Nathan 2026-09-23 10:57 PM)
- Token ledger - per-chat burn, Nathan vs automation, daily at 21:55 - plus the box offload audit
- Interior stage 3 step 2 is one reprojected piece per surface, as the cottage did it (#6142); registry records the cutter
- Quiet check pushes only for a named reason; overwatch every 2 h, on change

## v0.0.28-P4159

- The live hero ships in the build behind the LIVE view - walks, and attacks with the pack's own clip

Behind the scenes:
- Lanes.json record - Character Models v2 and iOS v2 rotations, tech lead effort high (cost tweaks 2026-09-23)

## v0.0.28-P4157

- Full-height see-through front walls, with art on and in the block view
- The LIVE view - a default-off toggle that draws the hero live in the cottage (#6110 cards 7-8)
- Live-hero slice 3 - a second character is a spec, not code (#6110 card 6), and the board harness
- Standing pages are never closed, and a new Fleet board unpins the closed one *(fix attempt - still being verified)*
- Live-hero slice 2 - a weapon in his hand via BoneAttachment3D (#6110 card 4)
- Live-hero spike slice 1 - drawn live from the model, card 1/2/3/5 measured
- The rotation's mid-turn guard reads the transcript's turn, not the keepalives
- The exit is the square inside the door, and the front walls are see-through over the room *(fix attempt - still being verified)*
- The cottage's gate-2 positions are gated, not written down - base_locks_gate pins locked_values; walls locked; the grow step edits FOOTPRINTS_M; DECISIONS 08-13 superseded for interiors
- Governance docs are tech-lead-held paths - stream plans, pipeline docs, interior specs, base locks (#6080/#6109/#6111 merged before their review)

Behind the scenes:
- LiveCharacter is the owner of "a rigged model drawn live in 2D" - trial, default off, with its go-live conditions
- Board harness writes each clip frame's real game time, so clips play back at true speed
- Four forward-work lines from closed issues
- The interior-room row records what gate 2 now enforces - positions locked by base_locks_gate (#6117), sizes grow in FOOTPRINTS_M (#6115), the stage-2 tooling (#6100/#6105/#6118)
- Who talks to whom - the tech lead owns process; the console is reached for four things
- Fit blocks to art - positions frozen at gate 2, sizes may grow to approved art; cottage positions LOCKED
- The live-model plan records the tech lead's readings of the #6110 card

## v0.0.28-P4140

- Blockout walls stand at declared metres, not the rejected wall art *(fix attempt - still being verified)*
- A TECH-LEAD BLOCK holds its commits - a PR built on a blocked branch inherits the BLOCK (#6100 landed #6096's blocked code)
- The blockout is one command, one spec file and an operator card
- The collision check counts a lane's OWN unpushed changes, not main's commits it merged in (#6099's false positive)

Behind the scenes:
- Build-publish macos + publish legs run on the box - zero cloud minutes per interim build
- The live-model card's height is HERO_WORLD_HEIGHT = 56 px, re-synced from #6110 (the copy carried a stale 32)
- The live-model plan carries #6110's acceptance card and tripwires verbatim
- The live-model spike plan - Godot pieces by name, measured acceptance, tripwires
- Interim builds on demand - a merge fires a build only when its PR names something to TEST
- Interim builds at least 3 h apart (6 h via build-cadence.json until #6103)
- Base locks - the wireframe under every skin, named as data and gated
- Chats rotate by context at a clean spot - rotate-chats.ps1 every 30 min
- The hero is the pack as its author ships it (#6094); the bone-scale-table rule is marked superseded by rule 4; #6022's remaining items named

## v0.0.28-P4127

- The refactor pace cap holds merges - refactor-program.json briefsPerDay is enforced on the merge path (merge-pr.ps1 + the sweep), not only read by the nudge task
- The Stage 2 blockout - the same room with every piece of art replaced by a flat box

Behind the scenes:
- The hero is the downloaded model, assembled the way its author says
- The tab-entity row gains the pool tabs, the one stat-row body and the refresh hook (brief #9, #6087); dup_pairs 22 to 21 in provenance
- A rotated lane keeps its model, its paused suffix and its lanes.json row
- The refactor pace holds the briefs, not only the nudges (2/day)

## v0.0.28-P4121

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- The pool tabs answer _tab_entity() and lose their private stat-row and upgrade copies (#5907 brief #9)

## v0.0.28-P4119

- A routine never backgrounds a pipeline - no-background-gate.ps1 blocks run_in_background while FORTRESS_ROUTINE is set
- RENDER-EVIDENCE must carry a link or a capture path, not prose *(fix attempt - still being verified)*
- The five bare Out-String captures the daily capture-idiom self-test names get -Width 4096 (#5559); one of them was mine

Behind the scenes:
- Roster row names the third copy of both type orders (cheat_manager.gd:1538-1539) for #8b; source_commit c770c8b4
- The tab base owns the roster grouping and split template (brief #8, #6083); dup_pairs 24 to 22 in provenance
- One roster grouping and one split-roster template on the base (#5907 brief #8)
- Interior rows from the interior pipeline (#6080) - the room as data, the TileSet per art set, the one art path; the #6025 tile generator deprecated as a drawing script
- The interior pipeline - Describe, Lay out, Skin (Nathan 2026-09-23 12:02 PM)
- Models 2026-09-23 (Nathan: yes on all): tech lead on Opus 5.5, active lanes at medium effort, refactor pace 2/day; applied on the box at 11:59 AM
- The tab base owns the per-frame state poll (brief #7, #6076); dup_pairs 43 to 24 in provenance
- One per-frame state poll on the base (#5907 brief #7)
- The audit JSON carries every scored pair (dup_all), so a brief is sized on the whole family, not the top-20 window
- The week's capture and test gotchas land where sessions read them - overlay_parent() is the root, is_visible_in_tree() under a capture Window, capture-state's six facts

## v0.0.28-P4106

- A gold Level Up from a card confirms like the header's XP one (#5969, #5907 brief #6)

Behind the scenes:
- Reading pass 2 (scripts/data) - four new rows (lock conditions, checkpoint singleton keys, progression availability, settings persistence), four rows corrected, G items 15-19, provenance
- The roster row's gold Level Up confirms (brief #6, #6064); the 06:30 audit numbers and brief #7's target in provenance
- The floor follows main - floor followed main by the weekly audit: theme_overrides 2542 to 2535. Every count may only fall from here

## v0.0.28-P4102

- Native ratchet gets the floor-is-min-of-branch-and-main notice and own-delta bar (#5944, #5955)
- The issue pass exempts live standing pages by title/label, not closed numbers *(fix attempt - still being verified)*
- Box-lane terminal checks salvage first and gates COMPLETE on agent success
- A turn-cap timeout grades INCONCLUSIVE, not FAIL, and leaves pass_all
- Step-4 deploy carries capture-assets/ one level deep
- The odd hearth was a stray frame and two rows of feather, not a bad drawing
- A branch that keeps going after its own partial squash must not read STALE *(fix attempt - still being verified)*
- Steward-handoff reads trigger clauses and marks fired items RETIRE-CANDIDATE

## v0.0.28-P4093

- The dresser and washstand wear the set's OWN wood - PASS 5
- One variant must not draw at a different WIDTH from its siblings
- Capture-state -Content 540x1170 renders 540x1170, graded by the result *(fix attempt - still being verified)*

Behind the scenes:
- The capture harness row records how capture-assets/ deploys (deploy_subdirs, #6053) and why it had not
- The capture harness row records #6043 resolved by #6045 - result-graded captures (read-back sidecar + Assert-CaptureSize), verified live
- The capture harness row records #6043 (540x1170 renders 540x960, routed to the box lane) and the -DebugRedirect-after-driver-change rule

## v0.0.28-P4087

- Redraw the cottage dresser + washstand, per-set geometry — PASS 2
- Prop conventions are a PR gate - art a PR changes must pass validate_prop_conventions.py (tech lead ask 2026-09-23 2:00 AM)
- A SECOND codex run for the same issue must not die at setup
- The validator can read testing/, and a run that reads NOTHING is not a pass

Behind the scenes:
- The coming-soon modal is owned (brief #5 landed); the prop validator row catches up with #6031/#6034; G item 15 = brief #5b
- Eight placeholder modals become one opener and data (#5907 brief #5)

## v0.0.28-P4081

- The hero walks at the pace he did before, whatever the room's zoom
- Put the touch-steer vector into Copy game data (#6020 attempt 2)

Behind the scenes:
- The validator gains the one cross-file check it could not make
- Prop art conventions have one validator that no gate runs (G item 14); #6031's second walker is recorded as the copy to fold in

## v0.0.28-P4077

- Skin the native floor and walls from the painted materials we already own
- The tech-lead hold has ONE definition, covers the render pipeline and the vendored roots, and BLOCK holds on any path
- USE THE SYSTEM AS SHIPPED - vendored-asset manifest gate; lane-scoped return brief so a lane sees only its own questions (Nathan 2026-09-22 11:20-11:22 PM)
- The modularity scan is a HARD gate locally, because CI blocks on it

Behind the scenes:
- The hero's on-screen pace (a three-branch contract, #6028), the native cottage's shell tiles (#6025), and the vendored-asset gate's real paths
- The hero frame source row records the #6022 follow-up owed on main (bone-scale knob + skin-shrink path, defaults off)
- Render acquired rigs as shipped: all body reshaping defaults OFF
- Rule 4 - an acquired rig, asset, library or engine feature is used AS SHIPPED
- The hero's body model is data - a measured proportion table, never paint over an unmeasured body (Nathan 2026-09-22 11:12 PM)
- Management chats never address Nathan: their status block starts NEEDS CONSOLE and the console routes (Nathan 2026-09-22 11:13 PM)
- Lanes.json: Character Models is Storybook only (Nathan 09-22 11:05 PM); Interiors' done includes the woodsman built native with the painting as reference

## v0.0.28-P4066

- Painterly grain, the one lever that reaches this set's texture

Behind the scenes:
- Delete the LEVELING roster forge never routes to (#5907 brief #4 PR B)
- The hero's weapon overlay has an owner (#5993) - one placement pass, the turned views and their factors derived from the side art by one generator

## v0.0.28-P4062

- A tab is never handed a mode it is not listed under (#5907 brief #4 PR A) *(fix attempt - still being verified)*

Behind the scenes:
- Warm leather boots, and the finding that this set is painterly rather than flat
- Box-ops: rotate-management.ps1 - the management chats rotate on their own schedule (overwatch weekly or >8 MB, tech lead >15 MB); lanes are Nathan's, consoles by /clear (Nathan 2026-09-22 9:17 PM)
- Mode membership has an owner (#6004), and the two "unreachable" branches are recorded as what they were - reachable through a routing defect
- Ink the hero at final resolution, and measure his colours off the set's own hero

## v0.0.28-P4057

- The spike is the only cottage, which is why the save now comes back *(fix attempt - still being verified)*
- The hero's linework, drawn from a rendered part map
- Skins for the hero - a colour per garment, painted on the model's own atlas

Behind the scenes:
- One command renders a named skin, its material map and its linework
- Lanes.json: paused lanes run at medium effort (ops review 2026-09-22 item 4); launchers and registry already carry it
- The tab's entity has an owner - #5996 put _tab_entity() on TabBase; the pool and building variants stay contested for brief #6
- The base owns the stat-upgrade path (#5907 brief #3)

## v0.0.28-P4050

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- The hero's weapon turns when he does

## v0.0.28-P4049

- The hearth stands AGAINST the west wall, not a quarter metre inside it *(fix attempt - still being verified)*
- The refactor is a PROGRAM - refactor-program.ps1 keeps the next brief flowing at a set pace; daily audit; program line on the board (Nathan 2026-09-22 6:17 PM)

Behind the scenes:
- Reading pass 1 - the tab family: six new rows, two corrected, the two unreachable branches and the base's own repeats recorded
- Five lines for Nathan gain AS OF: the date and time copied from the stamp, never computed (Nathan 2026-09-22 6:44 PM)
- The assignment sheet has an owner (#5984, brief #2), and dup_pairs is a floor - said where the number is read
- Structure-audit: measure daily, post only when a ratcheted count moved or on Sunday (Nathan 09-22: capacity)
- One owner for the assignment sheet (#5907 brief #2)
- The tab level-up row is owned - #5975 put the roster row's level-up on TabBase with the entry point as a Callable

## v0.0.28-P4041

- Merge-pr.ps1 holds a game-code PR for the tech lead's review line (and honours TECH-LEAD: BLOCK), so the gate applies to lane merges, not only the sweep's
- Collision check flags real work only; audit and board find their issue by list-and-match
- The board leads with the questions and comes INTO the chat (return brief + "board" keyword); merge list removed; Discord-as-one-surface on the roadmap (Nathan 2026-09-22 5:46 PM)

Behind the scenes:
- The hero in the game is now the downloaded model, rendered
- Clock-context: a line on every prompt while an account's Claude login is broken (process review 2026-09-22, item 5: account B's OAuth expired for 3.5 h and only Nathan can log in)
- Structure-audit: the report lists the named target file's own pairs
- One owner for a roster row's level-up (#5907 brief #1)

## v0.0.28-P4033

- The hearth is 1.00 m deep, which is what its picture draws *(fix attempt - still being verified)*
- Refactor collision check, DECISION lines + done-in-24h on the board, steward closing arm, new-lane and decisions rules (Nathan 2026-09-22 4:37 PM)
- Paused lanes are never quiet-checked; the Refactor lane executes what the tech lead briefs (Nathan 2026-09-22 4:17 PM)
- Render unlit, because a flat texture does not make a flat sprite
- One title-bar factory, so a new window cannot pick the square-cornered one
- Five lines for Nathan on every pushed lane message; (work paused) titles; set-lane-state.py (Nathan 2026-09-22 3:55 PM)
- Lanes registry + Fleet board + fleet naming convention (Nathan 09-22)
- Restyle on the MODEL, because a repaint moves the geometry

Behind the scenes:
- Fleet-board: Routines section (overnight digests, audits, sweeps) with last-run and late state
- The stylebox row lists all 13 factories - create_subtab_style was never in it
- Lanes.json: the cottage lane is Fort A: Lane - Interiors (Nathan 09-22; the title and launcher already were)
- The directional wall-art row - one ladder owner since #5952, the wall-side decision still written twice

## v0.0.28-P4021

- The hearth faces its wall, and the red wall marks come off the overlay *(fix attempt - still being verified)*
- The identifier gate knows a built-in Object member is not a hallucination
- The structure ratchet judges a PR on its own delta, so main's exempted rise is not charged to the next PR

Behind the scenes:
- Refresh the registry against #5931, #5947 and #5954 - the mob sprite is native, FLAT_SETS has one owner, hook overrides left the duplicate count

## v0.0.28-P4017

- An override of a base hook is not a duplicate
- One list says which art sets are flat - world_scale.gd stops keeping its own
- The type-swap row paints both type words, and the capture lane can render a levelled item
- The nightly records what its subject CONTAINED, not just how old it was *(fix attempt - still being verified)*
- The ratchet's floor is the lower of the branch file and main's, and the weekly audit lowers the file itself
- A stale baseline is not a loosened one, and the ratchets stop telling you to undo your own work
- PRECONDITION - a test that bails instead of failing is caught, not caught by eye
- The collapsed-chip Escape guard stops reading process-global viewport state
- The pre-push gate runs all eight static-gates scans, not three *(fix attempt - still being verified)*

Behind the scenes:
- Render the hero's whole frame set from the rig, anchors and all
- The engine owns the mob's animation, not a hand-written index
- Refresh the registry against a day that acted on it
- One inspect-close refresh on TabBase, and the two seams that were hiding under six copies

## v0.0.28-P4004

- The timers row counted the accumulate form and missed the countdown form the tree actually uses
- An exemption GRANTED is not an exemption DISCUSSED
- The hand position comes out of the SAME render as the frame
- Declare the nine prop projections that were CHECKED, so the art inventory stops inferring *(fix attempt - still being verified)*
- The art inventory measured a front elevation against depth it never draws *(fix attempt - still being verified)*
- The navigation row read ours=0 while a live BFS router ran every frame
- The scope gate's block names the two accepted status forms and says a subagent's look does not count
- WINDOWRADIUS - the corner-radius rule is enforced instead of documented

Behind the scenes:
- The stylebox and override counters scan code, not comments
- The surface factory names the gold edge, so the settings rail stops being a special case
- The native room already owns the footprint, and the art-set row was wrong
- The window-surface factory takes a body tone, so the settings panel stops hand-building one
- The owners registry - one file and one function own each shared behavior

## v0.0.28-P3990

- The soak retains the field that answers the next question, not just the verdict *(fix attempt - still being verified)*
- The green-PR sweep holds a game-code PR for the tech-lead review up to 60 idle minutes, then merges and counts the gap; DECISIONS: the company model and the structure floor (2026-09-22)
- The structure ratchet - duplicates, oversized files/functions, code-built styles, data-in-code may only fall
- The structure audit - structural health as numbers, a committed baseline, a weekly report with a refactor target, and a skill
- The settings window wears the same chrome as every other window

## v0.0.28-P3985

- Round props stand on a disc, and a wall's grid line stops floating in front of the wall *(fix attempt - still being verified)*
- Damage types wear their colour, the settings window has four corners, and a clicked rail item stays lit
- The contention guard tests for a GPU contender, not for any Godot, and the reaper compares paths canonically

## v0.0.28-P3982

- Run-soak gets a real -NoTabChurn switch, and its proof of work asks for scene trips, not tab presses *(fix attempt - still being verified)*
- The clock hook adds a RETURN BRIEF when Nathan's last message in a chat is 90+ min old
- The registered height is the WHOLE sprite, not the shoulder *(fix attempt - still being verified)*
- The cron-slot self-test's "no gh" case made a REAL API call, so its REST fallback had never run *(fix attempt - still being verified)*

Behind the scenes:
- Post-brief's self-test is asked on every PR whether it still passes

## v0.0.28-P3977

- A prop's projection is declared per art set, not guessed per variant file

## v0.0.28-P3975

- Latest-build.json only ever names a game build (v<x>.<y>.<z>-P<n>), never the launcher release
- The conflict resolver handles the collision that actually happens
- The scope gate's detector consumed its own evidence
- The invisible-engine report had three producers and an exit keyed on one
- The self-heal guard reverted every deploy of the file it guards
- The meta-review ledger push reads its exit code, and provisioning never resets over unpushed work
- The delivery driver keeps a log
- A write that never happened is a failure, not a 0-file success
- Counters carry ArtCache retention, so the census can kill its own leading suspect
- A file that is always running never deployed - the step-4 write retries a lock (#5562 follow-up)
- The JSON-array collapse, fixed once at a shared helper instead of a sixth time in prose

Behind the scenes:
- A parameter named after a PowerShell automatic variable never binds - now a guard, not a fourth comment
- The clipped-foot detector is asked on every PR whether it can still fail
- A mob's size comes from how big it really is (#5864) — DRAFT, needs Nathan on the rat
- Step 4 says WHICH kind of nothing happened
- Week of 2026-09-17 - 5 ideas, 2 decisions

## v0.0.28-P3958

- Restore the acquire tool SOURCES.md tells you to use
- The lane-escape test asserts ABSENCE, over every spec, and can fail
- A captured message must survive the console it was captured on
- The render harness can shoot a rig that carries its OWN clips
- The prop validator reads every declared prop, and can see a foot the canvas cut through *(fix attempt - still being verified)*
- Delete a refuted claim that was hiding six pieces from the reach test *(fix attempt - still being verified)*
- Mobs CAN be animated now, and none of them moved
- Nathan's queue reads pull requests too, and says so when it truncates
- When nobody captured the visual change, go capture it - and never publish a frame the lane refused

## v0.0.28-P3948

- A piece is drawn the size of the box that stops him *(fix attempt - still being verified)*
- Soak-no-tab-churn, so scene transitions can be measured without tab churn
- /box capture renders a freshly-synced tree instead of dying on C:\

## v0.0.28-P3945

- The classic room's colliders leave the physics space; collision is declared data again *(fix attempt - still being verified)*
- Read-ci-failure prints the REASON first, not 150 lines of the script that failed
- The stick layer sizes itself, so it stops asking the engine to fight it *(fix attempt - still being verified)*
- Tag outdoor props so the geometry sidecar can SEE the overworld
- The component capture lane renders THIS commit, and cannot pass a blank frame
- The leak probe reports a fitted trend with its noise, not a two-point delta

Behind the scenes:
- The hero's boots land on the point the room says he stands on
- The capture lanes share one harness, and a blank PNG is no longer evidence in six of them

## v0.0.28-P3937

- The overwatch digest goes to a dedicated pinned chat, and the RDP consoles are never quiet-checked
- The leak probe's OS summary counted a post-exit sample as its endpoint

Behind the scenes:
- Hero.png carried the hood too, and it is the texture the live sprite loads

## v0.0.28-P3934

- The relay retries once on opus when the first model returns an API 5xx - account B's sonnet alias failed every call for an hour
- An undelivered ask keeps the chat's prior state so the next pass retries; the hourly re-ask key is spent only on delivery; Stalled-chats note once per hour
- The Stop hook's promise match ignores blockquotes and fenced code (#5817 item 14)

Behind the scenes:
- Get rid of the hood - 29 frames, verified, as an approval-gated draft
- The keep-alive process as reviewed and rebuilt on 2026-09-21

## v0.0.28-P3929

- The title keeps its words, and the chip wraps between them
- An exempted rise must also be recordable, or NATIVE-EXEMPT is unreachable
- A chat that answered CONTINUING is not asked again until it moves; after an hour unmoved it gets one different question per hour (#5817 item 15)
- He carries his weapon in every room, and holds the axe by its handle
- Check a PR body against the three gate contracts before opening it
- The leak probe reaps its OWN orphans instead of being blocked by them
- A rotated chat's builds are announced to its successor - lineage recorded at rotation, announcer follows it and the pin registry (#5817 item 5)
- The quiet check logs every pre-digest skip and duplicate-registration decision

## v0.0.28-P3921

- Levelling says what it bought, instead of closing the card
- The equip lesson is taught once, not whenever a slot is empty

## v0.0.28-P3919

- Every piece's collision box is read off the art it draws; hidden overlay lines recede *(fix attempt - still being verified)*
- Build-on-merge baseline is the latest published build's head by commit count, not the gh run listing
- Keep-alive review batch 2 - answers need a live ask, STATUS must lead, backoff bookkeeping, dedupe, merge-path retries
- Keep-alive review batch 1 - no mid-turn asks, relay timeout + pid lock, recycler spares live tools and honours DryRun, quotes are not build claims

## v0.0.28-P3915

- The Stop hook blocks a build-number claim the box has not announced for that chat
- The static hero is the same man as the one who walks

## v0.0.28-P3913

- Escape closes an open chip from one place, and the settings window is one colour
- The whole loot area takes a drag-out, not just the tiles in it
- The quiet check's waiting guard counts only shell tasks under 60 min, never subagent outputs

Behind the scenes:
- Nathan's 09-21 order - cottage and model, then the story remainder, then stat wiring; the full code review (one owner per shared behavior, native over home-built) after the lanes close

## v0.0.28-P3909

- His weapon shows in his hand - the first visible gear swap
- The build-landed message names the build head and each merge commit, so the receiving chat can verify ancestry before telling Nathan
- The Playable message is three plain lines - Playable, Changed, Test

## v0.0.28-P3906

- The native cottage is walkable end to end, the exit works, and the overlay reads as depth *(fix attempt - still being verified)*

## v0.0.28-P3905

- The settings rail gets an edge on every side
- The build announcer accepts the in-progress run that owns a fresh release
- A landed build is announced to the chat that made it, with the P-number

Behind the scenes:
- Mixed gear on the character is deferred, with the cost that defers it

## v0.0.28-P3901

- Back out one level at a time, and put the values beside their labels
- The build-on-merge baseline refuses a stale run listing (two redundant builds, P3886 and P3899)

## v0.0.28-P3899

- The overwatch change key excludes the receiving console, whose own reply changed it every pass
- An unchanged overwatch digest is not delivered again (fresh copy every 180 min)
- Step-4 self-test retries a short hash read; six live routines get contract rows
- Quiet check clocks a chat by its OWN activity and names a stuck turn
- Branch cleanup must not leak a classification answer as its exit code
- Narration is not a closing keyword, and a Closes list may not outrun its own diff
- The RUNS-outcome panel folded broken-workflow-file runs into "killed" too
- Steward handoff extractor keeps whole items, plus a committed lane-ref instrument (#5744, #5772)
- A comment naming the verdict tokens is not a verdict, and close the RENDER-EXEMPT escape hatch
- A short-circuited nightly can no longer look like a full sweep

Behind the scenes:
- Commit the 16 deploy-dir orphans flagged by deploy-parity
- STALE banners on game-design-world-v2 and game-design-loop-v3

## v0.0.28-P3886

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- Auto-pin machinery tears down a pinned chat's supervisor on ANY archive event with zero alert to Nathan

## v0.0.28-P3885

- ScreenChrome closed a RefCounted cycle on itself, leaking 4 objects per mode entry
- Run-soak can force a rendering driver, and voids a silent WARP fallback

## v0.0.28-P3883

- The native cottage's collision follows what is DRAWN *(fix attempt - still being verified)*
- Probe-scene-leak can force a rendering driver, and voids a silent WARP fallback
- A soak with no proof of work is INCONCLUSIVE, never PASS - and the nightly picks a save that can actually churn

## v0.0.28-P3880

- The axe hits for nine, and the card says so once
- The quiet check's delivery agent has no file tools; the deployed script self-heals from a golden copy; the installer refuses a stale checkout
- Tools/ must never ship - #5699 put 14.6 MB of it in every build
- Overwatch - every 30 min the meta console gets every chat's last message and pushes what a script cannot judge; delivery hardened

Behind the scenes:
- Add a windowed GPU/native-memory leak probe for issue #5595

## v0.0.28-P3875

- 'show collision' toggle on the cottage prompt, in both rooms
- Character pipeline - acquire CC0 rigs, render at real-metre scale, gate the ground contact
- The quiet check ignores the registration's busy flag - quiet is measured from the transcript only
- Quiet check composes the exact ask; delivery agent sends it verbatim

## v0.0.28-P3870

- Native cottage spike - the Builder's cottage from engine nodes, Classic/Native on entry

## v0.0.28-P3869

- The quiet check's delivery agent gets the spec inline on stdin, never a path it can misread
- Claude Code on the box updates itself daily at 04:30, ahead of the 05:00 recycle that adopts it

## v0.0.28-P3867

- Furniture is drawn on the box you collide with, not on the cell it is filed under
- The quiet check reads the STATUS line where it asked for it - the head of the reply, not only the tail
- The board's freshness panel graded staging leftovers, not publish targets
- Quiet check backs off on prose replies, persists answers, puts STATUS first; build-on-merge baselines on the last SUCCESSFUL build
- Gate the hero's walk frames on a VERTICAL contract, with a one-way debt list

Behind the scenes:
- Two texture quirks that cost real test failures today

## v0.0.28-P3861

- Size him by the man, not by his canvas
- The 3D capture lane was burning out the props it exists to inspect

## v0.0.28-P3859

- A set whose projection is locked does not get a vote from the pixels

Behind the scenes:
- Stale-3d can never re-arm after a non-driver label removal: an orphaned marker blocks the flag and the clearing arm cannot see it (#4782, 22.4d unworked, unflagged 1.4d)
- Patrol 1's new supersession test exits 2 when run exactly as documented, and the 4 self-test checks that would notice are silently skipped in the only environment that grades them

## v0.0.28-P3856

- Refuse a scene-cycling soak on a pre-repair save instead of measuring a bounce loop
- The native-coverage audit counts CODE, not prose - every row was inflated by commentary
- Name the scene the driver is stuck on, not just that it is lost

## v0.0.28-P3853

- The player's collision box is a real 0.40 m person, not an eyeballed 10 px

## v0.0.28-P3851

- Add --soak-3d mode and emission
- Square overhead capture and proven occlusion for the 3D capture lane
- Hide every CanvasLayer generically, tighten overhead framing, and prove per-humanoid frustum membership

Behind the scenes:
- The capacity gate's data path collapses in bash too
- Make the routine's own printed recipes runnable

## v0.0.28-P3846

- A modal host is identified by what opened it, not by its node name
- Suppress overlays, freeze sim, and fix overhead framing in the 3D capture lane
- Render lane + geometry sidecars for the 3D Explore layer
- Furniture is sorted against furniture, not only against the hero
- The quiet check never asks a chat that is archived on claude.ai
- Quiet check reads a STATUS answer before the busy/quiet filters, and asks in one short line
- Quiet check at 5 quiet / 5 cadence, and a chat waiting on a background task is not quiet
- The quiet check - ask every quiet chat Nathan's three questions instead of classifying its last message
- Wire the three orphan self-tests into box-self-check
- A routine's heartbeat must grade its own receipt, name its stand-down, and be readable by its successor (#5630, #5642, #5594)

Behind the scenes:
- Delete the dead compare modal and re-point its tests at the live surface
- The Steward spec has no scratch-file clause: its banked remedy writes and reads two different files, and served this pass a 5-hour-stale board
- A second, un-versioned copy of patrol 6's clock classifier lives in the deploy dir - the duplication #5352 exists to prevent, and the parity check runs one direction only
- Correction - the Stop hook has been executing since 09-06 14:43; the 09-05 'dead' verdict was the hook-path corruption

## v0.0.28-P3832

- "it'll ride the next one" is a promise, and the sweep fires the next build itself
- Collision is answered by the physics space, not a second copy of the geometry

## v0.0.28-P3830

- A top-layer badge stops drawing when it leaves the list, not when its tile does *(fix attempt - still being verified)*

Behind the scenes:
- A screenshot taken in _process is blank, and content_scale_size does not stay where you put it

## v0.0.28-P3827

- The level-up confirmation draws on top, and a levelled weapon says what it gained (#5656 #5657)
- The week-away meta batch - soak evidence, scope-gate add, vN replacements, grader negation, filing budget, idle-with-work sweep
- Startup_failure runs are a broken-workflow-file signal, not a timeout kill
- Chart freshness is read from the publish target, never a staging leftover
- Classify resolved salvage refs so the -box-partial- pile can stop growing
- The box lane's terminal strings are a closed set the driver is total over, an existing-ref update is a delivery, and a bolded bundle member still closes (#5546 #5551 #5629)

Behind the scenes:
- Two shipped capabilities have no roadmap line: the box rebuild runbook (28 days) and the green-PR sweep

## v0.0.28-P3819

- Freeze the hero's bob/sway phase when blocked, not just standing
- Cottage_chair as a real parametric GLB model
- The full-sweep panel identifies the nightly by workflow, not run title
- The release gate now requires evidence the suite actually ran
- Bound the nightly bundle, and end the silence on a repeat turn-cap bust
- Release_notes.py no longer prints untyped issue-headline commits as player features
- Post-brief.py never emits an over-cap chunk, and a mid-sequence 400 aborts cleanly instead of tracebacking
- The cron-slot delivery backstop - restore CronDelivery, and make one due slot produce exactly one run (#5518 #5552 #5553 #5554 #5555 #5564)
- Route the box lane's own pre-push gate through the sanctioned wrapper, and correct the rationale that kept the rule needing restating
- The delivery driver's five silent-path defects - it waits for THIS branch's verdict, keeps its once-ever promise, escalates where someone reads, stops retrying a deliberate abort, and holds the close on executable infra (#5524 #5525 #5526 #5530 #5531) *(fix attempt - still being verified)*
- The overnight audits' four gate/sweep defects (#5517 #5529 #5533 #5534)
- One owner applies the three-day flags, needs-nathan can clear, and the >7d arm actually reaches Nathan
- Rotated chats keep their name plus vN and open with a continuity brief; the promise guard reports the promise nearest the end
- The three silent disk reapers stamp a heartbeat, so a dead one stops looking quiet
- Green-PR sweep - a green, idle Claude-session PR is merged by cron, wherever its chat lives

Behind the scenes:
- Record the shipped agent-guardrail workstream (v46)
- Steward patrol 1 has no supersession test: 2 of its 6 'undelivered' branches were fully delivered by another PR (one within 24 minutes), restated as a decline for 25 passes
- Correct stale modularity-gate pattern count (v45)
- Codex usage/capacity collector found broken again this week - possible recurrence of #5067
- Box lane can post a concurrent job's verdict comment verbatim (/tmp collision) - diagnosed 08-28, recurred 09-06 and reached main

## v0.0.28-P3796

- The comparison says what it is comparing, and shows both ends
- Place decor from its real centre, not its cell corner
- Capture sidecar reports BOTH coordinate spaces - one number silently scaled every prop measurement by 1.71x
- Rotation seed capture reads stdout only and verifies the seed file exists
- Drop two mis-classifying native-coverage tells - the navigation blind spot was not real
- A real collision world, built from the map and proven against it
- Ui-layout tell counts Control properties only; BASELINE-REBASE path for detector redefinitions
- Scope-gate matches git commit at command position only
- Native-first RATCHET - hand-rolled subsystem counts may only fall
- Scope-before-commit keystroke gate (rule-audit #5428 item 1)
- Native-first keystroke gate - prior-art-gate.ps1 with ACQUIRE + NATIVE scopes
- Pin badge-pulse re-apply invariant by tween identity, not a raced scale snapshot
- Detect runner-workspace ownership mismatches (item 2 of #5028)

Behind the scenes:
- Stop-guard self-check line is informational (Stop event dead by verdict); evals spec notes hooks do not run in -p

## v0.0.28-P3782

- Promise sweep skips routine and sandbox transcripts
- Rescue-chat resolves same-dir transcripts by bridge-session id

Behind the scenes:
- Escape lane triggers in more routine specs, fix steward-clock empty-timeline, log macOS import count

## v0.0.28-P3779

- Furniture stands at a real position, and the painted pieces stand where their art is
- The promise sweep nudges DELEGATED ASKS - a permission question is not a decision
- Acquire-first keystroke gate + plan mode narrowly un-banned
- Agent-evals v0 - test the agent the way we test the game

## v0.0.28-P3775

- The comparison is inline deltas in one modal
- Promise sweep - the hook-free Stop-guard replacement
- The card widens with the surface, and Escape backs out of anything hosted
- Branch cleanup proves tip-on-main, never fires on a daily snapshot push
- Steward-clock.ps1 -Issues now binds under -File
- The hitbox is the floor the thing stands on

Behind the scenes:
- Patrol 6 calls steward-clock.ps1; escape-render lane mentions in comments; codex/* verdict-comment exemption; nightly-suite release-gate truth (#5352, #5386, #5420, #5441)

## v0.0.28-P3768

- The floor is actually square, and the near walls are parapets you see over

## v0.0.28-P3767

- The room is square because the painting is

## v0.0.28-P3766

- The card fits the screen, and the dim leaves the UI lit

## v0.0.28-P3765

- The compare is visible, complete and consistently labelled

## v0.0.28-P3764

- The compare uses the shared modal, and the badge escapes its clip
- Weekly worktree reap with -Apply (janitorial autonomy, Nathan 09-04)
- A new game starts clean because the wipe enumerates its own state instead of listing it
- Four routines that read GitHub state wrong, and the state each one actually needs to read

Behind the scenes:
- Model releases trigger a same-week routing review (Nathan 09-04)
- Batch-fire codex bundle (#5434 + #5386 partial)
- Batch-fire codex bundle (#5321 + siblings)

## v0.0.28-P3756

- The badge pulse survives its host repainting it every frame
- A modal never outlives the surface that opened it

Behind the scenes:
- Fail fast without a non-empty Flux justification

## v0.0.28-P3753

- One floor box drives collision, anchor and overlay; the pedestal rule becomes a test

Behind the scenes:
- Actions-budget.json JSON twin + chart-data-feeds coverage
- Weekly-meta-review carries the 09-02/03 rethink panel; guard learns two live promise shapes

## v0.0.28-P3749

- One modal layer for every modal; HP bar above his head; the alert flashes again

Behind the scenes:
- Record Nathan's 09-03 milestone sequencing (GUI to art to story to stat wiring)

## v0.0.28-P3747

- Kill the rim glow and the pedestal illusion

## v0.0.28-P3746

- Minimal keeps its original icon; slow the swing so each pose reads

Behind the scenes:
- The box is ~28 days from a full C: and 167.84 GB of reclaimable worktrees sits behind a hand-run command that is scheduled nowhere
- Close the RENDER-EVIDENCE contract's three holes
- Make the weekly->monthly meta-review handoff mechanical
- Gdignore the tiny-swords vision-subagent draft dir so its QC crops stop shipping
- Post acquire-first motion pipeline, refresh hero animation status

## v0.0.28-P3739

- Standing pose + attack scale (two more defects found by the new tests)

Behind the scenes:
- Box rebuild-contract audit: 6 of its 12 drift findings are checker artifacts, hiding 6 real ones (CronDelivery has no contract row)

## v0.0.28-P3737

- Furniture sized in the projection it was drawn in, a room in three zones

## v0.0.28-P3736

- The real cause of 'walks backwards' - swapped yaw mapping in the capture rig

## v0.0.28-P3735

- Storybook hero rebuilt on downloaded motion - adult, flat 2D, no chibi
- Scrolling rows keep a gutter from the scrollbar

Behind the scenes:
- ACQUIRE FIRST - download the asset, skin it with Codex (Nathan 09-02)

## v0.0.28-P3732

- The painted room covers the floor, and every piece stands on it
- Stop-guard installer must not BOM the settings file it edits
- Nightly production soak lane (churn+scenes vs current main)

## v0.0.28-P3729

- The list gets the panel height; the capture lane proves its checkout

Behind the scenes:
- Self-check watches the stop-guard invocation log
- Visual-surface PRs require render evidence or a stated exemption

## v0.0.28-P3726

- Long trousers + a real walk cycle borrowed from CC0 gait reference
- Non-animating sets now TURN - side-profile companion art
- His 2026-09-02 arrangement is the default, on all three surfaces

Behind the scenes:
- Record the app-icon wiring and the exe-waits-for-the-next-epoch decision
- A read-only errand's FAILED terminal is not a dead run

## v0.0.28-P3721

- The art chip fits the row, and the mobile rail can widen again

Behind the scenes:
- Instrument stop-promise-guard + close the 09-02 scan's regex gaps

## v0.0.28-P3719

- Storybook walk faced against travel; redraw as an adult, upright
- Auth classifier recognizes the live expiry wording (#5348); read-only guard reads comment-fired errands (#5168 false-FAILED)

## v0.0.28-P3717

- One metre of floor is one metre of height
- Storybook swing frames (windup + strike) in the 2D sprite style

## v0.0.28-P3715

- Storybook gets its own 2D sprite hero; frame counts become per-set

## v0.0.28-P3714

- The modularity scan can fail again - 'return 0 ADVISORY' never implemented the 2026-06-21 blocking decision
- The bar fits the screen, and the gear obeys one-at-a-time

Behind the scenes:
- Post the character-animation roadmap line (direction-2 code-to-roadmap gap, #5349)
- Silhouette-style-guide slot taxonomy matches live StatConfig (17 slots, all unlocked)
- The capacity model and building roster catch up to the code
- Put Codex-first into the art pipeline docs
- Retire citations of deleted/renamed machinery (Monthly Docs Aug action 3)
- Shadow rule scoped to the 2D renderer (monthly-docs finding 17)

## v0.0.28-P3706

- Back to the last state not reported as disastrous
- The dump proves renewal RAN, not just that nothing broke
- The hero walk-frame contract points at the set that actually ships the frames
- Dismiss every popup class an interior raises, and drain the narrative queue

## v0.0.28-P3702

- The Windows build's import pass imports the project, and a crash-shaped export gets one retry

## v0.0.28-P3701

- The macOS bundle, the launcher, and the identity Windows shows
- You are not asked to leave the moment you walk in
- The layout dump describes the frame that was captured
- The gear capture presses the real button and proves the menu opened
- A broken capture driver says so instead of rendering nothing

## v0.0.28-P3696

- The room is the size the design says - all three ratios at target
- Size per FORMAT, and centre the collapsed rail glyph

## v0.0.28-P3694

- The game wears its own castle icon, not the Godot logo
- One unit indoors — delete the floor stretch, let the fit-zoom do its job

Behind the scenes:
- Scope retiring the tiny-swords name + last pack-era art
- Arm the low-disk alarm - the sampler recorded diskFreeGB for weeks and nothing ever compared it to anything
- Hero-walk truth in CLAUDE.md + character-animation roadmap line

## v0.0.28-P3689

- Animation moves to Painterly; two back-view frames were front views
- The FLAKE signature was the crash signature - a crash-shaped red must prove it is non-deterministic

Behind the scenes:
- The Codex token panel reads the account ledger; --ephemeral stays
- Unify screen scaling: one resolution/aspect-independent path (desktop === phone)

## v0.0.28-P3685

- A readable dropdown, and the box can drive the game to a UI state

## v0.0.28-P3683

- The off-screen guarantee moves to the shared seam, so the wallet gets it too
- Side walk faced against travel; feat: two-frame sword swing

## v0.0.28-P3681

- The dropdown shows its menu; the test now reads the contents

## v0.0.28-P3680

- A fit pass must not measure its own output; settings drops from the gear
- Put the real character in the room render

## v0.0.28-P3678

- Four-facing walk + distance-driven stride (fixes moonwalk)

## v0.0.28-P3677

- Frame-animated walk from mocap-derived skinned frames (Storybook)
- Walls are 2.74 m, derived from the painting - not 1.35 tiles
- CronDelivery - the box delivers the repo's own workflow schedule

Behind the scenes:
- Patrol-7 cap widened per-slot + arm-2 retirement scheduled

## v0.0.28-P3672

- An open expansion can never push its close button off-screen
- Agent-authored report comments carry the routine stamp (#5259 arm-1 gap, step 1 of its recommendation)
- The chips claim the width the fit pass measured for them
- Collapsed rail buttons carry a tooltip

Behind the scenes:
- Add arm 1b, the author arm, to the automation-author test
- Add the GitHub Steward and four other unlisted box routines to Infrastructure
- Order the dispatch-opener check between arm 1 and arm 2, and write the too-BROAD failure direction into the spec
- PRIOR ART FIRST mechanical backstops - analyzer prior-art check + weekly reinvention scan

## v0.0.28-P3664

- The cheat chip's pink is its rim and icon, not the whole panel
- Scoped per-session vision opt-in in the image-read block (model-style saga)
- Restore the working cottage - the room resize, wall-height and painting changes shipped broken
- The digest self-test counted a substring; now it anchors on the heartbeat write and RUNS it
- Steward arm 2 marker matches the timestamped opener

Behind the scenes:
- PRIOR ART FIRST key rule - never rebuild what the world has solved (Nathan 2026-08-29)

## v0.0.28-P3658

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- The cheat menu IS the chip widget, not a third construction
- Regenerate Storyline Art Bible + coverage (nightly)

## v0.0.28-P3656

- The gear behaves like the chips; the movement guard names its blocker
- Registry-restore the root Window's surface — one leaked landscape canvas was reddening two unrelated suites
- 'the next build will have it' is a promise too (the 08-29 4.4h merge-to-build gap)

## v0.0.28-P3653

- Only one inline expansion is open at a time
- Stamp every script-side issue comment; patrol 6's opener list becomes the backstop, not the path *(fix attempt - still being verified)*
- An already-signed-in player gets a device key too
- A real ceiling and door — the room was a crawlspace, not the character a giant
- Stop hook - a turn may not end on a promise of ongoing work (08-29 meta-review)
- A hitbox is the size of the thing you can see, and the room has one scale
- Name the boot orphans, and record that they are not a leak

## v0.0.28-P3646

- Copy game data reports the wallet's real geometry
- Free the cached Coming-Soon panel with its tab

## v0.0.28-P3644

- A wrapping expansion stacks in even columns, not ragged rows

## v0.0.28-P3643

- The gear popover is bounded and scrollable, not exactly-fitting
- The renewal triggers actually fire, and the dead path is gone

## v0.0.28-P3641

- Chrome big enough to hit, and the X centres because it is an icon
- Keep people logged in - device re-login instead of provider refresh
- The soak leaves the keep - Explore/Defend round trips (#5094, #5208)

Behind the scenes:
- One tile is one metre - the world stops being anchored to the hero's height

## v0.0.28-P3637

- A window cannot be placed hanging below the info strip
- A failed renewal is not a backup warning either
- Freshen a stale PR only when a push can change its verdict

## v0.0.28-P3634

- The fake button joins the family; one glyph rule; title bars match
- Furniture is sized from real metres, not eyeballed against the painting
- Honor explicit do-not-merge; roadmap/DECISIONS join the review-required paths
- Gear glyph draws at the shared chip size, at the icon-button seam
- Pair crash beacon build stamp with delta-applied release
- Make the Storyline Art Bible render byte-reproducible
- Widen #4948 mapping to cover HARD-EXIT
- Stamp bookkeeping comments, drop dead AUTHORED-BY test
- CI-gate tooling accuracy bundle (#4969, #5124, #5128)

Behind the scenes:
- Character bar gear popover overflows screen; bar misaligned with info strip; buttons mismatch Area bar shape (device-only)
- VRAM-compress the 3 storybook cottage textures the Aug-13 sweep missed
- Regenerate Storyline Art Bible + coverage (nightly)
- Widen patrol 1 to every delivery lane, define patrol 6's clock positively, close the storyline hand-off
- Recurring cross-suite gdUnit test-pollution / static-state leaks block unrelated PRs

## v0.0.28-P3616

- Patrol 7 - cron repair (Nathan-authorized, #5169)
- A yielded daily still prunes the channel - only a FAILED run skips
- Read the CI-throughput day-store as utf-8-sig, not utf-8
- The auth dead-man's issue lookup ran zero times
- Unarchive a card thread before writing into it

Behind the scenes:
- ONE bar-button widget instead of six tuned to match
- The box PAT CAN workflow-dispatch - the read-only-Actions line was stale and blocked cron repair
- Week of 2026-08-27 — 1 idea staged
- Arm a routine whose installer merged but whose task was never registered
- Conditional Closes, ATTEMPT ledger line, needs-nathan carve-out in the delivery driver

## v0.0.28-P3605

- Customize keeps a saved placement; zoom always skinny; one corner rule for every bar button

## v0.0.28-P3604

- IOS app-icon set + generator, wired into the export preset

## v0.0.28-P3603

- The soak drives real navigation, not just idling

## v0.0.28-P3602

- A saved window placement survives reload; zoom rail always skinny
- The character bar's buttons wear the Area bar's corners
- A failing backup says so instead of failing silently

Behind the scenes:
- Brief 08-26 follow-ups - roadmap session-renewal truth; steward idle clock ignores label-only updates
- Builder's cottage on the DEFAULT art set: 26 invisible walls and 6 walk-through furniture sprites ΓÇö #5116's collision map is traced from a painting only Storybook has
- Shrinking the health bar leaves a gap above the info bar (P1013) ΓÇö live on main, and the tested fix is stranded on a never-PR'd branch

## v0.0.28-P3596

- Mason cottage is a real navigable 2:1 space - collision, depth occlusion, door at the painted door
- Capture-state died to SingleInstanceGuard too - real-game captures never ran
- The capture harness never rendered - SingleInstanceGuard was killing it

## v0.0.28-P3593

- The keystone gave desktop the phone-LANDSCAPE canvas
- 1-day channel window for EVERY digest grain - the same-day-handling contract
- The soak judges private bytes, not working set
- Delivery driver stops crying wolf, freshener stops chasing declines (#5086, #5091)

## v0.0.28-P3589

- The room IS the mockup + invisible collision (real walkable space)
- A failed renewal is not a dead session

## v0.0.28-P3587

- His desktop arrangement is the third anchor; the zoom buttons stop stretching
- A wrapper-hosted window can no longer bury the OPTIONS drawer
- The keystone — desktop uses the phone's scaling path (#4851), rebased and green
- Pin Mergify's checks_timeout to 45 minutes
- Monthlies clear after 3 days too (Nathan: 'i dont think it should sit for that long. a few days')

## v0.0.28-P3582

- The soak verdict cannot say PASS about nothing
- A docked SKINNY window reloads where it was docked, not 64px left
- A soak harness that measures "left running for a long time"
- Restore the real user:// directory and rescue what was stranded there
- Sessions renew themselves instead of expiring

## v0.0.28-P3577

- Reload snaps a wedged saved position to walkable ground
- A lost identity ends the run and says why

## v0.0.28-P3575

- Name the HUD window whose hitbox vetoes cottage movement
- A live session stays in the silo it was opened from
- Weekly-grain digests clear after 3 days, not 7
- 'full sweeps not green' counts MAIN nightlies only - branch-side dispatch runs are developer-loop, not the release gate
- Make the hearth depth-coupling guard content-independent
- Stop no-op known-bugs-sync runs from cancelling real renders *(fix attempt - still being verified)*
- Detect a stale merge base once, use it twice; stop freshening PRs already in the merge queue
- Routine-fleet reliability bundle (#5013, #5063, #5064)
- Codex-usage token feed - name the ephemeral mechanism, fix the double count, alarm on the dark half

Behind the scenes:
- Account A OAuth token only refreshes on an A-engine API call, leaving archive-sync token-dark for hours
- Record whole-room-painting interior path (#5049), point CLAUDE.md at it

## v0.0.28-P3564

- Self-heal the cottage 'frozen with a clean screen' freeze

## v0.0.28-P3563

- Fit painted interiors to the screen so the cottage fills the view, not a tiny box

Behind the scenes:
- Fill in Doran, Hollis and Sela from their art; fix stale wiring claims

## v0.0.28-P3560

- The Builder's cottage renders the approved painting AS the room

## v0.0.28-P3559

- Promote 9 re-authored cutscene plates at native 1.75 aspect

Behind the scenes:
- Fire interim build for the re-authored cutscene plates

## v0.0.28-P3557

- Storybook cottage skin — painterly walls, floor, furniture + mason props
- The Builder's cottage is a rectangular long hall, not a square
- Render-cutscenes announces every outcome, not just success
- Conversion sweep restores a converted chat's title (rename-chat.py, PUT /v1/code/sessions)
- Pinned chats keep their names across conversions - auto-pin NAME-SYNC keeps each revival launcher's -n equal to the chat's current title
- Batch-fire consumes the board BY STATE - cap 2/night, nightly cadence made authoritative
- A read-only errand that posted its report is COMPLETE, not 'FAILED - no branch pushed'
- Supervisor auth-hold (#5001 class) + DedupJanitor armed with its sources in the repo
- Step4 deploys CONFIG too, and grades itself against main
- The release gate reads ancestry, not recency

Behind the scenes:
- Mason + woodsman cutscene re-author review boards
- CI-throughput store lost 163 runs (08-16..18) and is publishing insights computed on 4 of 30 days ΓÇö backfill, widen the collect window, alarm on the gap
- Weekly Meta-Review moves Sunday 03:00 to Thursday 05:30; gets its own 7-day brief retention

## v0.0.28-P3544

- Absorb a transient Android export crash instead of losing the release
- A broken login beats every capacity number
- Prior day clears again - split merged routine bursts; verify-after-prune; failed prune files an issue
- Merged == live, no matter who merges
- Enforce ArtCache.tex() over bare load() of art paths (ARTCACHE gate)
- Warn before switching to an unfinished art mode
- Watch the NPC dossier's CONTENT, not just its builder script
- Published docs track ALL current artwork - tileset audit regenerates + publishes, silent generator failures alarm, currency in the weekly check

Behind the scenes:
- Mechanize the ATTEMPT ledger in check-bugfix-shape
- Batch-fire deterministic empty-queue pre-check
- Route cutscene modal textures through ArtCache (overnight queue B)
- Overnight-queue status - D/E done (#4984), I measured-closed (macOS 2min), B/C/G dispatched (#4987/#4988/#4989)
- Overnight queue D+E - readable *.import diffs; compression check documents the SHIPPED policy
- Published-currency audit - EVERY published surface verified live, weekly (Nathan 2026-08-22)

## v0.0.28-P3529

- His landscape arrangement becomes the THIRD default anchor
- Bram's build follows the art; /box gains a Codex render lane

## v0.0.28-P3527

- His 2026-08-22 arrangement becomes the phone-portrait default, skinny included
- The nine craftsman cutscene beats get a recorded recipe, and a re-author can carry its own scene forward
- The OPTIONS drawer clears the bottom info strip
- Modal still frame is 1.75, matching the art — not 16:9
- Save commits the window you placed, not the re-abut's version of it
- The daily brief reads the real release P again - monotonic, no ceiling
- A self-check that throws can no longer emit nothing
- One digest worktree per routine label - a starting routine no longer deletes a running one's files

Behind the scenes:
- Map web CRASH on management screen to #4948
- Tileset regen + Android download size lines (v36)

## v0.0.28-P3516

- The re-abut never steals the window you just placed
- Modal still frame is 1.75, matching the art — not 16:9

Behind the scenes:
- Cutscene 4:3->16:9 crop evidence for the 24 mis-ratio stills

## v0.0.28-P3513

- The OPTIONS drawer shrinks to the surface it is on - landscape no longer hides its bottom rows

## v0.0.28-P3512

- MacOS leg stops fetching Docs/ — blobless sparse checkout

## v0.0.28-P3511

- The OPTIONS chrome is a snap target, so a window can be lined up against it

## v0.0.28-P3510

- Compress the engine .so via the export preset — 162.8 → 118.2 MB

## v0.0.28-P3509

- Publish leg can't finish — blobless clone, 30→60 min budget
- The OPTIONS drawer sits BESIDE the handle in landscape instead of starving below it
- The layout capture reports the OPTIONS reserve and per-window PIXEL rects
- The OPTIONS reserve pushes out the SHORT way, so a window can rest flush against it

Behind the scenes:
- Walls & floors — measured scope for the interior envelope
- Self-check detects stale RDP console markers (post-/clear rotation + 4-day backstop)
- Art-gap loop reworked and armed — Codex queue, never Flux
- Cutscene texture format: measure VRAM vs fidelity for ETC2 / ASTC / lossy WebP before adopting policy B
- Close the specified-but-never-armed class — widen check 19b, fix premortem code misread, unblock ruleset-snapshot, deploy *.sh
- Cut the Android download ~80 MB — drafts out, engine .so compressed, cutscene size cap
- Cutscene texture policy comparison sheets (issue #4906)
- Weekly asset-bloat check — policy-aware (cutscene policy B), draft-leak + WAV classes, wired into the weekly digest

## v0.0.28-P3497

- Skinny windows get a skinny floor - MIN_W no longer reserves width for chrome that isn't there

## v0.0.28-P3496

- Room composition — chairs, barrel redistribution, painterly hearth 1.8m

## v0.0.28-P3495

- Resize grips follow a MOVE, and the zoom window docks clear of the OPTIONS handle

## v0.0.28-P3494

- The zoom +/- rail becomes a movable window; the OPTIONS reserve is now exactly its gold edge

Behind the scenes:
- Record the monotonic build-number decision

## v0.0.28-P3492

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- Monotonic build number (total commit height), never resets per version

## v0.0.28-P1071

- Game-feel prop scale, storybook chimney hearth, painterly slope trued

## v0.0.28-P1070

- Skinny mode must not overwrite a saved window height with the content floor

Behind the scenes:
- Pick the release by comparing the numbers, version then integer P

## v0.0.28-P1068

- Discord post reads the repaired release body (single source) + authenticated PREV fetch
- Source the release tip authoritatively; make the drift guard see it

Behind the scenes:
- Final lockdown — frozen-constant rule in CLAUDE.md; regen-program status + next section

## v0.0.28-P1065

- Balance the size<->font ledger so a saved bar reloads at the height it was saved

## v0.0.28-P1064

- Hearth depth scales with the prop — back on the wall

Behind the scenes:
- Deployed-versions coverage grows with the platforms - a new surface ships WITH its stamp
- Lock the world-art & rendering rules into CLAUDE.md

## v0.0.28-P1061

- Raw pixel + scale fields in the HUD layout capture (P1056 diag)

Behind the scenes:
- Fire build for HUD-capture diagnostic

## v0.0.28-P1059

- Scheme-aware release pick — filter legacy tags, then publish time
- WORLD SCALE — real sizes, one conversion; ghost space purged
- Repair notes in ALL locations - historical #releases Discord posts + builds CHANGELOG.md

## v0.0.28-P1056

- Pin content_scale_factor=1.0 — kills the 2x DPI height doubling
- Exterminate the raw-P/lexicographic comparison class - banner survives version close, crash facts version-aware, backfill publish-time sorted

Behind the scenes:
- Fire build for DPI factor pin

## v0.0.28-P1053

- Deployed-versions sync fact + standing daily line (web P993 vs Android P1045 class)
- Pick newest release by publish time, not /releases list order
- Incremental notes for real - scheme-aware PREV pick + self-healing repair of every drifted release body

Behind the scenes:
- Fire build to catch the web game up post-#4882

## v0.0.28-P1049

- Re-apply font after the reflow reparents — kills the residual bar growth on restart
- Re-apply font after reflow reparent — residual bar-tall-on-restart
- Annotation follows the PR ref one hop into its body (P1043 gap - subjects cite PRs, not bug issues)

Behind the scenes:
- Fire build for font-after-reflow bar fix

## v0.0.28-P1045

- Minimal furniture sized realistically; flat hearth ON the seam

Behind the scenes:
- BOX-FIRST VERIFICATION - the ask-Nathan gate + the box-verification skill (capability menu)

## v0.0.28-P1043

- #releases stops declaring unverified fixes fixed - open-issue fix bullets get 'still being verified'

## v0.0.28-P1042

- Retry R2 mirror uploads instead of abandoning the tail
- Thursday correctness - scoped yield markers, weekly lives its week, weekly gets merged-is-not-fixed language

## v0.0.28-P1040

- Persist resize after layout settles — kills the bar growing tall on restart

Behind the scenes:
- Fire build for bar-bug persist-after-settle fix

## v0.0.28-P1038

- Bug-hunt bundle — strict pools, flat 2D barrels, ghost-cap fade

## v0.0.28-P1037

- No light source, no shadows — floor-prop decals removed

## v0.0.28-P1036

- Minimal furniture is TRUE 2D — the locked rule, written down
- VERIFIED-ON declaration required in VERIFY-SUMMARY on game-code PRs (retry-week lesson)

## v0.0.28-P1033

- Minimal set goes flat-iso — sheared hearths, rhombus-top furniture
- Self-check 19b - flag specified-but-never-armed routines (installer with no registered task)

## v0.0.28-P1031

- Minimal-set isometric wall hearths (5 + mirrors)

Behind the scenes:
- Record the MISSING ART / art-availability-per-state decision

## v0.0.28-P1029

- Front-edge anchor forward on the tile; shadow = footprint touching every leg

Behind the scenes:
- Merged-is-not-fixed language rule + retry-loop counter in the Daily Brief (retry-week lesson)

## v0.0.28-P1027

- Floor-prop shadows are crisp sprite-child decals; framebuffer-space measurement

## v0.0.28-P1026

- Crossing a door is a save boundary (#4796 follow-up)

Behind the scenes:
- Fire a build for the door save-boundary fix
- BUG RETRY PROTOCOL — issue-thread attempt ledger, reframe at attempt 3, instrument-first, verified-on-surface (Nathan 2026-08-19)

## v0.0.28-P1023

- Content dims scale so the area bar can actually get small (P1017 root)

Behind the scenes:
- Fire build for P1017 content-scale root fix

## v0.0.28-P1021

- A save banks WHERE the player is, not the last tile crossing (#4796 follow-up)

Behind the scenes:
- Fire a build for the save-location fix
- Remove the #4744 on-screen diagnostic machinery — leave no debt
- Web text-entry is native HTML, not a Godot LineEdit over the canvas (#4744 lesson)

## v0.0.28-P1017

- Native HTML email form on web — the framework fix for the iOS keyboard saga

## v0.0.28-P1016

- Interior-prop conventions — baked shadows, directional hearths, one placement path
- Archive-sync heals chat conversions exactly and never kills a live successor

## v0.0.28-P1013

- Resize-clamp behind OPTIONS, reload keeps saved font, drawer in landscape, gold chrome

Behind the scenes:
- Fire build for P1006 four-item HUD fixes

## v0.0.28-P1011

- Full-state save/reload round-trip for Explore + Defend

Behind the scenes:
- Fire a build for the full-state save/reload round-trip

## v0.0.28-P1009

- Release the LineEdit's engine focus so Godot stops blurring the overlay per keystroke
- Top-bar currencies are icon + amount only, flow left-to-right
- Repair the full-sweep SIGNAL - the sweep itself was never broken

## v0.0.28-P1006

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- Fire rebuild + per-job timeouts so a wedged leg can't hold releases hostage

## v0.0.28-P1005

- Route cottage furniture through real Codex GLB models
- Route world-decor NPCs onto the 3D humanoid rig
- Switch Fortress is save-and-resume, not a jump to the keep (#4787 follow-up)
- Script the planned pinned-chat transcript rotation
- Stop re-styling the focused input every frame — the iOS blur-to-body root cause
- Visible boxes on fixed chrome + reserve that actually blocks (incl landscape)

Behind the scenes:
- Fire a build for the Codex-authored cottage models
- Re-fire build for #4800 (prior macOS leg wedged)
- Fire a build for 3D world-NPC models
- Fire a build for the Switch Fortress save-and-resume fix
- Capture-world.ps1 — render any game map on the box + screenshot it
- Fire build for chrome-boxes + reserve

## v0.0.28-P993

- An Explore save reloads as a perfect continuation, not a launderable reset

Behind the scenes:
- Fire an interim build for the Explore continuation fix

## v0.0.28-P991

- Minimal hearth is a fireplace (not a plaque) + nudge wall-clipping furniture
- Cottage floors are flat, and Codex becomes the default for all visual work

Behind the scenes:
- Fire a build for the verified cottage fix
- Fire a build for the flat interior floor

## v0.0.28-P987

- A live texture swap must RE-DERIVE what was computed from the old texture
- Post-brief carries ALL attachments on ONE final message (08-17 fragmentation)

## v0.0.28-P985

- Name the iOS focus-thief on-screen + cap the reclaim loop
- A cap_raise research buys max_modification, not cap
- A save banked mid-Explore/Defend loads back INTO that mode, not the keep

Behind the scenes:
- Fire an interim build for the resume-into-saved-mode fix

## v0.0.28-P981

- Reserve the top-right chrome, freeze world interaction in edit, hide drawer in landscape
- Furniture float + hearth (upright on wall seam) + minimal iso table

Behind the scenes:
- Fire a build for HUD edit-mode polish
- Fire a build for the cottage float/hearth/table fix

## v0.0.28-P977

- 3D props get real-world scale and real geometry, not a spinning cutout

Behind the scenes:
- Fire a build for real-world 3D prop scale + real geometry

## v0.0.28-P975

- The MISSING ART card is never mirrored - it carries baked-in lettering

## v0.0.28-P974

- 3D cottage furniture gets 2D's variant scatter + floor shadow

Behind the scenes:
- Fire a build for 3D furniture variety + floor shadows

## v0.0.28-P972

- The 3D hero stands one tile tall, and the settings gear locks the art style too

Behind the scenes:
- Fire a build for the 3D scale rebase + gear art-lock

## v0.0.28-P970

- The chopped log shows the MISSING ART card - retire its private drawing lane
- ONE missing-art card, and the world layer finally shows it

Behind the scenes:
- Fresh-eyes fixes part 2 (#4746) - notional labels, liveness badges, sheet callouts

## v0.0.28-P967

- Shear the hearth onto its wall for every set (not just flat)
- Trim transparent padding under interior furniture so it sits on the floor

Behind the scenes:
- Fire a build for furniture float + hearth shear

## v0.0.28-P964

- Info-strip reserve = the strip's REAL height, so the health bar drags flush
- 3D interiors get real walls, honest scale, storybook-locked art
- Device-language Google sign-in + on-screen diagnostic for the iOS keyboard jump

Behind the scenes:
- Fire a build for the info-strip reserve fix
- Fire a build for the 3D interior/scale/art-lock pass
- Fire a build for the keyboard-jump diagnostic + device-language sign-in (#4744 #4757)
- Fresh-eyes fixes part 1 - misleads, render bugs, cuts, stale-copy guard

## v0.0.28-P957

- The cut log was drawn BEHIND the treeline - anchor the halves on the crossing

## v0.0.28-P956

- Furniture sits on the floor — anchor the art's CONTENT base, not the image

Behind the scenes:
- Fire a build for the furniture float fix

## v0.0.28-P954

- Commit window size+position on SAVE, re-abut on drag (the real layout fix)
- The 3D warning locks out the chrome too, so choosing is the only way on

Behind the scenes:
- Fire a build for the HUD layout real fix
- Fire a build for the 3D warning hard-lock

## v0.0.28-P950

- Stop the game reflowing under the iOS keyboard
- IOS export preset + inert TestFlight workflow scaffold

Behind the scenes:
- Fire a build for the iOS-keyboard reflow fix + sign-in overlay (#4741 #4747)

## v0.0.28-P947

- Painterly cottage furniture — Codex iso set, many variants for scatter variety

Behind the scenes:
- Fire a build for painterly cottage furniture

## v0.0.28-P945

- Hide Google's DOM button while the email dialog is open
- 3D warns before you enter, and hands you the way back out
- The chopped log has to LOOK chopped - gate the log art PER STATE

Behind the scenes:
- Fire a build for the 3D in-development warning

## v0.0.28-P941

- Seat a window floating above the health bar flush to it (bottom gap)
- Daily board audit - fix-it-or-close-it runs automatically every day (Nathan 08-16)
- Real field migration ladder + retire the persisted stat 'cap' (#4619, #4665)
- Tear the dialog nodes down, not just the flag, when clearing Explore's input guards
- Size the Options edge handle on BOTH axes from the word it holds
- Propagate the gate's own exit code + one change-set derivation for local and CI (#4625, #4626)
- Soft-delete fortresses with a 30-day recovery window

Behind the scenes:
- Fire a build for downward-abut bottom-gap fix
- Lock in accounts sign-in workstream — roadmap, DECISIONS, accounts architecture (08-16)
- Desktop sign-in: a second sign-in attempt in the same session fails with 'localhost refused to connect'
- In-game update notification line (moved from issue #4528, board hygiene)

## v0.0.28-P929

- Account switch shows "signing you in", not the outgoing account's saves + local-saves no-backup warning
- Persist a window's effective size so it doesn't grow taller on load

Behind the scenes:
- Fire build for account-switch fix + local warning
- Fire a build for window size-persist fix

## v0.0.28-P925

- Flat-set iso furniture rule - shear wall pieces, shadow-plant the rest

Behind the scenes:
- Fire a build for the flat-set iso furniture rule

## v0.0.28-P923

- Mirror builds to R2, launcher downloads mirror-first

## v0.0.28-P922

- Email code sign-in goes straight to roster, no chooser flash

Behind the scenes:
- Fire build for email code sign-in flash fix
- Rebuild runbook - one contract, a bootstrap, and an audit that proves it

## v0.0.28-P919

- Fixed section keeps a 10-day window, not a forever graveyard (Nathan 08-16)
- Re-abut stacked windows to the real edge (close the layout gaps)

Behind the scenes:
- Fire a build for window re-abut fix

## v0.0.28-P916

- Restore window chrome (slim option A did not close the gaps)
- Weekly supersession sweep - solved-elsewhere issues/PRs get closed, not lingered (Nathan 08-16)
- Email-code rate-limit TTL 30->60 (Cloudflare KV minimum)

Behind the scenes:
- Email sign-in: CODE flow in-game + chooser rework (ship-ready)

## v0.0.28-P912

- Declare EMAIL_CODES KV binding in wrangler.toml
- Email sign-in CODE backend — request + verify Cloudflare functions (WIP)
- Slim window chrome so stacked windows abut cleanly (option A)

Behind the scenes:
- Fire a build for slim window chrome (option A)

## v0.0.28-P908

- Hearth sits on the floor; painterly hearth matches the iso chimney
- Daily brief goes FULL AUTO - decisions to Nathan, work to the box (Nathan 08-15)

Behind the scenes:
- Fire a build for iso-interior QA batch 4

## v0.0.28-P905

- QA batch — nav reserve, corner-snap, inline wallet, grabbable aim rail, Area icons

Behind the scenes:
- Fire a build for the topbar/HUD QA batch

## v0.0.28-P903

- Email sign-in working end-to-end on desktop

## v0.0.28-P902

- Force landscape in 3D only, restore free rotation in 2D (#4607 follow-up)

Behind the scenes:
- Build for force-landscape-in-3D

## v0.0.28-P900

- Aggressive edit contrast, bottom clamp above info bar, 2D-only aim rail
- Rebase font default so 140% is the new 100%
- RESTORE the wallet - modal on narrow, compact inline font (no phone boost)

Behind the scenes:
- Fire a build for wallet restore + font 140-is-100 + HUD edit fixes

## v0.0.28-P896

- Run early-exit is a 3rd Area button in both modes — Explore "Retreat", Defend "Abandon"

Behind the scenes:
- Fire a build for the run early-exit rework
- Chat-harvest archive candidates = FYI note, never a needs-nathan issue (Nathan 08-15)
- Code debt: #E8C45A color dup + armament/guard cheat twin + hardcoded MAX_LEVEL ΓÇö weekly 08-13 seed 5

## v0.0.28-P892

- The wallet/cheat inline expansion stays HORIZONTAL, never a vertical modal-like stack

Behind the scenes:
- Fire a build for the wallet/cheat horizontal-expansion fix

## v0.0.28-P890

- Top-bar GROW-DOWN - cheat/wallet expand the bar, not a modal/popover
- Fog stores a bounded per-map bitmask, not one entry per tile

Behind the scenes:
- Fire a build for the top-bar grow-down + glyph centering (#4661 #4666)

## v0.0.28-P887

- S Pen / stylus can move the hero — catch the stylus mouse event in _input
- Centre the art/wallet chip glyphs
- Desktop default layout from Nathan's capture; carry captured font
- Interiors moved ~2.1x too fast — ROOM_SCALE was applied twice (#4607 follow-up)
- Rehook Codex usage collection to the account usage API

Behind the scenes:
- Build for the interior-speed + S Pen movement fixes
- Add dev-debug-copy-game-data to the manifest

## v0.0.28-P880

- Drive movement from raw touch — phone 2D movement was dead (emulated mouse never reached the mover)

Behind the scenes:
- Build for the #4607 raw-touch movement fix

## v0.0.28-P878

- Self-heal a stuck tree pause — phone 2D movement was dead from a boot pause

Behind the scenes:
- Build for the #4607 stuck-tree-pause self-heal

## v0.0.28-P876

- A map swap clears the dialog flag — cottage restore left phone input dead

Behind the scenes:
- Build for the #4607 cottage-restore input fix

## v0.0.28-P874

- One comparable-row rule for every ledger reader; isolate user:// by default
- Round 2 for #4607 — name the input eater (raw touches, blockers, guards)

Behind the scenes:
- Build for the #4607 round-2 movement diagnostic

## v0.0.28-P871

- Capture the LEFT-press outcome for the phone 2D-movement freeze
- Shrink Copy-game-data dump to a deviations-only view
- Session claim expires without a heartbeat (no prompt for a closed device)

Behind the scenes:
- Build for the #4607 movement-press diagnostic
- Document the "Copy game data" on-device debug tool

## v0.0.28-P865

- Close the desktop sign-in window on success (P864 regression)

## v0.0.28-P864

- Shrink desktop sign-in flash + recover when the window is closed
- VRAM-compress 181 of the 183 lossless tileset PNGs
- Condense Copy-game-data dump and add a movement-diagnostic block

Behind the scenes:
- Apply the 08-13 weekly review updates - 3 closed, 2 changed, 5 backdated + DA-13 figure refresh
- Week of 2026-08-13 - 5 ideas, 6 decisions
- Desktop launcher: update fails intermittently ΓÇö GitHub throttles the builds download endpoint (503/empty-reply) and the launcher gives up with no retry

## v0.0.28-P858

- Desktop sign-in window was tall/off-screen — PowerShell $h/$H collision set height to the window handle

## v0.0.28-P857

- Desktop Google sign-in — real chooser in a chromeless app window, no served page
- Json fields must be comma-joined with NO spaces (gh argv-split, #4610)
- Let Google open the sign-in popup, because Google is the one that sizes it

## v0.0.28-P854

- "Copy game data" state export in the Options drawer
- The wallet is ONE unit - icon + currencies in one border
- Hearth upright not askew, translucent walls veil items behind them

Behind the scenes:
- Fire interim build for Copy game data state-export diagnostic
- Fire a build for the wallet one-unit
- Fire a build for iso-interior QA batch 3

## v0.0.28-P848

- Nathan's portrait layout as the phone default; stop losing windows on rotation

Behind the scenes:
- Build for the portrait default + rotation rescue

## v0.0.28-P845

- Rename Resume action + fire a build

## v0.0.28-P844

- The art-style switcher ships in regular builds, not just QA
- A crash-then-reload no longer files as a clean exit
- Return to Game action above Switch Fortress

Behind the scenes:
- Fire a build for the art switcher in production

## v0.0.28-P839

- Options panel always pops on top, and the layout capture is shown on screen

Behind the scenes:
- Build for the Options popup + on-screen layout capture

## v0.0.28-P837

- A blocked Google script no longer looks like a broken button
- Sign-in popup is sized and closes itself; second instance no longer covers the running game
- Options list scrolls, and a Copy layout capture
- Wall-mount hearths, door frame, more wall dressing, fix NPC void + near-wall top
- Pause/run-details use the shared chip corner, not a circle
- Area window Kills/Time read as tight pairs, no wrong wrap
- ExpandingChip — the art chip is ONE bordered box (foundation)

Behind the scenes:
- Fire build for the sign-in popup and single-instance fixes (#4579 #4583)
- Build for the reachable reset row + Copy layout
- Fire a build for iso-interior QA batch 2
- Fire a build for the top-bar pass (#4574 #4575 #4576)
- Fire a build for wall features + hearth/workbench fixes

## v0.0.28-P825

- Scattered wall features + fix painterly hearth & workbench cutout
- Wire the Firebase/PlayFab transport for email sign-in
- One Fortress process at a time — game and launcher share one lock

Behind the scenes:
- Fire build for the layout-override removal
- Delete the forced layout override, keep the arrangement as defaults

## v0.0.28-P820

- No thumb sticks on desktop, rings that count down, every mob fights
- Desktop sign-in read the wrong registry key, so it never found a default browser

Behind the scenes:
- Fire build for the layout defaults and the 3D polish pass

## v0.0.28-P817

- Real log/stone wall textures + cartoon & painterly hearths
- Mobile layout round 2 + a Reset default layout button

Behind the scenes:
- Fire a build for wall textures + cartoon/painterly hearths

## v0.0.28-P814

- Spawn rings were invisible in 3D

Behind the scenes:
- Fire build for 3D spawn rings

## v0.0.28-P812

- Pitch on drag, wheel to zoom, walkable camera, combat beats
- Art expansion fits the bar + stays open; movement never dismisses a cutscene

Behind the scenes:
- Fire build for the camera and combat pass
- Fire a build for the art-expansion + cutscene-dismiss fixes

## v0.0.28-P808

- Isometric cottage furniture for cartoon and painterly sets

Behind the scenes:
- Fire a build for isometric furniture across all art sets

## v0.0.28-P806

- Always show Google's account chooser instead of silently auto-signing-in
- Stop guessing the default browser - it opened Edge over Chrome

## v0.0.28-P804

- Screen-aligned interior controls + stop mirroring iso furniture
- Mobile first-run HUD layout, adopted once over saved layouts

Behind the scenes:
- Fire a build for the interior controls + furniture-flip fixes
- Fire build for the door fix and the mobile default layout

## v0.0.28-P800

- The OPTIONS drawer can never be covered by a window
- Doors broke 3D, and the stick zones ate the HUD

Behind the scenes:
- Fire a build for the OPTIONS-never-covered fix

## v0.0.28-P797

- Make the interior wall coursing actually read as material

Behind the scenes:
- Fire a build for the interior wall-coursing texture

## v0.0.28-P795

- The three top-row chips are uniform in shape and in both states

Behind the scenes:
- Fire a build for the top-chip uniformity fixes

## v0.0.28-P793

- Pool forest collision, and draw the touch sticks on top

Behind the scenes:
- Fire build for the 3D perf fix and visible touch sticks

## v0.0.28-P791

- Square the cottage furniture up with the room
- Give the interior walls real thickness and visible coursing

Behind the scenes:
- Fire a build for the isometric interior round 2

## v0.0.28-P788

- A killed app no longer locks the player out of their own fortress

## v0.0.28-P787

- ONE button interaction standard across Explore/Defend
- Passwordless email sign-in foundation (Firebase), config-gated

Behind the scenes:
- Fire a build for the button interaction standard

## v0.0.28-P784

- The 2D hero spun like a top

Behind the scenes:
- Fire build for the 2D hero-spin fix

## v0.0.28-P782

- Align the interior walls and seat the placeables on their tiles
- The cheat chip stops growing to 60 wide after it is opened

Behind the scenes:
- Fire a build for the isometric interior fixes
- Fire a build for the cheat-chip width fix

## v0.0.28-P778

- Refuse a second instance, raise the running one instead

## v0.0.28-P777

- Android sign-in opens in a Custom Tab, so the browser goes away again

## v0.0.28-P776

- Run the Android gradle build with no daemon - it deadlocks on the runners
- Per-runner GRADLE_USER_HOME so the Android gradle build cannot deadlock
- Android sign-in returns to the game automatically (Gradle custom build + deep link)

Behind the scenes:
- Fire build for the Android deep-link auto-return

## v0.0.28-P772

- Rotation placement drift, landscape UI scale, OPTIONS tab reserve
- Test_hud_window is 13s not 100s - kill the false budget breach at all three surfaces

Behind the scenes:
- Fire a build for the rotation round-2 fixes

## v0.0.28-P769

- Rebuild the cottage placeables isometric
- Real wall art in the isometric interiors + a red doorway marker
- The touch sticks were never usable - zero-size layer
- Drop the unworkable Android intent link, stop prompting on legacy session claims

Behind the scenes:
- Fire build for the touch-stick fix
- Fire build for QA round 4

## v0.0.28-P763

- Rotation loads the other orientation's layout; OPTIONS can't be buried
- Test anchor keys with value_present, not a null check

Behind the scenes:
- Fire a build for the rotation + OPTIONS fixes

## v0.0.28-P760

- QA round 2 — layout persistence, chip consistency, first-resource guidance

Behind the scenes:
- Fire a QA build for the round-2 batch

## v0.0.28-P758

- Local no-save option on web, with a disclaimer
- Punch the cottage doorway, size walls to the floor, project the "!"

Behind the scenes:
- Fire overnight build - sign-in round 3 + web local saves (#4487 #4491)
- Fire interim build for sign-in QA round 3

## v0.0.28-P754

- Sign-in QA round 3 - Android Play-Store regression, popup sizing, same-device kick prompt
- Relative free-look, character stops following the camera, real forest scatter

Behind the scenes:
- Fire build for free-look, camera decoupling, and the forest rebuild

## v0.0.28-P751

- Sign-in QA round 2 - Android auto-return, Chrome-first popup, session-kick race

Behind the scenes:
- Fire interim build for sign-in QA round 2

## v0.0.28-P749

- Free the 3D camera, scatter the forest, pull in the view distance
- Isometric interiors — one coordinate space, distinct cottages, tiling floors
- VRAM-compress the 10 worst cutscene plates
- COLORDUP - duplicated color literal added to the modularity known set
- Canonical UTF-8 brief poster + routine posting rule (08-06 mojibake incident)

Behind the scenes:
- Fire build for the camera-jam fix and forest scatter
- Strip the 9 leftover debug prints outside the cheat system

## v0.0.28-P741

- Run the OAuth loopback accept loop on a background thread
- Session-kick UX - confirm, real dialogs, fast-but-lean detection
- First-boot sign-in gets a real cancel escape

Behind the scenes:
- Fire interim build for accounts fixes (#4460 #4461 #4462)
- Fire build for the WASD fix, the gray slabs, and phone rotation

## v0.0.28-P736

- Allow the phone to rotate, and notice when it does
- WASD camera-relative + oversized decor props, with a 3D contract suite
- The 08-06 QA batch — alert consistency, the palette chip, and ONE icon-button rule

Behind the scenes:
- Fire build for the 08-06 QA batch

## v0.0.28-P732

- Popup registry fallback + local-saves sorts last
- Isometric interior renderer - diamond floor, ghosted near walls

Behind the scenes:
- Fire interim build for popup fallback + door reorder

## v0.0.28-P728

- Close four quest-guidance gaps found by the marker audit

Behind the scenes:
- Fire interim build for the quest-guidance gap closes

## v0.0.28-P726

- Per-orientation HUD layout saves
- Dual virtual sticks for Explore 3D touch

Behind the scenes:
- Fire build for dual sticks + per-orientation layouts

## v0.0.28-P723

- ONE alert badge design, deduplicated per anchor

Behind the scenes:
- Fire interim build for the alert-badge unification
- Isometric-interior convention + the asset prompt recipe

## v0.0.28-P720

- Clearer Switch chooser copy - no redundant sign-in prompt
- The Builder gets a stone cottage, the Woodsman a log cabin

Behind the scenes:
- Fire interim build for the Switch chooser copy fixes

## v0.0.28-P717

- Builder = fortress INTERACTION, window persistence on restart, resize cursors, aim auto, top-bar chips

Behind the scenes:
- Fire interim build for the 08-06 window/HUD batch

## v0.0.28-P715

- SessionGuard claims a restored session at boot

Behind the scenes:
- Fire interim build for the session-guard restore fix

## v0.0.28-P713

- 3D Explore sky renders a real gradient, not a flat slab
- Minimal fortress tiers t1-t5 cleanup re-render, colours locked

Behind the scenes:
- Fire build for the 3D Explore sky gradient

## v0.0.28-P710

- 3D Explore camera-relative movement + forest collision
- Bound every PlayFab request with a timeout

Behind the scenes:
- Fire interim build for the PlayFab request timeout fix

## v0.0.28-P707

- Open Google sign-in as a popup window on desktop

Behind the scenes:
- Fire interim build for the OAuth popup window
- Retry 5 - web-epoch fix build
- Retry 4 - web-epoch fix build
- Retry 3 - web-epoch fix build
- Retry 2 - web-epoch fix build

## v0.0.28-P701

- 3D Explore roof artifact - void backdrop child rect never hid
- Consistent Cost:/You-have: shape across the ruins repair modal and all six weapon-quest trades
- Bump web-epoch E16->E17 - SessionGuard broke web boot
- One alert per icon (equip-trail vs badge), HUD Cancel/Save split, art-style collapse, log art fix

Behind the scenes:
- Fire build for the confirmed roof-artifact fix
- Retry the web-epoch fix build
- Fire interim build for the web-epoch fix

## v0.0.28-P694

- Request a nonce on the native OAuth loopback flow
- Benign token-skips count as reader liveness - stops the idle-window false alarm

Behind the scenes:
- Fire interim build for the native OAuth nonce fix

## v0.0.28-P691

- Single-active-session enforcement
- The nightly's 21 failures - 3 isolation defects + a faceless-font guard

Behind the scenes:
- Fire interim build for single-active-session enforcement

## v0.0.28-P688

- 3D Explore movement-facing, fog overcorrection, prop collision

Behind the scenes:
- Fire build for the movement/fog/collision fixes

## v0.0.28-P686

- Chooser layout - continue button sized/positioned like other doors

Behind the scenes:
- Fire interim build for the chooser layout fix
- 08-05 chart fixes - slowest-15 panel replaces the red block, dead-feed panels withheld, freeze mapping marked resolved

## v0.0.28-P683

- 3D Explore camera/HUD polish - mouse-look gate, button clipping, fog/sky tuning
- One alert+sound per pickup, Builder waits for real tower sight (P641 follow-up)

Behind the scenes:
- Fire build for the 3D camera/HUD polish batch

## v0.0.28-P680

- Flush user:// to IndexedDB after HUD/settings writes

Behind the scenes:
- Fire interim build for the HUD web-persistence fix

## v0.0.28-P678

- Unify desktop/Android sign-in onto the same OIDC connection web uses
- Zombie-chart alarm - self-check flags a brief chart whose data feed died (#4374 follow-through)
- Wire the ruins/repair discovery dialog's missing image slot (P641-I)
- Server-side Google token exchange, for desktop/Android OIDC unification
- A minimized native app is not a freeze

Behind the scenes:
- Fire interim build for the sign-in account unification
- The three chart fixes Nathan asked for (#4374) - per-job runner minutes, honest Codex chart, PR long timeline
- Record the web-vs-native account fragmentation gap

## v0.0.28-P670

- Clear Switch flow (continue vs new account), CloudScript logging

Behind the scenes:
- Fire interim build for the round-3 sign-in fixes
- Tileset outline/palette rules + active regen queue

## v0.0.28-P667

- One alert for a quest tool + hut-door flashing markers (P641)

Behind the scenes:
- Fire build for P641 quest-marker fixes

## v0.0.28-P665

- Web sign-in - real email, per-attempt nonce, framed button

Behind the scenes:
- Fire interim build for the sign-in follow-up fixes

## v0.0.28-P663

- Play buttons skip the light door's own click for capable devices
- Position Google's sign-in button with real canvas scaling
- Map the Android management-screen FREEZE signature to #4323

Behind the scenes:
- Fire interim build for the sign-in button position fix
- Refresh the World Tileset Audit PDF with tonight's fortress/log fixes

## v0.0.28-P658

- Interior wall blank/repeat bugs + isometric faces, log single-cap geometry

Behind the scenes:
- Fire build for tonight's P625 follow-up batch

## v0.0.28-P655

- Native sign-in success page tells the player to switch back
- Tiny-swords fortress_t4 base wall reconstruction, extended to ground
- Woodsman decor is npc_woodsman, matching the generator

Behind the scenes:
- Fire interim build for the Android sign-in copy fix

## v0.0.28-P650

- Web sign-in needs a nonce claim for PlayFab's OIDC check
- Minimal fortress_t5 crenellation gap - clean negative space

Behind the scenes:
- Fire interim build for the web sign-in nonce fix

## v0.0.28-P647

- 3D Explore is the zoom-to-max transition, not a menu entry
- Delivery-driver stops retrying read-only dispatches that completed (#4339 lesson)

Behind the scenes:
- Fire build for the zoom-to-3D correction
- GdUnit pool 2 to 4 per the #4339 controlled ladders + fix the two heuristics that misfired

## v0.0.28-P643

- Web Google sign-in is now a real in-page popup, no redirect_uri

Behind the scenes:
- Fire interim build for the web Google sign-in rework

## v0.0.28-P641

- The P625 playtest batch (13 fixes — beep/push/loot/spawn-dot/cheat/builder/vagabonds/map/decor)

Behind the scenes:
- Fire build for the P625 playtest batch (13 fixes)
- Batch-fire receipt must not contain the box lane trigger literal

## v0.0.28-P638

- Cross-device delete now propagates via a server-side tombstone
- Minimal fortress_t2 fog artifact + painterly fortress_t4 washed-out merlons

Behind the scenes:
- Fire interim build for cross-device delete fix

## v0.0.28-P635

- Wire real cottage_wall art into interior walls

Behind the scenes:
- Fire build for the corrected 3D Explore observer
- Rebuild 3D Explore as a pure observer of the real 2D game

## v0.0.28-P632

- Pipeline-tests.png labels collide when two tests share a long prefix

Behind the scenes:
- Add 3D Explore reachable-preview line to v0.0.28 shipped

## v0.0.28-P628

- Delete clears the cloud backup too, not just the local file

Behind the scenes:
- Fire interim build for the device QA round 2 fixes
- Step gdUnit pool 3 to 2 per today's CONCURRENCY HEADROOM verdict

## v0.0.28-P625

- Builder's 'sets out for the tower, meet you there' waits until the tower is found (P603)
- Status label truncation, web redirect_uri_mismatch, desktop refocus

Behind the scenes:
- Fire build for P603 batch pt3 (builder sets-out gate)

## v0.0.28-P622

- Wire real NPC rescue, real combat, real quest chain

Behind the scenes:
- Fire build for 3D Explore full (rescue + combat)
- Re-fire build - prior run for #4308 was cancelled, never published

## v0.0.28-P619

- P603 batch pt2 — spawn-dot (remove red QA marker) + open the (23,71) impassable spot
- Split identity status text from the action button

Behind the scenes:
- Fire build for P603 batch pt2 (spawn-dot + map spot)
- Fire interim build for the status/action split

## v0.0.28-P615

- Promote the 3D camera spike to a real, reachable preview mode

Behind the scenes:
- Fire build for 3D Explore preview

## v0.0.28-P613

- P603 batch pt1 — gentle push, hut respawn, I-key toggle, boot beep

Behind the scenes:
- Fire build for P603 batch pt1 (push, hut, I-key, beep)
- Refresh the World Tileset Audit PDF against tonight's fixes

## v0.0.28-P610

- Cutout defects in tiny-swords tree3/cottage_table/npc_quarryman + minimal tree3
- Decor_cart was a leftover scarecrow in the cartoon style

## v0.0.28-P607

- Identity chip was collapsing to an invisible zero-width sliver
- Log sprite width-cap regression (pre-emptive)
- World-sprite scale consistency (hero-relative sizing)

Behind the scenes:
- Fire interim build for the identity-chip fix

## v0.0.28-P603

- One door-list chooser for sign-in AND switching, flip-only

Behind the scenes:
- Fire interim build for the unified sign-in chooser

## v0.0.28-P601

- Organic bandit-chief loss + Archer bridge-bow (#4214) - salvaged, under review
- Piper (scout) appears 3rd Explore by the keep, click-sequence into first Defend, she's a woman
- Vale layout D+E+H - fog leak at the glen seam, bare tool-gate cells, clumped keep economy

Behind the scenes:
- Fire build for the P524 playtest batch (Piper + organic bandit death + archer bow + map)

## v0.0.28-P597

- Walking into a mob nudges it instead of wedging the player
- Rescue NPCs reset on a hut/cottage round-trip
- Death forfeits only this run's haul, never XP
- Silence the boot 'beep/donk' - blueprint-trail alert chimes on startup
- Mode-nav alert uses the consistent NotificationBadge, not a bespoke gold dot
- Bridge vagabonds repeat their refusal on later walk-ups
- Interior exit re-prompts the entrance on the doorstep
- Remaining cutout defects across minimal + painterly-terrain
- Spawn dots draw their tier color, not a flat red
- Defend mode locked+grayed until the player meets the scout
- Misc cutscene art backlog, 7 plates
- Bridge vagabonds cutscene art, 3 plates (final backlog batch)
- Builder_joined_fort fires on first PRODUCTION open, not fortress creation
- Mason quest cutscene art, 6 plates
- Minimal rarity color scheme + fix hero.png wooden-leg defect
- Merge the snowflow 3D-explore camera prototype into main
- Thresher quest cutscene art, 5 plates
- West_boulder visual gap - too small/off-center
- Cartoon npc_builder gradient defect, third attempt
- Cartoon rock3 still had a jagged spire point, redesigned
- Minimal log.png was still green, now genuinely brown
- Conversion-sweep - server recycles convert spawn pins with a silent sidebar dupe
- Weekly recycle exemption for auto-pins was dead code - minted dupe chats every Sunday
- Backfill disambiguates same-title pins by connection status
- Benign token-staleness class (#4178) + orphan-detector runaway guards
- Unstick the merge queue (#4177) + settle the digest posting path

Behind the scenes:
- Fire interim build for QA6 batch A (6 fixes)
- Mark #3950 QA round 4 items closed (PART 1, 2 items 6-7, 3 items 10-11)
- Cheat_manager snapshot builders: same ~95-line shape eleven times (monthly finding 8)
- Follow-up: move fresh-new-game reset to GameManager + close the gaps in _reset_state_silent
- Update snowflow manifest — NPC bug resolved, 4 mob types, real corpse pose
- Update snowflow manifest — resource respawn, Fortress greeting
- Update snowflow 3D-explore manifest — NPCs + interactions

## v0.0.28-P560

- Identity-scoped local saves + a Quit path off the roster/gate
- Decor_arrows3 hollow/translucent cutout defects
- Decor_body3/4 + decor_arrows2/3 scatter variety, all styles
- Cartoon npc_builder + new npc_archer NPC, all styles
- Tree_fallen_cleared angle match + widened gap, all 3 styles
- Real arena_gate sprite art, all 3 styles
- Real bramble_wall sprite art, all 3 styles
- Real bridge + hedge_wall sprite art, all 3 styles
- Real tent sprite art, all 3 styles
- Generate the World Tileset Audit PDF, wire into #about
- Sprite-preferred rendering for the 5 remaining procedural map markers
- Redesign rock3 as a rounded boulder, all styles
- Log barrier prefers real art over the procedural chevron
- Fortress_t3/t4 cartoon had a leftover drop-shadow ghost

Behind the scenes:
- Fire interim build for identity-scoped saves + Quit path
- Mark #3950 QA round 4 items closed (PART 1, 2 items 6-7, 3 items 10-11)
- Refresh the World Tileset Audit PDF (194/198, up from 163/198)
- Cross-reference the parallel 3D-explore spike's model manifest
- Snowflow 3D-explore spike model manifest — sync point for parallel 3D effort
- Rewrite remaining-work spec for QA round 4 (issue #3950)

## v0.0.28-P540

- Outdoor scatter-variety pools (arrows/bodies)
- Unwrap PlayFab's "data" envelope in login + cloud-script parsers

Behind the scenes:
- Fire interim build for the PlayFab data-envelope fix
- Fire interim build for the Google sign-in stable-port fix

## v0.0.28-P536

- Painterly catch-up - barriers + cottage scatter-variety
- Tree/boulder barrier cleared-state art (minimal + cartoon)
- Tree/boulder barriers get a cleared visual
- Cottage furniture real art + scatter-variety + cartoon tree_fallen
- Stable loopback port for Google sign-in redirect_uri
- Self-check's INLINE web-drift pick uses version+publish-time, not max(P)
- Promote Nathan's picks - fortress tiers, hut, cottage, tree_fallen barrier
- Delivery driver drops the VERIFY-SUMMARY it is supposed to carry

Behind the scenes:
- Monthly code findings: mechanical batch - div-by-zero guard, tautological check, per-frame lookup, stale TODO, dead twins

## v0.0.28-P524

- All craftsman tool costs to 10 + audit every quest number is a numeral (Nathan 08-01)

Behind the scenes:
- Fire interim build for costs-to-10 + numerals

## v0.0.28-P522

- Zero-storage artifacts + a storage panel on the budget chart

## v0.0.28-P521

- Purge the 175.9 GB artifact debt + 1-day retention; monthly docs post gets a plain title
- Sibling digests coexist, yields are not failures, monthly+weekly carry the health sheets

Behind the scenes:
- Rewrite building level ceilings + gear ids to config truth, flag narrative doc as stale

## v0.0.28-P517

- Tag-deletion race guard on rebuilds + exempt Mergify speculative drafts from the body contract

## v0.0.28-P516

- Consistent alert system (#4049) - salvaged from a died dispatch, under review

Behind the scenes:
- Fire interim build for the consistent alert system

## v0.0.28-P514

- Tighter respawn mark, and the minimap speaks the same countdown
- Cheat menu expanded as a vertical stack, not one row

Behind the scenes:
- Fire interim build for cheat-horizontal + spawn-mark tighter (#4045 #4046)

## v0.0.28-P511

- Regenerate CARTOON nodes/rocks/trees via Codex
- Cartoon dead-soldier bodies were still old bones art
- Regenerate MINIMAL nodes/rocks/trees via Codex
- Minimal rescue_npc was a keyhole icon, not a person
- Save/Exit fell below the fold - the panel had no internal scroll
- QA round 3 - dying-man art-switch bug + graphics-mode switcher
- Utf-8 stdout on the runner - the note's emoji crashed the log print AFTER a successful post
- Rolling 'Roadmap updated' note in Discord - edits-in-place never light the unread badge
- Concurrency headroom verdict windows to the last 2 days - stale regimes stop driving pool advice
- Google sign-in failed with "network error (8)" - PlayFab gzip response Godot couldn't decompress

Behind the scenes:
- Commit tileset-regen pick boards for durability (issue #3950)
- Fire interim build for settings sticky footer
- Flag the stat-wiring track PARKED honestly - Nathan approved the Explore divergence
- Record the orphan-tax kill + one-version-everywhere under Infrastructure shipped
- Tileset-regen remaining-work continuation roadmap (issue #3950)
- Fire build for the PlayFab gzip sign-in fix

## v0.0.28-P493

- The respawn spawn-mark is a clock-fill sweep, not an accelerating pulse

Behind the scenes:
- Fire interim build for pulse B sweep-to-full

## v0.0.28-P491

- Art-style switch reskins IN PLACE ΓÇö stop rebuilding the world (hero art, mob respawn, fog); hut in/out stops respawning too
- The CHEAT menu expands INLINE on the top bar, dropping below only when the bar is out of width
- A weapon equipped mid-fight now actually swings

Behind the scenes:
- Fire interim build for QA batch 3 (#4007 #4005 #4009)

## v0.0.28-P487

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- Fire diagnostic build for the sign-in failure reason surfacing
- Surface the Google sign-in failure reason + layer on the gate (temporary device-QA diagnostic)

## v0.0.28-P485

- Craftsman dialogue quotes the real cost, as a numeral
- Integrate the spawn-mark pulse phase per spawn so the countdown reads as accelerating
- One pink CHEAT menu replaces the CHEAT + x1/x5/x10 rail cluster

Behind the scenes:
- Fire interim build for QA batch (#3993 #3994 #3995)

## v0.0.28-P481

- Promote held painterly picks (decor/rocks, rock=cell1) + first minimal fill (hero/log/cart/body/body2/arrows)

## v0.0.28-P480

- New Fortress cloned the last save's state instead of starting fresh
- Web-drift check picks the tip by version+publish-time and compares tag IDENTITY, never P magnitude

Behind the scenes:
- Fire interim build for the New Fortress fresh-start fix
- Bump LAUNCHER_VERSION 1.1.59 to 1.1.60 so deployed launchers self-update to the tip-identity fix

## v0.0.28-P475

- One version on every surface - tip-identity updates, publish-time ordering, P1 at version close

Behind the scenes:
- Fire interim build for the Archer patrol reframe

## v0.0.28-P473

- The Archer patrols a big meadow loop instead of standing still
- Regenerate world sprites (mobs/NPCs/fortress/placeables/cottage, 3 styles) + NPC art routing

## v0.0.28-P471

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- Re-measure slow-suites on post-#3954 main - return 9 suites to the everyday pool
- Fire interim build for story-lane QA batch (#3961 #3962)
- Fire interim build for device QA of the #3931 sign-in fix

## v0.0.28-P468

- Render commits stranded on the wrong branch - breaches.json blocked the silenced checkout
- Spawn-ring redo ΓÇö small-circle color = rarity/tier, big aggro ring constant, patrol = icon at spawn point
- Gate 2nd-tier tools behind 1st barrier, sharp tool replaces basic, builder ruins-card ordering
- Sign-in failure was silent on the roster gate + browser tab mojibake
- Monotonic-serve guard compares tip IDENTITY, not P magnitude - P-reset broke it

Behind the scenes:
- Record the week's three shipped workstreams + flip Accounts Stage 1 to SHIPPED

## v0.0.28-P461

- Snapshots loaded main.tscn into an empty tree - 702 orphans taxed the whole nightly
- P-numbers restart at each version (v0.0.28 goes P2878 to P457)

## v0.0.28-P459

- Nathan's five chart notes - timeout-only alarm, drop daily totals, disk on concurrency, regroup box health
- Spawn-ring schema - rarity color, wander icon, path toggle

Behind the scenes:
- Test_phase3_snapshot_relock does not finish in 20 min running alone (probable hang, not slowness)
- Log the rare/named spawn-chance idea as an open design question

## v0.0.28-P2874

- Remember-me checkbox persists sign-in across app launches
- Wander_points was silently dropped by the bake/load round-trip
- Two wolves wander, ring color marks which ones
- Tie the wander-wolf popup to sight, not a fixed row

Behind the scenes:
- Fire interim build for remember-me sign-in

## v0.0.28-P2869

- Account gate before the roster - sign in or use local saves
- Desktop Google sign-in redirect_uri must be localhost, not 127.0.0.1
- Promote Alpha Wolf minimal sprite (pick #5)
- Scale the suite timeout by SELECTION SIZE - the nightly was killed again
- Promote Alpha Wolf painterly-terrain sprite (pick #4)
- The Archer's northernmost wolf wanders a patrol loop
- The Archer's wander ground — river bends west, big open glade
- Promote Bandit Leader tiny-swords sprite (pick #2)

Behind the scenes:
- Fire interim build for oauth redirect fix + account gate (#3932/#3933)
- Pull archerloop's left edge in further, clear an unrelated ring
- Widen the archerloop preview crop, its top edge clipped the wolf
- Add a wander-path overlay to the map preview harness

## v0.0.28-P2857

- Stage 1 - Google sign-in + backup-all + boundary sync
- The engines metric still carried a "suites" unit

Behind the scenes:
- Fire interim build for Accounts Stage 1 (#3534/#3875)

## v0.0.28-P2854

- Stats-overlay exit + convert aim-rail buttons to a real HUDWindow
- The pool panel counts ENGINES, not slots - say so
- Separate a KILLED run from a harmlessly superseded one
- Emit breaches.json - every threshold, its value, and whether it is past
- Prune to the latest RUN, not the latest DAY - the brief was doubled
- Judge a test's cost by its BEST run, not its worst
- Give the web<->release drift check a deploy grace period
- Repair check 18's corrupted path + gate raw control characters
- The release gate has been DEAD for 8 nights - raise its timeout, chart it, alert on it

Behind the scenes:
- Add bramble/SE region to map_preview render tool
- Fix stale blueprint-popup status + reassess Housing and idle

## v0.0.28-P2843

- Aim-mode facing was stomped every frame by the walk-bob
- Forced first-defense gate — Explore greyed until one Defend
- First-defense card + Defend's story pump + TWO popup presentations
- Craftsman first-greeting parity + every character names himself
- Escalation must ADD the core smoke set, not replace the impacted selection

Behind the scenes:
- Mark chapter 5 fully shipped — first-defense card + forced gate

## v0.0.28-P2837

- Prototype aim-mode control scheme (zoom-triggered facing)
- Name gate STARVATION in the daily check, not just gate cost
- Raise gate slot-wait patience 4 to 7 attempts (~28 min to ~47 min)
- No PR gate may run the whole suite - close the four remaining escalations
- Session record
- Reap-orphans staleness threshold matches its DAILY cadence
- Promote Bandit Leader minimal sprite (pick #8)
- Nightly cost guards - catch suite creep before it kills the gate again
- No gate ever runs the whole suite again - core smoke instead, full sweep is monthly
- The three uncovered slowness causes get charts (freshness, screen build, RAM by concurrency)
- Column-pack the composed sheets - row alignment wasted a screen of space
- Nightly hook stages the RENAMED sheets (spend / machine / automation)
- Six sheets - one question each, AUTOMATION alone at the top
- Sheets are two columns at double resolution - readable AND screen-shaped
- Composed sheets are one FULL-WIDTH chart per row, not quartered thumbnails
- Composer searches for its inputs - it composed NOTHING in the real nightly job
- Mob attack-lunge animation, mirrors the hero's swing
- Promote Bandit Leader painterly-terrain sprite (pick #9)
- Cache textures - management screen builds 11x faster (5:04 to 28s)
- Stop escalating every *_config.gd change to the full suite
- Android boot mirrors the retired PC/web chooser
- GdUnit pool back to 3 - the raise to 5 starved every suite
- Two panels that watch the pool raise (usage vs cap, cost by concurrency)
- GdUnit pool 3 to 5 concurrent suites (measured), + ops-cadence chart joins the machine sheet
- Composer runs LAST - it was skipping the charts rendered after it
- Nightly hook renders + stages the five sheets; brief spec fetches them
- Pipeline sheets + grouped usage/machine sheets (11 images to 5)
- Board v13 - WORK split open/done, TESTS owns file inventory, A before B; fix(docs): pre-push gate is TIERED, stop hand-running the full suite
- Gate scripts warn when THEIR OWN tree is stale (box B's wedge)
- Board v10 - framed panels, category bands, and RESTORE the test-files panel
- Board v9 - categorized rows (WORK/RUNS/TESTS/MACHINE), runs-by-outcome, day-bucket bubbles, shared window
- Board v7 - every slot a real chart (Nathan: '2 charts are just text')
- Board v6 - cost-concentration panel + plain-numbers week summary
- Board v5 - full-population histogram + ALL over-budget tests
- Snapshots and throne re-evals rebuild only the LIVE screen (#3826 part 2)
- Board v4 - plain language everywhere + suite-count context; self-check covers service worktrees
- Pipeline-health board v3 - issue-age + run-minutes-by-tier panels, clock-time axes
- Codex chart liveness + board readability pass
- Codex-usage chart re-collects nightly - it was FROZEN at 07-17
- Woodsman lead_the_way + the Fighter's arc actually closes
- Pipeline-health board - six would-have-caught charts, each dashed at its threshold
- Build the Scout beat + retime it ahead of Perrin
- Self-check 16 - canonical-tree freshness, self-healing (the 439-commit box-A rot)
- Gate wedged on raw --import; story-beat adds forced the full suite
- Codex imagegen is the cutscene renderer, Flux becomes the fallback
- Drop autoload/viewport signal subscriptions on _exit_tree
- Cost-vs-information screen - self-change smoke rule, conformance test/ exemption, brief Test health block + 2x2 chart
- Pipeline-audit decisions A+C, test-runner isolation+ratchet, brief test-health
- The "0% CPU Godot wedge" is a measurement bug - the console binary is a relauncher
- Retreat is a standalone milestone, not a storyline chapter
- Nathan's 07-27 storyline pass - payoffs close their arcs
- Restructure the Storyline Bible into Nathan's three channels
- Capture-state stream redirects are opt-in - they caused the hangs they were built to diagnose
- Make the visual tier testable locally and stop stale goldens reading as regressions
- Capture driver clears retrospective popups at the shutter
- The 44-minute full suite runs WEEKLY; nightly runs the fast net
- A FULL suite run gets 60 min - 45 was under its measured time
- Issue-dedupe lookups fork a new issue on every run (PS 5.1 arg splitting)
- Beat pre-marking is a dictionary read, not a lock evaluation
- Snapshot beats stay suppressed after the event pump
- A snapshot no longer leaves a story popup on the screen
- A snapshot rescue also clears the spawn that gates it
- Dev-only cheat autoload no longer forces the full suite; probe stops adding load
- Full-suite gate gets 45 min; the probe now samples contention
- Self-check commented-vs-duplicate alert lookup was always failing
- Web-sync checks read the orphaned ROOT build-id.json, not /play/
- Ops-cadence render writes a heartbeat
- Cut gate creep at its cause - two screen-building suites were 89% of the always-run set
- Cut gate creep at its cause - the always-run set is state-level only
- Generate the Ops Cadence card from live box state, nightly
- Mergify config error - priority_rules is top-level, not under queue_rules
- Monthly digests stamp a heartbeat on their gated no-op days

Behind the scenes:
- Correct the tiering rules in CLAUDE.md - no PR gate runs the whole suite
- Record the measured lane-scaling curve on SlotCount
- Log aim-mode prototype design pattern + open design question
- Lock in the mob/NPC tileset renderer decision + CI-defer pattern
- Art-cache rule + narrowed tier rule in CLAUDE.md; brief posts the FIVE SHEETS only
- CLAUDE.md tells the truth about the gate (five checks, all on box, tiered pre-push)
- Lock the mob/NPC tileset sprite generation recipe
- Retract a wrong wedge diagnosis I left in the warmup comment
- One-off diagnostic to print the Android release signing SHA-1
- Retire the four workflows superseded by static-gates (decision A)
- State asserts gate, pixels only inform
- Retire the two permanent standing-board issues
- Fast dead-man for expired Claude Code login (2026-07-25 incident)
- Upgrade configuration to current format

## v0.0.28-P2749

- Make the daily brief fail loudly - account failover, artifact verification, honest heartbeat
- Add --validate self-check to the storyline board generator
- Kill the archive-resurrection mint - recycler exempts auto engines, archive-sync sweeps fresh shell dupes
- Stop the COMMAND-mode capture hang - bulk gear-fill refresh storm + no-op alert revision bump (#3717, #3718)
- Poller comments can no longer self-fire a dispatch lane
- Storyline board generator had 3 stale-data bugs
- Archive-sync backfill matches deliberate pins' title suffix
- Capture-state.ps1 redirects Godot's console output to a log
- Docs-nightly-regen didn't watch the doc-pipeline code itself
- Usage-poll writes a heartbeat file
- Storyline coverage tool never read PENDING_ART
- Docs_channel_sync posts one message per section, not one for all 12
- Harden ci-sentinel FREEZE detector against PS 5.1 array-collapse
- Frame-pacing probe writes a heartbeat file
- Reference-pdfs.yml literal backslash-n broke 3 of 12 docs since #3547
- Visual-tier standing-issue dedupe swallowed gh failures, forking into 5 duplicate issues
- Ci-sentinel gh --json args rejected by gh (comma+space)
- Skip SystemFont in glyph fallback under headless (nightly-suite 4-nights-red)
- Run-visual-tier.ps1 reads scenarios from its own fetched worktree
- Root-cause the 4-day recurring box self-check alert
- Deterministic daily-brief archive-then-prune
- Disable gdUnit fail-fast so the full failure surface is always reported
- Instrument archive-sync reader failures + alert on sustained outage

Behind the scenes:
- Fire interim build - current build for tonight's dev/QA
- Finish matching Garrick/Wren/Piper text to approved art (no hedging)
- Rewrite Garrick/Wren/Piper descriptions to match approved portraits
- Clear the Woodsman portrait blocker + Builder ship status
- Mark heroes/guards/armaments/gear inspection in-progress (v25)
- Record 5 design decisions recovered by the #3558 chat-harvest backfill
- Week of 2026-07-25 -- 0 ideas, 7 decisions
- Refresh Mason/Thresher/Warrior/Archer status in quest-master

## v0.0.28-P2715

- Woodsman axe wood cost 20->10 - unblock tonight's playtest for Ike

Behind the scenes:
- Fire interim build - axe-cost unblock for tonight's playtest
- Android entry mirror: boot to entry board, Obtainium updating, one APK runtime QA
- Frame-pacing probe to map the #3410 headless-Godot oscillation

## v0.0.28-P2711

- World Atlas uses the real in-game map render + zone lines
- Universal "!" markers + resource respawn + Perrin retime + death-card clarity
- Blueprint-to-build "!" trail + library cost matches camp loot
- Craftsman quest framework + Mason + Thresher arcs (locked shape)
- Never park a job on a 0%-headroom account inside the slack deadband
- QA round 8 — fog redesign, Info Bar switch, skinny grab, popover dismiss, reflow, modal teardown
- Billing self-check alerts on SLOPE not cumulative crossing
- World fog gray-cloud, borders fog-gated, one white for popup buttons
- Restore mipmaps on two woodsman cutscene plates — main-side defect unblocking full-suite CI
- One alert not two — equip marks seen, aggregate badge removed
- Mechanical Codex-first routing with Claude-Sonnet fallback (#3608/#3700)
- Mechanically force the Codex lane for recipe bundles
- All 12 Player Documents on the website + R2
- State-driven PR+issue passes in box-poller - route every state, never rot silently
- Delivery-driver step2b - the RED-PR consumer (closes the dead zone, #3608)
- Bramble+hedge refusal popups + seal the bridge walk-around (Nathan 07-21 round 3)

Behind the scenes:
- Re-fire interim build - android flake retry
- Fire interim build - v0.0.28-wip content batch
- Promote Nathan-approved arc plates (quarry/cleared/bargain/joins/sharp-pick), re-rendered to Doran dossier
- Promote Part 2 plates (north-tree found/chopped, sharp-axe, blueprint, house-built)
- Promote Nathan-approved arc plates (first-seen/tree/after/trade/axe/chopped/hut)
- Doc style unification: one shared template for the whole published set, mapped to the game style guide

## v0.0.28-P2688

- Pin wrangler exactly + recovery build - registry race killed web run 177

## v0.0.28-P2687

- QA round 7 — kills+time row, title-bar drag, fog-proof transparency, collapse removal, Version row, log font
- Poller auto-merge is a DENY-list, not an allow-list (#3608 root-cause)

Behind the scenes:
- HUD QA round 7 build for Nathan re-test
- Unify all Player Documents on the light parchment theme
- Plain-text rule for ALL channel blocks + human crash block

## v0.0.28-P2682

- Woodsman Part 2 — practice, north tree, sharpen quest, sharp axe, town blueprint, move-in closer
- Codex-run.ps1 - one-command Codex-lane driver
- Merge-pr guards against admin-merging an UNSTABLE PR whose checks have not attached yet
- Poller safety - closed-issue guard + fail-closed kill switch + self-mod deny-list
- Pre-push-gate impacted mode - pass the test list as a real array
- QA round 2 - markers visible+placed right, single-button cards green (Nathan 07-21)
- Event-reactive delivery driver + per-routine digest map
- Test-value ledger slice 1 — per-suite cost/catch capture
- Wait-pr-green counts only LIVE runs (in_progress/queued) as running
- Mechanical pre-mortem audit + close self-check watch-list gaps

Behind the scenes:
- Fire interim build - round-2 fixes + Woodsman Part 2 (PRs #3673 #3678)
- Route recipe-shaped dispatches through Codex ΓÇö the grind is burning Fable while the Codex pool sits idle
- Woodsman board shows the specced Part 2 as outline rows

## v0.0.28-P2669

- Backup+snapshot redundancy layers

Behind the scenes:
- Fire interim build - android retry after herd-pressure crash

## v0.0.28-P2667

- Pack s3tc for web VRAM textures + suppress OS-caused load-stalled dead-man
- Pins created via new-pinned-chat.ps1 get a cse so archive-sync can track them
- Capture defaults to native 540x960 portrait, not 480x8xx
- Art-auto-promote canonical import profile + declared-plate guard
- Daily art-gap scan loop (ArtGapScan) #3531
- Render session_ms/save_kb on the crash report

Behind the scenes:
- Add backfill scope + archive-candidates duty to Chat Harvest

## v0.0.28-P2660

- Live-QA markers + barriers — aggro cue instant, equip clear, vagabond block+fire, bramble beat, log "!"
- Retreat = End Run & Return unified — confirm modal + 25% wallet loss
- Split 6-month dispatch bar into self-hosted vs cloud lanes
- Weekly Meta-Review self-diagnostic routine with a closed adoption loop
- Art-auto-promote honors autonomy kill switch, labels auto-origin
- Crash-sweep reads a sessions-index key, not a namespace LIST
- Ci-sentinel FREEZE detector - unfreeze stuck action_required/queued PRs
- Box-capacity sampler + Daily Brief chart and alerts
- Add 'steward' to digest-runner ValidateSet - map entry alone rejects the arg
- GitHub Steward hourly routine - spec + digest-runner map entry
- Repair renamed snapshot + dedupe nightly issue spam (#3476 #3477 #3478 #3479)
- Single _apply_mute_state so icon and audio never disagree (#3297, #3239)

Behind the scenes:
- Fire interim build - QA marker/barrier fixes retest (PR #3620)
- Billing - gate job off cloud + launcher DMG release-only
- Lock Woodsman (Bram Thorne) redhead dossier portrait
- Idle-offload-lane vs saturating-cap = standing Needs-you
- Institute holistic cross-chart read step (the point of the loop)
- Queue-urgent priority lane - incident fixes jump the merge queue
- Plain-language CI health + dispatch-spike & cap-saturation guards
- Retire the parked-label class - 13 issues moved to roadmap/queue

## v0.0.28-P2639

- Builder_joined_fort + reusable Blueprint Received popup (Nathan 07-21 review bundle)
- Mob Audit player document (mobs + NPCs) — render + interaction fixes
- Playable Audio audit player document
- Arc boards — correct dossier characters, descriptive beat names, encounter dialog copy; woodsman_after_tree rework flag
- Batch-fire - the nightly backlog pump
- Woodsman arc board includes woodsman_axe_given
- Quest-walk fixes batch — title-case titles, axe-presentation beat, reset gap, hut plate, hygiene (#3492 walks)
- Kill switch false-ENGAGED on empty issue list
- Autonomy kill switch + auto-origin cooling-off (SLICE 1)
- Death-lesson slice — first_death_rise, chief loss both ways, land renewal, respawn rule
- Commit .import (mipmaps on) for 6 testing pngs shipped without one
- Wake_cold_open_a-e .import mipmaps/generate=true
- Arc review boards v2 — flow, triggers, copy + quest-master taxonomy

Behind the scenes:
- Chore(deps)(deps): bump actions/download-artifact from 4 to 8
- Librarian board — vagabonds in-arc, Builder in strip, Blueprint Received milestone, Archer→bramble (Nathan 07-21)
- Fold Audio audit into ART/STORY (audio is art)
- Distinct Woodsman appearance brief + Builder arc closer builder_joined_fort, drop fortress_enter (Nathan 07-21)
- Four-section Player Documents taxonomy + Quest/Cutscene promotions + Progression tables rename
- Main Storyline spine + Woodsman resequence + milestone renames (Nathan 07-20)
- Needs-you items are decision-shaped (problem/options/recommend)
- Rule - bundle by iteration, split by seam (one PR per surface per QA pass)
- Chore(deps)(deps): bump actions/setup-python from 5 to 7
- Accounts & cross-device sync design v1 — Nathan-locked 2026-07-20 (rev 5)

## v0.0.28-P2616

- Batch-3 — watermark band, Top Bar window row, log fit-font, C4 skinny round-trip, C5 gear popover
- #crash-reporting is a 1-day feed; GitHub is the durable crash record
- Storyline art review boards + Storyline Art Bible PDF
- World Atlas player document + reference-pipeline wiring
- Autoqueue: true - queue_conditions auto-embark is OFF by default
- Purge-qa-assets — correct secret name (BUILDS_PUBLISH_TOKEN) + fail-fast error branches
- KV capacity chart + daily-brief attachment
- Queue label auto-embarks via queue_conditions (modern Mergify)
- Emoji font fallback + tofu-glyph icon replacement + glyph gate
- A minimized tab is no longer a false "crash" (1fps = background throttle)
- Name-entry format parity + unified dismissal contract, drop dead BottomSheetHelpers
- Phone default layout - shared dock resolver + surface predicate
- Tutorial touch-to-attack mechanics - soldier '!', button-free first fight, lowest-spawn cue

Behind the scenes:
- Final HUD QA build - full 07-20 GUI push in one build
- Upgrade configuration to current format
- Commit Storyline Bible nightly task install script
- Preserve Nathan-approved Codex Mason render (mason_quarry_intro candidate)
- The published document set is the canonical interface (categories, format rule)
- Capital-T title style, The Mason canon + Walls finale, hut materials, map-art roadmap line
- Manual workflow to purge retired TheFortressQA-* assets from all releases (#3459 follow-up)
- Auto-promote 5 rendered plate(s) - wake_cold_open_a, wake_cold_open_b, wake_cold_open_c, wake_cold_open_d, wake_cold_open_e
- Promote cold-open concept A v1 (lone survivor rising)
- Daily brief pins the ops-cadence card source (Message 0)

## v0.0.28-P2593

- Unified size<->font model + Area/Character wide-reflow + 8-edge resize

Behind the scenes:
- Interim - HUD window redesign for Nathan QA

## v0.0.28-P2591

- One build per platform — retire TheFortressQA-* debug exports (#3459 phase 1)
- Daily Cloudflare KV capacity audit
- Bridge vagabond gate + scripted first bandit-chief death
- Reframe combat tutorial to touch-to-attack (no button)
- Mergify merge-queue config - label-gated enqueue, 7 required checks
- Register woodsman first-seen/after-tree plates — live cutscenes were imageless
- Branch-freshener state round-trip + pass log
- Classify CI reds (FLAKE/STALE/REAL) + auto-freshen stale PR branches

Behind the scenes:
- Canonical quest-master list + log touch-combat / bake-source / channel-merge decisions
- Track orphan-detector in repo + 'Resurrected' naming (Nathan-approved)

## v0.0.28-P2581

- Oversized windows can pan + grab raises window to front
- Tutorial aggro-ring cue + woodsman/veil beat ordering (Nathan 07-20 QA)
- Tiered gate - narrow full-suite escalation to what needs it

## v0.0.28-P2578

- Edit-mode QA — grip/popover follow resize, popover flips up, skinny persists, big-map area toggle
- Save-loss defense in depth — last-good generation, recovery ladder, pre-migration snapshots, web storage persistence

## v0.0.28-P2576

- Bridge vagabond gate + scripted first-death lesson

Behind the scenes:
- Interim build - story bridge/death data layer + latest main for morning QA

## v0.0.28-P2574

- Corner-resize shrinks the font past the text floor
- Create_vale falls back to procedural bake source when vale_map.tscn nulls

## v0.0.28-P2572

- Android QA pass — glyph tofu, settings dock, map labels, fade, fog gray
- Nightly box-suite robust seeded import + vale-draft test isolation
- The Vale's 12 named areas live - approved partition attached
- Unseen-item "!" badges - loot marks unseen, viewing clears

## v0.0.28-P2567

- Occlusion refactor - tool gates drop the veil, barrier faces go sight-opaque

Behind the scenes:
- Web is a release platform — the web game compiles in build-publish from the release commit

## v0.0.28-P2565

- Edit Mode PR2 - snapping + grid + Nathan's default layout + Reset
- Pre-push gate gdUnit step is tiered - impacted selection, same escalations as CI (-FullSuite to force)

Behind the scenes:
- Interim - HUD Edit Mode complete for device QA
- Daily-brief CI analytics snapshot + Zapier/narration corrections

## v0.0.28-P2561

- Autosave toast on every surface + cross-milestone reload change note
- Edit Mode PR1 - Play/Customize gate, drag-anywhere, Lock retired
- Strip baked-in contact-sheet numbers from shipped plates + flag imageless beats
- Iter5 - touch-size resize corner, finer minimap zoom + steady centering, dbl-click big map + modal gear
- Log north + wolf-den pack + barrier modals + 1-yield nodes + vale-enter fix
- Tiered test gate - impacted selection on PRs, full suite nightly + release gate
- Await the patch pack at web boot (the P2460 update loop); save-stamp QA authority; Switch Fortress + update-recovery policy

Behind the scenes:
- Auto-promote 13 rendered plate(s) - mason_after_boulder, mason_boulder_cleared, mason_joined_fort, mason_quarry_intro, mason_sharp_pick, thresher_after_hedge, thresher_bramble_cleared, thresher_field_intro, thresher_hedge_cleared, thresher_joined_fort, thresher_sharp_scythe, woodsman_after_tree, woodsman_first_seen
- Auto-promote 1 rendered plate(s) - rescue_freed
- Daily brief carries Nathan's queue (needs-nathan label)
- Daily brief nags stalled handoff-labeled issues - the prosthetic-memory loop closes cross-lane obligations

## v0.0.28-P2550

- Tall-phone surface reaches the true bottom + drag top-bar floor + web text bridge emits text_changed
- Stop the Librarian rescue from queuing a duplicate generic freed modal
- THE GOLDEN SAVE CONTRACT — production saves are never invalidated

Behind the scenes:
- Interim - android HUD fixes for device QA

## v0.0.28-P2545

- THE SIGHT-COST MODEL — terrain stretches and shrinks the sight bubble (v0.0.28-wip)
- Enforce ONE PLAYABLE VERSION at the web publish choke point

## v0.0.28-P2543

- QA5 — mobile-safe fog shader noise + snapshot spawn-ids on the expanded map + roster-aware capture driver
- GdUnit suite cap 15->25 min + phase0 envelope 60 (cap-kills over real failures)

## v0.0.28-P2541

- Windowing iteration 3 (opaque fog, big-map rework, scaled resize, two-section Options) — crash-fixed

Behind the scenes:
- Interim — HUD windowing iter3 (opaque fog, big-map rework, scaled resize grip, two-section Options, leak fix)

## v0.0.28-P2539

- QA4 — water is sight-transparent + reveal radius 14 (v0.0.28-wip)
- Mason + Thresher quest beat outlines

## v0.0.28-P2537

- QA3 — the Woodsman HARD-blocks the west walk; the NORTH tree returns (two trees) + build
- Resource sampler reads the real CPU counter, not LoadPercentage

Behind the scenes:
- GdUnit pool baseline to 3 + timeout headroom; analytics govern scaling (Nathan, 2026-07-18)
- Content-pipeline entry-point rule (new quest work starts with Story)
- Content pipeline (Story to Painter to Maps) + published-docs list

## v0.0.28-P2532

- Expanded-Vale QA1+2 — data-driven story triggers, deeper fog, Woodsman #3376 wiring, north-tree gate cut + build
- CI-throughput chart + narrated insights (queue-vs-work on the gdunit gate)
- Monotonic update offers, session-only banner, portrait splash manifest (round 6)

Behind the scenes:
- In-run resource telemetry - the analytics name the binding constraint (CPU vs RAM) per concurrency level
- GdUnit gate → pool of 2 concurrent suites + concurrency-headroom analytics
- IsolateUserDir - per-run user:// isolation for gdUnit suites (the 2x-concurrency unblocker, #3381)
- Run-gdunit-headless gains -SkipWarmup / -SlotWaitMinutes / -FailIfNoSlot (defaults unchanged)

## v0.0.28-P2525

- Woodsman-first gate beats + drop stale library_discovery beat

Behind the scenes:
- Interim build — THE EXPANDED VALE live (v0.0.28-wip)

## v0.0.28-P2522

- Librarian quest art (locked-face re-renders) + ballista + one build
- Expanded-Vale v5 — straight roads + content placement (mobs/resources/rings)
- Reframe fortress-enter modal as 'end your journey'
- Expanded-Vale draft v4 — wood-entry restructure + alpha pinch

Behind the scenes:
- Fix stale Library-unlock gate descriptions in popup-audit

## v0.0.28-P2517

- The static light door can't crash — stop the died-young false positives

Behind the scenes:
- Race-proof interim-build trigger - per-lane trigger files replace version/code counter bumps
- Interim QA build (code 59) - playtest tutorial fight + Librarian quest + death modal

## v0.0.28-P2514

- Roster round 4 — standard save-screen UX, typed-DELETE modal, segmented Regular|QA; NameEntryScreen retired (release)
- Ship Nathan's picks — distinct story plates + rotating death art
- Expanded-Vale draft v3 — fog pull-back + Nathan's v3 layout notes
- Publish NPC Dossier to #about + weekly hash-gated art-doc regen
- Instrument the native shutdown path for the #3169 Windows clean-marker test
- Rat immune to fists, even 1-dmg trade — win with HP intact
- Expanded-Vale draft v2 — Nathan's layout notes + bridge/blockade marks + fogged preview
- NPC dossier — canonical portrait references locked (Nathan's picks)

Behind the scenes:
- Trigger the round-4 release — version/code 57->58
- Move About-docs regen check weekly to nightly
- Retire the usage-charts card from #about — Daily-Brief-only (Nathan)

## v0.0.28-P2503

- Windowing iteration 2 — movement guard, popover clamp, chip removal, coords-on-minimap, skinny rework
- Incremental gear-doll refresh — reuse the silhouette, kill the per-equip texture burst
- Expanded-Vale layout DRAFT (#3334) — preview-only generator + guards
- Library unlocks at the blueprint (in-town), not the field rescue
- Script_errors skips synthetic/gate-test JS errors
- 07-18 QA batch — overlay toggle matrix, fog-gated rings, stone-respawn fix, tree clarity, geography borders
- Healthy-session perf baseline + JS-error aggregate + launch privacy notice

Behind the scenes:
- Interim — HUD windowing iter2 (movement guard, popover clamp, chip removal, coords-on-minimap, skinny rework)

## v0.0.28-P2495

- Windowing polish (Area rename, Size+Font, three-line resize grip) + Skinny mode

Behind the scenes:
- Interim — HUD windowing polish + Skinny mode (Area rename, Size+Font gear, three-line resize grip, skinny toggle)
- Approved craftsman self-task flows + wandering archer + Warrior-before-Archer + map-progression note
- Add a Usage header for the charts in the Technical review

## v0.0.28-P2491

- Roster round 3 — create-not-start, actions below list, visible QA toggle, level/played/time cards, Switch Fortress, playtime
- Fold crash analysis into Daily Brief
- Make the Player Documents post text-free — just the PDFs, no bullets
- Footsteps way sparser + quieter (Nathan: "too many and too loud")

Behind the scenes:
- Bigger popup images + Woodsman P2 / Mason / Thresher flows + Librarian unlock correction

## v0.0.28-P2486

- Roster QA round 2 — select/Load/Delete, character naming, 3 slots, session lock, explore persistence; launcher = one Start button (1.1.58)

Behind the scenes:
- Charts-only for token usage - drop the 80% prose exception + record HUD windowing on roadmap
- Add in-game 'Report a bug' button to Placeholder (v24)

## v0.0.28-P2483

- Mute-at-boot actually mutes, version display in sync, door cleanup
- Session_ms/save_kb + freeze detection in crash beacon
- Wire batch-3 beds — combat swap, arena/hut, hooves + mgmt single bed

Behind the scenes:
- Interim build — audio wired (SFX batch-2 + music beds + hooves + summaries, v0.0.28)

## v0.0.28-P2479

- Overnight close-out — library/retreat plates, wood/stone currency, forge/treasury launcher

Behind the scenes:
- Interim build — overnight art close-out (library/retreat/currency/launcher, v0.0.28)

## v0.0.28-P2477

- Actions window + visible resize-corner grip — windowing completion

Behind the scenes:
- Interim — HUD windowing complete (all 6 windows + Actions + visible resize grip)

## v0.0.28-P2475

- Organic area partition — terrain-grown zones + smoothed state-map borders

Behind the scenes:
- Interim build — organic area partition + curved state-map borders (v0.0.28)

## v0.0.28-P2473

- Librarian quest part 2 - Perrin joins the fort, blueprint unlocks the Library
- Coordinates window (Explore-only), retire minimap inline coords — windowing PR6/6
- Web-deploy cancel-in-progress false + lock the one-release-stream invariant
- Death modal + 50% wallet loss on explore death (gear exempt)
- Summary-bleed fix + footstep seam + sub-state bed override API

Behind the scenes:
- Interim build — Librarian quest + explore-death modal + club balance (v0.0.28)

## v0.0.28-P2467

- Batch the downscale-revert git checkout (E14 command-length failure) — epoch E15
- Tutorial_armor card art — patched-hide leggings (Nathan's Codex pick, cell 1)
- Drop texture cap 256->128px for 2GB iOS load survival — epoch E14
- Trust pass 2 — drop background reaps, add exclusions + release-health counters
- Options drawer → Windows list, retire Map/Log edge tabs — windowing PR5/6
- Suf batch-2 SFX (3 combat + 5 redos) + fold sound-coverage audit into the Daily Digest

Behind the scenes:
- Interim build — telemetry trust pass + iPad memory drop (v0.0.28)

## v0.0.28-P2460

- Unified in-game character roster replaces Continue/New-Game
- Run-control window (readout + Pause + Run Details), both modes — windowing PR4a/6
- Meadow/arena split + zone naming + state-map borders
- Librarian quest part 1 - Builder's charge, bandit-chief see/win beats, rescue flavor
- Place Suf batch-3 music (explore combat/summary, defend summary, arena)
- Character window both modes, replaces the bottom band — windowing PR3/6
- SaveManager + schema v1 + autosave + Continue entry (Stage-1 MVS)
- Map + Game Log ride the shared HUDWindow chrome — windowing PR2/6 (#3220, closes #3179)
- Register auto-promoted enc_dying_man plate + restore its mipmap flag
- Weekly audit checks About-page description sync
- Sound & Music audit page + audio credits
- HUDWindow base + HudWindowSettings persistence — windowing system PR1/6
- Static light door at the bucket root - the wasm launcher moves to /launcher/ (#3176, v1.1.56)
- Build-QA round 5 — 9-tile sight, path-gated aggro, pinned wolf '!', minimap refill rings back on
- Normalize four too-quiet SFX to -1 dB peak
- Modal scrim follows panel visibility - stuck gray screen after X in Explore
- F5 QA launches directly - the QA sub-screen is retired, dev tools become board buttons
- F5 board fills the window - expanding art + notes, no dead space (#3215 stage A polish)
- Party-slot fill/clear cheats - mirror the sentry pair
- Honest download-progress phases - verifying cached data vs downloading the update (v1.1.55)
- Every snapshot reveals full fog + steeper gear ramp
- #about fully carded - title-only cards, all content in threads, charts card added
- World / Explore panel section - fog, rescues, waves, beats, spawns
- The Modularity Pass - one engine, one source for every shared piece
- ONE-board F5 entry — GameEntryBoard + CheatManager session QA flag (#3215 stage A)
- Snapshots grant opening items + pre-mark opening story beats
- Releases sync skips Discord's thread-starter system message
- Versioned release notes in About - card + collapsible thread per version; roadmap goes future-only
- Snapshots land arc-coherent world state
- Round 4 — respawns, alpha wolf, glen packs, aggro tuning, NE-corner camp + interim build
- Slice 7 tier-1 — minimap fog authority, transparency overhaul, grip=move, log toggle removal, title bars, scrim unify
- Web completion notice mirrors desktop + settled Game row says 'current' (v1.1.54)
- Usage-poll backs off on 429 instead of hammering every 5 min
- Web Launcher row says 'current' like desktop, not the platform tag (v1.1.53)
- Slice 6 — Nathan 07-16 QA batch: pulses removed, big-map polish, Esc, handle trio + Log, draggable log, popup layer
- Nathan-approved batch — remove Ike banner, probe parked-tab fix, revert iOS redirect — epoch E13
- Log→ring road corridor + Warrior's hut/track restored + unreachable-grass fill (Nathan-approved layout)
- Correct the #3151 auto-promotion to Nathan's curated picks + wire the milestone art ids
- Mute launcher-surface load-stalled — false positive from parked tabs
- Download copy states facts, no promises (v1.1.52)
- Split beast-falls from armor-equip tutorial + aggro-ring marker
- Capacity router treats a failed poll as unknown, not 100% headroom
- Quarry ovals in every set, fields/quarry on the minimap, fog survives Fortress round-trips
- Digest bot-posting override attaches real files via multipart; usage-poll keeps lastGood across consecutive failed polls
- IOS Play goes straight to the game — the launcher wasm front door kills low-memory iPads
- The world never visibly ends — off-map is an endless cloudbank
- Download/load-phase dead-man in the probe + epoch E12
- Encounter/discovery dialogs match the tutorial card width
- Raw-token chart tells the TRUE divergence story + permanent day-store
- Trust pass — silent-end risk gate, dead-man dedupe order, handoff-lost mute
- #2914 — keyboard focus defense: reclaim engine-stolen blur, suppress canvas refocus while typing
- Update size story as its own yellow board line + same-build deploys no longer false-offer (v1.1.51)
- Crash-lane half of #3145 — LAUNCHER-ERROR relay rendering + web-handoff watchdog
- Complete the #3151 cutscene promotion — POPUP_ART wiring, sibling import flags, testing-source cleanup
- Raw-token loader accepts BOM'd ccusage JSON
- Raw-token history in the daily pipeline - accounts, models, cache split
- Failure telemetry (#3145) + full-vs-incremental update hint + publish-lookup hardening (v1.1.50)
- Alerts get art + match tutorial card, encounter dialogs get a fixed width
- First click on the active speaker starts the music, not mutes it + named Windows audio identity (v1.1.49)
- Load-crash probe on both web surfaces + divergence breadcrumb — epoch E11
- Epoch E2->E3 — #3102 autoload rename broke patched installs (#3126) + CI autoload-epoch guard + interim build bump
- Cap bumps draw as raised allowance, never as usage shrinking
- Token charts v3 - Actions format (bars + sawtooths + allowance bumps)
- Weekly docs auto-regen - fire the About-docs pipeline only on doc-source change
- Fog QA round 2 — deeper wall sight, ruins fog-gated, rings warn from the fog, generic interior walls, visible Woodsman
- Render charts independently - token first, Actions best-effort
- Phone content-scale parity + mute button clears divider + honest web mute memory (v1.1.48)
- Honest copy for the launcher-web flow — no more 'no download' promise
- Token chart v2 - overage dollars panel + phone-readable type
- Compress the split art-audit PDFs for the About post
- Split the art audit into Icon+Building and Gear+Loot documents
- Design-language slice 5 — big-map zoom rail + always-visible settings, Defend chip 3 lines, labeled Map/Options handles
- Billing-chart-render PS5.1 parse error - ASCII-only strings
- Token-usage chart on the daily brief + Codex offload committed to roadmap
- #3116 hardening — mode-aware resize poll, unconditional content-scale re-poke, divergence telemetry
- Add the popup/cutscene art audit PDF to the Player Documents post
- Unify modal formats + hard-modal popups
- World fog = true line-of-sight — you see only what you've seen
- Mute audio/persist/icon + distinct tab + interim release to sync versions
- Stop the vision sync from deleting the About "Player Documents" post
- Enclosed cottage interiors + Woodsman's cottage + mockup-look fields
- Mute — pref-based icon (fixes desktop first-click), bigger icon, web autoplay, v1.1.46
- Release-driven sync — web game builds only on release, web launcher on launcher change
- Show deployed launcher + game version in the site footer
- Run the launcher on web — launcher-web front door + game at /play/ (+ live-QA fixes)
- Dead-man switch — a silent kill reports at DEATH time, no reopen needed
- Design-language slice 4 — alert pulse, expand glyph, band material, one stat-row shape, minimap routing, Explore low-HP parity
- Honest memory-growth escalation — settle window + growth floor, one shared rule
- First-light fog shows only the wake clearing + procedural log gate graphic (3-gate airtight pass)
- Crash beacon covers ALL platforms — native next-boot lane + rename to CrashBeacon
- Classify iOS background-reap as bg-reap instead of a clean exit
- A desktop window close no longer reports as a crash
- Launch label reads 'Starting' for a cached build, and names the QA build
- Equip !-marker trail + live-QA batch (log choice, labels, gather cards, no-flash repair)
- Idle-queue nudge clears on observe + softer dot (Nathan QA)
- Design-language slice 3 — Log window chrome, minimap drag grips, Defend chip alert
- Re-integrate web-only texture downscale (Ike iPad equip crash)
- Defend-mode combat cues + audio-asset housekeeping
- Land Nathan's two door paintings (cottage v4 + arena v4)
- Full-history checkout in web-deploy so the baked version is real
- Tree-gate cards — tree_found (Nathan v3) + tree_chopped (reference art)
- QA flag now takes — return a string from JavaScriptBridge.eval, not a bool
- Unify to ONE web build with a runtime QA toggle (download to choose to start)
- Fog of war reads as a real cloudbank (tileable cloud texture)
- Wire the committed encounter art that shipped as ? placeholders
- Pre-fill random tower name + never swallow keys on the naming input page
- Misty fog look, all-open-past-the-log, visible log, wolves further north
- Loading bar reads "Downloading" from t=0 (QA looked stuck)
- Minimap settings on the expanded map (slice 2b)
- Tree find/chop beats + a door painting per door + timing fixes
- No ring on the tutorial rat, ring drops on aggro, swing only on a hit
- Full-map build pass — quarry/fields/bandits/vale-ring/river + procedural markers
- Expanded map is a navigable window — pan + wheel-zoom + title bar (slice 2a)
- Woodsman's-axe trade — 10 wood for his old axe
- Design-language surface material — chip differentiation + zoom centering (slice 1)
- Wire level_up + milestone cues to their triggers
- Wire tutorial_equip + tutorial_combat card plates
- Suf's SFX batch 1 — event + combat cues live, nature ambient
- Reveal-all-fog cheat reveals the whole Explore map (fog + movement + confinement)
- Phase B card badges — 'now affordable' dot on picker cards
- Bit 1 below-log — roamable Builder's Wood, aggro rings, harvested-node fix
- Show the played build as the version, kill the release-feed flash
- Remove VO placeholder chip + harden Defend-report Escape dismiss
- Phase B mode-button badges cascade from tab badges
- Wire tutorial_spawn + fortress_repaired to their approved plates
- Real byte-progress loading bar on the web shell
- Bake derived SUB_PATCH into the web game export
- Cinzel/Crimson font parity across launcher + web loading shell
- Restore canonical VRAM/mipmap import profile on 7 cutscenes + drop orphaned drafts
- Promote Nathan's picks for the 5 opening encounters (override auto-v1)
- Drag loot to a slot to equip (native drag-drop)
- Hide the chooser while loading — kills the mobile caption overlap
- Minimap "Coordinates" toggle
- Land opening-flow encounter art ids in code + re-map 2 mis-placements
- Top-right mute toggle + persisted mute preference (v1.1.43)
- Touch-drag scrolls clickable lists (scroll_deadzone)
- Defer the engine boot until the player picks a build (no double-load)
- Minimap settings popup stays put on resize
- Loading-screen music + top-right mute toggle (mirrors the launcher)
- Solid framed bottom band + red health
- Shell polish + epoch bump — version stamp, honest load copy, P473 fix
- Rename log to "Log", drop Clear, add expand
- Color the Vale TileSet in-editor via committed palette PNG
- Windows self-heal — trust-on-first-use exe integrity check
- One-click QA/Regular — carry play intent across the build switch
- Retry button on the Defend battle report
- Explore map is now a native editable Godot scene (TileMapLayer + nodes)
- VRAM-compress all remaining lossless textures + promote 4 storyline cutscenes + record compression policy
- Draggable minimap, position persisted per mode
- Give the tip its own bordered card so it stops blending into notes
- Label the loading states clearly (checking vs loading vs ready)
- Per-mode persistent minimap + game-view zoom
- Wave Details is Defend-only, removed from Explore
- Downscale loot roster 1024->256 (iPad memory crash, Nathan 07-14)
- Cutscene banner scales up on widescreen
- Log lines for currency + resource pickups
- Hash-based Validate — verify installed files by SHA-256
- Promote 8 storyline paintings (heroes, encounters, duels)
- Shift/Alt/Windows/Ctrl don't advance a cutscene
- Brotli the wasm + js on deploy (37.7MB wasm to 6.3MB transfer)
- Route @claude cloud lane by capacity
- Phase0 skips the Godot suite on infra-only PRs (test-suite serialization #1)
- Daily orphan-process reaper (#4 cleanup)
- Billing-chart render as a box task (replaces the Daily box render cloud Routine)
- Mirror the launcher's Validate + Update on the web entry shell
- Shared entry-screen layout definition — one source, launcher + web render from it
- Route @vzqz box dispatch lane through the capacity router (lane 3)
- Canonical import profile + registry rows for auto-promoted cutscenes
- Box digest tasks replace the paused cloud Routines (lane 2)
- Route ChatHarvest through the capacity router (lane 1)
- Auto-promote cloud-rendered cutscene art to production
- Zoom +/- on the minimap face
- Promote 3 world-encounter paintings (beast, caged ranger, craftsman)
- Always-visible zoom +/- rail on the right edge
- Mirror the PC launcher pre-play screen (QA/Regular chooser)
- Sword-swing on attack + fortress-exterior re-entry spawn (P2180 F5)
- Promote woodsman's axe + mining pickaxe paintings (nanobanana seed-edit)
- Experience, loot, and regen lines in the combat log
- Confine mobs behind unbroken fog barriers (P2180 F5)
- Timestamp under each release-notes header (launcher 1.1.39)
- Health-only bottom band, kills/time to the corner chip
- _kill_tween crash on removed tween meta (Godot 4 set_meta null)
- Bank 4 approved later-beat cutscene paintings (first_death, library_built, forge_built, throne_built)
- Drawer + minimap handle chevrons as SVG icons (web tofu #2912)
- Split the spawn-dots tip into its own beat
- Vale world-fog rework + set-swap/persistence fixes (P2164 F5)
- Loading shell = the launcher v2 board (Game row + notes header + timestamps)
- First-three-wolves '!' markers flash until dead
- Promote tutorial_equip (dying-man) + sharp woodsman's axe painting
- Re-baseline epoch E4 so audio+QA fixes reach the client
- Bigger cutscene still + 'The Wild' waits for a step + spawn message reword
- Play Free goes straight to the game, not the chooser
- Compress 5 live tracks to Ogg (19MB to 11.8MB, masters kept)
- Game window born on the saved monitor (kills the left-monitor pop-up) + boot splash
- Unship 16.6MB of superseded tracks (masters/ + .gdignore)
- QA web build = prod (release delta), not a debug monolith
- One-map Vale — lock-gated section fog + staged gated opening (Nathan-approved layout)
- Suspend player regen during the tutorial beast fight
- Tighten interaction proximity to near-touch
- Cutscene stills at one fixed aspect ratio + drop the VO chip's stray placeholder image
- Region-unlock quest weapons — woodsman's axe, sharp woodsman's axe, mining pick
- Nathan's 6 refinements — no title, opaque surround, no fog/spawn toggles, deeper zoom, center-tap modal, left-edge handle
- Phase0 duration-creep alarm in the daily self-check
- Validate as a board row + epoch-aware detection (1.1.38)
- Flashing '!' marker over the beast during the tutorial
- Storybook rat + tree/rock variants + calmer water + lusher tree3
- Promote 3 Critical Path cutscene paintings (fortress_named, tutorial_combat, tutorial_aggro)
- Slot-cap Godot CI suites at 3 + gh-free advisory comment poster
- Crash beacons use text/plain so cross-origin sendBeacon isn't dropped
- Re-baseline game epoch E1 to E2 — fixes NotificationBus autoload crash
- Player-docs line points to the About post, not deleted #spam-updates
- Beast-spotted intro + how-to-fight ordering + equip benefit
- Clear one-time progression-message flags + bump Android code 24 for QA build
- Reusable imperative alert primitive in AlertState
- First Critical Path cutscene paintings — wake + tower-ruin
- Validate + Open-game-folder buttons, hyperlink notes (1.1.37)
- Modal scrim behind the cheat panel (kills click-through)
- Minimap spawn-dot respawn state — ring shrinks/flashes to respawn
- Drop autoload-signal leak on mode exit + memory-walk harness
- Compile Pages Functions in deploy + working crash relay
- Launcher self-update renders in the board frame (1.1.36)
- Installer registration + ASCII-only (PS 5.1 box compat)
- FITS filter defaults to none; empty/locked slots use committed icons (no emoji)
- Warm the Cottage interior — hearth/workbench/props, drop the boulder ring
- Vale ground loot persists across cottage/arena swaps — only respawns on fortress re-entry
- Fortress body — mobs stand off at and hit from the outer edge
- Tutorial timing + aggro tip + cottage text + vale-on-cottage
- Make the Giant Rat visible in painterly + re-roll minimal fighter
- World-art buttons fit + tappable on mobile; add a third 'Save' (persist, no exit)
- Fire the Vale-reveal beat at the Vale mouth, not the fortress
- Equip-gated tutorial — nothing auto-equips, real beast fight (F5)
- Combat log — shared drawer tab, damage in/out + kills, both modes
- Fighter-duelist + stone-hut sprites (recovered) — wire into all 3 sets
- Open on the overview + never hide the nav column (icon rail worst case)
- Minimap hoisted to shared CombatHud; drawer+minimap default hidden with reachable toggles; size grows footprint — Explore/Defend parity
- Generalized per-cue sample loader — Suf foley goes live at the slot
- Lower player anchor so less void shows below (F5)
- Reserve image + voiceover placeholder slots on narrative/story/tutorial/encounter modals
- IPad keyboard — bridge follows the shell SubViewport (focus + rect transform)
- Builder's stone hut + cottage mini-zone (arena pattern)
- Self-update-check retry + rate-limit clarity (1.1.35)
- Per-NPC encounter frame — Builder convinces, not captive
- Multi-currency cost chips wrap instead of forcing the card wide — Forge picker overflow
- Re-land 1.1.34 batch — QA-direct + board polish + download info
- Single mobile texture format + load-crash beacon + epoch E3
- Real tutorial dialogue + encounter re-arm (no proximity spam)
- Edge-to-edge attack reach + cornered shove; Android code 13
- Split minimap into independent map display + settings popup
- Minimap panel wraps its controls (force viewport size) + build code 11
- VRAM-compress terrain/building art + re-baseline epoch — iPad load crash
- Tutorial 2-room/2-door redesign + readable minimap + void backdrop (interim build code 10)
- Drop heavy terrain + entry art from web build — iPad load crash
- Mode bar + rail drop to icons when labels don't fit — phase 3b
- Guaranteed Enhancement slot per tab — phase 2 of the unified scaling system
- Re-layout on single-axis window EXPANSION — poll the window size
- Dock minimap to the left edge so it actually renders (+ build code 9)
- Folding minimap + map-only fog + spawn-point toggles
- Tutorial opening as two sealed rooms + Giant Rat (F5)
- Tutorial modal format (Format B) + equip/combat tutorial beats
- Flow-field enemy pathing + hard body collision
- Memory/crash beacon + Ike popup + Discord relay
- V2 block-model window - merged build+action status board (1.1.33)
- Scripted tutorial opening on the Approach + enemy-ring standoff fix
- TEMPORARY equip-access button — character gear overlay for the equipping tutorial
- Live form-factor + top-bar fit ladder — phase 1 of the unified scaling system (#2186 #2757)
- Say 'Launcher is current.' + kill the boot window flash (1.1.32)
- Unbuilt cards show 0/1 build axis, not 0/9
- Routine must NEVER self-render the Actions chart — it hangs the digest
- Save & Exit fully exits the gear overlay
- Palette sync reads the shared entry source (entry_palette.gd)
- Sectioned navigation + Save & Exit (N9)
- Mobs/spawns/rat + building yield + Minimal default/icons/borders + live art swap
- Phase B badge vocabulary — colored dot/!/count/glow on tabs (slice 1)
- Column auto-compression on navigation (round-4 N1)
- ONE shared entry source — launcher / F5 / in-game notes / web unified, copies deleted (launcher 1.1.31)
- Duel arena + map swap, amorphous Vale + SW tendril, per-map respawn, per-mob aggro
- One right-edge cluster — zoom row inside the drawer, explore wave details (round 5)
- Wire Crown of Ashes victory sting (Fighter-duel win) + Forge of Quiet Hands management rotation
- Suf mode beds — Wandering Vale (explore) + Broken Gate March (defend); reserve Crown of Ashes + Forge of Quiet Hands
- Suf's "Ashen Keep" management theme + audio contribution manifest
- Fighter duel + encounter gates on build order (#2714 rebased onto Slice A)
- Phase C queue-idle condition-badges
- Walking sprites + enemy separation + Minimal flat art set
- Opening cutscene beat system + per-captive rescue flavor (Slice A)
- World Art toggle joins the pending/apply model + clearer label
- Multi-open category accordion + compact-view collapse (N2)
- D-57 wired — the Throne needs the rescued Fighter
- Toggleable world art sets + the Storybook (Tiny Swords) set
- Hall/Armory/Guardhouse desktop splits — roster cards right, Skills left
- Sampled resource pickup, brighter explore music, no mgmt ambient
- Combat HUD round 3 — side drawer, retreat confirm, wave chip, bottom info strip
- QA round 2 — builder captive, richer rescue gates, map reads
- Rescue NPCs — D-61 shipped
- Pre-play placeholders (Login/Resume/Switch) + phone-fit loading card
- Fortress grows with progression — 5-tier world-sprite ladder
- Approach carries EXACTLY the repair cost, spurs mandatory
- World-logic map pass + FreeStylized pro terrain textures
- Doll slots wear their real gear icons + names; only level-locks remain
- Coming Soon split for gathering + discovery tabs; mode-agnostic split probe (R12/R13)
- Corner plate replaces the top band + vertical pop-out button stack, distinct Run Stats/Attributes, zoom MAX/MIN, real icons
- Wake battlefield scene + the tail stays walkable
- Re-click cycles all three buildings widths; picker icons constant 48px (R9/R14)
- Master control + inline mute, battle march, resource/gear cues
- Announce after availability, gated on real version change
- CHEAT anchors the right cluster + pink 1x/5x/10x speed cheats
- Split watermark into Show Version / Show Performance + fix flaky perf render
- Name leads the detail modal + no double wallet in pickers
- Auto-refresh the launcher release's feed position every publish
- The Approach tail + claim-reveal — one map, two phases
- Two-section notes so every release matches the roadmap
- Looping CC0 theme music while the launcher is open
- Self-update by-tag fetch (#2628) + no off-spot splash + zoomed art
- CHEAT far-left, collapsed wallet, boxed wallet + equal box heights, optional fortress chip
- Music-by-context + sparse ambient one-shot scheduler
- Grittier Diablo-verdant terrain textures (water/grass/dirt)
- Pin moves right beside the close X, entity icon takes its old top-left spot
- Clickable identity chips + fortress/hero modals, boxed chrome, download slot
- Restore single-open accordion in the building picker
- Developer toggle to show/hide the QA perf-overlay
- Pop-ups clear the top bar + on-map zoom controls
- Loading-screen parity — building art, Current/Available build, file names
- Music + ambient beds, 3-channel settings, placeholder voice (free CC0)
- The Vale — new home map replacing Verdant Plains
- Hero names on startup + web version-sync + launcher window-spot fix
- Pure-ASCII loading shell (encoding-proof) + palette from launcher
- Launcher-mirror web loading shell + bottom-left watermark unify
- Unify explore/defend onto DesktopTopBar + fix HUD menu dismiss trap
- NotificationBus — one-bucket feedback seam (Phase A)
- Shared CombatHud shell + ExploreHud/DefendHud per battle-v3 §4/§5
- Split view for every COMMAND tab — fortress, party, defense Coming Soon
- Entity art pass — WorldArtSet table + painterly nodes/fortress/mobs/rescue
- Memwatch v2 — color escalation, GL-lost black box, fps
- Round 5 — one selected look, re-click width grammar, tap-anywhere slots, adaptive picker columns
- Doll slot grid — 5-column non-overlapping layout, bigger slots
- Swap confirmation missing on builder track-card swaps
- Live memory readout on the QA watermark — #2577 growth diagnostic
- Delta deploy hardening - EAP guard on native calls + R2 base liveness check
- DELTA DOWNLOADS - epoch base + KB patch replaces the 55MB per-release monolith
- Pin-aware auto-collapse + one slot highlight (QA round 4)
- Update detection survives background-tab throttling — 3s boot check + focus-return poll
- Never trust GitHub feed order — sort by numeric version+stamp (launcher 1.1.27)
- Heroes show locked pre-Throne (never hidden) + one recruit-gate source for UI and queue
- Banner on-brand + "Not now" minimizes to an Update chip
- Global click-sound auto-wire + composite tappables + builder swap confirm
- Shader-blended ground — organic terrain borders, diagonals read as diagonals
- Round 3 — desktop split view, bigger slots, square image-first loot tiles
- Banner strip renders solid + above HUD — CanvasLayer 150, deferred height snap
- IPad keyboard bridge — detect touch via maxTouchPoints (covers Chrome + trackpad iPads)
- Recruit/craft/research picker refreshes live — stale lock state after level-up (Nathan QA, Barracks 5)
- Tier widths are STICKY — clicks never resize the rail or buildings column
- ONE build-stamp convention — F5 derives the same P&lt;commit count&gt; as releases
- Watercolor seamless ground + organic map + wallet icon chips in both HUDs
- IPad keyboard — visible HTML input receives the tap directly; + Eleanor/Indiana hero names
- Gold target border shows which slot the pane will fill
- Update banner shows version X to Y + "your run will be restarted" wording
- Management-GUI tactile feedback — action-class SFX, shared press hook, Settings Audio
- Update banner renders correctly — viewport mount, no self-anchor, Not now dismiss
- Permanent wallet icon — desktop expand/collapse toggle, currencies open the modal
- Inspection pane is ALWAYS on for queue makers
- IPad text-input bridge — route iOS keystrokes into LineEdit fields (P467)
- Derived build stamp - P<commit count> at build time + build queue
- Unified top row — one bar on both form factors, adaptive wallet + modal, card off Equipment
- Barracks 5 levels — every level unlocks a unit type (L4 Fighter, L5 Archer)
- Tilemap terrain rounds 1+2 — painterly ground + 2.5D tree/rock sprites, ASCII world killed
- Queue-slot picker becomes the right inspection pane (queue-tier spec)
- SubToggle — style-A sub-view switch, shared with the mode bar
- "new version ready" update banner — build-id beacon + web-only notifier
- Cap heavy-art import resolution at 512 — iPad Safari still hit the WebGL ceiling post-compression

Behind the scenes:
- Interim build — push unified roster to all surfaces (v0.0.28, base-E4)
- Gnarled club to 1 damage (match other starters; equipped-clamp still guarantees the tutorial win)
- Flag Equip/Armed/Builder beats as needing new art so Painterly sees them
- Regen gloves + gauntlets via Codex — real open fingers, no more mangling
- 3-layer format (arc index to arc flows to detailed renders); split Intro/Builder/Woodsman/Librarian/Archer + deferred Mason/Thresher/Warrior
- DECISIONS - snapshot coherence + systematic cheat coverage + scrim-follows-visibility
- Auto-promote 1 rendered plate(s) - enc_dying_man
- Fallen Soldier shows the club-in-hand plate
- Reassign Forge->huts, cutscene decision, SFX redo list
- Number popups 1-65 for reference
- Tutorial_armor prompt + rework-fence (new story blank)
- QA characters + per-character save model (Nathan, 2026-07-17)
- Web is sign-in only - Nathan's override of the auto-minted web guest design
- Backend refinements - checkpoints, time envelope, cap/leash dial, web has no local-only mode
- Fold What's-in-the-game into the v0 to v0.0.27 card - one cumulative release card
- Daily brief attaches the Codex/ChatGPT usage chart (box-rendered, same branch mechanics)
- Open v0.0.28 - VERSION to 0.0.28, CLAUDE.md milestone to stat wiring and inspections
- Backend vendor doc - trail mechanics + fabrication-resistance explainer (ledger not snapshot, era split, perfect-play envelope)
- Backend vendor doc - replace generous reconciliation with bounded replay-verified admission (Nathan's integrity correction)
- Backend vendor doc - lazy-creation practice section (server-witnessed rule, feature map, milestone nudges, test-save/no-redo framing)
- ZERO green on the roadmap - every done item sweeps into the v0.0.27 release; intro reads v0.0.28
- 6-arc structure - fold Builder+Woodsman into Opening, merge library chain into Librarian, reorder
- Ratify D-50 - PlayFab backend + lazy server-account creation (Nathan, 2026-07-17)
- Clearer summary-track prompts + swap-never-stack rule
- Batch-3 music slots finalized with Nathan (5 tracks)
- Restructure by arc - primer + arc index + per-character sections
- Music-context coverage audit + proposed batch-3 music slots
- V0.0.27 modularity checklist complete - mark the last two lock items done
- Lock/unlock through ONE evaluator - derived building unlock, shared reason lists (#2564 #1387 #2418)
- One active play session per logged-in account - multi-instance duping resolved at the account layer, not now (Nathan 2026-07-17)
- Backend vendor decision doc v1 - research summary + PlayFab-primary recommendation, awaiting ratification
- Week of 2026-07-17 — 4 ideas, 1 decision flag, 1 status update
- Interim build - HUD slice 6 + keyboard-focus fix for Nathan's Launcher QA
- Make the VERIFY-SUMMARY block REQUIRED on game-code PRs
- Charts are displayed, not narrated + stop the daily backup false-alarm
- Mark shared maker-row builder item done, refine lock-reason line
- Route Barracks/Forge rows through shared row builder
- Re-capture encounter/rescue popups at the #3170 width fix + add missing discovery panel + surface library-unlock chain
- Add a "discovery" kind to the popup capture harness
- Self-check catches silent harvest deaths; fold deployed-ahead drift into repo
- ONE game-version source = the release feed - web bakes the release's P, never a local count + converging interim release
- Rebuild popup audit with full text + real captures
- Art-pool coverage count + startup-hints catalog
- Interim QA release — puts a fresh game version on the feed so the new full-vs-incremental update hint shows live (v1.1.50 QA)
- Re-fire interim build - publish step of run 29541069884 lost to the GitHub API outage (artifacts built clean incl. E3 epoch; no code change)
- Popup-aware capture harness for the full popup audit rebuild
- Auto-promote 7 rendered plate(s) - enc_stone, enc_straw, forge_discovery, library_discovery, rescue_freed, retreat_unlocked, throne_transition
- Hygiene batch D — delete dead loading-shell lane, truthful SPEC, stale refs
- Roadmap - add vision range skill (extends fog-of-war clear distance in Explore), v22
- Expand Sonnet model routing per Nathan's cap-conservation directive
- Central popup-art registry — one id->plate table for every popup
- Activate dead-man switch — CRASH_KV binding + epoch E9→E10
- Scope VERIFY-SUMMARY to game-code PRs + advisory block-presence check
- Capture Residence/Housing + Vale gated-opening + category lock-display design
- 7/16 brief small-fixes — launcher tip truth + cutscene release titles
- 7/16 brief tooling - drop retired SUB_PATCH check + fix moved tip-pool path
- Stop shipping ~130MB art-review boards in every build
- Epoch E8->E9 — ship beacon bg-reap fix + launch-label + false-crash fixes to live web
- 7/15 brief triage - battle-HUD spec matches #3005 (red hero bar, solid bottom band), badge vocab marked half-shipped
- Interim QA build (code 37) — tree-gate beats wired to their committed plates
- Record the Explore full-map build + fog=clouds, and the next map passes
- Commit the approved HUD design-language spec + roadmap BUILD NOTES
- Social-assist skills + waterwalking ring + assist-circle note; split Placeholder block
- Add mob inspect popup + Enemies tab (Discovery-gated later) to Placeholder
- Add assist radius for social mobs to Placeholder
- Interim QA build — HUD design-language batch
- Add foraging tool packs (side pickaxe slots via NPC quests) to Placeholder
- Web<->release version-sync drift guard + daily self-check nag
- Regenerate storyline-art-coverage — wire enc_cottage/door/road_opens/wood/woodsman
- Fold the weekly sound-coverage audit into the Weekly Digest
- Launcher<->web pre-play parity as planned work (one shared look + divergence gate)
- Auto-promote 7 rendered plate(s) - enc_cottage, enc_door, enc_road_opens, enc_wood, enc_woodsman, tutorial_combat, tutorial_equip
- Drop 2 orphaned tutorial paintings (story lane moved the art to encounters)
- Code-derived storyline art-coverage generator
- Record the native-map scene migration (#2984/#2996)
- Explore survival bonus (spoils multiplied if the hero makes it home)
- Install page — a "launcher won't open? re-download" reassurance
- Record the A/B capacity rebalance in BUILD NOTES
- Weekly mechanical art-compression check
- Chat Harvest capture (week of 2026-07-13) — staged ideas for review
- Correct dispatch/conformance/digest/Discord model for the 2026-07-14 rebalance
- Auto-promote 10 rendered plate(s) - duel_lost, duel_won, enc_arena_enter, enc_dying_man, enc_fighter, enc_fortress_enter, first_hero_archer, first_hero_fighter, first_passive_run, tutorial_spawn
- Installer for the ArtAutoPromote scheduled task
- Auto-promote 1 rendered plate(s) - fortress_repaired
- Move conformance required check to the box (headless npx + capacity router)
- Interim build code 34 — sword-swing + fortress-exterior re-entry (P2180 F5)
- Canonical cutscene/popup image registry + drift-lock test
- Interim build code 33 — mobs no longer attack from the fog (P2180 F5)
- Test-suite jam is concurrency not size — serialize/shard/harden, not cut coverage
- Refresh narrative-opening SHIPPED state — 07-14 combat-polish pass
- Interim build code 32 — P2164 Vale fog + set-swap fixes for F5
- Richer combat log tracked in Placeholder
- Move pure-utility workflows off cloud runners to the box (P1 lockdown)
- Monthly RAM price watch in the Monthly Digest ops checks
- Content-scale in root viewport (kills SubViewport) + QA build code 30
- Interim build code 29 — staged one-map Vale
- Milestone build — opening through fortress-repair for QA (version/code 27->28)
- Interim build code 27 — art variants, fixed rat, calmer water/tree3
- Repeatable sound-coverage audit + committed Suf request list
- Interim build — version/code 24->25 for device QA
- Capacity router — pick the account with the most headroom (prep, unused)
- Record cutscene painterly art pipeline + decisions
- Named resident roster + personalities, the Scout/Defense unlock, full narrative-opening design record
- Interactive-session merges may carry VERIFY-SUMMARY in the PR body
- Resident roster draft + residence increment (story lane)
- Tune spec from dry-run review + roadmap the PAT rotation
- 6-month single-chart Actions view + utf-8 gh fix
- Capture Residence/Housing + Vale gated opening + category lock display
- Weekly Chat Harvest — capture missed decisions/ideas/bugs from the week of chats
- Interim build code 23 — FITS default none, empty-slot icons (no emoji), vale loot persistence
- Interim build code 22 — cottage interior reads as a home
- Interim build code 21 — rat visibility, HUD unify, fortress hitbox
- Interim build — version/code 20->21 for device QA
- Unify Defend/Explore HUD — single-sourced shared drawer skeleton
- Interim build code 20 — settings art-buttons fit + third Save button
- Morning interim build code 19 — explore overnight batch
- Re-fire build code 18 — Windows/Android exports crashed under box load (exit -1); box now quiet
- Interim build code 17 — night HUD/nav/combat-log + iPad keyboard fix (APK + web)
- Capture the narrative-opening work + interim build for AM QA
- Weekly sound-coverage audit + Suf request batch 1
- Interim build code 15 — GUI fit-system day complete + Forge picker fix
- Interim build — version/code 13->14 for on-device QA
- Action-button + header/pill width caps — phase 3a of the unified scaling system
- Interim phone build — explore movement + tutorial rooms + minimap (Android code 8)
- Interim build — Android version/code 6->7 for on-device QA
- Shared card-width clamp + clipped-label factory — leaf pass of the unified scaling system
- N6 uniformity sweep — one factory per shape (columns, rounding, green CTAs)
- Discord-posting playbook (memory) + daily brief fetches box-rendered real billing chart
- Story-harness item - replay the storyline across all orders, verify every message (Nathan 07-12)
- B-primary/A-fallback token so a capped account can't freeze merges
- Daily-brief Actions budget chart + real per-day billing, plus fixes
- Out-of-game notifications roadmapped (v0.3, wire-ready) + Phase B/C badge contract
- One shared ModalHeader — icon-first, pin beside ✕, everywhere the grammar exists
- Pre-play screen placeholders + single-instance + concurrent-session saves
- Re-fire the changelog backfill in the two-section format
- Log the one-map Vale+Approach model — DECISIONS.md + roadmap BUILD NOTES
- Native-features audit (#2538) state in BUILD NOTES — slices 1/2/3a done, 3b deferred
- Terrain paint-then-chop research verdict in BUILD NOTES
- Record roadmap-drift backlog find + fix so the weekly reports it
- Native-first slice 3a — shared COMPACT_PILL_MIN_SIZE token
- Explore HUD cleanup — drop dup earnings ticker, zone tier, hero name; fix combat chip icons
- Native-first slice 2 — tab_base banner/teaser + header inset
- Game-design-audio-v1 — sound+notification spec + music/voice map
- CLAUDE.md tells the truth about spawn mode — same-dir (Artifact) + worktree discipline + never tree-kill live spawns
- Map-layout changes require Nathan's confirmation (process rule, 2026-07-10)
- Serialize gdUnit box-wide via Global mutex - kills the load-induced exit=-1 flake

## v0.0.27-P464

- 3x resource-node yield + faster/stronger waves (P462)

## v0.0.27-P463

- VRAM-compress heavy art + ship mobile formats — WebGL context-lost root fix
- Ike + Atticus hero names, Cobble Hill + Los Osos fortress names
- Unify own-capacity term on 'Capacity' across labs/messages/armaments (#2533, P459)
- IPad virtual keyboard + touch DPR headroom; version watermark legibility/placement
- Coordinate header cards + scale nav-bar icons (QA round 2, #2547)
- Cache-header revalidation on R2 uploads — stop re-downloading unchanged web files
- Production header — full-width Improve, art+info condensed
- Restore Tactics lab-tab hero gate + guard tab-unlock research clobber
- Roster-row pill width + class-icon adjacency — slice B

Behind the scenes:
- Remove all Discord alert posts — alerts are GitHub issues only
- Remove dead card-body builders — slice C item 8

## v0.0.27-P454

- Shell format slice A — Straw reserve / Filter styling / COMMAND tile inset
- Cost buttons render real currency icon chips — shared CostButton composite
- Gear-doll v2 — full-width doll over always-visible LOOT, modal interactions
- Remember the window's position between sessions (1.1.26)
- Pause-proof input — the desktop shell froze ALL input while paused
- Deploy-slot cap enforced + builder-gated Improve shows its lock (#2526, #2528)
- Count-card action says the action + remaining, not "Capacity"
- QA round 2 — inline wallet, natural chips, MARCH in-column, detail-click folds to icons
- Tip-truth pass 2 — remove unbuilt-content tips, grain→straw

Behind the scenes:
- Fix full web rebuild — non-fatal import seed + VERSION touch for #2537
- Web 'new version ready' banner for the browser build
- Version-touch — force full web rebuild for #2537 pause fix
- Redeploy trigger — ship the #2537 pause-input fix to the browser build
- Portable native widgets — form-factor-free, mobile-first (Nathan 2026-07-09)
- Native-first slice 1 — battle HUDs size to content, no hand-coded boxes
- Close DA-2.6 — (a)/(b) moot, (c) re-homed in DA-4.1, (d) 'Tactics Labs' verified correct
- Roadmap v13 - strike three shipped modularity items, mark two partials in progress

## v0.0.27-P448

- Game delta assets — epoch base + cumulative patch per release (phase 2c)
- Game delta-update client — download the patch, not the build (phase 2b)
- Truthful lock messages + lock-message Auditor suite
- Delta-update boot overlay — first-autoload patch mount (phase 2a)
- Restore VCAP_CLEAN (regressed by #2530) — capture-driver repo/deployed now identical
- 3-column nav — thin top bar, tri-state buildings column, pip width controls
- Built-building modals go info-complete — real ladder, Effect/Total, maxed pill preserved (#1736 superseded)
- Remember the desktop window's position, not just its monitor
- Composite unit badge — class icon + dynamic damage-type rings (#2322 iter 13)
- 1.1.24 — first real delta release + friendly patch-download label
- Progression fuzzer runs full sweep in nightly, light smoke per-PR
- Delta self-update via boot-time patch overlay (delta engine, part A)
- TYPECARD — per-type build-card/open-detail fork shape added to the modularity known set
- Archive-sync covers cse-less pins; tombstone+skip by cse
- Scaler buildings to 99 levels + vault cap = gear-equipping unit count
- Speedup family routed through CheatManager — CHEAT FINISH unreachable in release
- Merge-pr.ps1 - the sanctioned merge; stop advisory reds hanging auto-merge
- Show release notes on the self-update screen
- Credit game-icons.net, drop the 'everything handmade' overclaim
- Host player docs on R2 + link them from the site Codex
- Tip-truth pass — tournament tips pulled, Leveling renamed Units
- Site-only unless a real release; seed import cache before export
- Archive-driven chat machinery - archive status IS the lifecycle signal
- Fresh non-maxed marketing screenshots + recover clean-capture mode
- Flush-left fill + Option-A detail pane (density pass v1)
- Wide-viewport overlay floats with a bottom gap instead of butting the bottom edge
- Grid gallery + lightbox, drop false expand-chevrons
- Digest dead-man check — silent #daily-brief morning alerts and self-announces
- Retired chats get tombstones so AutoPin cannot resurrect them
- Render cost/price as real flat-icon chips, not emoji (web tofu)
- Decode git-diff subprocess output as utf-8 in gate scripts
- Mipmaps on ALL art imports — completes the small-icon clarity fix tree-wide
- Icon-audit PDF in the Player Documents post + box dead-man check
- Re-gate QA snapshots 02-10 to the new Builder spine + Auditor gate lock-tests
- Rail label fits natively (no PRODUCTION clip) + native-first rule
- Mipmap-aware default texture filter — small icons render crisp, not muddy
- Conformance back to ubuntu — Claude Code CLI can't install on the box runners
- MARCH mode-bar action slot gets its walking-boot icon
- Read the box token file, not the pasted secret
- QA round 12 — smooth badges, recruit-picker damage badges, Capacity wording, assign-sheet icons (#2322 iter 12)
- Trim Cloudflare token so a pasted-secret newline can't break the auth header
- Resolve project root when $PSScriptRoot is empty
- True-width step 2 — desktop-only left mode rail
- Auto-deploy pipeline - Web export preset + deploy script + CI

Behind the scenes:
- Location pins on every open row — weekly re-verification jumps straight to each finding
- Illustrate the player documents with in-game icons + art (deferred)
- Multi-AI execution offload — deferred parking-lot entry
- Schematic was never retired — five discovery types restored across all claim sites
- Delta downloads — native patch-PCK chosen, zsync parked (roadmap v12)
- Seed rides the Technical review as an attachment — 🌱 message retired
- 2026-07-09 Weekly Digest bookkeeping — roadmap v11, D-68, ledger, doll-anchors v1
- Auto-retire window back to 7 days - Nathan travels
- Unify mode-button styling across the bar AND rail (one shared definition)
- Auto-retire spawned chats after 2 idle days, not 7
- Desktop rail — consistent row boxes; MARCH drops its green box
- Gut #spam-updates — documents become a fixed About post, alerts go to issues/daily-brief
- PR checks run on the box's self-hosted runners
- Move the seven PR checks to the box's self-hosted runners
- Remove the fat-context Discord sentinel
- Chat sentinels never quote chat content to Discord
- Recover live website source into the repo

## v0.0.27-P424

- 80px damage badge on cards + 40px row icons; hero rows show weapon damage type (#2322 iter 11)
- Trim level counts to milestone-delivering levels
- True-width step 1 - aspect-matched game surface, capped at 1080 logical
- F5 flow = the launcher's flow — notes first, then choose, then launch
- Drop D-65-deleted threshold parsers — unblocks the player-docs generator
- Doll proportions + production contrast + armguards final — roster 36/36
- Version subtitle under the title
- Uniform damage-type icon lines on all cards/rows/modals (#2322 iter 10)
- Unified notes — current-minor history, Full-notes link, --notes-shown
- F5 flash fix + current-minor full history + Full-notes link
- Unify level-up milestones + reshape Builder-track unlock pacing
- _relayout must not call get_tree() in a size_changed callback (#2394 follow-up)
- Mode pill fills its space - icon 56, label 22, stretch 2.6
- Unify release-notes trigger — one ReleaseNotesGate (Step 1)
- Live resolution change re-syncs content_scale_size
- Icon-first mode bar — big idle icons, active gold pill with label
- In-game screen is mobile-only; PC/Mac use the launcher
- Anchor-based doll layout — slots at anatomical positions over the silhouette
- All 19 doll slots visible (staged locked), equipped slots show painterly, light silhouette backdrop
- Once-per-launch boot gate before any mode
- Modal uses the shared cost button; net value rides the description row (#2322 iter 13)
- Header-card names never clipped — own row; action button own row (#2322 iter 12)
- Health checks never apply to adopted server spawns
- Loot painterly visible in-game + silhouette doll backdrop + redo promotions
- Snapshots build capacity buildings; Improve reaches the rendered card (#2322 iter 11)
- Improve button on building cards + real effect/total (#2322 iter 10)
- Itemization redesign + loot art final state — earrings/tabard, 6 sets, flavor text, seed library, audit v25
- Nightly real-game visual regression tier
- Show on every launch with a Continue button (all platforms + Godot)

Behind the scenes:
- MARCH becomes a bottom-bar action slot; compress space above modes
- Add web auto-deploy + live docs/roadmap plumbing lines
- Add browser-playable build + thefortressgame.com website
- Add browser-play option to the QA setup forum
- Fat-context sentinel — Discord nudge when a chat's per-call context crosses 300k
- V27 — roster complete 36/36 verified, modes second, bright production icon
- Progression permutation fuzzer + progression design philosophy
- Relabel mis-aimed character scenario to what it captures
- Runaway-process report in self-check; goldens in nightly backup; golden-review-board roadmap line
- Static Critic for research/lab progression
- Progression walk driver + static Critic (Harness foundation)
- Record desktop resolution-switch fix; mark confirmation-gate shipped
- Graphics audit joins the monthly player-docs post + on-demand lane
- Production gears brightened to #C7CDD6 (Nathan-approved contrast fix); audit order - MODES page follows currencies
- V26 — roster-truth edition (35/36, armguards straggler flagged) + roadmap RECORD
- Ids match display names — 25 renames + CI contract + recurring audit flag
- Roster complete — all 37 items Nathan-approved + shape-control playbook
- Mode bar shipped (icon-first #8 design); roadmap v8
- Knotted Sling + Rusty Sabatons promotions; registry picks recorded
- Seeded-round candidates + noun-seed registry draft + cuffs/girdle promotions

## v0.0.27-P402

- In-game "What's New" screen — recent release notes on all platforms
- Per-release notes history on the update and ready screens
- Per-build incremental notes, everything that reached the game since last build
- Wide-ratio shell — game in a SubViewport with real side margins

Behind the scenes:
- Mark "remember the monitor" done under v0.0.27
- Zombie-link detector — sustained zero connections = dead bridge, recycle
- Dynamic Discord retrofit — fix recent #releases posts in place
- Retroactively fix the 34 release notes (launcher scrollback + old Discord)
- Activity-signature hang detection + canonical PR-checks watcher
- Desktop side-margins shell + QA watermark done
- Robust Godot import wrapper + hung-import reaper

## v0.0.27-P401

- Header cards tap through to the building modal (#2322 iter 9)
- Real Armory/Guardhouse/Hall buildings; capacity research gated by building level (#2322 iter 8)
- Remember which monitor the desktop game was on and reopen there
- Pixelated style resolves the real transparent -pixel asset (closes #2081)
- DEFENSE drill-in tabs replace the modal shortcut (#2322 iter 7)
- Loot itemization — 4 sets, 18 new items, renames, staged slots
- DEFENSE picker section + camp art wired (#2322 iter 6, v2)
- Watermark visible at window top-left — drop the stretch-inverse transform
- Remove the .gdignore #2344 re-added to the zztest portrait fixture
- Portrait tier cadence audit - real caps, maxed=T5, UNITS levels wired (#2322 iter 5)

Behind the scenes:
- Placeholder for muddy small icons + remember-the-monitor request
- V25 prep — zztest skip, no content titles, silhouettes bare+geared, loot after silhouettes
- Record watermark, desktop-margins fix, coin-icon fix, launcher-notes
- Gear-slot placement approved + audit v24 cover versioning
- Record the cloud CI-minute usage guard + health-check retirement (shipped)
- Watch cloud Actions minutes vs the free cap (corrects #2338 target)
- Cover page, THE-FORTRESS in COMMAND, silhouettes third + gear-slot mockups
- P391 + wire character painterly tiers to resolver naming
- SUB_PATCH set at merge time from main's live value
- Worklist item 1 + party/camp/character model + audit restructure
- User-level bypass assertion; harness-owned tree settings excluded

## v0.0.27-P390

- Watermark off-screen — use OrientationLock's proven stretch transform
- Hall gold entity card (barracks level) + modal title wraps full name (#2322 iter 4)

Behind the scenes:
- Retire dead health-check scaffold; report runner volume not dollars

## v0.0.27-P389

- Watermark to true window top-left + remove duplicate version displays

## v0.0.27-P388

- Header panel parity + policy-gated empty flavor (#2322 iter 3)
- Always-on version watermark in the top-left (QA/dev builds)
- Silence the last 4 integer-division warnings (intentional window math)
- Missing-art placeholder, character art identity + L1-5 tiers, all-caps labels (#2322 iter 2)

Behind the scenes:
- Chat-durability model + auto-pin addendum
- Pin system, incident fixes, tech-reference v6, roadmap v6 retro-fill
- Record today's v0.0.27 ships (boot cleanup, settings + launcher polish)

## v0.0.27-P385

- Clear ~67 console warnings + the rp_font null runtime error
- QA/Regular order + Icon Testing parity in editor picker
- Restore Standard/Scientific notation example on Numbers buttons

Behind the scenes:
- Bump LAUNCHER_VERSION to 1.1.19 so installed launchers self-update

## v0.0.27-P384

- Icon/label resolution fix + regression test (rescued from dead chat)
- Remove the .gdignore that un-imported the zztest portrait fixture
- Commander #8 + pixel, approval-gate convention, state-doc rewrite, regen

Behind the scenes:
- Code-only orchestration - CLAUDE.md current-world rewrite + live-doc staleness sweep
- Headless servers spawn worktrees; gdunit runner seeds the box-local addon
- Monthly-cadence-aware reference-PDF check
- Require in the dispatch verdict comment
- Box-local driver art.py + promote primitives + 147 .import stub backfill
- RC four-engine infra sync + always-on hardening
- Roadmap v5 - art workstream items (silhouettes, doll layout, loot, box-local pipeline)
- Supervisor-managed Remote Control engines (best-practice self-heal)
- Record browser-direct self-healing AI sessions (in-flight infra)
- Runner count 4 to 7 (live-verified on the box)
- Regenerate icon-audit PDF from current main

## v0.0.27-P383

- Margin fortress icon points at importable art (P382)
- Label the chunky icon style 'Pixelated' (P381)
- Center all settings popups (P378, verified)
- Center all popups on full screen; fix invisible debug margin content
- Vault in 02-08, walls+stonemason in 05-08 (P373)
- Add walls and stonemason to _snapshot_build_side_buildings (P371)
- Promote damage/slots/headers to flat; fix classifier; D-81 gear model
- Remove Guardhouse empty-state overlay; Builder Improve button own row
- Display-settings overhaul + desktop full-width prep + quit relocation
- Built buildings never show locked in mode picker
- Missing-art placeholder when painterly absent (Outriders portrait)
- Promote 10 assets, large-font sheets, pagination, gear fix
- One dispatch run per issue (stop parallel duplicate re-fires)
- Drive-to-state visual capture (real-game tier)
- Redesign generator, promote 12 flats, generate candidates, rename sheets
- Wrap empty-state flavor text; cap Improve button width (P364)
- First-open picker stacking (P364)
- Font bump + lock, generalize generator, 8 contact sheets
- High-contrast palette maximum-strength pass (P362)
- Landscape-readiness prep; roadmap lines for font-scaling and landscape UI
- Quit nav item + comprehensive high-contrast mode
- Relocate never-ending tracks from Library to buildings
- Unsaved-changes detection, popup cancel, bottom bar, window modes, HC toggle
- Reap orphan Godot on normal gdunit completion — the tail-wedge
- Remove resolution control from mobile tab
- Retire launcher-picker shared-submodule line
- Enable resolution control on PC tab; remove window-size workaround
- Label the picker buttons; picker survives a blocked window resize
- Reload ThemeConstants profile after picker resolves
- Missing-image fallback in icon_lookup + warning log
- Launcher picker as a true shared component (deferred infrastructure)
- Set content_scale_size to PICKER_RES; host screen in MarginContainer
- Picker window — 480x440 at picker stage, resize to profile on selection
- Daily box self-check — PAT expiry + poller/watchdog heartbeats → alert
- Mechanical chat↔box coordination poller (live)
- F5 picker — brand styling, mobile window sizing, profile-aware display defaults
- Box reads CI logs directly via gh + read-only PAT
- AUTOLOAD-HANG rule — a boot-pausing autoload can't silently hang CI
- F5 launcher mode picker (Prod/QA, Desktop/Mobile), CI-safe
- Phase B building art reorg — single-tree consolidation
- Single pre-push-gate.ps1 keystone + fix box-only pytest unicode false-fail
- Full-suite floor on the gdunit pre-push gate so a subset can't false-green
- Building-lock single-source line + Character pre-throne portrait art line
- Change placeholder text to "Coming soon."
- P342 device-test bug batch — cold-start, icons, heroes, overflow, locked-flavor, Esc-back
- Save+Exit buttons; fix chunky icon preview black square
- Four settings-panel follow-up fixes
- One combined card across all four modes + overflow/cold-start/empty-state
- Settings panel layout, rail collapse, icon color fix
- Bring main's watchdog to the validated safe-detector (auto-recycle live)
- Npx stderr-abort + guaranteed terminal-outcome comment
- Roadmap - gear menu/settings marked in-progress
- Gear menu cleanup
- Gear menu shell + Mobile/Desktop settings switch
- Picker compact rows + landed hero build for testing

Behind the scenes:
- Armory/guardhouse/hall painterly T1-T5 + throne re-tier with new ornate T4/T5
- Gear-slot placement mockups + anchor table for fighter/commander dolls
- Archer candidate set v2 (screened) + pre-throne icon candidates
- Restore all historically deleted drafts (full window); content dedupe
- Restore wrongly deleted drafts; dedupe by image content; fix chunky/painterly tokenizing
- Classes page: fix mislabeled flat draft + regroup into heroes/soldiers/armaments
- Commit fighter/commander silhouettes; archer candidates; workstream state doc
- Style-aware stale-draft sweep + orphan building pixels + audit regen
- Audit cleanup: stale drafts + promote fix, building pixels, 3-col buildings, silhouette panels
- Promote forge + treasury pixels; regenerate audit
- Player reference PDFs monthly + icon-PDF roadmap line
- Promote forge + treasury flats; add their pixel candidates
- Mark never-ending tracks built (existing-slot, #2258)
- Never-ending tracks become a KIND in the existing queue slots
- Restore buildings T1-T5 ladder + source loot roster from gear_config
- Fix build_icon_audit.py: regenerate sheets from live tree before stitching
- Promote 59 flat-seeded pixel candidates to committed root
- Settings/display: fix Quit hang, Keep/Revert visibility+trigger, center popups, restore desktop margins
- Infinity tracks: post-max slot UI so maxed buildings surface their 999 track
- Lock icon-audit format: 5-column sheets, slot recolor, LOOT, audit PDF
- Revert desktop full-width margin layer (black-screen regression); keep other display fixes
- Record session infra wins (7 runners, drive-to-state, dispatch dedup) + watchdog gap
- Infinity tracks: queue wiring + D-39 cheat-placement fix
- Exclude .runner_migrated from runner clone (the real runner-5/6/7 cure)
- Install scripts register tasks windowless (no console flash on reinstall)
- Runner-add clean-slate + child-process isolation (real fix)
- Fix add-runner stale-config collision (runner-5 stall)
- Stamp version v3
- Currency curation: stone rock flat, stone/straw pixel icons, spoils dedupe, classifier fix
- Split Infrastructure block; record dispatch-reliability fix
- Gitignore Python bytecode — the salvage-commit junk
- Rule 7 — done items stay until build close, migrate to #about by category
- Visual-testing channel built; drive-to-state next
- Lock in the /box capture visual channel + the --branch rule
- Art-review: structural promoted-archive dedupe
- Weekly committed-art PDF publish to Discord (planned, v0.1.0)
- Art-review: visual-match dedupe + single-element stone/straw flat candidates
- Art-review: promote 6 pixel icons + content-hash dedupe + stone/straw glyph options
- Art-review: fully enclose every contact-sheet tile in its style frame
- Current with five-style model, reorg, lanes, and review system
- Promote corrected stone-pile flat + pixel candidate, closes #2067
- Art-review: recolor sheet + demote goblet + flat-seeded pixel candidates + expand art-system docs
- On-screen visual testing in progress, mechanism proven
- Art-review: lock generator + promotions + fallback asset + art-system doc
- Art-gen: fix stone flat glyph (rock fist to stone-pile), part of #2067
- Mark gdUnit version-pin shipped
- Pin gdunit-smoke to gdUnit4 v6.1.3
- CI failure auto-diagnosis sentinel
- F5 shows the real shared launcher selection screen; recreation deleted, drift gate added
- Strike 3 shipped lines; park deferred tooling ideas
- Archive Project Instructions v128
- Mark engine-file split shipped, move to #about built record
- Art-gen: repoint flat-icon generator + regen lane to assets/art testing/ layout
- Finish open-issues/impl-plan retirement
- Unify mobile profile into single source of truth
- Two homes only — collapse implementation-plan + design-backlog into roadmap.md
- Art-gen: extract icon glyph definitions into icon_defs.py (data-only, behavior-preserving)
- Single-source roadmap.md, design-backlog rename, bug routing, archive PI v127
- Extract HeroesBarracksState slice — final D-78 slice
- Session continuity: QA launcher on roadmap + implementation plan v86
- Add art-manifest-v1 — full repo image inventory
- Extract BuildingsMilestonesState slice
- Phase A icon reorg — one tree under assets/art/
- Box session reads deployed state from origin/main, not the working tree
- Extract ProductionQueueState slice
- Merge-authority rule + run-python-gates helper + box-facing CLAUDE.md rules
- Lock pass into impl-plan(v85) + open-issues(v37) + DECISIONS + art-roadmap
- Add art-directory-layout-v1 — one-tree layout spec
- Session docs: settings/gear overhaul shipped on roadmap; open-issues v36
- Extract ResearchState slice
- Add auto-rebase-pr.ps1 dirty-PR recovery reflex
- Add select-impacted-tests.ps1; run-gdunit-headless -Paths takes a list
- Add dispatch-status.ps1 forensics tool
- Archive Project Instructions v125, restart archive practice
- PR/CI gotchas from ForgeState #2008
- Extract ForgeState slice
- Settle CREDIT line — remove CONFIRM flag, mark confirmed 2026-06-26
- Document workflow-file versioning gotcha for in-flight box runs
- Correct self-heal timing to ~15-20 min, promote modularity-gate to required
- Correct runner pool to 4, update watchdog to safe-detector + live recycle, add terminal-signal / visibility-split / npx-fix / add-runner facts
- Fold watchdog tooling to repo; disable auto-recycle (detection-only)
- Godot import cache + per-ref concurrency on check workflows
- Box pre-push gate, run CI checks locally and self-correct before push
- Update CLAUDE.md with two-runner infra, watchdog facts, repo slug, CompleteJobAsync root cause
- Encode container-ceiling cadence in poll docs (P339)
- One nightly Discord-sync backstop + poller to every 4h
- Runner-discipline rules + verdict comment + overnight audits
- Extract GuardState slice

## v0.0.27-P333

- Compact rows + landed-surface hero
- Tabs-to-picker navigation build for testing

Behind the scenes:
- Archive project instructions v115 and v116

## v0.0.27-P329

- Tabs-to-picker swap, all four modes
- Level-aware tier-ladder portrait resolver
- Remove pre-dispatch lint from both dispatch lanes

Behind the scenes:
- Per-profile settings 3/3: NumberFormat notation onto the per-profile store
- Per-profile settings 2/3: ThemeConstants accessibility + appearance onto the per-profile store
- Per-profile settings 1/3: per-profile store + per-device->per-profile doc reconciliation
- Field manual - record the no-investigate lint revert case
- Entity section-header parallel-naming pass (dev-gui-management v7, game-style-modals v8)
- Gear menu: icon-row destinations, relabels, rename removed, gear glyph swapped
- Revert Infinity to in-progress (not confirmed in-game)
- Add standard UI menu icons (Tabler MIT) for gear menu restructure

## v0.0.27-P322

- Cut build - entity section-header parallel-naming + Armory pill rename
- Cut build - settings gray-screen fix + two-style icon system

Behind the scenes:
- Conformance gate: echo verdict to a connector-readable PR comment
- Mark Infinity lab category shipped (P320)
- BuildingModePicker component + contract test; data-gather in SelectionData adapter
- Launcher-publish: add a macOS dmg leg (drag-to-Applications install)

## v0.0.27-P321

- Single scene reload on settings-close (fix gray screen)
- Cut build - Infinity lab category
- Infinity lab category - four never-ending 999-level tracks (placeholder effects)
- Anchor macOS data paths to per-user data dir (App Translocation)
- Infinity lab category - reframe v0.0.27 never-ending tracks, add Infinity icon art item
- Building portrait art

Behind the scenes:
- Launcher-publish: include download links in the #releases announce
- Two-style icon system: flat/chunky resolver, per-device setting, settings toggle (P320)
- Launcher-publish: announce launcher updates in #releases on success
- Launcher SPEC: macOS and self-update are in scope; republishes launcher v1.1.18
- Reframe delta-download as undetermined-future, low priority
- Art roadmap: two currency icon styles (flat + chunky), drop pixel and cloud lane
- Add chunky currency icon set (8 PNGs)
- Art roadmap: currency icon style system + stylized-currency cloud lane
- Record GameManager decomposition + scope the doc-edit write-barrier
- Building portrait hero notes in dev-gui-management-v6
- Fold the two scheduled overnights into the Watchtower routines
- Record building-art-into-UI in DECISIONS and roadmap source
- Mark engine-file split progress on the roadmap (3 self-contained slices done)

## v0.0.27-P318

- Painterly building portrait hero in maker-tab header
- Building portrait hero in DetailModal
- Add gold-box stat bonus and never-ending-track gate to Placeholder
- Regen currency icons with locked glyph set, retire desktop/
- Strike the two shipped tab-restructure items
- Add monthly source-file-size regrowth check
- Add engine-file decomposition workstream to Infrastructure track
- Cleaner release notes, Update button above notes, bigger window
- Bug-mirroring (GitHub <-> #known-bugs) at top of infrastructure
- Mark modularity items confirmed by P312 QA
- Cut QA build

Behind the scenes:
- Centralize portrait resolution with id/filename normalization
- Builder never-ending track ships as a coming-soon placeholder
- Archive instructions v106 before v107
- Impl-plan v83 - Builder never-ending track parked as a placeholder
- Extract gear/loot slice into GearState component
- Add daily reconciliation + monthly god-file review overnights
- Lock down building flat-icons to assets/icons/buildings/ (glyph source 82d9488)
- Extract alert/badge slice into AlertState component
- Implementation plan v82 - correct v0.0.27 close-out STATUS
- Extract wallet/run-earnings/lifetime-stats into EconomyState component
- Implementation plan v81 - record v0.0.27 tab restructure
- Establish instructions archive with v105 baseline
- Remove the dead qa-setup text channel: source doc, sync workflow, and references
- Qa-setup forum: Mac post uses the launcher (link + flow)
- Qa-setup: Mac uses the launcher (link + flow), matching Windows
- Fix launcher macOS build: enable ETC2 ASTC import for universal export
- Rename business-infrastructure v12 to v13
- Fix launcher macOS export path (run from project dir) + self-diagnosing failure alert (#1799, #1801)
- Record server-authoritative fair play (early groundwork + v1.0 cluster)
- Scrub change/delta narrative from 12 resident docs; version-bump
- Promote chosen building tiles + recipe to canonical slots (cloud)
- Fix launcher macOS build: export on a Linux runner like the game (#1787, #1788)
- Launcher 1.1.16: rotating tips, resizable window, update line above notes, fix macOS preset (#1781, #1783, #1785)
- Snapshot top-level Docs baseline 2026-06-23 (pre-index-restructure backup)
- MacOS launcher (unsigned): export preset, cloud Mac publish leg, Mac install/launch/self-update (#1775, #1776, #1777)
- Security/competitive-integrity spec + roadmap fair-play update
- Launcher 1.1.14: bigger window, readable release notes, unclip update buttons (#1771, #1772)
- Add context-payload revert runbook (safety net before slimming always-on context)
- Icon-lookup-and-currencies spec v3
- Add Launcher tip audit to the Weekly Test (#1769, #1770)
- Launcher 1.1.13: all 17 building images + random startup tip line (#1763, #1768)
- Art-flux: machine-readable failure signal (issue, not Discord)
- Fix the #welcome install link (qa-setup forum)

## v0.0.27-P312

- Incorporate icon-style picker recommendations

Behind the scenes:
- Route hero-sheet level-up pill through shared ProgressionButton + contract test
- Launcher 1.1.12: randomize building-art order per launch (#1758, #1760)
- Lock unified skill/progression modal field set + testable picker builder
- Add the painterly building-art pipeline doc
- Launcher 1.1.11: restore real zip filename in download label (#1752, #1755)
- Launcher 1.1.10: Hearthfire palette + rotating building art + release notes (#1743, #1751)
- Update binary-art doctrine to the cloud Flux lane (CLAUDE.md + field manual)
- Icon pipeline v3: cloud art lane in the canonical art doc
- Single StatusDisplay resolver for availability status
- Parallelize the building-tile Flux generator (2 workers, 429 backoff)
- Add cloud Flux art lane (art off the box, never blocks releases)

## v0.0.27-P308

- Icon Testing launcher entry + in-game true-size icon preview
- Built building's picker modal shows build-state only
- Cut QA build (build-state/level decoupling, green caption)

Behind the scenes:
- QA forum: iOS post, Android Play Store note, rebuild sync
- Delta-update step 1: ship hpatchz.exe in the launcher installer (#1630, #1727)
- QA forum: reorder, rename, pinned overview
- Mirror icon reference docs into Docs/ (icon pipeline, icon style guide, icon-lookup/currencies spec). These existed only in project knowledge; bringing the repo into sync
- Trigger qa-forum-sync first run
- Add qa-setup forum (bot-synced)
- QA setup: dividers + suppress link previews

## v0.0.27-P306

- Per-device window mode/resolution with boot validation
- Exempt the test harness from the fork heuristic
- Add art-style toggle (ASCII / flat icons / painterly) to Placeholder
- Promote display settings to active (v0.0.29), per-device
- Render the cap-rise caption in green, not muted
- Cut QA build for real building level + green cap-rise caption
- Consolidate modularity and infra embeds; add PC graphics item
- Desktop preview shows the portrait UI centered instead of stretched

Behind the scenes:
- Builder picker cards show build-state, not level
- QA setup: rewrite cards with real markdown for readability
- Separate build-state from level (derived)
- Art-gen: walls orthographic low-wide iterative; fix battlements t1 and t5
- QA setup: re-fire the sync now the bot has permission
- Art-gen: split castle-section framing into walls (side elevation) and battlements (3/4)
- Delete superseded game-design-economy-v1
- QA setup: trigger the sync so the bot posts
- QA setup: move #qa-setup onto the Fortress bot, rework doc for readability
- Make #general a clickable link in the welcome message
- Economy v2 - art/skins framework as the cosmetic monetization vehicle
- Trigger welcome-sync (bot now has #welcome permission)
- Add user-selectable art and skins framework to roadmap Placeholder
- Art-gen: reframe walls and battlements as single wall sections
- Roadmap forward-only: remove Foundation, Art before Infrastructure
- Launcher 1.1.8: version bump to demonstrate the compressed self-update
- Add #general to the welcome message
- Art-gen: add walls and battlements diorama ladders (set complete)
- Launcher 1.1.7: compress the self-update download with raw-exe fallback
- Shipped work migrates to #about; drop Bugs in progress; regroup Infrastructure
- Batch-3 building tiles (stonemason, academy, treasury)
- Launcher 1.1.6: show the file being updated on screen
- Art-gen: add stonemason, academy, treasury diorama ladders
- Add #welcome bot sync (source + workflow)
- Batch-2 building tiles (forge, quarry, thresher)
- Grant actions: read so @claude can read CI run logs
- Launcher 1.1.5: desktop boot splash matches the launcher window (480x440)
- Art-gen: pulled-out diorama style for forge and thresher
- Desktop QA boot to landscape 16:9 + two roadmap done-marks
- Art-gen: self-heal sparse cutouts, denser quarry t4 prompt
- Make build-publish trigger explicit, note SUB_PATCH bump never builds
- Launcher 1.1.4: download size readout + update log, skip-path notice
- Pack roadmap embeds into fewer Discord messages
- Art-gen: drop phantom armory/hall/academy ladders, add forge/quarry/thresher
- QA setup: Windows now installs via the self-updating launcher
- Field manual v9 to v10: box workflow-push capability + android exit-code case
- Picker/modal: real building level instead of 1/1; cap-rise caption green
- Android build step exits 0 reliably (aapt2 badging exit-code fix)
- Art-gen: add armory, hall, academy ladders (batch 2)
- Launcher v1.1.3: version bump for serial-update demo

## v0.0.27-P303

- Tactics lab, cap-raise +10, picker cards, detail-modal fixes
- QA Desktop opens landscape, QA Mobile opens phone-sized, each with its own graphics
- Full base fetch so the governed-paths diff always resolves a merge base

Behind the scenes:
- Desktop preview pillarboxes the portrait UI; phone preview keeps the launcher window
- Launcher v1.1.2: serial update (launcher gates game) + self-update progress bar
- Re-fire roadmap sync now that the bot can embed
- Skill detail modal: cap-rise caption on a maxed-but-research-raisable skill
- Building detail modal: omit Effect/Total in build context, populate Total in tab context
- Batch-1 building tiles (vault, throne, sentry-towers)
- Launcher v1.1.1: show version in title (self-update test marker)
- Cap-raise topics: per-level descriptor now reads +10 max level per research
- Launcher self-update: the launcher updates itself in place
- Modularity Gate promoted from advisory to blocking
- Add launcher self-update and smaller-update items

## v0.0.27-P301

- Desktop window opens large and centered, sized to the monitor
- Build on the box instead of cloud Linux

Behind the scenes:
- QA form-factor drives both graphics and window: phone-sized portrait vs landscape desktop
- Roadmap to Discord embeds: one post per section
- Builder picker cards: 1/1 build status and gold completion for built buildings
- Library cap-raise: +10 per level across Commander, Fortress, Tactics caps
- Field manual v8 to v9: record the build-publish release-skip case file
- Note that workflow-file edits can ride the box lane (CLAUDE.md)
- Art-gen: walk the seed forward on empty Pollinations responses
- Box lane: let the box push workflow files via a workflows-scoped PAT
- Restore the Tactics lab to the Library (party-cap lab re-listed)
- Fail on findings so it can serve as a required gate
- Art-gen: revise vault and throne ladders, fuller-frame composition
- QA build trigger for v0.0.27-P300 (desktop window opens large)

## v0.0.27-P300

- 3-screen wizard installing the clean build that honors --qa
- Mark shipped pipeline savers done
- Pin gate model to claude-sonnet-4-6
- Add leaner-pipeline savers to infra track

Behind the scenes:
- Desktop window: open large centered portrait sized to the monitor
- Add mobile-preview line under v0.0.29
- Mark self-updating Windows install as done
- Revert quick-checks consolidation (skipping it)
- Quick-checks: consolidate the four fast gate checks (step 1, advisory)
- Art-gen: committed 5-tier building-tile recipe
- QA build trigger for v0.0.27-P298 (wallet-row boost)

## v0.0.27-P299

- Coming-soon flavor line under header-only building cards
- Split the over-length Placeholder post to unblock the channel sync
- Split infrastructure post, add multi-LLM harness investigation
- Builder tab is build-only, uniform per-building leveling on each tab
- Add endlessly repeatable gathering-building queue to placeholder
- Single tester build, one download
- Currency phone icons (grad+outline) + desktop flat overrides
- Non-destructive publish so the link can't break
- Download progress bar

Behind the scenes:
- Cheats gate on dev_features_enabled() honoring a --qa launch flag
- Gdunit-smoke: short-circuit on no-code PRs
- Currency wallet row: per-platform size boost (phone only)
- Note box runner is PowerShell 5.1 only (use shell: powershell)
- Field manual v8 (binary-art-born-on-box doctrine), drop v7
- Add before-launch interface reassessment to Placeholder
- Builder Select Building picker is build-only, no upgrades past level 1
- Box-born painterly art rule + corrected binary-transfer facts in BOX SESSION
- Nightly-suite: box-suite shell pwsh to powershell
- Amend D-75/D-76: sanction per-platform sizing through the IconLookup switch
- Utility tabs use the shared production header card in Discovery
- Gathering tabs use the shared production header card (Improve), not bare rows
- Art roadmap: add mobile font/UI scale-up (twin + Art - ahead mirror)
- Nightly-suite: box-primary + cloud-fallback + docs
- Stage 5 painterly building tier ladders (25 PNGs, 5 tiers each)
- Trigger P293 tester build (render + cheat fixes + currency icons)
- Add locked phone currency icon generator (grad+outline)
- Parking-lot v18 + watchtower - drop gh-CLI, record box-nightly, note engine cache already done

## v0.0.27-P293

- Render PRODUCTION gathering tabs (gate early-return on maker type)
- Newest-game-release selection + castle icon
- Windows export preset + Inno Setup installer script
- Windows update launcher standalone project

Behind the scenes:
- Move nightly re-test to the always-on box with a cloud fallback
- QA cheat fix: build gathering/utility buildings (not maxed) in mature snapshots
- Mark runner self-heal watchdog LIVE - \Fortress\RunnerWatchdog SYSTEM task installed and registered
- Launcher-publish workflow (installer at fixed link)
- Route currency icons through IconLookup
- Route gdunit reproduction back to @vzqz + record infra items (headless runner #1484)
- Trigger v0.0.27-P289 tester build

## v0.0.27-P290

- Shared per-platform icon lookup
- Truly-headless gdUnit suite runner for the @vzqz lane
- Add self-updating Windows install to the infrastructure track
- Valid watchdog repetition duration + fail-loud registration
- Add shared combat-HUD-button component to v0.1 Enhance Explore
- Move passive readout to its own layer below the buttons (P286)
- Move gear/CHEAT chrome onto its own CanvasLayer above the HUD (P285)
- Reverse milestone order - Enhance Explore v0.1, Enhance Defense v0.2
- Gear lower-edge dead zone, passive HUD strip steals the tap (P284)

Behind the scenes:
- Wire queue-leveling into the gathering and utility building tabs (single-source)
- Wrap the top mode-tab bar onto a second row (native flow, no scroll arrows)
- Fold box diagnostics & routing into BOX SESSION
- Runner health probe + draft diagnostics doctrine
- Runner self-heal watchdog (recycle script + installer)
- Rate-limit-aware Discord retrofit (finish remaining posts)
- Box lane: force truly-headless Godot so engine errands stop hanging
- Retrofit existing #releases posts with the one-click changelog link
- One-click changelog link in the #releases post
- Trigger v0.0.27-P284 build
- One-off backfill - release bodies to deltas, cumulative CHANGELOG.md, Discord dedup
- Gate republish + Discord on real delta; changelog link at release bottom
- Remove debug overlay (Play Protect block)
- Fix dead row-based spend confirmation (RowRenderer ancestor-search method name)
- Trigger v0.0.27-P283 QA build

## v0.0.27-P283

- Explore button hit-rect + press overlay (diagnostic, P283)
- Release notes show only the delta since the previous build
- Run macOS verify only on version-closes

Behind the scenes:
- Trigger v0.0.27-P282 QA build

## v0.0.27-P282

- Drive Explore movement from mouse stream only, tighten corner buttons
- Add two missing approved items to placeholder

Behind the scenes:
- Split over-length v0.0.27 post so roadmap-sync passes
- Trigger v0.0.27-P281 QA build

## v0.0.27-P281

- Implement UI occlusion gate on Explore screen
- Fold branded startup splash into the v0.0.29 intro-splash item
- Add startup splash and Android portrait boot splash to placeholder
- Add custom controls to placeholder (tracked, not scheduled)

Behind the scenes:
- Release notes: clean, human-readable changelog in releases + Discord
- Art roadmap: add undated management tab-wrap (twin + Art - ahead mirror)
- Mark app launcher icon done in art-now roadmap block
- Add input/gesture architecture requirement for gameplay screens

## v0.0.27-P280

- Maintenance build (no player-facing changes in this range).

Behind the scenes:
- Fold Library/Forge/Barracks into the Miscellaneous build category
- App icon: add zoomed castle launcher icon and wire it into the Android preset

## v0.0.27-P279

- Corner-as-gear guard for Explore-screen gear taps

Behind the scenes:
- Add Treasury, Academy, Vault utility tabs (thin, Discovery)
- Add Quarry and Thresher gathering tabs (thin, Production)
- Consolidate building improve/detail plumbing into the shared tab base
- Build-publish: stamp real Android version into export preset (Obtainium fix)
- Trigger all-platform QA build for v0.0.27-P276

## v0.0.27-P276

- Fold building/tab unification into the modularity-pass block
- Park the bug-loop back half as a future item

Behind the scenes:
- Proof tab: header-card-only Lumber Mill tab in Production
- Bump dev-implementation-plan v78 to v79
- Art-roadmap: note placeholder launcher icon and a proper game icon to replace it

## v0.0.27-P275

- Reopen v0.0.27 with remaining modularity items as features

Behind the scenes:
- Replace gear font glyph with bundled SVG icon, fix CHEAT geometry (P275)
- Define the digest icon legend; seed posts as banner + file only
- Drop the weekly technical appendix entirely, fold ledger lines into the seed
- Fold save-multichar spec into the implementation plan (docs-only, no code)

## v0.0.27-P274

- Add a quit button in the settings gear to the Placeholder bucket

Behind the scenes:
- Pin gear button to a square box + arm release
- WATCHTOWER coherence - daily appendix and branch-cleanup residuals
- Add advisory test-accompaniment gate (game-code PR with no test)
- Remove the technical appendix from the channel
- Weekly schedule on the branch-cleanup errand as a backstop

## v0.0.27-P273

- Add on-screen (non-headless) testing to the infrastructure track
- Expand v0.0.29 save work with multiple characters, QA slot, unified build, and entry flow

Behind the scenes:
- Gear glyph fills its box + arm release build
- Extract shared ScreenChrome (gear + CHEAT) across screens
- Add multiple-characters and unified-QA-build save spec
- Add game-style-sizing standard and index it
- Digest icon lists + deterministic reference-PDF staleness check
- Header + settings: enlarge gear, drop CHEAT below, add Credits menu, fix About
- Build-publish: correct stale fresh-key release note
- Daily Digest carries a conditional seed when Needs-you is non-empty
- Modularity gate: advisory check for hand-rolled building-detail popups

## v0.0.27-P270

- Remove dead Forge armament-detail path
- Selection-flow lock-reason consolidation + locked wording
- Mark phone tap-to-update done
- Rewrite v0.0.27 block to show the six open must-do items
- Force portrait at runtime; bump Android version/code

Behind the scenes:
- Qa-setup: fix POST 3 list rendering, drop auto-update post, add pull-to-refresh
- Qa-setup: step-by-step Android install + auto-update setup
- Regenerate currency icons frameless + mipmaps on
- Wallet bar: wrap cells so it can't stretch the screen

## v0.0.27-P268

- Fund gems/spoils/crowns from the +99,999 All button
- Add class/magic activatable combat effects to the Placeholder bucket

Behind the scenes:
- Qa-setup: beginner Android/Obtainium install walkthrough + stable-signing update note
- Promote 8 currency icons to assets/icons/currencies + fix config path
- Roadmap header: fix stale art twin filename reference
- Route wallet/resource bar through CurrencyDisplay (sweep 2)
- Build-publish: stable Android signing via keystore secret
- Roadmap + art: add sounds to Placeholder, add maker-category icons to the art list

## v0.0.27-P266

- Add screen-ratio scaling to the Placeholder bucket
- Add phone test-delivery and Google Play internal testing to infrastructure track
- Add general long-press-for-info feature (Placeholder, no version)
- Add detailed-wallet feature under v0.5
- Regression-test discipline; pin and place the alert badge
- V0.0.29 run data collection, v1.0 cheat prevention; art-track economy rule
- Hosted-runner sync + real-world-money-only disclosure rule
- Tooling onto the art side path; sync art editorial rule
- One list, full transparency. Add the tooling and pipeline track; rewrite editorial rules to hold back only economics and monetization
- Confirming a bug files it to known-bugs without auto-launching the fix
- Strip whitespace from all the poller's env reads
- Strip whitespace from the poller's NATHAN_ID env read
- Discord User-Agent on all three loop scripts; watcher posts into the forum thread
- Poller reads the bug-reports forum's posts (threads), not channel messages
- #about self-sync by channel name + milestone-tree roadmap
- Remove dead build-queue-slot text from Builder alerts
- Point branch-cleanup at github.repository, not the pre-transfer repo path
- Watcher matches non-closing Bug-loop-fixes: #N
- Known-bug label + confirm-to-close on the poller
- Known-bugs list publisher (with tests)
- Weekly digest reviews the player roadmap
- Roadmap sync runs on source change (no manual dispatch)
- Library research queue to level-gated multi-slot
- QA bug-report loop (poller + merge watcher, fail-inert until secrets set)
- Roadmap sync posts before deleting (fail-safe migration)
- Roadmap sync (bot-posting script + workflow + source of truth)
- Drop construction queue to a single slot at every level

Behind the scenes:
- Currency single-source correction: config owns all 8 currencies + icon paths
- Route confirm modal currency display through CurrencyDisplay (sweep 1)
- Currency display system: renderer + two registries + tests (stage 1)
- Remove dead placeholder _open_building_detail from armory and guardhouse tabs
- Reuse gate: add archetype-routing check to the analyzer subagent (MOVE 3)
- Builder popup label: Production to Building
- Modularity Pass (v0.0.27): fix maker-popup category labels in the shared adapter
- Implementation plan v78 - realign the 27/28 split to the roadmap
- Modularity Pass (v0.0.27): detail-popup single source - extract building-detail config into DetailConfigBuilder
- Monthly Test box-offload self-interrogation
- Impl plan v77: strip the delta changelog; re-cut the Foundation to the roadmap
- Impl plan v76: fold in run data collection and cheat prevention
- CLAUDE.md: v0.0.27 = the Modularity Pass; roadmap: per-version progress rule
- Reference PDFs: alert #spam-updates when the nightly build fails
- Weekly digest seed must account for every Needs-you/Watching item
- Move vision-sync to the vzqz box runner, add daily schedule
- Restore infrastructure track as its own parallel roadmap section
- Move roadmap-sync to the vzqz box runner
- Reference README - add Progression Atlas, correct cadence to nightly+dispatch
- Weekly Digest: one-line status per check (Checks block), detail still in the appendix
- Weekly Digest: exception-only Technical review, full mechanical output to the appendix, seed 0-5
- Roadmap-sync: add an hourly schedule so queue-merged roadmap changes reach the forum (bot merges do not trigger the push)
- Painterly building generator + 17 placeholder renders
- One-off workflow to post the bug-forum explainer as the Fortress bot
- Field manual: box Python generation capability proof (s3) and the v91 chronicle entry (s5)
- CLAUDE.md: record the box as the primary art-generation lane (conda toolchain), cloud as pinned fallback
- Pin cloud art fallback to the proven glyph commit; mark as fallback to the box lane
- Bug loop: skip pinned forum posts; correct stale poller workflow comments
- Record roadmap canonicalization and decision reversals
- Bug loop: owner-gated close, verdict disagree-invites, known-bugs thread links, back-half env-strip
- Add idle loop v0.3, NPC build-out, tournament split, onboarding + achievements
- Regenerate flat icons (glyph source 82d948812bfe3f269ef8f731dcdb07b08160edc4)
- Icon guide: add storage and movement section (staging, production paths, engine import)
- Art regen runner: add chat-fireable push trigger (art-regen-run branch) and record glyph-source commit
- Reorder side sections to the end, decouple art from versions, add v2.0 biomes + placeholder items
- Work-model version numbering + full parallel art track
- Lock flat-icon system, art roadmap, style guides, regeneration runner
- Bump business-infra to v11 and field manual to v6
- Record bug-loop go-live in WATCHTOWER and DECISIONS
- 1:1 note, version clarification, bugs + placeholder sections, phased art, Defense reframe
- Stat-rollup reframe, split Explore into three milestones, balance to v0.6.0
- Merge stat-wiring build, Enhance Defense/Explore, art track up
- Milestone-based detail, split 27, blueprints to Explore, local-then-cloud saves
- Reference-pdfs: nightly schedule + on demand, drop on-change trigger
- Add the Progression Atlas as a third generated player document
- Future tiers as prose paragraphs, no version numbers
- Expand the roadmap - evergreen intro + full aspirational tree
- Business-infrastructure v9 to v10 (roadmap/about bot-sync, art-pipeline fix, tooling note)
- Stamp the build version on the Reference and Manual PDFs
- Add workflow to regenerate + publish player PDFs on config change
- Add config-driven Reference/Manual PDF pipeline (tools/reference)
- Version tree, versioning defined, Defend/Explore/Throne moved to in-the-build
- Bug-report loop + known-bugs sync armed (all secrets set)
- Business-infrastructure v9 - bug loop armed (all secrets set)
- Add generic empty-slot icon set (wip, draft for review)
- Concise patch-oriented #roadmap + vision-source.md for #about
- Adopt the channel as the authoritative active backlog + Current Build working list
- Game-design-items v15 to v16 (Library research-slot count corrected)
- Add proportional humanoid silhouette for gear doll (wip)
- Stage premium-currency and discovery-item placeholder icons in art/icons-wip
- Stage live-currency placeholder icons in art/icons-wip (gdignored)
- Correct the #spam-updates mute state in WATCHTOWER.md
- Docs reconciliation: rarity removed, research multi-slot, Library level 9
- Spec the full lifecycle and conventions
- Drop dead state-commit step from the poller workflow
- Run the known-bugs publisher on issue events and daily
- Extend Library to level 9, render research multi-slot
- Remove orphaned state file
- Stateless watcher, no main write (with tests)
- Stateless poller, no main write (with tests)
- Record the roadmap publishing system in WATCHTOWER.md
- Seed poller cursor to now so first run ignores pre-existing channel history
- Delete four retired build/release workflow stubs
- Add Discord #qa-setup channel source
- Point build/release references at unified build-publish.yml
- Six assets, two per platform (split Windows) + idempotent publish
- Remove dead pip ecosystem from dependabot config
- Unify builds: one workflow, one release, one Discord post
