<header class='header' title='Loops' subtitle='Lesson 1.08'/>

<notable>
<iconp src='/icons/activity.png'>### Overview</iconp>
In Lesson 08, students continue their work with loops by refactoring code to make it shorter and still achieve the same goal as the starter code. Students will first be asked to identify the core in a pattern, then rewrite the start code to include a loop. Use this lesson to reinforce key points regarding loops and encourage students to make their code shorter and easier to read.

<iconp src='/icons/objectives.png'>### Objectives</iconp>

- I can rewrite a sequence of code with a loop.

<iconp src='/icons/agenda.png'>### Agenda (45 min)</iconp>
1. Engage: Unpacking (8 min)
1. Explore: Try It Out (4 min)
1. Explain: Try It With Loops (10 min)
1. Elaborate: PixelBot Practice (18 min)
1. Evaluate: Debrief (5 min)

<note>
<iconp src='/icons/materials.png'>### Materials</iconp>
###### Teacher Materials:
- [ ] Computer
- [ ] Projector
- [ ] [Slide Show][slides]

###### Student Materials:
- [ ] Computers
- [ ] [Playlist: 1.08 Practice | Code: R442D][practice]
- [ ] [Playlist: 1.08 Bonus | Code: WR483][extension]
</note>

## Room Design
![room](/images/layout-grid.png)
<note>
<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
-  **Starter code:** Code you build on to improve a program.
- **Loop:** A sequence of actions that is repeated.
- **Pattern** A sequence that repeats more than once.
- **Core** The base sequence of a pattern that is repeated in a loop.
- **Refactoring:** Rewriting code to make it easier to read, like by adding a loop.
</note>

<pagebreak/>

## 1. Engage: Unpacking (8 mins)
- [ ] **Introduce** the first challenge of the day in the PixelBot playlist.
>>“Coders, our first challenge of the day is on the board. Take the next 20 seconds to do your best to observe the grid, the PixelBot, and the code.”

- [ ] **Unpack** the challenge as a class.

<iconp type='question'>What do you notice about this challenge?</iconp>
<iconp type='question'>What do you think the code does?</iconp>

Follow up questions:

<iconp type='question'>Do you see a pattern?</iconp>
<iconp type='question'>What is the core of the pattern?</iconp>
<iconp type='question'>What is our job as coders this time?</iconp>
<iconp type='question'>Do we have code to begin with?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

<note type='tip'>At this point, students have been through the unpacking process four times in the debugging lessons. Aim to have students guide the conversation and answer all of the questions in the suggested list themselves, interjecting when necessary to guide them to the key points.
In this lesson, do not let students walk away without noticing that the number of code lines are above the limit at the top of the editor. The slideshow will show a red circle over the limit after an initial picture of the challenge.</note>

- [ ] **Challenge** students to share out what is different about today’s challenge if they have not already done so.

<iconp type='question'>What do you notice about the amount of lines we are supposed to use? How many are written?</iconp>
<iconp type='answer'>We are supposed to write only three lines of code, but there are four written.</iconp>

- [ ] **Model** how to solve challenge one using student observations to identify the pattern on PixelBots.
>>“Now that you’ve told me that the core of this pattern is “step, paint” and that it repeats twice, I can go ahead and shorten this code to fit my line limit. How many lines should I have again? (3!) How many times does the pattern repeat? (Two times!) First I click the number 1 and the number 2 to highlight them, and then I click the loop block to place it around the core. Finally, I change the number of times it repeats to two.”

<iconp type='question'>Am I at the line limit? How do you know?</iconp>
<iconp type='answer'>You are, because at the top of the editor it says 3/3.</iconp>

- [ ] **Introduce** Challenge 2.
>>“The challenges we work on today will be pretty similar to our first one! Let’s try unpacking another one before we begin coding on our own.”

- [ ] **Unpack** challenge number two as a class.

<iconp type='question'>What do you notice about this challenge?</iconp>
<iconp type='question'>What do you think the code does?</iconp>

Follow up questions:

<iconp type='question'>Do you see a pattern?</iconp>
<iconp type='question'>What is the core of the pattern?</iconp>
<iconp type='question'>What is our job as coders this time?</iconp>
<iconp type='question'>Do we have code to begin with?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

<note type='tip'>This lesson unpacks and solves the first challenge and then unpacks the second challenge to help students better understand the new skill of refactoring.</note>

