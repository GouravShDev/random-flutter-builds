# Random-Flutter-Builds
This repo contains github action that can be used to compile flutter app and generate apk without pc. All you need is to provide link of the repo of the source.

## How to use
1. Find the url of the repo which you want to build apk. 
    - For example : https://github.com/GouravShDev/Tv-Maze-App
2. Only username and repo name is required for github action to work.
    - So the url becomes : GouravShDev/Tv-Maze-App
3. Now go ahead and fork this repo and go to the Actions tab in your fork.
4. In left panel click on Build Job after that "Run workflow" button will appear click on it.
5. Now a dialog will appear asking various question regarding the building the app.
6. Enter any name for the build and enter the flutter sdk version you want to use to compile app ( It can be found in pubspec.yaml file of the flutter project ).
7. finally enter the repo string from the Step 2 in "Get Repo".
8. Then Run workflow and You're done. easy right?.
