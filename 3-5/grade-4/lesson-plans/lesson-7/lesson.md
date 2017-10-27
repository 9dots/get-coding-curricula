<header class='header' title='Debugging Loops' subtitle='Lesson 4.07'/>

<notable>
<iconp src='/icons/activity.png'>### Overview</iconp>
In this lesson, students will begin by analyzing code with a loop to find and fix a bug. Students will then engage in a discussion sharing out the different strategies used. They will identify one bug that they’ve already been exposed to (unwanted code bug) and learn about a new bug (repeat bug). They will solidify the skill of debugging with loops by completing a PixelBots playlist and end the lesson by reflecting on their process of debugging.

<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can debug a program containing a loop.

<iconp src='/icons/agenda.png'>### Agenda (60 min)</iconp>
1. Engage: Unpacking (8 min)
1. Explore: Try It Out (7 min)
1. Explain: Debugging Loops (15 min)
1. Elaborate: PixelBot Practice (20 min)
1. Evaluate: Reflection (10 min)

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
- [ ] [Playlist: 4.07 Practice | Code: 967PU][practice]
- [ ] [Playlist: 4.07 Bonus | Code: M2M7T][extension]

</note>

## Room Design
![room](/images/layout-online.png)

<note>
<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Loop:** A sequence of instructions that is continually repeated until a certain condition is reached.
</note>

<pagebreak/>

## 1. Engage: Unpacking (8 min)
- [ ] **Introduce** the first challenge of the day.
>>“Coders, our first challenge of the day is on the board. Take the next 20 seconds to observe the grid, the PixelBot, and the code.”

- [ ] **Unpack** the challenge as a class.

<iconp type='question'>**What do you notice about this challenge?**</iconp>
  <iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
  <iconp type='question'>What color does it need to paint the squares?</iconp>
  <iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>
  <iconp type='question'>Is the PixelBot facing the square it needs to paint?</iconp>
  <iconp type='question'>What else do you notice?</iconp>

- [ ] **Discuss** the questions below after executing the code.

<iconp type='question'>**What did you notice about the PixelBot?**</iconp>
  <iconp type='question'>What did you want the PixelBot to do?</iconp>
  <iconp type='question'>What did the PixelBot do instead?</iconp>

<note type='tip'>The first question in the engage activity is meant to give students the opportunity to call out anything they notice about the challenge. The subsequent questions are follow-ups that are meant to guide students to make the types of relevant observations they should make every time they approach a challenge. After playing the code for students, they should notice what the program did and what they want it to do instead.</note>

## 2. Explore: Try It Out (7 min)
- [ ] **Challenge** the students to debug the code without deleting it and rewriting it.
>>“Your challenge in this activity is to fix the code by only changing the part that doesn’t work. You should not delete all of the code and rewrite it.”

- [ ] **Independent Exploration:** Have students attempt to debug the code on their own.

- [ ] **Monitor** students as they work. Look for students who can be called on to share their strategy for debugging in the next activity. See “Notes” as a reference for what types of strategies you might look for.

<note type='tip'>As students work, circulate the room asking students, “What did you do to find the bug?” As students step you through their process, select 1 to 2 students who used different strategies to share out in the next activity. Possible strategies are:
- Playing the code and first comparing what they wanted the code to do vs. what it actually did.
- Stepping through each line of code.</note>


## 3. Explain: In The Loop (15 min)
- [ ] **Turn and Talk:** Students share their responses to the questions below with a partner. After each partner has shared, call on pre-selected students from the prior activity to share their strategies.

<iconp type='question'>What changes did you make?</iconp>
<iconp type='question'>How did you know to make those changes?</iconp>

- [ ] **Introduce** the idea that there are multiple strategies students might use to solve a problem. Jot both shared strategies on a new anchor chart titled, “Debugging Strategies”.
>>“Student A and Student B both fixed the bug successfully. Even though they used different strategies to find and make changes,  they both got to the same solution. Let’s keep their strategies in mind because they might help you solve the problem, too!”

- [ ] **Explain** the new type of bug: Repeat Bug, and the purpose of debugging today.
>>“We’ve already learned about two types of bugs, and now we’ve encountered a new one! This is called a Repeat Bug (reveal on anchor chart). A Repeat Bug happens when the number of repeats for a loop is wrong and we have to fix it. Let’s keep practicing debugging, because sometimes bugs are going to be found inside of a loop.

- [ ] **Introduce** Challenge Two.
>>“Here is our second challenge today. Take the next 20 seconds to observe the grid, the Pixelbot, and the code.”

- [ ] **Unpack** Challenge Two as a class.

<iconp type='question'>**What do you notice about this challenge?**</iconp>
<iconp type='question'>What is the PixelBot supposed to do?</iconp>
<iconp type='question'>How many squares does the PixelBot need to paint?</iconp>
<iconp type='question'>What color does it need to paint the squares?</iconp>
<iconp type='question'>Which way is the PixelBot facing? (up, down, left, right)</iconp>
<iconp type='question'>Is the PixelBot facing the square it needs to paint?</iconp>
<iconp type='question'>What else do you notice?</iconp>

- [ ] **Model** debugging Challenge Two on PixelBots using the stepper tool.
>>“When I run the code, it starts by painting the correct squares, but then it keeps repeating on the same squares instead of going on to the next ones. To find the problem I can use the stepper tool. As I continue to click, I can see that when it goes back to the top, at line 2, the pixelbot turns right when it needs to stay in the direction it already was…”

- [ ] **Identify** the type of bug.
>>“Sometimes with loops, we will come across a repeat bug, but other times, the bug might be within the loop. In this case, we found an Unwanted Code Bug within our loop. Have you seen this type of bug before?”

<note type='tip'>Put an emphasis on the strategies that students share out to give them voice and ownership in the classroom. As selected students share the changes they made and how they knew to make those changes, have the class give a thumbs up if they also used the same strategy allowing for all student voices to be heard.

As a student shares out the strategy of stepping through each line of code, put a strong emphasis on the idea that they are not finished reading the code when they reach the bottom. If it repeats, they have to go back to the top of the loop to continue reading the code!</note>

## 4. Elaborate: PixelBot Practice (20 min)
- [ ] **Independent Exploration:** Students work through the rest of the challenges in the PixelBots playlist.

<note>Use challenges 3 and 4 for exit ticket data.</note>

- [ ] **Monitor** the class for students in need of additional assistance.

- [ ] **Extension:** Have students who finish early work on the Bonus playlist.

<note type='tip'>As students gain comfort with the skill, consider pulling a small group of students who need extra support. Use this time to provide extra guidance and solidify understanding.</note>

## 5. Evaluate: Reflection (10 min)
- [ ] **Reflection:** Students answer the following reflection question in their journals.

<iconp type='question'>How do you debug a program that has a loop?</iconp>
<iconp type='question'>What types of bugs do you know about? Explain.</iconp>

</notable>

[slides]: https://drive.google.com/open?id=1KO2UgvrxEz52OK_fpMuDjJ4SDsZ0DAQNIgWlcNFuMyU
[practice]: http://www.pixelbots.io/967PU
[extension]: http://www.pixelbots.io/M2M7T