## 2. Explore: Try It Out (4 mins)
- [ ] **Challenge** the class to re-write the code to be within the line limit for challenges one and two in the practice PixelBot playlist.
>>“Today we have two things you need to think about for this challenge. First, we need to get PixelBot to this goal using our code blocks. Second, we have to be careful to make sure we don't use more than the amount of code blocks that we see at the top of the editor. Each code block is a line a code. Look here to remind yourself of how many lines of code you're allowed to use.” (Point to line limit.)

<note type='tip'>If students delete all code and re-write it inside the loop, allow them to explore that way. The best way to re-write with a loop, however, is to highlight the code to go inside the loop and then click the loop button.</note>

<iconp type='question'>Can you use more than the amount of code in the limit?</iconp>
<iconp type='answer'>No!</iconp>

<iconp type='question'>Can you use less than the amount of code in the limit?</iconp>
<iconp type='answer'>Yes!</iconp>
>>“Use the blocks that you have in your editor wisely, and try not to delete all of your starter code if you can.”

- [ ] **Independent Exploration:** Have students attempt to write the code on their own for challenge one and two.

- [ ] **Monitor** the class to find students who can be called on to share their strategies in the next activity. Strategies might include highlighting the core of a pattern and placing a loop  around it, using the layover button, etc.

## 3. Explain: Try It With Loops (10 min)
- [ ] **Debrief** challenge two as a class.

<iconp type='question'>What did the starter code do today in challenge two?</iconp>
<iconp type='answer'>The starter code had us paint, step, paint, step, paint step.</iconp>

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>What did you do to solve the problem of being over the line limit?</iconp>
<iconp type='answer'>I used a loop to make the code shorter.</iconp>

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>Do you remember working with patterns last year? What is a pattern?</iconp>
<iconp type='answer'>A pattern is a sequence that repeats more than once.</iconp>

<iconp type='question'>What pattern do you see in the code for challenge two?</iconp>
<iconp type='answer'>The pattern is paint, step, paint, step, paint, step.</iconp>

- [ ] **Define** a pattern as a sequence that repeats and a core as the sequence of code that is repeated.
>>“We are going to be using a loop to represent a pattern today instead of writing it all out!”

- [ ] **Define** refactoring as rewriting code to make it easier to read, like by adding a loop.
>>“This is called refactoring! Refactoring is great because it makes coding easier for us. Today, if you used a loop to rewrite your code, you refactored.”

- [ ] **Reveal** challenge two to students again, and challenge them to find the core in a Think, Pair, Share.

<iconp type='question'>What is the core of the pattern in challenge two?</iconp>
<iconp type='answer'>The core is paint, step.</iconp>
>>“Great! I see the core of the pattern is paint, step. I also see the pattern repeats three times, so I know for my loop block I’ll have to set it to repeat three times. Once we identify the core, we put the loop around it.”

- [ ] **Introduce** Challenge three.
>>“The challenges we work on today will be pretty similar to our first two! Here is our third challenge today. Take the next 20 seconds to observe the grid, PixelBot and the code.”

- [ ] **Unpack** challenge number three as a class.

<note type='tip'>Push students to make predictions as they did in the previous lesson by examining the code closely and sharing out what they think will happen.</note>

<iconp type='question'>What do you notice about this challenge?</iconp>
<iconp type='question'>What do you think the code does?</iconp>

Follow up questions:

<iconp type='question'>Do you see a pattern?</iconp>
<iconp type='question'>What is the core of the pattern?</iconp>
<iconp type='question'>What is our job as coders this time?</iconp>
<iconp type='question'>Do we have code to begin with?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>What do you predict will happen in this challenge based on the starter code?</iconp>
<iconp type='answer'>Students share out predictions using what they already know and what they see in the code.</iconp>

## 4. Elaborate: PixelBot Practice (18 mins)
- [ ] **Independent Coding:** Students work through the rest of the challenges in the PixelBot playlist.

- [ ] **Monitor** the class for students in need of additional assistance.

- [ ] **Extension:** Have students who finish early work on the PixelBot bonus playlist.

<note type='tip'>As students gain comfort with the skill, consider pulling a small group of students who need extra support. Use this time to provide extra guidance and solidify understanding.</note>

## 5. Evaluate:  Debrief (5 min)
- [ ] **Discuss** the question below as a class.

<iconp type='question'>How do loops shorten our code?</iconp>

<note type='tip'>Use the debrief question as an informal check to see which students can verbalize why good coders use loops, and which students need additional support in the next two lessons.</note>

</notable>

[slides]: https://drive.google.com/open?id=1YMGJcmxE2icvkkFanaWP--E6WqpbRJ7hIwdMgwPSLMY
[practice]:http://www.pixelbots.io/R442D
[extension]: http://www.pixelbots.io/WR483
