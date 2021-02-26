# Online-DS-PT-022221

A repository for all study group or optional review resources for the Flatiron School's Online Data Science Part-Time 022221 Cohort

![welcome aboard gif from giphy](https://media.giphy.com/media/FQyQEYd0KlYQ/giphy.gif)


## Written Instructions to Connect to This Repository:

PLEASE NOTE: A recording of me walking through these steps will go live on the Cohort YouTube Playlist around March 4 - I recommend waiting for that recording, and walking through these instructions after watching.

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone your fork down to your local computer
```
git clone https://github.com/[yourusername]/Online-DS-PT-022221.git
```

3. Add the `/flatiron-school/` version as the `upstream` (to pull future changes)
```
git remote add upstream https://github.com/flatiron-school/Online-DS-PT-022221.git
```

4. You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to put your local changes up online):
```
git add [filename]
git commit -m 'message here'
git push
```

### Whenever you want to get updated notes:

5. Grab the changes from the upstream repo
```
git fetch upstream
```

6. Merge new changes onto your local repo
```
git merge upstream/master -m "meaningful message about what you're updating"
```

7. Now you can push the new notebooks to your fork
```
git push
```