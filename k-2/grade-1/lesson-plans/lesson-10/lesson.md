<header class='header' title='Bug Catchers II' subtitle='Lesson 1.10'/>

<notable>
<iconp src='/icons/activity.png'>### Overview</iconp>
This lesson takes students’ prior knowledge about types of bugs (unwanted code, missing code, two-step bugs) and combines it with what they have learned about loops. This lesson specifically focuses just on bugs of unwanted code and bugs that are caused when a loop doesn’t run the correct amount of times. Lesson 12 will add on bugs with missing code.

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
- [ ] [Playlist: 1.10 Demo | Code: M698U][demo]
- [ ] [Slide Show][slides]

###### Student Materials:
- [ ] Computers
- [ ] [Playlist: 1.10 Practice | Code: RJONB][practice]
- [ ] [Playlist: 1.10 Bonus | Code: DBB8E][extension]
</note>

## Room Design
![room](/images/layout-grid.png)
<note>
<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Loop:** A sequence of actions that is repeated.
- **Bug:** An error in code.
- **Debugging:** Finding and fixing errors in code.
</note>

<pagebreak/>

## 1. Engage: Unpacking (8 mins)
**Location:** Rug

- [ ] **Introduce** the first challenge of the day in the PixelBot demo playlist.
>>“Coders, our first challenge of the day is on the board. Take the next 20 seconds to do your best to observe the grid, the PixelBot, and the code.”

- [ ] **Unpack** the challenge as a class.

<iconp type='question'>**What do you notice about this challenge?**</iconp>
<iconp type='question'>How many blocks do you think the PixelBot will paint?</iconp>

  Follow up questions:

  <iconp type='question'>Do you see a pattern?</iconp>
  <iconp type='question'>What is the core of the pattern?</iconp>
  <iconp type='question'>Is there a loop?</iconp>
  <iconp type='question'>What is our job as coders this time?</iconp>
  <iconp type='question'>Do we have code to begin with?</iconp>
  <iconp type='question'>What is the PixelBot supposed to do?</iconp>
  <iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
  <iconp type='question'>What color does it need to paint the squares?</iconp>
  <iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>

- [ ] **Reveal** the bug to students by playing the code.

How has playing the starter code changed what you notice about the challenge?
I see that there is a bug in the code because it doesn’t repeat enough times!

Challenge students to make observations about the loop in order to solve the challenge.

What pattern does the loop repeat?
It repeats step, paint red, step, paint black.


According to the loop in the starter code, how many times does the loop repeat? Show me on your fingers?
Students hold up one finger.

Model how to solve challenge one using student observations to identify the bug.

“You’ve all let me know that the core in the pattern is supposed to repeat twice, but the loop only repeats once in the starter code. This is a repeat bug! Say repeat bug. (Repeat bug!) To fix a repeat bug, all I do is change how many times the loop repeats that what I want to paint the grid correctly. First, I click on the number on the loop. Then, I click on the correct number, in this case two. Last, I play my code to check that it’s correct.”

Did I fix the bug?
Yes!

Introduce Challenge One in the practice playlist.

“Repeat bugs are just one type of bugs with loops. In this next one, I want you to look to see if we have a repeat bug, or if we maybe have something different.”

Unpack Challenge One as a class.

What do you notice about this challenge?
How many blocks do you think the PixelBot will paint?

Follow up questions:

Do you see a pattern?
What is the core of the pattern?
Is there a loop?
What is our job as coders this time?
Do we have code to begin with?
What is the PixelBot supposed to do?
How many squares does the PixelBot need to paint?
What color does it need to paint the squares?
Which way is the PixelBot facing? (up, down, left, right)

Reveal the bug to students by playing the code.

How has playing the starter code changed what you notice about the challenge?
I see that there is a bug because there is an extra step!

## 2. Explore: Try It Out (4 mins)
**Location:** Rug/Desks

- [ ] **Challenge** the class to write the code for the challenge within the line limit.
>>“Today we have two things you need to think about for this challenge. First, we need to get the PixelBot to this goal using our code blocks. Second, we have to be careful to make sure we don't use more than the amount of code blocks that we see at the top of the editor. Each code block is a line a code. Look here to remind yourself of how many lines of code you're allowed to use.” (Point to line limit.)

<iconp type='question'>How many lines are you allowed to use?</iconp>
<iconp type='answer'>Five!</iconp>

