# RN diff PURGE

# THIS REPO HAS MOVED TO THE OFFICIAL REACT-NATIVE-COMMUNITY ORGANIZATION. 😍
# FIND IT HERE:  
# 💪 [react-native-community/rn-diff-purge](https://github.com/react-native-community/rn-diff-purge) 🎉
## Huge thanks to everyone involved, and everyone using and praising this repo! No, you are the best!

This repository exposes an untouched React Native app generated with the CLI
`react-native init RnDiffApp`. Each new React Native version causes a new project to be created, removing the old one, and getting a diff between them. This way, the diff is always clean, always in sync with the changes of the init template.

A dedicated branch per version makes changes very easy
to watch. For example:

* https://github.com/pvinis/rn-diff-purge/compare/version/0.28.0...version/0.29.0
(Change in Android template)
* https://github.com/pvinis/rn-diff-purge/compare/version/0.29.0...version/0.29.2
(no change)
* https://github.com/pvinis/rn-diff-purge/compare/version/0.30.0...version/0.31.0
(minor change in `.flowconfig` )

See table below for the complete list.

For some more info about the benefits of this repo's way versus the default way and rn-diff's way, read some of the conversation around [here](https://github.com/react-native-community/discussions-and-proposals/issues/68#issuecomment-452227478).

Please :star: this repository if I helped you, and if you upgraded successfully because of `purge`, [buy me a pizza](https://www.buymeacoffee.com/DGWwHVZ4s) :pizza:

## Diff table (full table [HERE](https://pvinis.github.io/rn-diff-purge))

| From->To    | I                                                                                                         |                                                                                                           | L                                                                                                         | O                                                                                                         | V                                                                                               | E                                                                                               |                                                                                                 | D                                                                                               | I                                                                                               | F                                                                                               | F                                                                                               | S   |
| ----------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --- |
| 0.59.0-rc.3 | X                                                                                                         | -                                                                                                         | -                                                                                                         | -                                                                                                         | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.59.0-rc.2 | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.59.0-rc.2..version/0.59.0-rc.3) | X                                                                                                         | -                                                                                                         | -                                                                                                         | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.59.0-rc.1 | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.59.0-rc.1..version/0.59.0-rc.3) | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.59.0-rc.1..version/0.59.0-rc.2) | X                                                                                                         | -                                                                                                         | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.59.0-rc.0 | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.59.0-rc.0..version/0.59.0-rc.3) | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.59.0-rc.0..version/0.59.0-rc.2) | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.59.0-rc.0..version/0.59.0-rc.1) | X                                                                                                         | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.58.6      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.6..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.6..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.6..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.6..version/0.59.0-rc.0)      | X                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.58.5      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.5..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.5..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.5..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.5..version/0.59.0-rc.0)      | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.5..version/0.58.6)      | X                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.58.4      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.4..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.4..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.4..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.4..version/0.59.0-rc.0)      | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.4..version/0.58.6)      | [->0.58.5](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.4..version/0.58.5)      | X                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.58.3      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.59.0-rc.0)      | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.58.6)      | [->0.58.5](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.58.5)      | [->0.58.4](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.3..version/0.58.4)      | X                                                                                               | -                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.58.2      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.59.0-rc.0)      | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.58.6)      | [->0.58.5](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.58.5)      | [->0.58.4](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.58.4)      | [->0.58.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.2..version/0.58.3)      | X                                                                                               | -                                                                                               | -                                                                                               | -   |
| 0.58.1      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.59.0-rc.0)      | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.58.6)      | [->0.58.5](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.58.5)      | [->0.58.4](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.58.4)      | [->0.58.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.58.3)      | [->0.58.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.1..version/0.58.2)      | X                                                                                               | -                                                                                               | -   |
| 0.58.0      | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.59.0-rc.3)      | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.59.0-rc.2)      | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.59.0-rc.1)      | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.59.0-rc.0)      | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.58.6)      | [->0.58.5](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.58.5)      | [->0.58.4](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.58.4)      | [->0.58.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.58.3)      | [->0.58.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.58.2)      | [->0.58.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0..version/0.58.1)      | X                                                                                               | -   |
| 0.58.0-rc.3 | [->0.59.0-rc.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.59.0-rc.3) | [->0.59.0-rc.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.59.0-rc.2) | [->0.59.0-rc.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.59.0-rc.1) | [->0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.59.0-rc.0) | [->0.58.6](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.6) | [->0.58.5](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.5) | [->0.58.4](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.4) | [->0.58.3](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.3) | [->0.58.2](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.2) | [->0.58.1](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.1) | [->0.58.0](https://github.com/pvinis/rn-diff-purge/compare/version/0.58.0-rc.3..version/0.58.0) | X   |

## To see the full table containing all versions click [HERE](https://pvinis.github.io/rn-diff-purge)

## Notes

### History of this repo

Once upon a time there was react-native. Lots of people used it and loved it. And there were ofter updates. As many as one per 2 weeks. People loved the new versions with all the new cool APIs and components and bugfixes. But how did they upgrade?

Many people tried to upgrade and automate the process, and many failed. One succeded. Nicolas Cuillery ([github](https://github.com/ncuillery), [twitter](https://twitter.com/ncuillery)) made a great script and kept it in the [rn-diff](https://github.com/ncuillery/rn-diff) repo. It basically consisted of a `project` branch, which had a react-native project initialized and upgraded

### Hooks
React Native [0.59.0-rc.0](https://github.com/pvinis/rn-diff-purge#version-changes) gets hooks! 🎉🥳  
Here are some docs:
- [Hooks API Reference](https://reactjs.org/docs/hooks-reference.html)
- [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html)
- [Hooks at a Glance](https://reactjs.org/docs/hooks-overview.html)

Thanks to the RN team!

## Why this repository?
`react-native-git-upgrade` is painful. A simple diff by recreating the project is a much much simpler way to get a diff on every new React Native version.


## FAQ

### Why starting from 0.22.0?

Because I couldn't run `react-native init` with an older version than that without the cli throwing errors. I hope people are not using still 0.22.0 anymore (Jan 2019).

### How did you do this?

I made a [script](https://github.com/pvinis/rn-diff-purge/blob/master/new-version.sh). Then I ran a [helper script](https://github.com/pvinis/rn-diff-purge/blob/master/new-version.sh) to make the rest of the versions.
Now I just ran the `new-version.sh` script manually when I get the email that there is a new version published on npm, and I am making a bot to do that for me.

### How can I contribute?

Unfortunately it's a bit weird. The `master` branch is the keeping-track one. Then there is the `app-base` branch that is the starting point of every other branch. Every react-native verison gets its own branch. So having PRs that change master is great, but for adding a new version, a new branch has to be created, and that is only possible by the contributors of this repo.

Nevertheless, when a new version of React Native is released, we'll have to be prompt to provide
the new diff. Having more collaborators on this project will help in the future. If you're interested, please open an issue to discuss.

One thing that could get some love is the `docs/index.html` file, which produces a very basic html table. I would like to make it prettier and easier to navigation, but my css-fu is level 0. I would love to see what you can do to make it so! <3

### Down here!

If you have: 
- questions
- suggestions
- ideas to make this even better
- the urge to just to say hello to me :)

feel free to make an issue or contact me. I'm pretty easy to find!
