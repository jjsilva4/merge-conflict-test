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

1. Clone the repo (no need to fork) with GitKraken
2. Checkout `merge-conflict` in GitKraken (to create local branch)
3. Checkout the `dev` branch.


### Test 1: Trigger the merge conflict in CLI


1. Start your timer
2. Use the `git merge merge-conflict` to attempt a merge. Conflict should trigger
3. Use a file editor tool to open conflicted file (or use preferred conflict resolution tool that is NOT GitKraken)
  - Index.md
    - Accept the dev version of the Our Team section _(The founding was in 2020)_.
    - Accept the merge-conflict version of About section _(I am not a cat)_.
    - Change line 6 from "Wonder Kraken" to "Keif Kraken"
  - reset.css
    - Accept `dev` version 
4. Stage changes and commit to resolve conflict.
5. Stop timer and write down duration. 

### Reset repo

1. Open repo in GitKraken
2. Reset `dev` branch to "Mario and Luigi" commit and discard all changes.

### Test 2: Trigger the merge conflict in the GK

1. Start your timer
2. Merge "merge-conflict" into "dev". Conflict should trigger
3. Use the merge tool to resolve the conflict such that: 
- Index.md
    - Accept the `dev` version of the Our Team section _(The founding was in 2020)_.
    - Accept the `merge-conflict` version of About section _(I am not a cat)_.
    - Change line 6 from "Wonder Kraken" to "Keif Kraken"
- reset.css
    - Accept `dev` version
4. Stage changes and commit to resolve conflict.
5. Stop timer and write down duration. 


That's it! Please submit your durations AND operating system to Jonathan over Slack. Thanks so much for your help.
