<header class='header' title='Coding Conditionals' subtitle='Lesson 4.09'/>

<notable>
<iconp src='/icons/activity.png'>### Overview</iconp>
In this lesson, students learn how to write a program with a conditional statement. A conditional statement is a boolean expression that determines which sequence of code to perform. In order to write a conditional in PixelBots, students will discuss how an “if-then statement” will execute code and how to use the switch block to switch colors. At the end of the lesson, students will describe how conditionals are executed by writing in their reflection journals.


<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can write a program with a conditional to solve a challenge.

<iconp src='/icons/agenda.png'>### Agenda (60 min)</iconp>
1. Engage: Lights On (5 mins)
1. Explore: Write the Code (10 mins)
1. Explain: Conditions (10 mins)
1. Elaborate: PixelBots (20 mins)
1. Evaluate: Exit Ticket/Reflection (15 mins)

<note>
<iconp src='/icons/materials.png'>### Materials</iconp>
###### Teacher Materials:
- [ ] Computer
- [ ] Projector
- [ ] [Slide Show][slides]

###### Student Materials:
- [ ] Computer
- [ ] Pencils
- [ ] Journals
- [ ] [Playlist: 4.09 Practice | Code: 7MB9J][practice]
- [ ] [Playlist: 4.09 Exit | Code: BGMBD][exit]
- [ ] [Playlist: 4.09 Bonus | Code: 3EQEM][extension]

</note>

## Room Design
![room](/images/layout-online.png)

<note>
<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Boolean:** A value that either can be “true” or “false”.
- **Conditional:** A boolean expression that determines which sequence of code to perform.
</note>

<pagebreak/>

## 1. Engage: Lights On (5 mins)
- [ ] **Introduce** students to today’s robot scenario.
>>“Today, I want you to imagine you are writing the directions for a robot to turn ALL the lights on in a building. The only direction we can give the robot is to flip a switch. When you see the light in a room is off, I want you to call out ‘Switch!’ and we will use this switch block to give the robot directions to flip the switch on. (Use slideshow to show visual of new switch block)”

- [ ] **Run** through slide show as students call out when to ‘switch’ the lights on.
- [ ] **Discuss:** Have students share out when they needed to direct the robot to flip the switch.

<iconp type='question'>How did you know when to tell the robot to flip the switch?</iconp>
<iconp type='answer'>If the light was off.</iconp>
<iconp type='question'>What happened if the light was already on?</iconp>
<iconp type='answer'>The robot did not have to do anything.</iconp>

- [ ] **Make a Connection** to conditionals.
>>“This reminds me of the work we did last week with conditionals. Our instructions for the robot are just like “If, then..” statements. If the light is off, then switch on. If the light is already on, then do nothing.”

## 2. Explore: Write the Code (10 mins)
- [ ] **Introduce** students to today’s work by displaying the ‘Instructions’ for 4.08 practice playlist Challenge One.  Discuss the instructions with the class.
>>“Here are the instructions for Challenge One today. It says: Turn the random square on. This sounds like our robot light bulb scenario again. If something is off, we have to turn it on. If it is already on, we do nothing. However, we haven’t seen a ‘random square’ before, so it’s hard to understand what that might mean. Let’s take a look at the challenge to see if we can figure it out.”

<note type='tip'>Before students begin to explore with code writing for Challenge One, give them a helpful hint to click on the ‘Instructions’ tab over the grid to help them remember the goal of the challenge.</note>

- [ ] **Unpack** Challenge One.

<iconp type='question'>What do you notice about this challenge?</iconp>
<iconp type='question'>What do you notice about the blocks?</iconp>
<iconp type='answer'>There is a switch block just like we used for the robot in the building to switch something on.</iconp>
<iconp type='question'>What do you notice about the squares on the grid?</iconp>
<iconp type='answer'>There is a square with two colors. Maybe this is the ‘random square’ mentioned in the instructions.</iconp>

