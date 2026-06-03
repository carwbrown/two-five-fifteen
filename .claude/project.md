PROJECT: 2-5-15 Workout App
index.html — hosted at your GitHub Pages URL
The Method (2-5-15)

2 = train each muscle twice per week
5 = 5 hard sets per muscle per session
15 = cap total session volume at 15 sets

Structure

2 full-body sessions per week (Mon + Thu)
Each session = 3 compound exercises × 5 sets = 15 sets total
Both sessions hit every major muscle group — NOT an upper/lower split
Session A and B use different exercises for the same muscles to prevent accommodation
Rest ~72 hrs between sessions

Equipment

Dumbbells (various weights) + floor mat only
No bench, no bar, no pull-up bar

Session A (Monday)

DB Thruster — Quads, Glutes, Shoulders, Triceps
Deadlift → Upright Row — Hamstrings, Glutes, Traps, Shoulders
DB Floor Press — Chest, Triceps, Shoulders

Session B (Thursday)

Reverse Lunge → Bicep Curl — Quads, Glutes, Biceps
Single-Leg RDL → Row — Hamstrings, Glutes, Back
Push-Up → T Rotation — Chest, Triceps, Obliques, Core

Swap Library (rotate in after 4–6 weeks)

Clean and Press → replaces Deadlift→Upright Row (Session A)
Renegade Row → replaces Floor Press (Session A) if back needs more volume
Glute Bridge + Chest Fly → replaces Floor Press (either session)
Glute Bridge + Skull Crusher → replaces Push-Up→T Rotation (Session B)
Arnold Press → replaces any press when shoulders need direct work
DB Surrender → replaces Thruster (Session A)
Curtsy Lunge + Rotation → replaces Reverse Lunge→Curl (Session B)

Design

Dark theme: --bg:#0d0d0d, --surface:#161616, --card:#1c1c1c
Fonts: Bebas Neue (headings/numbers) + DM Sans (body) via Google Fonts
Accent colours: gold #c8a96e (2), red #e05c5c (5), blue #5b9bd5 (15), green #52b788 (muscles)
Layout: sticky header with pill badges, tab nav, exercise cards (120px gif + info), set tally boxes
GIFs sourced from media.tenor.com with emoji fallbacks on error

Research Sources

NASM: blog.nasm.org/functional-training-compound-workouts — movement patterns (push/pull/squat/hinge/lunge/rotate), beginner→advanced progressions
Fitness Phantom: thefitnessphantom.com/dumbbell-compound-exercises — 25 compound combos, Bridge Press, Deadlift→Upright Row, Surrender
NML: nourishmovelove.com/full-body-compound-exercises — Glute Bridge + Skull Crusher, Push-Up + Renegade Row combo
Runstreet: runstreet.com/blog/compound-exercises-with-dumbbells — Clean and Press

Key decisions made during build

Rejected upper/lower split — chest would only get hit on upper days, violating the 2× rule
Rejected rep-range interpretation of "2-5-15" (e.g. 2 heavy / 5 moderate / 15 light) — the numbers refer to frequency, volume per session, and session cap
Compound movements chosen specifically so one set counts toward multiple muscles simultaneously
Floor press chosen over bench press — mat only constraint
Reverse lunge chosen over forward lunge — easier on knees, better glute activation

GitHub Pages

Repo: github.com/[username]/[reponame]
Live URL: https://[username].github.io/[reponame]
To update: edit index.html in repo → commit → live within ~1 min