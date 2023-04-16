# mac-setup

This is how I setup a new macbook pro for my roles as a project manager and junior full stack developer.

## macOS-config-changes
completely personal preferences but each of these settings just annoy me.

- Minimize windows into application icon (dock)
- Turn off “show recent applications in the dock”
- Change default finder window to Downloads
- Show path (Finder)
- Change the computers name
- Switch to using bash in Terminal
- create a folder "developer" in the directory '/users/YOURUSER/'

## normal apps to install broken out per role

### general-apps
- 1Password
- Fantasical
- Edge
- Chrome
- Spotify
- Slack
- Magnet
- NordVPN
- Day One
- Authy
- Minecraft

### project-manager 
- Slack
- Bear
- Parallels Desktop
- Notion
- Loom
- Cloud storage (dropbox, google drive, ect)
- Zoom

### developer
- VS Code
- Discord
- Xcode
- Postman
- Docker

## setting up development enviornment

### install and configure VS code
1. install by visiting https://code.visualstudio.com/download
2. select a vs code theme 
3. turn on word wrap and autosave
4. install extensions

personal favorites:
TODO: add list of extensions here

### install homebrew
1. installing Homebrew first requires the Xcode Command Line Tools to be installed. enter this command into your terminal: ```xcode-select --install```
2. install Homebrew, copy the following two commands and paste them into your Terminal and press enter, one at a time:

```
touch ~/.bash_profile
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
note: the homebrew documentation can be found here https://brew.sh/

3. be sure to run the 2 commands found in the Next Steps instruction set after installing homebrew. it will provide the instructions on how to configure your shell for Homebrew.
4. run ```brew doctor``` at the end and you should see the message "your system is ready to brew". 

### install and configure git
1. open the terminal application and switch your default terminal to bash by typing in the following command ```chsh -s /bin/bash```
2. use homebrew to install git by entering this command ```brew install git```
3. once the installation is complete, close your Terminal window and open a new one
4. configure your user name and email using the following commands

```
git config --global user.name "your name"
git config --global user.email <your email address>
```

5. check your configuration by running the command ```git config --global --list```
6. create your personal access token in github (instructions: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

### install and configure docker
1. install by visiting https://docs.docker.com/docker-for-mac/install/
2. verify docter installation by running ```docker --version```

### install python

### setup windows 11 for parallels
# mac-setup