- [ ] **Explain** how the random square works and model how to use the layover tool in this type of challenge.
>>“This is called a random square. It has this name because when we run our code, it will randomly select one of the two colors you see now. The instructions tell us to turn the random square on. Yellow is on, and blue is off. What color means on? (Students: Yellow!) What color means off? (Students: Blue!)

- [ ] **Model** the solution to Challenge One. Think aloud as you solve it.
>>“Now I’m going to write the code to reach our goal. First I will use a step two times block to get to the random square. Now I need to think… When I run the code, this square will either become yellow OR blue. We want to turn it “on” which means yellow. So IF the square is blue, we want it to switch. I can use an ‘If, then.. ‘ block here to make that happen. If the square is blue, then switch. I’ll use the new switch block to tell the PixelBot to switch. If the square is already yellow, then nothing will switch. The light is already on. Let’s play the code to see what happens.”

## 3. Explain: Conditionals (10 mins)
- [ ] **Unpack** Challenge Two.

<iconp type='question'>What do you notice about this challenge?</iconp>
<iconp type='question'>What are the instructions?</iconp>
<iconp type='question'>What do you notice about the squares on the grid?</iconp>
<iconp type='question'>What is the condition?</iconp>

- [ ] **Independent Exploration:** Students log in to PixelBots to write the code for Challenge Two.

- [ ] **Share Out:** Have students share out their solutions. Use the PixelBot teacher platform to display a student’s code on the projector. Look for a student who makes the mistake of putting the ‘move forward’ block INSIDE the conditional and discuss how to fix this common error.

>>“I noticed many of us making a common mistake. Let’s tackle it as a whole class. If we put the move forward block inside of our conditional we might have a problem. Remember, the code in the conditional ONLY happens if the condition is true. So in this case, if the random block is yellow, then the code inside will run. BUT if the random block is not yellow (if it’s false), then all of the code we wrote inside will NOT happen. We need to make sure that the code we do want to happen every single time, is not nestled inside of our conditional. I want the PixelBot to move forward two steps every time I run the code, so I will make sure to put this after my conditional.”

<note type='tip'>The main goal for discussion in this Explain section is to guide students to identify that their code will only execute under certain conditions. For example, they should notice that their code should only execute if the square is blue. If it is blue, then it will switch to yellow.</note>

- [ ] **Define** ‘execute’.
>>“We are going to learn another new word today. Execute. Everyone say ‘execute’. This means: to carry out or put into effect. In coding, when you press the green play button, you can see the lines in your code execute. But sometimes, certain lines in your code will not execute like the example we just looked at.

- [ ] **Discuss:** Students discuss the condition in Challenge Two and when it will or will not execute.

<iconp type='question'>When does the code inside the conditional execute?</iconp>
<iconp type='answer'>If the first random square is yellow, then the code inside the conditional will run and it will switch to blue.</iconp>
<iconp type='question'>When does the code inside the conditional not execute?</iconp>
<iconp type='answer'>If the first random square is blue, then the code inside the conditional will NOT execute because it says “if yellow” and that condition is false. The bot will skip the code inside the conditional and move to the next line in the sequence.</iconp>

## 4. Elaborate: PixelBots (20 mins)
- [ ] **Independent Exploration:** Students work independently to solve the rest of the challenges in the practice playlist.

- [ ] **Extension:** Early finishers can complete the 4.08 Bonus playlist.

## 5. Evaluate: Exit Ticket/Reflection (15 mins)
- [ ] **Exit Ticket:** Have students navigate to the 4.08 Exit Ticket and complete independently.

- [ ] **Reflection:** Once they have completed the exit ticket, they can logout of computers and complete the reflection question in their journals.

<iconp type='question'>How do you know if the bot will execute the code in the conditional?</iconp>

</notable>

[slides]: https://drive.google.com/open?id=1soexXuRMkowtw9FKn8EjBhdPJmawVh39mfLzcbm0d70
[practice]: http://www.pixelbots.io/7MB9J
[exit]: http://www.pixelbots.io/BGMBD
[extension]: http://www.pixelbots.io/3EQEM
