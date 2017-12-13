<header class='header' title='Loop and Loop Again' subtitle='Lesson 1.15'/>

<notable>
<iconp src='/icons/activity.png'>### Overview</iconp>
Where Lesson 14 teaches students how to read code with and without loops, Lesson 15 pushes students to write similar code. The basis of this skill is in identifying which part of a target grid needs a loop and which part does not by finding regular patterns and outliers. Remind students to use what they know about patterns and loops to build their code.

<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can step through a program that contains code outside of a loop.



<iconp src='/icons/agenda.png'>### Agenda (45 min)</iconp>
1. **Engage:** Unpacking (8 min)
1. **Explore:** Try It Out (4 min)
1. **Explain:** Code Outside of Loops (10 min)
1. **Elaborate:** PixelBot Practice (18 min)
1. **Evaluate:** Debrief (5 min)
<note>
<iconp src='/icons/materials.png'>### Materials</iconp>
###### Teacher Materials:
- [ ] Computer
- [ ] Projector
- [ ] [Slide Show][slides]

###### Student Materials:
- [ ] Computers
- [ ] [Playlist: 1.15 Review | Code: 5XPQY][practice]
</note>

## Room Design
![room](/images/layout-online.png)
<note>
<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Loop:** A sequence of actions that is repeated.

</note>

<pagebreak/>

## 1. Engage: Introducing the Challenge (6 mins)
**Location:** Rug

- [ ] **Introduce** the first challenge of the day.
>>“Coders, in your last lesson, your job was to read code that had blocks in and outside of loops. Today, we are going to move on to a harder skill, which is writing code! You will be the expert in choosing when to use a loop and when not to use a loop.”

<iconp type='question'>How is writing code different from reading code?</iconp>
<iconp type='answer'>It is different because we have to choose which blocks to write instead of just following the steps.</iconp>
<br/>
>>“Our first challenge of the day is on the board. Take the next 20 seconds to to observe the grid, the PixelBot, and the code.”

<note type='tip'>
Rather than starting with regular unpacking, this lesson starts with a quick Think-Pair-Share and then allows for students to try Challenge One as a class. Then, it leads into unpacking Challenge Two and a teacher model. The goal of the additional think-aloud prior to the exploration of the playlist is to provide students sufficient support with a new, more difficult skill.
</note>
<br/>

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>What do you notice about the challenge?</iconp>
<iconp type='answer'>There are three black squares to paint and one blue one. The PixelBot is on the left middle facing right. We are writing code, not reading code. The line limit is seven lines.</iconp>
<br/>
>>“I am interested to see how you are able to solve this challenge as a class without me showing you how to first. I know that you can use what you’ve already learned about loops and code outside of loops to help you!”

<note type='tip'>
When taking and implementing student ideas, do not be afraid to take obviously wrong answers and test them out for the class. This will allow students to see their mistake and give them an opportunity to fix it.
</note>
<br/>

- [ ] **Share Out and Model:** Have students share out their answers to the questions below. Test their ideas by adding code in the editor and clicking run. Continue asking the question and testing out their ideas until the group comes up with a solution to Challenge One.

<iconp type='question'>What’s your plan for solving within the line limit?</iconp>
<iconp type='answer'>We could paint the blue dot and then loop for the black rectangle.</iconp>

<iconp type='question'>Which part should we start with first? The loop or the code outside of the loop?</iconp>
<iconp type='answer'>We should start with the code outside of a loop.</iconp>

<iconp type='question'>How should we code the part that is not looped?</iconp>
<iconp type='answer'>We should just paint blue one time.</iconp>

<iconp type='question'>How should we code the part that we want looped?</iconp>
<iconp type='answer'>We should step and paint black three times.</iconp>
<br/>
>>“Great job! Have we met the line limit?” (Yes!)

<note type='tip'>
When calling on students to share out their answers to the unpacking question, use positive narration to prompt more participation. (Ex: “I see three hands in the air. ________ is thinking and raising their hand…”)

Possible student answers for unpacking:

- I see that the PixelBot is on the left middle facing right.
- I see that we need to write code.
- I see that we need to paint squares black and blue.
- I see that the three black squares are next to each other and in a pattern.
- I see that the blue square is by itself and a different color.
- The limit is six lines.
</note>
<br/>

- [ ] **Introduce** the second challenge of the day.
>>“Coders, our second challenge of the day is on the board. Take the next 20 seconds to to observe the grid, the PixelBot, and the code.”

- [ ] **Unpack** Challenge Two as a class. Use the blank slide following the challenge to write down student observations.

<iconp type='question'>What do you notice about this challenge?</iconp>

<br/>
Follow up questions:
<br/>

For identifying the challenge coders need to complete
<iconp type='question'>What is our job as coders this time? How do you know?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<br/>

For understanding the components of the grid
<iconp type='question'>Is there a line limit? What is it?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>
<iconp type='question'>Is the PixelBot facing toward the squares it is supposed to paint?</iconp>
<br/>

