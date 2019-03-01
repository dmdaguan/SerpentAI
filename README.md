![](https://s3.ca-central-1.amazonaws.com/serpent-ai-assets/SerpentFBCover.png)

# Serpent.AI - Game Agent Framework (Python)

[![](https://img.shields.io/badge/project-website-brightgreen.svg?colorB=1bcc6f&longCache=true)](http://serpent.ai)
[![](https://img.shields.io/badge/project-blog-brightgreen.svg?colorB=1bcc6f&longCache=true)](http://blog.serpent.ai)
[![](https://img.shields.io/badge/project-wiki-brightgreen.svg?colorB=1bcc6f&longCache=true)](https://github.com/SerpentAI/SerpentAI/wiki)    
[![](https://img.shields.io/badge/pypi-v2018.1.2-brightgreen.svg?colorB=007ec6&longCache=true)]()
[![](https://img.shields.io/badge/python-3.6-brightgreen.svg?colorB=007ec6&longCache=true)]()
[![](https://img.shields.io/badge/license-MIT-brightgreen.svg?colorB=007ec6&longCache=true)]()  
[![](https://img.shields.io/badge/twitter-@Serpent__AI-brightgreen.svg?colorB=1da1f2&longCache=true)](https://twitter.com/Serpent_AI)

## Warning: End of life (November 2018)

SerpentAI 是一个 Game Agent 框架（ps：在人机对战中，为了区分玩家，通常称机器玩家为 agent ），简单而又强大。它能把任何一个游戏变成用 Python 编写的沙盒环境，供开发者在其中创造游戏 Game Agent 做实验，使用的都是开发者非常熟悉的Python代码。
Serpent.AI 中包含大量支持模块，在以游戏为开发环境时经常遇到的场景提供解决方案，同时也提供加速开发的 CLI 工具。支持 Linux、Windows 和 MacOS 。

#### The development work on the framework has stopped. The necessary time to keep up with the crazy nature of reinforcement learning, the bug fixing and community support cannot be justified anymore (sadly). The repository will remain up as it should be, for people interested in the field, a very exhaustive resource code-wise to interact with games for machine learning. There is a ton to learn by snooping through the code. Have Fun!

Serpent.AI is a simple yet powerful, novel framework to assist developers in the creation of game agents. Turn ANY video game you own  into a sandbox environment ripe for experimentation, all with familiar Python code. The framework's _raison d'être_ is first and foremost to provide a valuable tool for Machine Learning & AI research. It also turns out to be ridiculously fun to use as a hobbyist (and dangerously addictive; a fair warning)!

The framework features a large assortment of supporting modules that provide solutions to commonly encountered scenarios when using video games as environments  as well as CLI tools to accelerate development. It provides some useful conventions but is absolutely NOT opiniated about what you put in your agents: Want to use the latest, cutting-edge deep reinforcement learning algorithm? ALLOWED. Want to use computer vision techniques, image processing and trigonometry? ALLOWED. Want to randomly press the Left or Right buttons? _sigh_ ALLOWED. To top it all off, Serpent.AI was designed to be entirely plugin-based (for both game support and game agents) so your experiments are actually portable and distributable to your peers and random strangers on the Internet.

You'll also be glad to hear that all 3 major OSes are supported: Linux, Windows & macOS.

![](https://s3.ca-central-1.amazonaws.com/serpent-ai-assets/demo_isaac.gif)

_Experiment: Game agent learning to defeat Monstro (The Binding of Isaac: Afterbirth+)_

## Background

The project was born out of admiration for / frustration with [OpenAI Universe](https://github.com/openai/universe). The idea is perfect, let's be honest, but some implementation details leave a lot to be desired. From these, the core tennets of the framework were established:

1. Thou shall run natively. Thou shalt not use Docker containers or VNC servers.
2. Thou shall allow a user to bring their own games. Thou shalt not wait for licensing deals and special game APIs.
3. Thou shall encourage diverse and creative approaches. Thou shalt not only enable AI flavors of the month.

_Want to know more about how Serpent.AI came to be? Read [The Story Behind Serpent.AI](http://blog.serpent.ai/the-story-behind-serpent-ai/) on the blog!_

## Documentation

Guides, tutorials and videos are being produced and added to the [GitHub Wiki](https://github.com/SerpentAI/SerpentAI/wiki). It currently is the official source of documentation.

![](https://s3.ca-central-1.amazonaws.com/serpent-ai-assets/demo_ymbab.gif)

_Experiment: Game agent learning to match tiles (You Must Build a Boat)_

_Business Contact: info@serpent.ai_
