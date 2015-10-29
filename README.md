# useful-bash-scripts

> Provides useful bash scripts and file manager actions.

## Install

#### bash scripts

```
cd ~/Projects
git clone git@github.com:anton-johansson/useful-bash-scripts.git
sudo ln -s /home/<username>/Projects/useful-bash-scripts/diff-dev /usr/local/bin/diff-dev
sudo ln -s /home/<username>/Projects/useful-bash-scripts/diff-stable /usr/local/bin/diff-stable
```

#### Nemo actions
```
sudo ln -s /home/<username>/Projects/useful-bash-scripts/actions/diff-dev.nemo_action /usr/share/nemo/actions/diff-dev.nemo_action
sudo ln -s /home/<username>/Projects/useful-bash-scripts/actions/diff-stable.nemo_action /usr/share/nemo/actions/diff-stable.nemo_action
```

## Usage

```
cd ~/Projects/TestProject/Dev
diff-stable some-file.txt

cd ~/Projects/TestProject/Stable
diff-dev some-file.txt
```

