# Apache Cordova mobile framework

You will have to have Apache Cordova https://cordova.apache.org installed fully use this repo you can do this by runnning the following command in your terminal `npm install -g cordova` 

This repo comes with a cordova app already bundeled with it, which resides in the `cordovaapp` directory where you will find a file named `config.xml`. Inside that file you can edit your: app name, app description , author information which is recommended since the default is `HelloCordova`

Once you execute `npm run build` it will build your pristine app and copy it over to the `cordovaapp/www/` directory.

Then you can add your mobile app platform by typing: `npm run add-android` for Android and `npm run add-ios` for iOS apps.
this will tell cordova to build your project for the specific platform.

If you already have a platform added in your cordova project and need to updated it, you just need to run `npm run prepare` and it will update the source in your cordova project for all platforms. Or if you want to just updated a specific platform you can also. `npm run prepare-android` for Android or `npm run prepare-ios` for iOS platform.

Your platofrm project folders you can open in either Android Studio or xCode depending. Will be in `cordovaapp/platforms/`

Future updates will include automatic circleCI deployments and support for other platforms as requested.

# Pristine Typescript React Materal UI

An open source repository in its original condition. It leverages Typescript, React, Material UI theming, moment.js and i18next to give a good starting point for new and existing projects.

Pristine Typescript React Material UI is a fork of [Pristine](https://github.com/etclabscore/pristine).

There are a lack of repositories to start from to build community driven, multi-language open source projects. This is a complete starting point, it follows a Documentation Driven Development approach, and can be used as a resource to augment existing documentation.

![pristine-react-material-ui](https://cdn.discordapp.com/attachments/521369156751458316/636577714760843275/app_starter.gif)

## How to use Pristine in your project

There are 3 options for using pristine with your project.
1. Fork this repo as the start of your own, OR
2. [follow these instructions](https://thoughts.t37.net/merging-2-different-git-repositories-without-losing-your-history-de7a06bba804) to use it on an existing repository.
3. Use the `Use this template` button on this repository.

## Documentation Driven Development

There are many ways to drive open source development. Documenting the problem in the README gives a middle ground between technical and non-technical specifications. This allows organizing solutions to this challenge around community and documentation.

> [...] a beautifully crafted library with no documentation is also damn near worthless. If your software solves the wrong problem or nobody can figure out how to use it, there’s something very bad going on.

- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) by Tom Preson-Werner

### Conventions and Specifications

This repository has some strong opinions built in like circleci, semantic-release, npm. So feel free to fork and change it at your own discretion. It is only meant to be a starting point. That being said:

Using conventions, documentation and specifications make it easier to:
- communicate the problem you are solving
- ease onboarding
- build and use composable tools
- promote open source contribution and engagement
- promote issue and feature discussion on Github itself

#### Resources

- [Pristine](https://github.com/etclabscore/pristine)
- [material-ui](https://material-ui.com)
- [i18next](https://www.i18next.com/)
- [opensource.guide](https://opensource.guide/)
- [Github community profiles for public repositories](https://help.github.com/articles/about-community-profiles-for-public-repositories/)
- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
- [pengwynn/flint](https://github.com/pengwynn/flint)
- [Working Backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html)
- [Literate programming](https://en.wikipedia.org/wiki/Literate_programming)
- [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc)
- [Inversion and The Power of Avoiding Stupidity](https://fs.blog/2013/10/inversion/)
- [choosealicense.com](http://choosealicense.com)

## Getting Started

To get started, [fork](https://help.github.com/articles/fork-a-repo/) or [duplicate](https://help.github.com/articles/duplicating-a-repository/) the repository. Then edit this file and delete everything above this line.

Then edit the `package.json` and change the `name` and `homepage` fields to match your newly created repository.

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.
