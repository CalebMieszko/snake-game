# NYU-SD-01 Milestone Project: Planning

_Before you start programming your project_... plan it!

Complete the planning sections below and include them in the README.md of your project repository. Once you're done, reach out to your instructional staff -- they'll examine your plan, help you scope it appropriately for the tools available to you and think ahead toward technical solutions, and point out any areas that could use any more thought. _Use the template below!_

---

## Project Description

I'm creating a snake game (after the classic style of snake game from the old NES and Atari) that will allow players to try and grow their snake to 100 pieces in under 5 minutes. If they succeed, they will earn a chance to log their score in a "Top Scores" screen that will record the top 10 fastest records of all time.

I was inspired to do this the other day when I was in an arcade bar in Seattle and they had some fun old school games on arcade machines for patrons to play.

## Game Logic

```
Replace this text with pseudocode. Taking big ideas and breaking them down into very small steps. The more complex the portion of the idea is, the smaller and more focused the steps will become. For things I know how to do well, this might read more like cliff's notes or simple bullet points.

- Make a top nav
  - Home page
  - About
  - Contact

- Render snake game on home page
  - Should be adaptable size based on percentage of viewable area on any device
  - Set the game to take 80% of view width
  - Set max-width of 1200px

- Create scoring mechanisms
  - Points are earned by eating blocks to grow bigger and by clearing the map faster.
  - Score cap should be 1000 points for the fastest clear possible.
  - Players get 5 minutes to play. Points earned for time will be broken down like this:
    - For every second played, a potential point is lost. Points are only lost after the first 60 seconds.
      - This will not show up to the player actively, this will be abstracted away. Instead, a total of 500 points for time can be earned. Out of those 500 points, however many are earned will be added to the player's score.
    - 
    - 
    - 
  - What other things impact their score?
  - How will I store the top scores for players moving forward? Can I use localstorage?

  Loss/Victory
  - Players lose if they collide with the wall or if they collide with themselves
  - Players also lose if they run out of time
  - Victory condition is to collect all of the blocks without a collision before the time limit

  The pseudocode should describe in plain, simple language the logic of the game.
Describe the logic involved in player decisions.
  - What are the choices available to the player?
  - What happens when the player makes a choice?
Describe the logic that evaluates the player's victory/loss/progress status.
```

## Deliverables

### MVP Criteria

- My game must be winnable and clearly shows there’s a winner.
  - Loss conditions for running out of time or colliding with anything but a block.
- You must provide clear, easily accessible instructions on how to play the game.
  - Instructions will be on the main page of the site just beneath the game.
- Must have a functional playing field with a moving snake that follows input from the user.

### Post-MVP Plans

- Add instructions within the game, get rid of the text instructions outside of the game. These will be accessible from the main menu. (Which means I will be creating a menu with a Start and Instructions option list)
- Create scoring mechanisms.
- Create a leaderboard that saves top scores.
- Create a customization menu that allows the player to customize the snake.
- Create multiple maps that get more difficult and have different timers as the game goes on.
- Create powerups and map modifications that can be unlocked as the player progresses.

## Project Planning

| Date | Goals |
| ---- | ----- |
| Mon. 2/13 | Create GitHub repository. Complete README.md. |
| Wed. 2/15 | Making sure your deployment to GitHub Pages works.Test my file structure and build my main page. Begin coding basic functionality. |
| Sat. 2/18 |  |
| Mon. 2/20 |      |
| Wed. 2/22 | Test project and plan to test and ensure GitHub Pages deploy is up to date and working successfully ahead of your final commit.  |
| Sat. 2/25 |  Submit completed project. Project presentations. |
