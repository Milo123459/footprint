# 🐾 footprint

🐾 Footprint is the all-in-one project manager for Git.

[![wakatime](https://wakatime.com/badge/github/Milo123459/footprint.svg)](https://wakatime.com/badge/github/Milo123459/footprint) ![GitHub Repo stars](https://img.shields.io/github/stars/Milo123459/footprint?style=flat&logo=github) ![GitHub forks](https://img.shields.io/github/forks/Milo123459/footprint?style=flat&logo=github) ![GitHub Sponsors](https://img.shields.io/github/sponsors/Milo123459?logo=githubsponsors) ![GitHub repo size](https://img.shields.io/github/repo-size/Milo123459/footprint)

## The idea

The idea of footprint, is to make one tool, for managing git projects. With contributing in mind, and project ownership. I built this tool as a way of fixing a problem: **Git sucks**. Well, sucks on it's *own*. Contributing to projects requires forking, then cloning, then making a new branch, then making a pull request. This takes time, valuable time, time when you could be doing what you do best - coding. Well, footprint is designed to lead you down a path to a world, where Git has streamlined and optimized workflows.

Commands like `git status` show information you don't care about, or need. **footprint** simplfies it. Rather then running `git status`, it's simply `footprint status`, or, `fp status`.

Get back to doing what you do best, not messing with Git.

## The workflow

If you are contributing to a project, before you write any code, you fork the project, clone and make a new branch. Sometimes, this takes a long time, and you don't want to mess around with it. **Footprint** makes that simple.

Let's say I want to start working on [starship/starship](https://github.com/starship/starship).

Rather then running git on it's own, we can use Footprint.

To contribute, we type `fp contribute starship/starship` and folow a simple interactive menu. This'll allow you to make a branch, asking you what features you will be working on, and ask if you want to make a draft PR. The rest can be ran by seperate commands, for example `fp status` to get what you have changed on the current commit. Or, `fp changed` to see what you have changed on your branch.
