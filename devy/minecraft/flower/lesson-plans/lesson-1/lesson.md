<header title='Turtles & Minecraft' subtitle='Flower Garden: Lesson 1'/>

<notable>

<iconp src='/icons/activity.png'>### Overview</iconp>
Students learn the interface of MinecraftEdu and write programs in Lua to move and build simple structures and shapes with a turtle.  

<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can use function calls to move my turtle and build in Minecraft.

<iconp src='/icons/agenda.png'>### Agenda</iconp>

#### Length: 60 minutes

1. Engage: Flower Garden Project (3 minutes)
1. Explore: Turtle Actions (15 minutes)
1. Explain: Function Calls (12 minutes)
1. Elaborate: Build Challenges (20 minutes)
1. Evaluate: Exit Challenge (10 minutes)

<note>

<iconp src='/icons/materials.png'>### Materials</iconp>

#### Teacher Materials
- Computer
- Projector
- MinecraftEdu
- [Lesson 1 Slides][slides]


#### Student Materials
- Computer
- MinecraftEdu


<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Function call** - A programming element that tells the computer to do something. In the beginning, most function calls will cause the computer to perform an action.

</note>
<pagebreak/>
#### 1. Engage: Flower Garden Project (3 minutes)

- [ ] **Motivate:** Reveal the Flower Garden Project over the projector. Show turtle building a flower in Minecraft.
  >>“In this class we are going to create flower gardens in Minecraft using turtles! Turtles in Minecraft can build for us, we just need to code them using a programming language called Lua. Before we write programs in Lua for turtle, let’s read code in Lua.”



#### 2. Explore: Turtle Actions (10 minutes)

- [ ] **Group Exploration:** Students explore the different function calls of turtle in a whole class, unplugged activity. For each program, ask for a volunteer to be the robot and act out the code, then the class will be the computer and read the program one line at a time. Students will stand on the corresponding square.
  >> “Let’s read code and predict what will happen.”

<iconp type='question'>What will turtle do when we run this program?</iconp>
<iconp type='question'>What does each line mean?</iconp>
<iconp type='question'>What do you notice about the commands? How are they written?</iconp>



#### 3. Explain: Minecraft (12 minutes)

- [ ] **Code Along:**  Students follow along on their own computer as you walk through each step of logging onto MinecraftEdu. Before the end of the code along, review basic Minecraft player control keys.

> > “Open your computers and following along as we walk through the steps to log into Minecraft.”

**Steps:**
  1. Use Spotlight Search to find MinecraftEdu.
  2. Double click on app.
  3. Click on “Start MinecraftEdu”.
  4. Login Mode: MinecraftEdu, click Launch.
  5. Type in username: firstlaststudent. This will be your username for the class.
  6. Click Multiplayer, then Add server.
  7. Type _______ into Server Address then click done.
  8. Select Server, then click Join Server.
  9. Choose a minecraft skin, click ‘Connect’, then tilt screen down.
        - When all students are logged in, give remote to all and give turtle to all.  
        - Preview the next step before students do: Show students how to place turtle and hold remote. Students should have laptops halfway closed during this preview.
  10. Students open laptop, place turtle, and hold remote. Turtles are placed using ‘control’ click or 2 finger click on trackpad. To use a remote, hold their remote and use ‘control click’ or 2 finger on turtle to use remote.

Review: Review Minecraft basic player controls and how to use trackpad (2 finger click and ‘control’ click)

> > “Once you have placed your turtle in front of you and have a remote, close your laptop.”

<note type="tip">Uphold good classroom management on computers. When you give each step, students should have eyes on you and hands off computers.
</note>

<br/>

- [ ] **Model** coding turtle in Minecraft and how to navigate the editor. Write and run Program #3 from above. Narrate each step you do when coding turtle. Highlight key features of Turtle menu:
  >> “Let’s check our predictions and see what turtle does in program #3”


**Steps:**
  1. Right click on turtle.
  2. Select editor and create a new file program.
  3. Type code for Program #3 from above, reference API on the right.
      Tip: Teach autocomplete using right arrow or tab.
  4. Click on the Run Button.
  5. Observe turtle’s actions.
      Tip: Exit turtle menu to back up from turtle to get a better view of turtle building.
  6. Press ‘0’ (zero) to reopen turtle menu. Click undo to undo all building and reset turtle.
  7. Run program again.

#### 4. Elaborate: Build Challenges (20 minutes)

- [ ] **Guided Practice:** Together as a class, program turtle to build the build challenge.
  >> “Now we know how turtle moves, let’s start building in Minecraft.”

**Steps:**
  1. Go to Minecraft, add the correct wool color to turtle inventory slots.
	Note: Remember to give students wool using the Teacher Menu.
  1. Create a new file and name the file, ex: verticalLine. File names cannot have spaces, instead we can use camelCase. camelCase is when you take out the space and capitalize the first letter of the second word.”
  1. First we need to select an inventory slot for turtle, code turtle.select(1)
  1. Next we can place the block using, code turtle.place()
  1. Next we need to move up, code turtle.up()
  1. Continue asking students for the next line of code for turtle to build a vertical line.



- [ ] **Independent Practice:** Students continue to program turtle to build in Minecraft. Students reference build challenges in Minecraft.
  >> “Now that we’ve coded turtle together, you can continue coding turtle to build the challenges in Minecraft independently.”


#### 5. Evaluate: Exit Challenge (10 minutes)

- [ ] **Call and Response:** teach students the call and response. Teacher says: “I have a challenge for you.” Students say: “Bring it, bring it.”

> > “Before we get started I’m going to teach you a call and response. Whenever you hear me say ‘I have a challenge for you’, you will respond ‘Bring it, bring it’. Let’s try it. ‘I have a challenge for you’ … (students respond ‘Bring it, bring it.’)”

<br/>

<pagebreak/>
- [ ] **Exit Challenge:** Students work independently to write a program to code turtle to build a square.

> > “Okay coders, I have a challenge for you. *pause for students’ response*   Use what we learned today to program turtle to build a square! You will work on this challenge independently to show me and yourself what you learned this lesson.”


- [ ] **Evaluate:** Circulate and check students code to determine student’s understanding of moving turtle, focusing on placing a block to the right of another block.
  - To move turtle to the right, similar to the movement of bots in pixelBots, students need to code turtle to turnRight, forward, then turnLeft. In the next lesson students will write a file “function” called moveRight.



</notable>
[slides]:https://docs.google.com/a/9-dots.org/presentation/d/1YbEfKFvEG1JH4-fbbhKN3LyqjbSaiadGIdt19VskpbE/edit?usp=sharing
