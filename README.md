# TABLE Exercises

Group exercises for TABLE, published with GitHub Pages. The root `index.html` lists every exercise; each exercise lives in its own folder.

| Exercise | Folder | Saves answers under |
|---|---|---|
| Two Futures | `two-futures/` | `two-futures-v1` |
| Overcoming Objections | `client-fears/` | `client-fears-v1` |
| The Business Hierarchy of Needs | `business-hierarchy-of-needs/` | `hierarchy-of-needs-v4` |

## Adding a new exercise

1. Make a new folder, e.g. `my-exercise/`, with an `index.html` inside.
2. Give it its **own** localStorage key (e.g. `my-exercise-v1`). Every exercise shares the same domain, so two exercises with the same key would overwrite each other's answers.
3. Add `<a class="home" href="../">← All exercises</a>` at the top so people can get back to the list.
4. Add an entry to the `EXERCISES` list in the root `index.html` (path, title, blurb, storage key, and a small `hasAnswers` check so the list can show "In progress").

Don't rename an existing exercise's storage key unless you're fine with everyone's saved answers disappearing.
