# Rules of the Built-in Quality Game

[![A team playing the built-in quality game](photos/1-team-small.jpeg)](photos/1-team.jpeg)

## Goal of the game

To pull as many features from Idea to Production as possible.

Experience the increase in value delivery as we add more built-in quality to our software development process.

## What it looks like

You are a team of fresh grad starting a new project. You have a lot of ideas, but everything is still to do. During the game, we'll represent building the product as a [Kanban board](https://en.wikipedia.org/wiki/Kanban_board), and work items as small colored pieces of paper.

At first, as a fresh grads, you'll suffer from your lack of build-in quality practice. As time goes, and as you master industry best practices, you'll see your value delivery rate increase.

Every team member will take one 1 or more roles and will be responsible to pull work items in his column. If something goes bad when an item reaches production, it will have to be reworked. Regularly, you can chose to work on mastering new practices instead of features. The more best practices in place, and the smoother the release will become.

The game is played in rounds (representing days). During a round, each team member can pull items from the previous column. It's only when all the players have pulled their work items, that we can move to the next round.

The game ends when you feel you have learned enough. Take the opportunity to discuss your insights with other participants.

The material is built to be as self-explanatory as possible. So it should be possible to have people play without reading the full instructions up-front.

## Suggested session agenda

This is an agenda we prepared for a 1h30 conference workshop.

|Phase | Details | Duration | Elapsed Time |
|------|---------|----------|--------------|
| General presentation | Present the game and its goal | 5m | 5m|
| Think it then ink it | Let participants recall what they already know about built-in quality | 5m | 10m |
| Built-in quality presentation| Quick summary of what built-in quality is | 5m | 15m |
| Game setup | Show the instructions and let the teams setup their game | 10m | 25m |
| Play level 0 | The game starts, participants get use to it | 15m | 40m |
| Play level 1 | Participants get a free best practice | 10m | 50m |
| Play level 2 | Give red (improvement) tickets to participants | 20m | 1h10 |
| Learning log | Ask participants to write down what they learned during the session, and discuss about it together | 10m | 1h20 |

