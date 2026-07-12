# The Fortress - changelog

Every build that changed something, newest first. Each entry is that build's own changes.

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

- First published build.

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
- Regenerate icon-audit PDF from current main

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

## v0.0.27-P383

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
- Margin fortress icon points at importable art (P382)
- Promote forge + treasury flats; add their pixel candidates
- Label the chunky icon style 'Pixelated' (P381)
- Center all settings popups (P378, verified)
- Restore buildings T1-T5 ladder + source loot roster from gear_config
- Fix build_icon_audit.py: regenerate sheets from live tree before stitching
- Promote 59 flat-seeded pixel candidates to committed root
- Center all popups on full screen; fix invisible debug margin content
- Settings/display: fix Quit hang, Keep/Revert visibility+trigger, center popups, restore desktop margins
- Infinity tracks: post-max slot UI so maxed buildings surface their 999 track
- Lock icon-audit format: 5-column sheets, slot recolor, LOOT, audit PDF
- Vault in 02-08, walls+stonemason in 05-08 (P373)
- Revert desktop full-width margin layer (black-screen regression); keep other display fixes
- Add walls and stonemason to _snapshot_build_side_buildings (P371)
- Promote damage/slots/headers to flat; fix classifier; D-81 gear model
- Remove Guardhouse empty-state overlay; Builder Improve button own row
- Display-settings overhaul + desktop full-width prep + quit relocation
- Built buildings never show locked in mode picker
- Missing-art placeholder when painterly absent (Outriders portrait)
- Promote 10 assets, large-font sheets, pagination, gear fix
- One dispatch run per issue (stop parallel duplicate re-fires)
- Infinity tracks: queue wiring + D-39 cheat-placement fix
- Drive-to-state visual capture (real-game tier)
- Redesign generator, promote 12 flats, generate candidates, rename sheets
- Wrap empty-state flavor text; cap Improve button width (P364)
- First-open picker stacking (P364)
- Font bump + lock, generalize generator, 8 contact sheets
- Currency curation: stone rock flat, stone/straw pixel icons, spoils dedupe, classifier fix
- High-contrast palette maximum-strength pass (P362)
- Landscape-readiness prep; roadmap lines for font-scaling and landscape UI
- Quit nav item + comprehensive high-contrast mode
- Relocate never-ending tracks from Library to buildings
- Art-review: structural promoted-archive dedupe
- Unsaved-changes detection, popup cancel, bottom bar, window modes, HC toggle
- Reap orphan Godot on normal gdunit completion — the tail-wedge
- Remove resolution control from mobile tab
- Retire launcher-picker shared-submodule line
- Art-review: visual-match dedupe + single-element stone/straw flat candidates
- Enable resolution control on PC tab; remove window-size workaround
- Art-review: promote 6 pixel icons + content-hash dedupe + stone/straw glyph options
- Label the picker buttons; picker survives a blocked window resize
- Art-review: fully enclose every contact-sheet tile in its style frame
- Art-review: recolor sheet + demote goblet + flat-seeded pixel candidates + expand art-system docs
- Reload ThemeConstants profile after picker resolves
- Missing-image fallback in icon_lookup + warning log
- Art-review: lock generator + promotions + fallback asset + art-system doc
- Art-gen: fix stone flat glyph (rock fist to stone-pile), part of #2067
- Launcher picker as a true shared component (deferred infrastructure)
- Set content_scale_size to PICKER_RES; host screen in MarginContainer
- F5 shows the real shared launcher selection screen; recreation deleted, drift gate added
- Art-gen: repoint flat-icon generator + regen lane to assets/art testing/ layout
- Picker window — 480x440 at picker stage, resize to profile on selection
- Daily box self-check — PAT expiry + poller/watchdog heartbeats → alert
- Mechanical chat↔box coordination poller (live)
- Art-gen: extract icon glyph definitions into icon_defs.py (data-only, behavior-preserving)
- F5 picker — brand styling, mobile window sizing, profile-aware display defaults
- Box reads CI logs directly via gh + read-only PAT
- AUTOLOAD-HANG rule — a boot-pausing autoload can't silently hang CI
- F5 launcher mode picker (Prod/QA, Desktop/Mobile), CI-safe
- Phase B building art reorg — single-tree consolidation
- Single pre-push-gate.ps1 keystone + fix box-only pytest unicode false-fail
- Full-suite floor on the gdunit pre-push gate so a subset can't false-green
- Session continuity: QA launcher on roadmap + implementation plan v86
- Building-lock single-source line + Character pre-throne portrait art line
- Session docs: settings/gear overhaul shipped on roadmap; open-issues v36
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
- Player reference PDFs monthly + icon-PDF roadmap line
- Mark never-ending tracks built (existing-slot, #2258)
- Never-ending tracks become a KIND in the existing queue slots
- Record session infra wins (7 runners, drive-to-state, dispatch dedup) + watchdog gap
- Exclude .runner_migrated from runner clone (the real runner-5/6/7 cure)
- Install scripts register tasks windowless (no console flash on reinstall)
- Runner-add clean-slate + child-process isolation (real fix)
- Fix add-runner stale-config collision (runner-5 stall)
- Stamp version v3
- Split Infrastructure block; record dispatch-reliability fix
- Gitignore Python bytecode — the salvage-commit junk
- Rule 7 — done items stay until build close, migrate to #about by category
- Visual-testing channel built; drive-to-state next
- Lock in the /box capture visual channel + the --branch rule
- Weekly committed-art PDF publish to Discord (planned, v0.1.0)
- Current with five-style model, reorg, lanes, and review system
- Promote corrected stone-pile flat + pixel candidate, closes #2067
- On-screen visual testing in progress, mechanism proven
- Mark gdUnit version-pin shipped
- Pin gdunit-smoke to gdUnit4 v6.1.3
- CI failure auto-diagnosis sentinel
- Strike 3 shipped lines; park deferred tooling ideas
- Archive Project Instructions v128
- Mark engine-file split shipped, move to #about built record
- Finish open-issues/impl-plan retirement
- Unify mobile profile into single source of truth
- Two homes only — collapse implementation-plan + design-backlog into roadmap.md
- Single-source roadmap.md, design-backlog rename, bug routing, archive PI v127
- Extract HeroesBarracksState slice — final D-78 slice
- Add art-manifest-v1 — full repo image inventory
- Extract BuildingsMilestonesState slice
- Phase A icon reorg — one tree under assets/art/
- Box session reads deployed state from origin/main, not the working tree
- Extract ProductionQueueState slice
- Merge-authority rule + run-python-gates helper + box-facing CLAUDE.md rules
- Lock pass into impl-plan(v85) + open-issues(v37) + DECISIONS + art-roadmap
- Add art-directory-layout-v1 — one-tree layout spec
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
- Archive project instructions v115 and v116
- Tabs-to-picker navigation build for testing

## v0.0.27-P329

- Tabs-to-picker swap, all four modes
- Level-aware tier-ladder portrait resolver
- Per-profile settings 3/3: NumberFormat notation onto the per-profile store
- Per-profile settings 2/3: ThemeConstants accessibility + appearance onto the per-profile store
- Per-profile settings 1/3: per-profile store + per-device->per-profile doc reconciliation
- Remove pre-dispatch lint from both dispatch lanes
- Gear menu: icon-row destinations, relabels, rename removed, gear glyph swapped
- Add standard UI menu icons (Tabler MIT) for gear menu restructure

Behind the scenes:
- Field manual - record the no-investigate lint revert case
- Entity section-header parallel-naming pass (dev-gui-management v7, game-style-modals v8)
- Revert Infinity to in-progress (not confirmed in-game)

## v0.0.27-P322

- Cut build - entity section-header parallel-naming + Armory pill rename
- Conformance gate: echo verdict to a connector-readable PR comment
- BuildingModePicker component + contract test; data-gather in SelectionData adapter
- Cut build - settings gray-screen fix + two-style icon system
- Launcher-publish: add a macOS dmg leg (drag-to-Applications install)

Behind the scenes:
- Mark Infinity lab category shipped (P320)

## v0.0.27-P321

- Single scene reload on settings-close (fix gray screen)
- Cut build - Infinity lab category
- Infinity lab category - four never-ending 999-level tracks (placeholder effects)
- Launcher-publish: include download links in the #releases announce
- Two-style icon system: flat/chunky resolver, per-device setting, settings toggle (P320)
- Launcher-publish: announce launcher updates in #releases on success
- Launcher SPEC: macOS and self-update are in scope; republishes launcher v1.1.18
- Anchor macOS data paths to per-user data dir (App Translocation)
- Infinity lab category - reframe v0.0.27 never-ending tracks, add Infinity icon art item
- Art roadmap: two currency icon styles (flat + chunky), drop pixel and cloud lane
- Art roadmap: currency icon style system + stylized-currency cloud lane
- Fold the two scheduled overnights into the Watchtower routines
- Building portrait art

Behind the scenes:
- Reframe delta-download as undetermined-future, low priority
- Add chunky currency icon set (8 PNGs)
- Record GameManager decomposition + scope the doc-edit write-barrier
- Building portrait hero notes in dev-gui-management-v6
- Record building-art-into-UI in DECISIONS and roadmap source
- Mark engine-file split progress on the roadmap (3 self-contained slices done)

## v0.0.27-P318

- Painterly building portrait hero in maker-tab header
- Building portrait hero in DetailModal
- Lock down building flat-icons to assets/icons/buildings/ (glyph source 82d9488)
- Add gold-box stat bonus and never-ending-track gate to Placeholder
- Regen currency icons with locked glyph set, retire desktop/
- Strike the two shipped tab-restructure items
- Add monthly source-file-size regrowth check
- Add engine-file decomposition workstream to Infrastructure track
- Remove the dead qa-setup text channel: source doc, sync workflow, and references
- Qa-setup forum: Mac post uses the launcher (link + flow)
- Cleaner release notes, Update button above notes, bigger window
- Qa-setup: Mac uses the launcher (link + flow), matching Windows
- Fix launcher macOS build: enable ETC2 ASTC import for universal export
- Fix launcher macOS export path (run from project dir) + self-diagnosing failure alert (#1799, #1801)
- Bug-mirroring (GitHub <-> #known-bugs) at top of infrastructure
- Mark modularity items confirmed by P312 QA
- Promote chosen building tiles + recipe to canonical slots (cloud)
- Fix launcher macOS build: export on a Linux runner like the game (#1787, #1788)
- Launcher 1.1.16: rotating tips, resizable window, update line above notes, fix macOS preset (#1781, #1783, #1785)
- Snapshot top-level Docs baseline 2026-06-23 (pre-index-restructure backup)
- MacOS launcher (unsigned): export preset, cloud Mac publish leg, Mac install/launch/self-update (#1775, #1776, #1777)
- Launcher 1.1.14: bigger window, readable release notes, unclip update buttons (#1771, #1772)
- Add context-payload revert runbook (safety net before slimming always-on context)
- Add Launcher tip audit to the Weekly Test (#1769, #1770)
- Launcher 1.1.13: all 17 building images + random startup tip line (#1763, #1768)
- Cut QA build
- Art-flux: machine-readable failure signal (issue, not Discord)
- Fix the #welcome install link (qa-setup forum)

Behind the scenes:
- Centralize portrait resolution with id/filename normalization
- Builder never-ending track ships as a coming-soon placeholder
- Archive instructions v106 before v107
- Impl-plan v83 - Builder never-ending track parked as a placeholder
- Extract gear/loot slice into GearState component
- Add daily reconciliation + monthly god-file review overnights
- Extract alert/badge slice into AlertState component
- Implementation plan v82 - correct v0.0.27 close-out STATUS
- Extract wallet/run-earnings/lifetime-stats into EconomyState component
- Implementation plan v81 - record v0.0.27 tab restructure
- Establish instructions archive with v105 baseline
- Rename business-infrastructure v12 to v13
- Record server-authoritative fair play (early groundwork + v1.0 cluster)
- Scrub change/delta narrative from 12 resident docs; version-bump
- Security/competitive-integrity spec + roadmap fair-play update
- Icon-lookup-and-currencies spec v3

## v0.0.27-P312

- Launcher 1.1.12: randomize building-art order per launch (#1758, #1760)
- Add the painterly building-art pipeline doc
- Launcher 1.1.11: restore real zip filename in download label (#1752, #1755)
- Incorporate icon-style picker recommendations
- Launcher 1.1.10: Hearthfire palette + rotating building art + release notes (#1743, #1751)
- Update binary-art doctrine to the cloud Flux lane (CLAUDE.md + field manual)
- Icon pipeline v3: cloud art lane in the canonical art doc
- Parallelize the building-tile Flux generator (2 workers, 429 backoff)
- Add cloud Flux art lane (art off the box, never blocks releases)

Behind the scenes:
- Route hero-sheet level-up pill through shared ProgressionButton + contract test
- Lock unified skill/progression modal field set + testable picker builder
- Single StatusDisplay resolver for availability status

## v0.0.27-P308

- Icon Testing launcher entry + in-game true-size icon preview
- Built building's picker modal shows build-state only
- QA forum: iOS post, Android Play Store note, rebuild sync
- Delta-update step 1: ship hpatchz.exe in the launcher installer (#1630, #1727)
- QA forum: reorder, rename, pinned overview
- Mirror icon reference docs into Docs/ (icon pipeline, icon style guide, icon-lookup/currencies spec). These existed only in project knowledge; bringing the repo into sync
- Trigger qa-forum-sync first run
- Add qa-setup forum (bot-synced)
- Cut QA build (build-state/level decoupling, green caption)
- QA setup: dividers + suppress link previews

## v0.0.27-P306

- QA setup: rewrite cards with real markdown for readability
- Art-gen: walls orthographic low-wide iterative; fix battlements t1 and t5
- Per-device window mode/resolution with boot validation
- Exempt the test harness from the fork heuristic
- Add art-style toggle (ASCII / flat icons / painterly) to Placeholder
- QA setup: re-fire the sync now the bot has permission
- Art-gen: split castle-section framing into walls (side elevation) and battlements (3/4)
- QA setup: trigger the sync so the bot posts
- QA setup: move #qa-setup onto the Fortress bot, rework doc for readability
- Make #general a clickable link in the welcome message
- Trigger welcome-sync (bot now has #welcome permission)
- Promote display settings to active (v0.0.29), per-device
- Add user-selectable art and skins framework to roadmap Placeholder
- Art-gen: reframe walls and battlements as single wall sections
- Roadmap forward-only: remove Foundation, Art before Infrastructure
- Launcher 1.1.8: version bump to demonstrate the compressed self-update
- Add #general to the welcome message
- Art-gen: add walls and battlements diorama ladders (set complete)
- Launcher 1.1.7: compress the self-update download with raw-exe fallback
- Shipped work migrates to #about; drop Bugs in progress; regroup Infrastructure
- Render the cap-rise caption in green, not muted
- Launcher 1.1.6: show the file being updated on screen
- Art-gen: add stonemason, academy, treasury diorama ladders
- Add #welcome bot sync (source + workflow)
- Launcher 1.1.5: desktop boot splash matches the launcher window (480x440)
- Art-gen: pulled-out diorama style for forge and thresher
- Desktop QA boot to landscape 16:9 + two roadmap done-marks
- Art-gen: self-heal sparse cutouts, denser quarry t4 prompt
- Launcher 1.1.4: download size readout + update log, skip-path notice
- Pack roadmap embeds into fewer Discord messages
- Art-gen: drop phantom armory/hall/academy ladders, add forge/quarry/thresher
- QA setup: Windows now installs via the self-updating launcher
- Cut QA build for real building level + green cap-rise caption
- Field manual v9 to v10: box workflow-push capability + android exit-code case
- Picker/modal: real building level instead of 1/1; cap-rise caption green
- Art-gen: add armory, hall, academy ladders (batch 2)
- Launcher v1.1.3: version bump for serial-update demo
- Consolidate modularity and infra embeds; add PC graphics item
- Desktop preview shows the portrait UI centered instead of stretched

Behind the scenes:
- Builder picker cards show build-state, not level
- Separate build-state from level (derived)
- Delete superseded game-design-economy-v1
- Economy v2 - art/skins framework as the cosmetic monetization vehicle
- Batch-3 building tiles (stonemason, academy, treasury)
- Batch-2 building tiles (forge, quarry, thresher)
- Grant actions: read so @claude can read CI run logs
- Make build-publish trigger explicit, note SUB_PATCH bump never builds
- Android build step exits 0 reliably (aapt2 badging exit-code fix)

## v0.0.27-P303

- Desktop preview pillarboxes the portrait UI; phone preview keeps the launcher window
- Launcher v1.1.2: serial update (launcher gates game) + self-update progress bar
- Re-fire roadmap sync now that the bot can embed
- Tactics lab, cap-raise +10, picker cards, detail-modal fixes
- Skill detail modal: cap-rise caption on a maxed-but-research-raisable skill
- Building detail modal: omit Effect/Total in build context, populate Total in tab context
- Launcher v1.1.1: show version in title (self-update test marker)
- Cap-raise topics: per-level descriptor now reads +10 max level per research
- QA Desktop opens landscape, QA Mobile opens phone-sized, each with its own graphics
- Full base fetch so the governed-paths diff always resolves a merge base
- Launcher self-update: the launcher updates itself in place

Behind the scenes:
- Batch-1 building tiles (vault, throne, sentry-towers)
- Modularity Gate promoted from advisory to blocking
- Add launcher self-update and smaller-update items

## v0.0.27-P301

- QA form-factor drives both graphics and window: phone-sized portrait vs landscape desktop
- Roadmap to Discord embeds: one post per section
- Builder picker cards: 1/1 build status and gold completion for built buildings
- Library cap-raise: +10 per level across Commander, Fortress, Tactics caps
- Field manual v8 to v9: record the build-publish release-skip case file
- Art-gen: walk the seed forward on empty Pollinations responses
- Box lane: let the box push workflow files via a workflows-scoped PAT
- Restore the Tactics lab to the Library (party-cap lab re-listed)
- Desktop window opens large and centered, sized to the monitor
- Build on the box instead of cloud Linux
- Art-gen: revise vault and throne ladders, fuller-frame composition

Behind the scenes:
- Note that workflow-file edits can ride the box lane (CLAUDE.md)
- Fail on findings so it can serve as a required gate
- QA build trigger for v0.0.27-P300 (desktop window opens large)

## v0.0.27-P300

- Desktop window: open large centered portrait sized to the monitor
- Revert quick-checks consolidation (skipping it)
- 3-screen wizard installing the clean build that honors --qa
- Quick-checks: consolidate the four fast gate checks (step 1, advisory)
- Art-gen: committed 5-tier building-tile recipe
- Mark shipped pipeline savers done
- Pin gate model to claude-sonnet-4-6
- Add leaner-pipeline savers to infra track

Behind the scenes:
- Add mobile-preview line under v0.0.29
- Mark self-updating Windows install as done
- QA build trigger for v0.0.27-P298 (wallet-row boost)

## v0.0.27-P299

- Cheats gate on dev_features_enabled() honoring a --qa launch flag
- Gdunit-smoke: short-circuit on no-code PRs
- Coming-soon flavor line under header-only building cards
- Split the over-length Placeholder post to unblock the channel sync
- Currency wallet row: per-platform size boost (phone only)
- Builder Select Building picker is build-only, no upgrades past level 1
- Split infrastructure post, add multi-LLM harness investigation
- Nightly-suite: box-suite shell pwsh to powershell
- Amend D-75/D-76: sanction per-platform sizing through the IconLookup switch
- Builder tab is build-only, uniform per-building leveling on each tab
- Utility tabs use the shared production header card in Discovery
- Gathering tabs use the shared production header card (Improve), not bare rows
- Art roadmap: add mobile font/UI scale-up (twin + Art - ahead mirror)
- Add endlessly repeatable gathering-building queue to placeholder
- Nightly-suite: box-primary + cloud-fallback + docs
- Stage 5 painterly building tier ladders (25 PNGs, 5 tiers each)
- Single tester build, one download
- Currency phone icons (grad+outline) + desktop flat overrides
- Add locked phone currency icon generator (grad+outline)
- Non-destructive publish so the link can't break
- Download progress bar

Behind the scenes:
- Note box runner is PowerShell 5.1 only (use shell: powershell)
- Field manual v8 (binary-art-born-on-box doctrine), drop v7
- Add before-launch interface reassessment to Placeholder
- Box-born painterly art rule + corrected binary-transfer facts in BOX SESSION
- Trigger P293 tester build (render + cheat fixes + currency icons)
- Parking-lot v18 + watchtower - drop gh-CLI, record box-nightly, note engine cache already done

## v0.0.27-P293

- Render PRODUCTION gathering tabs (gate early-return on maker type)
- QA cheat fix: build gathering/utility buildings (not maxed) in mature snapshots
- Newest-game-release selection + castle icon
- Windows export preset + Inno Setup installer script
- Windows update launcher standalone project

Behind the scenes:
- Move nightly re-test to the always-on box with a cloud fallback
- Mark runner self-heal watchdog LIVE - \Fortress\RunnerWatchdog SYSTEM task installed and registered
- Launcher-publish workflow (installer at fixed link)
- Route currency icons through IconLookup
- Route gdunit reproduction back to @vzqz + record infra items (headless runner #1484)
- Trigger v0.0.27-P289 tester build

## v0.0.27-P290

- Shared per-platform icon lookup
- Wire queue-leveling into the gathering and utility building tabs (single-source)
- Truly-headless gdUnit suite runner for the @vzqz lane
- Wrap the top mode-tab bar onto a second row (native flow, no scroll arrows)
- Add self-updating Windows install to the infrastructure track
- Valid watchdog repetition duration + fail-loud registration
- Add shared combat-HUD-button component to v0.1 Enhance Explore
- Move passive readout to its own layer below the buttons (P286)
- Box lane: force truly-headless Godot so engine errands stop hanging
- Move gear/CHEAT chrome onto its own CanvasLayer above the HUD (P285)
- Reverse milestone order - Enhance Explore v0.1, Enhance Defense v0.2
- Gear lower-edge dead zone, passive HUD strip steals the tap (P284)
- Fix dead row-based spend confirmation (RowRenderer ancestor-search method name)

Behind the scenes:
- Fold box diagnostics & routing into BOX SESSION
- Runner health probe + draft diagnostics doctrine
- Runner self-heal watchdog (recycle script + installer)
- Rate-limit-aware Discord retrofit (finish remaining posts)
- Retrofit existing #releases posts with the one-click changelog link
- One-click changelog link in the #releases post
- Trigger v0.0.27-P284 build
- One-off backfill - release bodies to deltas, cumulative CHANGELOG.md, Discord dedup
- Gate republish + Discord on real delta; changelog link at release bottom
- Remove debug overlay (Play Protect block)
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
- Release notes: clean, human-readable changelog in releases + Discord
- Art roadmap: add undated management tab-wrap (twin + Art - ahead mirror)
- Fold branded startup splash into the v0.0.29 intro-splash item
- Add startup splash and Android portrait boot splash to placeholder
- Add custom controls to placeholder (tracked, not scheduled)

Behind the scenes:
- Mark app launcher icon done in art-now roadmap block
- Add input/gesture architecture requirement for gameplay screens

## v0.0.27-P280

- Fold Library/Forge/Barracks into the Miscellaneous build category
- App icon: add zoomed castle launcher icon and wire it into the Android preset

## v0.0.27-P279

- Add Treasury, Academy, Vault utility tabs (thin, Discovery)
- Add Quarry and Thresher gathering tabs (thin, Production)
- Consolidate building improve/detail plumbing into the shared tab base
- Build-publish: stamp real Android version into export preset (Obtainium fix)
- Corner-as-gear guard for Explore-screen gear taps

Behind the scenes:
- Trigger all-platform QA build for v0.0.27-P276

## v0.0.27-P276

- Proof tab: header-card-only Lumber Mill tab in Production
- Fold building/tab unification into the modularity-pass block
- Park the bug-loop back half as a future item
- Art-roadmap: note placeholder launcher icon and a proper game icon to replace it

Behind the scenes:
- Bump dev-implementation-plan v78 to v79

## v0.0.27-P275

- Replace gear font glyph with bundled SVG icon, fix CHEAT geometry (P275)
- Reopen v0.0.27 with remaining modularity items as features
- Fold save-multichar spec into the implementation plan (docs-only, no code)

Behind the scenes:
- Define the digest icon legend; seed posts as banner + file only
- Drop the weekly technical appendix entirely, fold ledger lines into the seed

## v0.0.27-P274

- Pin gear button to a square box + arm release
- Add advisory test-accompaniment gate (game-code PR with no test)
- Add a quit button in the settings gear to the Placeholder bucket

Behind the scenes:
- WATCHTOWER coherence - daily appendix and branch-cleanup residuals
- Remove the technical appendix from the channel
- Weekly schedule on the branch-cleanup errand as a backstop

## v0.0.27-P273

- Gear glyph fills its box + arm release build
- Add on-screen (non-headless) testing to the infrastructure track
- Header + settings: enlarge gear, drop CHEAT below, add Credits menu, fix About
- Build-publish: correct stale fresh-key release note
- Expand v0.0.29 save work with multiple characters, QA slot, unified build, and entry flow
- Modularity gate: advisory check for hand-rolled building-detail popups

Behind the scenes:
- Extract shared ScreenChrome (gear + CHEAT) across screens
- Add multiple-characters and unified-QA-build save spec
- Add game-style-sizing standard and index it
- Digest icon lists + deterministic reference-PDF staleness check
- Daily Digest carries a conditional seed when Needs-you is non-empty

## v0.0.27-P270

- Remove dead Forge armament-detail path
- Selection-flow lock-reason consolidation + locked wording
- Mark phone tap-to-update done
- Qa-setup: fix POST 3 list rendering, drop auto-update post, add pull-to-refresh
- Rewrite v0.0.27 block to show the six open must-do items
- Qa-setup: step-by-step Android install + auto-update setup
- Regenerate currency icons frameless + mipmaps on
- Force portrait at runtime; bump Android version/code
- Wallet bar: wrap cells so it can't stretch the screen

## v0.0.27-P268

- Fund gems/spoils/crowns from the +99,999 All button
- Add class/magic activatable combat effects to the Placeholder bucket
- Qa-setup: beginner Android/Obtainium install walkthrough + stable-signing update note
- Promote 8 currency icons to assets/icons/currencies + fix config path
- Roadmap header: fix stale art twin filename reference
- Route wallet/resource bar through CurrencyDisplay (sweep 2)
- Build-publish: stable Android signing via keystore secret
- Roadmap + art: add sounds to Placeholder, add maker-category icons to the art list

## v0.0.27-P266

- Currency single-source correction: config owns all 8 currencies + icon paths
- Add screen-ratio scaling to the Placeholder bucket
- Add phone test-delivery and Google Play internal testing to infrastructure track
- Route confirm modal currency display through CurrencyDisplay (sweep 1)
- Currency display system: renderer + two registries + tests (stage 1)
- Remove dead placeholder _open_building_detail from armory and guardhouse tabs
- Reuse gate: add archetype-routing check to the analyzer subagent (MOVE 3)
- Builder popup label: Production to Building
- Add general long-press-for-info feature (Placeholder, no version)
- Modularity Pass (v0.0.27): fix maker-popup category labels in the shared adapter
- Modularity Pass (v0.0.27): detail-popup single source - extract building-detail config into DetailConfigBuilder
- Add detailed-wallet feature under v0.5
- Impl plan v77: strip the delta changelog; re-cut the Foundation to the roadmap
- Regression-test discipline; pin and place the alert badge
- Impl plan v76: fold in run data collection and cheat prevention
- V0.0.29 run data collection, v1.0 cheat prevention; art-track economy rule
- CLAUDE.md: v0.0.27 = the Modularity Pass; roadmap: per-version progress rule
- Reference PDFs: alert #spam-updates when the nightly build fails
- Hosted-runner sync + real-world-money-only disclosure rule
- Weekly Digest: one-line status per check (Checks block), detail still in the appendix
- Weekly Digest: exception-only Technical review, full mechanical output to the appendix, seed 0-5
- Roadmap-sync: add an hourly schedule so queue-merged roadmap changes reach the forum (bot merges do not trigger the push)
- Tooling onto the art side path; sync art editorial rule
- Field manual: box Python generation capability proof (s3) and the v91 chronicle entry (s5)
- One list, full transparency. Add the tooling and pipeline track; rewrite editorial rules to hold back only economics and monetization
- CLAUDE.md: record the box as the primary art-generation lane (conda toolchain), cloud as pinned fallback
- Pin cloud art fallback to the proven glyph commit; mark as fallback to the box lane
- Bug loop: skip pinned forum posts; correct stale poller workflow comments
- Bug loop: owner-gated close, verdict disagree-invites, known-bugs thread links, back-half env-strip
- Regenerate flat icons (glyph source 82d948812bfe3f269ef8f731dcdb07b08160edc4)
- Icon guide: add storage and movement section (staging, production paths, engine import)
- Art regen runner: add chat-fireable push trigger (art-regen-run branch) and record glyph-source commit
- Confirming a bug files it to known-bugs without auto-launching the fix
- Strip whitespace from all the poller's env reads
- Strip whitespace from the poller's NATHAN_ID env read
- Reference-pdfs: nightly schedule + on demand, drop on-change trigger
- Add the Progression Atlas as a third generated player document
- Discord User-Agent on all three loop scripts; watcher posts into the forum thread
- Stamp the build version on the Reference and Manual PDFs
- Poller reads the bug-reports forum's posts (threads), not channel messages
- #about self-sync by channel name + milestone-tree roadmap
- Remove dead build-queue-slot text from Builder alerts
- Point branch-cleanup at github.repository, not the pre-transfer repo path
- Docs reconciliation: rarity removed, research multi-slot, Library level 9
- Watcher matches non-closing Bug-loop-fixes: #N
- Known-bug label + confirm-to-close on the poller
- Known-bugs list publisher (with tests)
- Extend Library to level 9, render research multi-slot
- Weekly digest reviews the player roadmap
- Roadmap sync runs on source change (no manual dispatch)
- Library research queue to level-gated multi-slot
- QA bug-report loop (poller + merge watcher, fail-inert until secrets set)
- Roadmap sync posts before deleting (fail-safe migration)
- Roadmap sync (bot-posting script + workflow + source of truth)
- Drop construction queue to a single slot at every level
- Unify builds: one workflow, one release, one Discord post

Behind the scenes:
- Implementation plan v78 - realign the 27/28 split to the roadmap
- Monthly Test box-offload self-interrogation
- Weekly digest seed must account for every Needs-you/Watching item
- Move vision-sync to the vzqz box runner, add daily schedule
- Restore infrastructure track as its own parallel roadmap section
- Move roadmap-sync to the vzqz box runner
- Reference README - add Progression Atlas, correct cadence to nightly+dispatch
- Painterly building generator + 17 placeholder renders
- One-off workflow to post the bug-forum explainer as the Fortress bot
- Record roadmap canonicalization and decision reversals
- Add idle loop v0.3, NPC build-out, tournament split, onboarding + achievements
- Reorder side sections to the end, decouple art from versions, add v2.0 biomes + placeholder items
- Work-model version numbering + full parallel art track
- Lock flat-icon system, art roadmap, style guides, regeneration runner
- Bump business-infra to v11 and field manual to v6
- Record bug-loop go-live in WATCHTOWER and DECISIONS
- 1:1 note, version clarification, bugs + placeholder sections, phased art, Defense reframe
- Stat-rollup reframe, split Explore into three milestones, balance to v0.6.0
- Merge stat-wiring build, Enhance Defense/Explore, art track up
- Milestone-based detail, split 27, blueprints to Explore, local-then-cloud saves
- Future tiers as prose paragraphs, no version numbers
- Expand the roadmap - evergreen intro + full aspirational tree
- Business-infrastructure v9 to v10 (roadmap/about bot-sync, art-pipeline fix, tooling note)
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
- Spec the full lifecycle and conventions
- Drop dead state-commit step from the poller workflow
- Run the known-bugs publisher on issue events and daily
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

## v0.0.27-P254

- First published build.
