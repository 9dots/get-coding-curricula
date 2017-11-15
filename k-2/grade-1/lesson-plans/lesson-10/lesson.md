<header class='header' title='Bug Catchers II' subtitle='Lesson 1.10'/>

<notable>
<iconp src='/icons/activity.png'>### Overview</iconp>
<<<<<<< HEAD
This lesson takes students’ prior knowledge about types of bugs (unwanted code, missing code, two-step bugs) and combines it with what they have learned about loops. This lesson specifically focuses just on bugs of unwanted code and bugs that are caused when a loop doesn’t run the correct amount of times. Lesson 12 will add on bugs with missing code.
=======
This lesson takes students’ prior knowledge about types of bugs (unwanted code, missing code, two-step bugs) and combines it with what they have learned about loops. This lesson specifically focuses just on bugs of unwanted code and bugs that are caused when a loop doesn’t run the correct amount of times. Lesson 11 will add on bugs with missing code.
>>>>>>> a0c84221c5dad06819959b7a7a09c91240ae89de

<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can debug a loop with repeat bugs.
- I can debug a loop with unwanted code.


<iconp src='/icons/agenda.png'>### Agenda (45 min)</iconp>
1. Engage: Unpacking (8 min)
1. Explore: Try It Out (4 min)
1. Explain: Debugging Loops (10 min)
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
- [ ] [Playlist: 1.10 Demo | Code: M698U][demo]
- [ ] [Playlist: 1.10 Practice | Code: RJONB][practice]
- [ ] [Playlist: 1.10 Bonus | Code: DBB8E][extension]
</note>

## Room Design
![room](/images/layout-online.png)
<note>
<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Loop:** A sequence of actions that is repeated.
- **Bug:** An error in code.
- **Debugging:** Finding and fixing errors in code.
</note>

<pagebreak/>

## 1. Engage: Unpacking (8 mins)
**Location:** Rug

- [ ] **Introduce** the first challenge of the day in the PixelBot **demo** playlist.
>>“Coders, our first challenge of the day is on the board. Take the next 20 seconds to do your best to observe the grid, the PixelBot, and the code.”

- [ ] **Unpack** the challenge as a class.

<iconp type='question'>**What do you notice about this challenge?**</iconp>
<iconp type='question'>**How many blocks do you think the PixelBot will paint?**</iconp>

Follow up questions:

<iconp type='question'>Do you see a pattern? </iconp>
<iconp type='question'>What is the core of the pattern?</iconp>
<iconp type='question'>Is there a loop?</iconp>
<iconp type='question'>What is our job as coders this time?</iconp>
<iconp type='question'>Do we have code to begin with?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

<note type='tip'>Consider having students log in to PixelBots and access the first challenge in the 1.10 Practice playlist before instruction begins so that the transition to computers after unpacking is more seamless.

In the initial unpacking, aim to have students guide the conversation and answer all of the questions in the suggested list themselves, interjecting when necessary to guide them to the key points.
</note>

- [ ] **Reveal** the bug to students by playing the code.

<iconp type='question'>How has playing the starter code changed what you notice about the challenge?</iconp>
<iconp type='answer'>I see that there is a bug in the code because it doesn’t repeat enough times!</iconp>

- [ ] **Challenge** students to make observations about the loop in order to solve the challenge.

<iconp type='question'>What pattern does the loop repeat?</iconp>
<iconp type='answer'>It repeats step, paint red, step, paint black.</iconp>
<iconp type='question'>According to the loop in the starter code, how many times does the loop repeat? Show me on your fingers?</iconp>
<iconp type='answer'>Students hold up one finger.</iconp>

- [ ] **Model** how to solve challenge one using student observations to identify the bug.
>>“You’ve all let me know that the core in the pattern is supposed to repeat twice, but the loop only repeats once in the starter code. This is a repeat bug! Say repeat bug. (Repeat bug!) To fix a repeat bug, all I do is change how many times the loop repeats that what I want to paint the grid correctly. First, I click on the number on the loop. Then, I click on the correct number, in this case two. Last, I play my code to check that it’s correct.”

<iconp type='question'>Did I fix the bug?</iconp>
<iconp type='answer'>Yes!</iconp>

- [ ] **Introduce** Challenge One in the **practice** playlist.
>>“Repeat bugs are just one type of bugs with loops. In this next one, I want you to look to see if we have a repeat bug, or if we maybe have something different.”

- [ ] **Unpack** Challenge One as a class.

<iconp type='question'>**What do you notice about this challenge?**</iconp>
<iconp type='question'>**How many blocks do you think the PixelBot will paint?**</iconp>

Follow up questions:

<iconp type='question'>Do you see a pattern? </iconp>
<iconp type='question'>What is the core of the pattern?</iconp>
<iconp type='question'>Is there a loop?</iconp>
<iconp type='question'>What is our job as coders this time?</iconp>
<iconp type='question'>Do we have code to begin with?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

