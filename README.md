## Merge Conflict Tests

Thanks for helping us with this project! We're looking to get 2 durations from you:

- Duration of resolving merge conflict in the CLI
- Duration of resolving merge conflict in GitKraken

### What you need

- Clone this repo to your local machine (it's okay to use GK)
- Have a text editor handy (VS Code, Atom, Notepad++ etc)
- Locate the stopwatch feature on your phone or any other app

Please follow these prep step instructions, but make sure you have forked and cloned the repo.

### Pre-test prep:

1. Clone the repo (no need to fork)


### Test 1: Trigger the merge conflict in CLI


1. Start your timer
2. Checkout the `merge-conflict` branch
3. Use the `git merge dev` to attempt a merge. Conflict should trigger
4. Use a file editor tool to open conflicted file (or use preferred conflict resolution tool that is NOT GitKraken)
  - Index.md
    - Accept the dev version of the Our Team section _(The founding was in 2020)_.
    - Accept the merge-conflict version of About section _(I am not a cat)_.
    - Change line 6 from "Wonder Kraken" to "Keif Kraken"
  - reset.css
    - Accept `dev` version 
5. Stage changes and commit to resolve conflict.
6. Stop timer and write down duration. 

### Reset repo

1. Open repo in GitKraken
2. Reset `dev` branch to "Margins at 10" commit (SHA: adc29a2f78b868e5d6b81febf7c86cc92d10898d) and discard all changes.

### Test 2: Trigger the merge conflict in the GK


1. Start your timer
2. In GitKraken, drag and drop the `merge-conflict` branch on top of `dev`
3. Select the "Merge "merge-conflict" into "dev"" option
4. Conflict should trigger
5. Use the merge tool to resolve the conflict such that: 
- Index.md
    - Accept the `dev` version of the Our Team section _(The founding was in 2020)_.
    - Accept the `merge-conflict` version of About section _(I am not a cat)_.
    - Change line 6 from "Wonder Kraken" to "Keif Kraken"
- reset.css
    - Accept `dev` version
6. Stage changes and commit to resolve conflict.
7. Stop timer and write down duration. 


That's it! Please submit your durations AND operating system to Jonathan over Slack. Thanks so much for your help.
