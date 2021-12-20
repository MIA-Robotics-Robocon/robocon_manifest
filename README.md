# Robocon Manifest

## Getting started
- Follow [this](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) tutorial to get git ready
- Use these commands to install Repo
```bash
mkdir -p ~/.bin
PATH="${HOME}/.bin:${PATH}"
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
chmod a+rx ~/.bin/repo
```
To initialize your local repository using the Robocon trees, use these commands:
```bash
mkdir Robocon_22
cd Robocon_22
repo init -u git@github.com:MIA-Robotics-Robocon/robocon_manifest.git -b main
```
Then to sync up:
```bash
repo sync
```