It relies on the C4 workshop model presented in the book [Training from the back of the room](https://www.goodreads.com/book/show/8141935-training-from-the-back-of-the-room).

Here are [corresponding slides](material/Built-In%20Quality%20Game.pdf).

### General presentation

Check [Goal of the Game](#) section.

### Think it then ink it

This is an activity from the book [Training from the back of the room](https://www.goodreads.com/book/show/8141935-training-from-the-back-of-the-room). Here are the instructions:

`Think about what you already know about built-in quality. Write three of these facts on an index card. Be ready to state them when asked.`

### (Optional) One person expert jigsaw (10m)

Again, this is an activity from the book [Training from the back of the room](https://www.goodreads.com/book/show/8141935-training-from-the-back-of-the-room). The goal is to provide different parts of the information to different people at the table. It's then up to them to summarize what they have understood and make all the parts fit together.

`You each received a different information about built-in quality.`

`Exchange with your colleagues until one of you can summarize the full content to all the table​.`

### Built-in quality Presentation

> Inspection does not improve the quality, nor guarantee quality. Inspection is too late. The quality, good or bad, is already in the product. Quality cannot be inspected into a product or service; it must be built into it.
>
> —W. Edwards Deming

Here is the key idea behind built-in quality: the earlier in the delivery process an error is made, the more waste it will generate until the feature satisfies the customer.
The earlier we fix an error, the better!

For example:

* If you build the wrong product, the design, coding, testing... in fact *all* the work on this product will be wasted
* If a developer leaves a bug in his implementation of a feature, this will limit waste to testing, support and rework
* At the other side, if an error is left in delivery configuration, then it should be fixed very cheaply 

Built-in quality is a set of practices and principles that enable to avoid errors in the first place, instead of trying to fix them later. Can you give examples of practices?

Typical built-in quality practices include:

* Test Driven Development
* Behaviour Driven Development 
* Continuous Integration
* Dev-Ops
* Walking Skeleton
* Lean Startup

We want to illustrate this with a game. We'll see how mastering these techniques increases the rate at which we can deliver value.

### Game Setup

Check the [What it looks like](#) section.

```
Let's start to play! 

1. Create a team of up to 8. Try to mix profiles (technical, business, test...)
   to maximize learning
2. Let's open the 'Level 0' sleeve together
    - 1st, you have the kanban board, where you'll try to pull items from
      idea to production.
    - 2nd, there are color tickets that represent the work item that will
      move through the kanban board
    - 3rd, there is a tracking sheet, to track how many complete features you
      have delivered at every round. Optionally, the production-role person
      can use a laptop and a shared spreadsheet (instead of a sheet of paper)
      to track the progress throughout the game.
    - 4th, you have 8 role cards. You'll each be responsible for one or more
      columns on the kanban board. Each team member should pick one or more
      roles (preferably in adjacent columns), and read their role(s)
      reference card.
    - 5th, 2 dices and a dice reference card. When you'll try to deliver
      things to production, you'll roll the dices to see the outcome. If a
      problems occurs, the item will be go back to a previous column to
      be reworked.
    - 6th, there are the full rules of the game. In case there is something
      that is not clear about the rules, you should find the answer there.
4. Take a few minutes to get a global grasp of the game.
5. It should all become clearer as we start to play. You can ask an animator if
   you are in doubt.
```

Here is [a google sheet scoreboard](https://docs.google.com/spreadsheets/d/15K90zPhD02unMYQVIwJEs9rjMmrr_ksaoTUjFuXrz4g/edit?usp=sharing)
 you can copy to track your progress.

### Play level 0, 

```
Before jumping in the game at full speed, it's a good time to have a few blank
rounds of play to get the grasp of it.

1. Let's start all together.
2. Production player, be ready to count rounds and keep track of what's 
   delivered.
3. Every round, from right to left, players can pull work in their column if
   there are tickets in the previous one
4. Let's do the first few rounds together
    - 1st round: 
         - The funnel-player pulls an idea into the funnel. Write down an
           idea ID (#1) on it. 
         - The production-player tracks: round 1 => 0 features
    - 2nd round:
         - the product-backlog-player pulls the #1 ticket from funnel to
           product-backlog
         - the funnel-player can pull a new idea into the funnel, with a new
           ID
         - The production-player tracks: round 2 => 0 features
    - 3rd round:
         - the sprint-backlog-player pulls *and splits* the #1 item from
           product-backlog to sprint-backlog. Items are always split there.
         - the product-backlog-player pulls another item from funnel to
           product-backlog
         - the funnel-player can pull a new idea into the funnel, with a new
           ID
         - The production-player tracks: round 3 => 0 features
    - 4th round: I'll let you continue
5. By the 15th round, work can be pushed to production. It's time to practice a
   blank release
```

#### Reminders and Notes

```
* Production player: don't forget to keep track of what's going on!
* It's not a good idea to pile work in queues
* Run the dice for every work item, not once per delivery or feature
* If in doubt: check the rules, or ask an animator
```

### Play level 1

```
Now that everyone masters the game, let's play for real!

1. Let's open the 'Level 1' sleeve together
    - 1st, there are 7 best practice game cards presenting the different
      practice improvements that are possible in the game.
    - 2nd, column hiders that you will use to 'skip' columns when improvements
      tell you to do so.
    - 3rd, a practice reference sheet, that you'll read aloud when you master
      a new improvement.
2. Pick a random 'free' unfair advantage best practice. If they get
   'Craftsmanship', no luck, they start with nothing :-(
3. Pause for a while and read out loud the reference sheet section about this new
   practice.
4. Apply the actions of this best practices, and resume the game.
5. As before, the production player should keep track of the delivered features
   per round
```

Here is the [reference sheet](Practices.md).

#### Reminders and Notes

```
* When you hide a column, put existing tickets on top of it and deal with them
  in the next round 
* Re-split tickets that were sent back at product-backlog!
* If you reach the end of the tracking sheet, start again from the left 
* If in doubt: check the rules, or ask an animator
```

### Play level 2

```
You now have red (improvement) tickets that you can use to master a new skills.

1. Let's open the 'Level 2' sleeve together
    - 1st, there are red (improvement) tickets that you will use to track your
      progress about mastering new best practices. 
    - 2nd, there is the 'How to master new best practices' reference card. It
      says that you'll need to pass an red ticket from funnel to production to
      master a new best practice. 
2. Discuss until you come to an agreement about what skill you want to invest
   in.
3. When the improvement ticket reaches production, pause and read the
   reference sheet section aloud.

/!\ Red (improvement) tickets:
* get split as any feature
* get through production without rolling the dice
```

#### Reminders and Notes

```
* Red tickets still need to split
* Don't roll the dice for red tickets
* Pause and read the reference sheet section aloud
* If you reach the end of the tracking sheet, start again from the left 
* If in doubt: check the rules, or ask an animator
```

### Learning log

This is an activity from the book [Training from the back of the room](https://www.goodreads.com/book/show/8141935-training-from-the-back-of-the-room). Here are the instructions:

`In what ways does this information change previous perceptions you’ve held about built-in quality? How do you think you might use this information? Be ready to share with your table.`


## Real-Time Variant

We tried a real-time variant of the game. On the plus side, it's faster and more engaging. On the flip side, there won't be the same kind or amount of learning.

You can squash this session in 45 minutes instead of 75. In this variant, there are no rounds. All the players play simultaneously, and are continuously pulling items to their columns. The time is tracked in real-time minutes instead of rounds.

Be warned though, that people will learn more about lean flow here than from built-in quality.

## Characteristics of the game

### Number of players

The game is played in teams of up to 8. Many teams can play alongside each other during the same session. The more teams the better to discuss learning at the end.

### Duration

1h to 1h15 including preparation and end of session learning.

## Material

Every team needs the following:

### An 8-columns board

![Printable picture of the board](material/board.jpg)

To print on A3

### A heap of colored work item cards

[![A bunch of small colored tickets to represent work items](photos/tickets-small.jpg)](photos/tickets.jpg)

Work is represented by small colored tickets. You'll need to cut out a bunch of these before the game. Cut these to fit in the width of the Kanban columns.

Use separate red tickets for best practice improvements 

### 7 Best practice cards

![Printable picture of the best practices](material/best-practices.jpg)

To print on A4

### Dice and best practices reference cards

![Printable picture of the dice and best practices reference cards](material/ref-cards.jpg)

To print on A4

### 2 6-faced dices

![Photo of 2 6-faced dices](https://upload.wikimedia.org/wikipedia/commons/6/6a/Dice.jpg)

_By Gaz at English Wikipedia [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/), via Wikimedia Commons_

### 8 roles cards

![Printable picture of the first 4 roles](material/roles-1.jpg)
![Printable picture of the last 4 roles](material/roles-2.jpg)

To print on A4

### A tracking sheet

![Printable tracking sheet](material/tracking-sheet.jpg)

To print on A3

### Column hiders

![Printable column hiders](material/column-hiders.jpg)

To print on A4

### Larger printing

If you want, it might be convenient to print everything at twice the size.

---
[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

Built-in Quality Game by <a xmlns:cc="http://creativecommons.org/ns#" href="http://philou.github.io/built-in-quality-game/" property="cc:attributionName" rel="cc:attributionURL">Philippe Bourgau</a> is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).