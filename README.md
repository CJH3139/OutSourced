# OutSourced
Repository for the OutSourced Minecraft server

# Setup
This repository contains all the server files and configurtions. Plugins and scripts are included.

1. Clone the repository locally, via git or GithubDesktop.
![Image of how to clone the repo](gitImages/clone.png)
2. Unzip world and config archives _(further explanations below this)_
3. Open a terminal or VSCode workspace
4. Run the project _(further explanations in the "How to run?" section)_

> [!IMPORTANT]
> The world file is zipped. Unzip it to use it. The default `world` folder is gitignored. If you wan't any changes to the world to be reflected in the repo, delete the current `world.zip` and create a new one from your world folder. Make sure you have pulled and replaced your local world before making map changes to avoid overwriting someone elses work.

Other configurations like `server.properties` and plugin ymls can be found in `configs.zip`. These unzip once during the setup. Again if you wish to change these files you will need to create a new zip.

## How to run?
Simply open the server project folder in a terminal or VSCode and execute the `./run` script. There is a Windows version: `./run.bat`, and `./run.sh` for Linux. The script runs the server on 2GB of memory by default.

![How to open in VSC](gitImages/openInVSC.png)

![alt text](gitImages/run.png)

If you do not see a terminal, click on `Terminal` in the navigation bar and select `New terminal` or use the default keybind. For Windows: Ctrl+Shift+`

## Contributing
### Branches
When contributing please make sure to follow the defined standarts. Do not push to the main branch! Always make a new branch for your changes. The branch name should follow a naming convention for e.g. `feature/add-spawn-command` or `fix/player-can-use-tomap-command`.

### Commits and PR
Commits to your branch should follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), e.g. `feat(commands): Added /spawn command`. When you are ready with your changes, create a PR and assign an administrator to review it. The PR name should also follow conventional commits and a description should be provided making it more clear.

### Tips
Before working on anything always _"Fetch"_ first to see if there are any new chages.
![How to fetch changes](gitImages/fetch.png)
If there are, make sure to _"Pull"_ the changes with the same button. This will update your local files with that is on the online repository.

### Tasks
Issues are handled on discord in the `#tasks` channel. 
