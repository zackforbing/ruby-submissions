Complete this Form before the third check in. Delete this line from your version.

# Game Time Check In # 2

## Instructor Goal Completion

### Increase speed and distance between pipes/Implement some type of level change/For example, 5 then sample

  - [Code](https://github.com/adamhundley/block_party/blob/master/src/LevelManager.js)
  - We completely refactored this to make it easy to constantly create new levels. The LevelManager pulls in modules that have a hash of data used to create each pipe/entry object. The interval manager uses the same information to the set the interval on the window. We are set up to create infinite levels or even have people submit levels via open source.

### Pause Game/Start Game

- [Code](https://github.com/adamhundley/block_party/blob/master/src/BlockParty.js#L147)
- We did the basic pause functionality per the request
- We are still determining a way to calculate the time that has passed in an interval. The difference is small enough that it isn't noticeable, but we would like to see how hard it is to make the intervals stay exact.

### Talk about gravity and movement along x axis

- we discussed this and are going to implement it

## Next Steps?

- color packs for level increase
- lateral movement
- make BlockParty.js under 100 lines
- make all functions under 5 lines
- improve testing
- readme
- firebase for shared high scores

### General Questions, Comments, Concerns?

-----

## Instructor Section

### Points for Second Check In (base 50)

50/50

### Instructor's Goals for Next Check In

Recommendations:
- Blog about this - specifically around building a game with React

'Requirements':
- readme
- make BlockParty.js under 100 lines
- revisit testing

Extensions:
- Colorpack changes (we really really like this one)
- lateral movement
- firebase for shared scores

### Feedback?
