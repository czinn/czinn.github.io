---
layout: default
---

I'm a software engineering student at the University of Waterloo.

I have a bunch of projects on [GitHub]. You can read some project summaries in the **Things I've done** section below. You may also want to take a look at my [résumé][resume].

You can email me at [{{ site.email }}][email].

## Things I do

I solve problems on [Project Euler][pe]. At the time of writing, I am 11th in Canada and in the top 1000 worldwide.

I speak Esperanto (*Mi parolas Esperanton*). Recently I've also been trying to learn Lojban (*.i mi jbobau nintadni*). I also took a weekend and learned Toki Pona (*mi kama sona e toki pona*). I like conlangs.

I play Go. I'm currently a 10-kyu on [OGS] and I'm slowly but steadily improving.

## Things I've done

### Fortuit

I made Fortuit with [Jim Zhang](http://neynt.ca/) at PennApps Winter 2015. Fortuit was inspired by something called overconfidence bias: when we make predictions about the future, we tend to be really optimistic. Fortuit aims to improve prediction-making by letting you track your predictions. This allows you calibrate your predictions and form a more accurate mental model of your mental model of the world.

Try using [Fortuit][tryfortuit]! You can test out the friends feature by adding **charles**. You can also view the source code in the [Fortuit GitHub repo][fortuit].

### Mafia

Mafia is a popular party game. A small number of players are the mafia, and their goal is to eliminate all villagers. The villagers can vote to lynch people, but they risk lynching one of their own number. Some villagers have special powers. When played in real life, a game master is required to faciliate interactions, and they can't play in the game themselves.

I created a simple, minimalistic web app that takes the place of a game master. There are existing websites that do this, but they overcomplicate things with variations and accounts. Plus, it was a fun way to test out some web technologies like AngularJS and Socket.io.

You can view the source code in the [Mafia GitHub repo][mafia].

### Depnunkei

The computer science club at my high school ran a two-week long idle game challenge. An idle game is a game in which most of your time is spent waiting; a perfect example is Cookie Clicker.

My project was Depnunkei, a stock-trading game written in HTML5 and JavaScript. The stocks are unique and randomly generated each game, and more enter the market as companies go bankrupt.

Try playing [Depnunkei][playdepnunkei] and see how much money you can make. You can also view the source code in the [Depnunkei GitHub repo][depnunkei].

### Condi

Condi was my entry to a casual 7DRL (7-day roguelike) among some friends. Condi features random dungeon generation, randomly generated items with special effects, and absolutely no balance. The dungeons gradually get harder as your character gains levels.

You can view the source code in the [Condi GitHub repo][condi].


[resume]: CharlesZinn.pdf
[OGS]: https://online-go.com/user/view/69260
[tryfortuit]: http://fortuit.semicolon.ca
[fortuit]: https://github.com/Semicolon314/fortuit
[mafia]: https://github.com/Semicolon314/mafia
[playdepnunkei]: /depnunkei
[depnunkei]: https://github.com/Semicolon314/depnunkei
[condi]: https://github.com/Semicolon314/condi
[email]: mailto:{{ site.email }}
[pe]: https://projecteuler.net/progress=semicolon7
[github]: https://github.com/{{ site.github_username }}
