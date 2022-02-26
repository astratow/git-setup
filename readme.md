# git-setup

## INTRO

This document is created because authour is sick and tired of looking through docs to solve issue

## INSTALL git

$ sudo apt-get install git

//This is for debian like linux system

## SETUP GITHUB

You need to get a token.

>Settings>Developer Settings> Personal Access Key

Settings is on top right and Developer Settings will appear on the bottom left (conviniently). Personal access key top left, last line.

## SETUP GIT

Just try to push it as normal. When asked for username set your normal username, when password use token. 

Copy token to text editor. Ensure no white spaces. Copy. SHITF + INSERT to paste into terminal. ENTER.

Any issues?

git config --global credential.helper cache

https://www.edgoad.com/2021/02/using-personal-access-tokens-with-git-and-github.html

git clone repo.git