For identifying the loop-able and non-loop-able components
<iconp type='question'>Do you see a pattern? Where?</iconp>
<iconp type='question'>Where do you think we can use a loop? Why?</iconp>
<iconp type='question'>Which part will be outside of a loop? Why?</iconp>
<br/>
- [ ] **Model** solving Challenge Two for students.
>>“Let me show you how I would approach this challenge. First, I see that there is a potential pattern for my PixelBot. I see that I can paint black, step forward three times. Since this is a pattern, I can write it in a loop. It will be paint black, step in a loop with an argument of three. Then, outside of the loop, I will simply write, paint blue. When I check my code, I see that it is within the line limit and solves the challenge successfully.”

## 2. Explore: Try It Out (4 mins)
**Location:** Rug/Desks

- [ ] **Unpack** the class to step through the code in Challenge One.
<note type='tip'>
Possible student answers for unpacking:

- I see that the PixelBot is on the bottom facing up.
- I see that we need to write code.
- I see that we need to paint squares black and blue.
- I see that the three black squares are next to each other and in a pattern.
- I see that the blue square is by itself and a different color.
- The limit is nine lines.
</note>
<br/>

<iconp type='question'>What do you notice about this challenge?</iconp>

<br/>
Follow up questions:
<br/>
For identifying the challenge coders need to complete
<iconp type='question'>What is our job as coders this time? How do you know?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<br/>

For understanding the components of the grid
<iconp type='question'>Is there a line limit? What is it?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>
<iconp type='question'>Is the PixelBot facing toward the squares it is supposed to paint?</iconp>
<br/>

For identifying the loop-able and non-loop-able components
<iconp type='question'>Do you see a pattern? Where?</iconp>
<iconp type='question'>Where do you think we can use a loop? Why?</iconp>
<iconp type='question'>Which part will be outside of a loop? Why?</iconp>
<br/>

- [ ] **Challenge** the class to write code for Challenge Three.
>>“I want you to try Challenge Three based on what we learned while unpacking as a class. Use what you know about loops to help you.”

- [ ] **Independent Exploration:** Have students attempt to debug Challenge Three at computers.

- [ ] **Monitor** the class to find students who can be called on to share their strategies in the next activity. Look for students who are successfully completing the code outside the loop once and looping the correct number of times.

<br/>
<note type='tip'>TIP: When circulating around the room for student answers, consider asking a student questions they might answer in front of a class one-on-one before calling them up to share their solution. This helps to prepare them for a whole-group share out.</note>
<br/>

## 3. Explain:  Code Outside of Loops (10 mins)
**Location:** Desks

- [ ] **Think, Pair, Share** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>How did you solve Challenge Three?</iconp>
<iconp type='answer'>Student answers may vary. Use the teacher platform (schools.pixelbots.io) to project student answers.</iconp>
<br/>

- [ ] **Explain** to students how to find patterns and outliers in code.
>>“Coders, you should be looking for what to loop and what not to loop in your code:“ (have students read from the slide)

- *Loops:* Look for repeating patterns in the goal grid.
- *Code outside of loops:* Look for different colors and blocks that aren’t part of the repeating pattern

- [ ]**Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>Once we have entered a loop, how do we know that it’s time to exit the loop?</iconp>
<iconp type='answer'>You will know once you’ve completed the code inside the loop as many times as it says.
</iconp>
<br/>
>>“Now that we’ve practiced this skill three times together, it’s your turn to try it on your own! Use what we came up with in class to help with independent work.”

## 4. Elaborate: PixelBot Practice (18 mins)
**Location:** Desks

- [ ] **Independent Coding:** Students work through the rest of the challenges in the PixelBot playlist.
- [ ] **Monitor** the class for students in need of additional assistance. If time permits, review challenges 5 and 6 with students by allowing them to share their coding process.
- [ ] **Extension:** Have students who finish early work on the PixelBot bonus challenges.

<note type='tip'>
As students gain comfort with the skill, consider pulling a small group of students who need extra support. Use this time to provide extra guidance and solidify understanding.
</note>
<br/>

## 5. Evaluate. Debrief (5 mins)
**Location:** Desks
- [ ] **Discuss** the question below as a class.
<iconp type='question'>How did you feel while coding today and why?</iconp>
<iconp type='question'>What did you learn today?</iconp>

<note type='tip'>
This debrief question aims to show the teacher more about students’ comfort and enjoyment with debugging. The purpose of asking students how they feel when coding is to allow students to reflect on their learning process. Allowing students a safe space to express their ideas with each other and with the teacher helps validate their thinking and feelings. As the teacher, make sure that all students have a chance to share their thinking and feelings with the class throughout the year.

The slideshow includes an array of emotions as a bank for students to choose from to support their answers to the debrief question.
</note>
<br/>

</notable>

[slides]: https://docs.google.com/presentation/d/1fSh86HrHRQnJmIBjOPxrHvADBKOpGL2FBp8jh_UBKOA/edit?usp=sharing
[practice]: http://www.pixelbots.io/5XPQY
