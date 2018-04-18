# [GamblingTec Bootstrap Lobby Test](https://www.gamblingtec.com)

To create our test lobby we used [Creative](http://startbootstrap.com/template-overviews/creative/), a one page theme for
[Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/).

## Overview

This is a simple one page HTML/Bootstrap application that provides the basics to setup a GamblingTec.com casino. It serves as a resource
to both game developers and casino merchants.

## As a game developer

As a game developer, this template will give you a good idea as to how our system interacts with games integrated into our network. You
will require:
* Our [API](https://docs.google.com/document/d/1_I-ffgrsLPocDhrwDLr6QI3XlmILbG0M8ntx1Mecbdw/edit?usp=sharing)
* A developer account on our [sandbox](https://sandbox.gamblingtec.com)
* A name for your game (the name is customer facing and can be something simple such as "ABC Slots")
* A name for your organisation (games you add to our network are organised under a game publisher name "ABC Slots by Your Organisation").
* An Oauth2 endpoint (https://game.example.com/endpoint)
* Once we have the above, you will be provide with an OAuth2 user name and password as well as a unique game code for your game.

## As a casino merchant

As a casino merchant, this template will explain how to build a casino brand and offer games to your customers from our network.
Each game comes with its own unique set of requirements, however, in general, you will require:
* A merchant account on our [sandbox](https://sandbox.gamblingtec.com)
* A [game uuid](../gamblingtec-code-samples/tree/master/games) (for each game you wish to offer and instructions on how to launch them)
* A good web designer and programmer to put it all together for you (if you wish to hire us, [get in touch](https://support.curacaowebhosting.com/submitticket.php))

## Download and Installation

To begin using this template:
* [Fork, Clone, or Download on GitHub](../tree/master/lobby-bootstrap)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes.
We opted to use bootstrap with this demo lobby in order to show you how a casino can be built so that it can operate
exclusively from a merchants brand.

We do not recommend using this demo as the foundation for a new project, its purpose is to explain how our software works in a simple one page instance.
Our preference is to build our apps using Angular which is too complex for demonstration purposes.

## Required codes

**As a game developer**, you will require a game code for each game you wish to add to our system. Each code must be associated to an account
with valid OAuth2 endpoints on your game application.

If the endpoints are invalid, the authentication will not work and your test game will not load.

**As a casino merchant**, you will be required to have a merchant code for each unique site you offer games from. This code is attached
to our customer account widget and it tells us which account to assign a new registration to, and what merchant links to
include in emails we send to them.

You will have a control panel account which you can access from the my account widget. You will have access to all stats relating to your casino such
as registrations, deposits and transactions.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](../gtec-merchant-code-sample/issues)
here on GitHub.

Found a spelling mistake, grammar error or a better way to explain something? You are welcome to fork this repo, make the update, and offer a pull request.

## Custom Builds

You can hire us to create a custom casino for you. For more information, **[contact us](https://gtec.curacaowebhosting.com/submitticket.php)**.

## About

We offer turnkey, hosted & bespoke casino solutions as well as gambling and casino webhosting products. We work with game
developers who use our licensed platform to get their client casinos up & running!

* https://www.gamblingtec.com
* https://www.curacaowebhosting.com

GamblingTec.com is a product of **[Sunseven NV](https://www.sunseven-nv.com)**, licensed out of Curacao.

* http://www.facebook.com/gamblingtec
* https://twitter.com/gamblingtec
* https://github.com/orgs/sunsevennv

## Copyright and License

Copyright 2006-2017 Sunseven NV Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-creative/blob/gh-pages/LICENSE) license.
