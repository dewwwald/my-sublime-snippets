# Installation

To install run:
```bash
# you might need to swap exclude with include
rsync -r --include='*.sublime-snippet' --exclude='*' ./  ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/

# OR

rsync -r --exclude='*' --include='*.sublime-snippet' ./  [your snippet location here]
```


To update repo:
```bash
rsync -r --exclude='./.git' ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/*.sublime-snippet './'

# OR

rsync -r --exclude='./.git' [your snippet location here] './'
```

Standard location on MacOs:
```
'~/Library/Application Support/Sublime Text 3/Packages/User/'
```
