# Ludo Khelo Game with Flutter 

Have you ever thought of gaining gaming experience with Flutter? Have you ever thought about building an app similar to Ludo King with modern features? Have you ever thought about how the Ludo app generates revenues? Here we go to build an interesting game with Flutter!

[![support](https://img.shields.io/badge/plateform-flutter%7Candroid%20studio-9cf?style=for-the-badge&logo=appveyor)](https://github.com/shahzebnaqvi/Ludo_Khelo)
[![License](https://img.shields.io/badge/License-Apache%202.0-2196F3.svg?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)
[![language](https://img.shields.io/github/languages/top/smokelaboratory/fludo.svg?style=for-the-badge&colorB=00bfab)](https://kotlinlang.org/)




## Features

* Tokens can come out of Home Area only when dice has 6.
* True Dice
* Cut/Token Kill logic implemented.
* User can tap on a token to make it move. Only valid moves are made.
* Safe area "Star" implemented.
* Safe area coloured path near-final destination implemented.
* Tokens follow the only eligible path.
* Animated reversal of cut/killed tokens.
* Works on both iOS and Android

This project is free to use and can act as a starting point for your awesome Ludo App.




## Gameplay

In order to play the game, you need to first run it using a simulator or device.

* Tap on dice at the bottom.
* Tap on the token.
* Token moves if the move is valid.
* Cut will happen when applicable.
* A cut token will traverse all the way back to home occupying the first available slot. <br><br>

![gameplpay](https://github.com/shahzebnaqvi/Ludo_Khelo/blob/master/images/ludo.jpg)


## ⭐ How to get started?

[![forthebadge](https://forthebadge.com/images/badges/not-a-bug-a-feature.svg)](https://forthebadge.com) <br>

### 1️⃣ Fork it :fork_and_knife:

You can get your own fork/copy of [Ludo_Khelo](https://github.com/shahzebnaqvi/Ludo_Khelo) by using the <kbd><b>Fork</b></kbd> button.

<br>


### 2️⃣ Clone it :busts_in_silhouette:

You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/Your_Username/Ludo_Khelo.git
```

> This makes a local copy of repository in your machine.

Once you have cloned the `Ludo_Khelo` repository in Github, move to that folder first using change directory command on linux and Mac.

```sh
# This will change directory to a folder Ludo_Khelo
$ cd Ludo_Khelo
```

Move to this folder for all other commands.

<br>



### 3️⃣ Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/Ludo_Khelo.git (fetch)
origin  https://github.com/Your_Username/Ludo_Khelo.git (push)
```
Now, lets add a reference to the original [Ludo_Khelo](https://github.com/shahzebnaqvi/Ludo_Khelo) repository using

```sh
$ git remote add upstream https://github.com/shahzebnaqvi/Ludo_Khelo
```

> This adds a new remote named ***upstream***.

See the changes using

```sh
$ git remote -v
origin    https://github.com/Your_Username/Ludo_Khelo.git (fetch)
origin    https://github.com/Your_Username/Ludo_Khelo.git (push)
upstream  https://github.com/shahzebnaqvi/Ludo_Khelo.git (fetch)
upstream  https://github.com/shahzebnaqvi/Ludo_Khelo.git (push)
```

<br>



### 4️⃣ Sync it :recycle:

Always keep your local copy of repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune

# Switch to `master` branch
$ git checkout master

# Reset local `master` branch to match `upstream` repository's `master` branch
$ git reset --hard upstream/master

# Push changes to your forked `Ludo_Khelo` repo
$ git push origin master
```

<br>



### 5️⃣ Ready Steady Go... :turtle: :rabbit2:

Once you have completed these steps, you are ready to start building this project.

<br>

