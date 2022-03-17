Battle
========

Task
----

Here are the complete User Stories for this project. They begin with some 'Basic' User Stories:
```
As two Players,
So we can play a personalised game of Battle,
We want to Start a fight by entering our Names and seeing them

As Player 1,
So I can see how close I am to winning
I want to see Player 2's Hit Points

As Player 1,
So I can win a game of Battle,
I want to attack Player 2, and I want to get a confirmation

As Player 1,
So I can start to win a game of Battle,
I want my attack to reduce Player 2's HP by 10

As two Players,
So we can continue our game of Battle,
We want to switch turns

As Player 1,
So I can see how close I am to losing,
I want to see my own hit points

As Player 1,
So I can lose a game of Battle,
I want Player 2 to attack me, and I want to get a confirmation

As Player 1,
So I can start to lose a game of Battle,
I want Player 2's attack to reduce my HP by 10

```

Getting started
--------
Start by cloning the project
```bash
git clone https://github.com/adamwoodcock98/rps-challenge
```
If you do not have it already, use Homebrew to install bundler
```bash
brew install bundler
```
Run `bundle` to install gemfiles

Testing
----------
The program contains a series of tests using Rspec and Capybara.

To run all tests across all class files, do the following:

```bash
cd Navigate/to/project/directory

rspec
```

To run tests for a specific class file, do the following:

```bash
cd Navigate/to/project/directory

rspec spec/spec_file_to_run.rb
```
The web app is both feature and unit tested.

> If you investigate the test files, you may notice continued usage of `lats` and `cats` as player names. This was a running joke between myself and my pair partner. Even though it makes no sense on the surface, please see it as a representation of how much fun we had on this project!


Instructions
-------
### Using rack
This app is built using Sinatra/HTTP requests, we can use rack to simulate a client/server on our local machine.

Start by navigating to the project directory in terminal:

```bash
% cd My/Project/Directory/battle
% rackup
[2022-03-14 20:40:38] INFO  WEBrick 1.7.0
[2022-03-14 20:40:38] INFO  ruby 3.0.2 (2021-07-07) [x86_64-darwin21]
[2022-03-14 20:40:38] INFO  WEBrick::HTTPServer#start: pid=23671 port=9292
```
You can now navigate to `localhost:9292` (or whatever rackup outputs as the port) in your browser.

![localhost](https://github.com/adamwoodcock98/MakersPortfolio/blob/main/Evidence/localhost.png?raw=true)

## Entering your name

You will be greeted with the following page:

![landing](https://github.com/adamwoodcock98/MakersPortfolio/blob/main/Evidence/battle_landing.png?raw=true)

Enter both of the players names, then hit Play!

## Playing the game

The game will tell you which player is attacking, both players use the same `ATTACK` button to deal damage to eachother.

You can watch the HP of your opponent dwindle as you attack!

## Takeaways

I thoroughly, thoroughly enjoyed completing this challenge with my pair partner, we had a *lot* of fun. I only wish we had time to complete all of the bonus user stories, to end up with a fully functioning replica of the Pokémon game.

This was our first step into web development, we learned so much, the learning curve was steep, but I feel we handled what we achieved very well, with good efficiency.

This is a project I definitely hope to revisit, and fully implement the rest of the games' user stories.

If you wanted to explore my thoughts and feelings more as we progressed through this challenge, [head over to my week 3 portfolio](https://github.com/adamwoodcock98/MakersPortfolio/blob/main/Week3.md#daily-reflections) where I've listed all of the relevant blog posts.