- [ ] **Reveal** the bug to students by playing the code.

<iconp type='question'>How has playing the starter code changed what you notice about the challenge?</iconp>
<iconp type='answer'>I see that there is a bug because there is an extra step!</iconp>

## 2. Explore: Try It Out (4 mins)
**Location:** Rug/Desks

- [ ] **Challenge** the class to debug the loops in Challenge One.
>>“Today I want you to try challenge one based on what we learned while unpacking as a class. Use what you know about loops and bugs to help you.”

- [ ] **Independent Exploration:** Have students attempt to debug Challenge One.

- [ ] **Monitor** the class to find students who can be called on to share their strategies in the next activity.

## 3. Explain: Debugging Loops (10 min)

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<note type='tip'>In the slideshow, sentence starters are provided for students to use.

For example:

1. The first step I took was...Then I…
1. I used a loop to…
1. The code inside my loop was…
1. The challenging part was...

Push students to be specific in their habits of discussion around coding by having them cite one line of code in the editor that they deleted.
</note>

<iconp type='question'>What was the bug that you found in Challenge One? How did you fix it?</iconp>
<iconp type='answer'>There was an extra step block in the challenge. I fixed it by deleting the code block.</iconp>

- [ ] **Model** playing challenge one with the error still in the code to have students pick out the line number with unwanted code.

<iconp type='question'>Which line had unwanted code? </iconp>
<iconp type='answer'>Line 2, 3, or 4 had unwanted code.</iconp>

- [ ] **Review** bugs from previous lessons to activate prior student knowledge.
>>“Coders, today we learned about a new bug: a repeat bug! But we have learned about a couple of different bugs in the past.”

<iconp type='question'>What are bugs we have learned about and debugged already?</iconp>
<iconp type='answer'>Unwanted code, missing code, two-step bugs.
</iconp>
>>“Today, we are only going to focus on two specific types of bugs: repeat bugs, and unwanted code bugs.”

- [ ] **Define** an unwanted code bug as a bug where there is an extra line of code that needs to be deleted.

<iconp type='question'>How do we fix an unwanted code bug?</iconp>
<iconp type='answer'>We delete code!</iconp>

- [ ] **Define** a repeat bug as a bug that is caused because the loop does not repeat the correct number of times.

<iconp type='question'>How do we fix a repeat bug?</iconp>
<iconp type='answer'>We change how many times the loop repeats!</iconp>
>>“You already have the tools to debug! Today, we are combining two skills: debugging, and using loops.”

- [ ] **Introduce** Challenge Two.
>>“The challenges we work on today will be pretty similar to our first two! Here is our second challenge today. Take the next 20 seconds to observe the grid, PixelBot and the code.”

- [ ] **Unpack** Challenge Two as a class.

<iconp type='question'>What do you notice about this challenge?</iconp>
<iconp type='question'>What do you think the code does?</iconp>

Follow up questions:

<iconp type='question'>Do you see a pattern? </iconp>
<iconp type='question'>What is the core of the pattern?</iconp>
<iconp type='question'>Is there a loop?</iconp>
<iconp type='question'>What is our job as coders this time?</iconp>
<iconp type='question'>Do we have code to begin with?</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>What do you predict will happen in this challenge based on the starter code? What might the bug be?</iconp>
<iconp type='answer'>Students share out predictions using what they already know and what they see in the code.</iconp>

- [ ] **Model** solving challenge three for students.
>>“First, I’m going to play my code to see what happens. When I play my code, I see that the loop doesn’t repeat the correct number of times. Next, I will fix it by changing the loop. How many times does it repeat? (2!) How many times should it repeat? (3!) I will change the number 2 to the number 3. Last, I run my code again to see that it is correct.”

## 4. Elaborate: PixelBot Practice (18 min)
**Location:** Desks
<note type='tip'>As students gain comfort with the skill, consider pulling a small group of students who need extra support. Use this time to provide extra guidance and solidify understanding.</note>
- [ ] **Independent Coding:** Students work through the rest of the challenges in the PixelBot playlist.

- [ ] **Monitor** the class for students in need of additional assistance.

- [ ] **Extension:** Have students who finish early work on the PixelBot bonus playlist.

## 5. Evaluate:  Debrief (5 min)
**Location:** Desks

- [ ] **Discuss** the question below as a class.

<note type='tip'>This debrief question aims to show the teacher more about students’ comfort and enjoyment with debugging.</note>

<iconp type='question'>How did you feel while coding today and why? What did you learn?</iconp>

</notable>

[slides]: https://drive.google.com/open?id=1GGku65apKcGPgMiuZf_6VDqY1rpvRpB_BfISq_jnGxI
[demo]: http://www.pixelbots.io/M698U
[practice]: http://www.pixelbots.io/RJONB
[extension]: http://www.pixelbots.io/DBB8E