<iconp type='question'>What do you think you will need to do to stay within the line limit?</iconp>
<iconp type='answer'>Use a loop!</iconp>
>>“Coders, today I want you to use what you learned from our last lesson to help you today. Try to solve the challenge using a loop.”

<iconp type='question'>How do we use loops? What goes inside the loop?</iconp>
<iconp type='answer'>Loops are used to repeat code. The code we want to repeat goes inside.</iconp>

- [ ] **Independent Exploration:** Have students attempt to write the code on their own at their desks.

- [ ] **Monitor** the class to find students who can be called on to share their strategies in the next activity. Strategies might include highlighting the core of a pattern and placing a loop  around it, using the layover button, etc.

## 3. Explain: Try It With Loops (10 min)
**Location:** Rug

- [ ] **Debrief** challenge one as a class.

<note type='tip'>In the slideshow, sentence starters are provided for students to use.

For example:

1. The first step I took was...Then I…
1. I used a loop to…
1. The code inside my loop was…
1. The challenging part was...</note>

<iconp type='question'>What was difficult about today’s challenge?</iconp>

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>What did you do to avoid going over the line limit?</iconp>
<iconp type='answer'>I used a loop to make my code stay below the limit.</iconp>

Review previous definitions of patterns and cores.

<iconp type='question'>What is a pattern?</iconp>
<iconp type='answer'>A pattern is a sequence that repeats more than once.</iconp>

<iconp type='question'>What is the core?</iconp>
<iconp type='answer'>The core is the part of the pattern that repeats.</iconp>
>>“We are going to be using a loop to represent a pattern today instead of writing it all out! When we place pattern inside a loop, we first find the core of our pattern. Then, we put a loop around it and figure out how many times we repeat the loop to meet our goal.”

- [ ] **Reveal** challenge one to students again, and challenge them to find the core in a Think, Pair, Share.

<iconp type='question'>What is the core of the pattern in Challenge 1?</iconp>
<iconp type='answer'>The core is step, step, step, paint orange.</iconp>
>>“Let me show you the pattern that I see in Challenge 1. I’m going to use arrows to show how my PixelBot moves and turns, and a dot to show when it paints. Can you call out the code with me?” (Step, step, step, paint orange. Step, step, step, paint orange.)
“I can see that this pattern repeats twice! So I know the ‘code’ inside the oval is what I need to write, and I’ll need to loop it as many times as I see the core.”

- [ ] **Introduce** Challenge 2.
>>“The challenges we work on today will be pretty similar to our first one! Here is our second challenge today. Take the next 20 seconds to observe the grid, PixelBot and the code.”

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

- [ ] **Think, Pair, Share:** Students share their responses to the questions below with a partner. After each partner has shared, call on students to share with the rest of the class.

<iconp type='question'>What do you predict we will write in the code?</iconp>
<iconp type='answer'>Students share out predictions using what they already know and what they see in the code.</iconp>

- [ ] **Model** stepping through PixelBot challenge number two.
>>“First, I’m going to use a loop block to start my code, and I’ll worry about how many times I’ll loop it later. I see that I will need to step forward once, and then paint purple. Then I’ll step forward once and paint yellow. Then my pattern repeats! So the core I write in the loop is step, paint purple, step, paint yellow. Since it repeats three times, I’ll change my loop number to three!”

## 4. Elaborate: PixelBot Practice (18 min)
**Location:** Desks

- [ ] **Independent Coding:** Students work through the rest of the challenges in the PixelBot playlist.

- [ ] **Monitor** the class for students in need of additional assistance.

- [ ] **Extension:** Have students who finish early work on the PixelBot bonus playlist.

<note type='tip'>As students gain comfort with the skill, consider pulling a small group of students who need extra support. Use this time to provide extra guidance and solidify understanding.</note>

## 5. Evaluate:  Debrief (5 min)
**Location:** Desks

- [ ] **Discuss** the question below as a class.

<iconp type='question'>How do loops shorten our code?</iconp>

</notable>

[demo]: http://www.pixelbots.io/M698U
[slides]: https://drive.google.com/open?id=1GGku65apKcGPgMiuZf_6VDqY1rpvRpB_BfISq_jnGxI
[practice]:http://www.pixelbots.io/RJONB
[extension]: http://www.pixelbots.io/DBB8E
