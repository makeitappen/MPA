# MPA
Multi platform architecture


## Problem
As a native mobile developer, you can deliver the best user experience with best performance. All good.

But you need to write all apps 2 times. Boss is coming that there is no budget for this anymore, he needs something cheaper...

## ~~Solution - Cross platform~~

> Write once, run everywhere! 


`Share all the code.`

It's cheap, boss is happy :sunglasses: :clap:

- Flutter
- React native
- Xamarin
- Ionic
- etc.


BUT...

... frustration for developers: you need to learn new language, new frameworks. :cry:

... frustration for users: bad user experience :cry:

At the end, boss is not happy, he loses users and developers (motivation). :cry:

## Solution - Multi platform

> Write once, use everywhere!

`Share code only, where it makes sense:`
- business logic (Presenter)
- data, repository (Model)
- utilites
- network, serialization

`Not the UI (View) part.`

As a developer you can use your favorite langauge and native SDKs.
A big part of the project can be shared (business logic and test). 

Users are :smiley:, developers are :smiley:, boss is :smiley:. 

All good. :sunglasses: :clap:



## Getting started


You can find the documentation in the [Wiki](https://github.com/makeitappen/MPA/wiki).

<!--
## Sample project

The [Bran](https://github.com/makeitappen/bran) project is a sample iOS and Android app, using MPA.
-->

### Todo

- [x] Write introduction
- [x] Write Project setup wiki page
- [ ] Finalize architecture
- [ ] Create sample project
- [ ] Create 'framework'
