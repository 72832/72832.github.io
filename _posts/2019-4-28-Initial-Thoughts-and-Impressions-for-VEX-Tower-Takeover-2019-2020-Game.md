---

title: "Inital Thoughts for Tower Takeover 2019-2020 Vex Game"

categories:
- Tower Takeover
- Design
- Strategy

last_modified_at: 2019-04-28T23:45:00-05:00
---

### Proven First(FRC) Robotics Strategies PDF run through


In the beginning I looked through this INCREDIBLE pdf that is linked [here](https://team914.github.io/tower%20takeover/design/strategy/First-Game-Strategies-PDF-by-Karthik-Kanagasabapathy/).

**Strategic Design**

  

  

You can't go through this game with a *concrete* aim.

  

  

Sacrificing effectiveness hurts your partners.

  

  

**Analyzing the Game**

  

  

Read the rules!

  

  

Examine every possible way to score points, no matter how obscure:

  

- A orange, purple, or green cube in the goal zone.

  

- Autonomous Bonus

  

- (you can get an additional bonus points for cubes in the goal zone with high cubes)

  

  

Examine every possible way to prevent your opponents from scoring:

  

- Moving cubes into the protected zones

  

- Making it so that cubes are in places harder for the opponent to get at

  

- Taking cubes out of the towers so that they are expecting to maximize on

  

- Play defense to make it so that the opponent can't get to their goal zone

  

- Make a certain color only worth one point and make it so that to score points they have to try to use that one

  

  

You cannot prevent your opponents from scoring in these ways:

  

- Mess up their autonomous period

  

- Take out cubes from the alliance towers

  

- Descore their stacked cubes that are already in the goal zone

  

  

Understand the ranking system:

  

- Just like the other vex vrc games

  

**Chokehold Strategies**

  

Is there a chokehold strategy (when executed guarentees victory independant of any action by your opponents or when there is one finite task that overwhelms all other possible ways of scoring)?

  

  

> Once you score cubes in your goal zone there is no way for them to be descored by the opposing alliance *unless they tip*. Once you have a cube in your alliance high zone then it can't be descored by your opposing alliance. This means that having control of the majority of the cubes will be extremely important. If you have all of a certain two colors and make the other one not be stacked at all then, that would mean that you could control the game by just keeping the right colors of cubes in the high cubes. You can also chockhold the other team by getting all of one color and then making it so that that color is put in as many high goals as possible. That wouldn be a great way to score the majority of the points UNLESS someone descores them and puts more of their color inside.

  

  

**Cost-Benefit Analysis**

  

|Item |Cost |Benefit |
|-----------------|---------------------------------------------------------------------|----------------------------------------------------------------|
|Goal Zone |not enough space to not stack cubes, if they tip over then your hosed|This is the only way to score any points except autonomous bonus|
|High Goal |it doesn't give you any points directly, more time and more difficult|the only way that you can affect the match that isn't purely defense and putting their robot between where they want to go|
|Autonomous Bonus |a lot of time and struggle |a 6 point reward and two additional cubes |
|Hogging Cubes |You can't really score cubes nearly as effecive this way |they can't score as many points and that affects swing points |

**Prioritization**

  

|Desired Robot Qualities |
|-------------------------------------------|
|Low center of gravity to avoid tipping |
|A efficient intake of cubes |
|Move lift up and down AFAP |
|Drive speed|


|Desired Robot Functionality |
|-------------------------------------------|
|Traverse field easily and also probably strafing |
|Move cubes to protected areas efficiently |
|Intake, Manipulate, and Stack Cubes |
|Easily get above goal zone plastic |


|Robot Function|Explanation|
|-------------------------------------------|------------------------------------------------------|
|Drive|Mechanum, X drive, or X drive/parallel combo|
|Lift|3x Reverse 4 bar, Scissor lift, cascade lift, 4 bar, or mix of the listed|
|Intake |Passive plastic similar to the passive intakes in ITZ or a automatic tensioned intake|
|Cube Stack Mover|?|
|Scraper Cube mover|?|



  

**Simplicity & Golden Rules**

Golden Rule #1: Always build within your team's limits

- Evaluate your abilites and resources honestly and realistically

- Limits are defined by manpower, budget, and expirence

- Avoid building unnecessarily complex functions

- As you get more experienced start cautiously pushing a few boundaries

  

Golden Rule #2: 
If a team has 30 cubic units of space to put the robot into, make it so that the functions that the robot has to do are efficent and take up the space that makes them as effective as possible.

  

**Other Tips**

Try to identify the different types of robots that will exist:

  

|Robot Type|Explanation|
|-------------------------------------------|------------------------------------------------------|
|Low Stacker|Stacks the cubes from the bottom rather than the top|
|Only High Goals|Moves cubes into protected area and then only manipulates high goals based off of what other people score|
|High Stacker|Stacks cubes from the top|
|Push Bot|Defensive only and tries to push all of the cubes over|

  
 
### Additional Thoughts
The max score is kind of complicated to find out. If you have 7 high purple cubes and the rest of them were stacked then you will get 109. However, if you high zone 6 cubes of the same color and get 1 in another color with all of them introduced in your alliance then it's 121. If it's 0, 2, and 5, and the rest of them are scored then you get 129. The max score that i have found out so far is 141 where you have 2,2, and 3 high stacked and the rest in your alliance.

So actually the way that the app scores it is wrong. It automatically makes it so that all of the scored cubes are zero points rather than one point by default.

My friend and I calculated what the max score is and it looks like if you stack 3,2,2 for the colors and score all of the other cubes then you can get a max of 190 I believe.

I looked through the rules and it looks like if you wanted to you could screw the other guys autonomous over by shoving a line of cubes over past the an autonomous line and screwing up peoples autons. I just read SG2 again and it looks like it should be fine. Sweet! I just read SG7 and it is definitely not ok.

There is also a line down the middle that has game pieces on it but according to SG2 you can't touch the opposing alliances cubes towers or cubes so it looks like you can interact with the cubes and towers on the line.
