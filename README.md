# useful-bash-scripts

> Provides useful bash scripts and file manager actions.

## Install

#### bash scripts

```
cd ~/Projects
git clone git@github.com:anton-johansson/useful-bash-scripts.git
sudo ln -s ~/Projects/useful-bash-scripts/diff-dev /usr/local/bin/diff-dev
sudo ln -s ~/Projects/useful-bash-scripts/diff-stable /usr/local/bin/diff-stable
sudo ln -s ~/Projects/useful-bash-scripts/textexists /usr/local/bin/textexists
sudo ln -s ~/Projects/useful-bash-scripts/mark-for-comparison /usr/local/bin/mark-for-comparison
sudo ln -s ~/Projects/useful-bash-scripts/compare-with-marked /usr/local/bin/compare-with-marked
sudo ln -s ~/Projects/useful-bash-scripts/is-marked /usr/local/bin/is-marked
```

#### Nemo actions
```
sudo ln -s ~/Projects/useful-bash-scripts/actions/diff-dev.nemo_action /usr/share/nemo/actions/diff-dev.nemo_action
sudo ln -s ~/Projects/useful-bash-scripts/actions/diff-stable.nemo_action /usr/share/nemo/actions/diff-stable.nemo_action
```

## Usage

```
cd ~/Projects/TestProject/Dev
diff-stable some-file.txt

cd ~/Projects/TestProject/Stable
diff-dev some-file.txt

cd ~/Projects/TestProject/Dev
mark-for-comparison file1.txt
compare-with-marked file2.txt
```
