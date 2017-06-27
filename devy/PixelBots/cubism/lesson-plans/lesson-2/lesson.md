<header title='Functions' subtitle='Cubism: Lesson 2'/>

<notable>

<iconp src='/icons/activity.png'>### Overview</iconp>
Students learn to write functions for reuse in JavaScript to code the bot in PixelBots to paint shapes. Students will define functions like, line and square. Students will use these functions in all programs moving forward.


<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can identify a chunk of code that is reused in a program.
- I can write a function and call that function in a program.





<iconp src='/icons/agenda.png'>### Agenda</iconp>

#### Length: 60 minutes
1. Engage: Less is More (5 minutes)
1. Explore: Reusable Code (10 minutes)
1. Explain: Functions (5 minutes)
1. Elaborate: Line & Rectangle Functions (25 minutes)
1. Evaluate: Exit Challenge (15 minutes)



<note>

<iconp src='/icons/materials.png'>### Materials</iconp>

#### Teacher Materials
- Computer
- Projector
- PixelBots.io
- [Lesson 2 Slides][slides]



#### Student Materials
- Computer
- PixelBots Account
- Omnifix Cubes
- Pencils
- [Lyrics][lyrics]
- [Cubism | Lesson 2 PixelBots playlist (code: OQ92Q)][playlist]


<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Function:** a reusable chunk of code that performs a task
- **Refactor:** the process of changing the structure of a program without changing what the program produces

</note>
<pagebreak/>

#### 1. Engage: Less is More (5 minutes)
- [ ] **Contrasting Cases:** Students compare two ways of writing song lyrics for A Cloud Away by Pharrell. One using Chorus to reference a set of lines that are reused and one writing out all lyric lines. Give students time to listen to part of the song and read printed lyrics.
  >>“We see two different ways of writing song lyrics. ”

  <iconp type="question">Are these lyrics for the same song or different songs?</iconp>
  <iconp type="answer">The same song.</iconp>
  <iconp type="question">So how are they different?</iconp>
  <iconp type="answer">In one set all of the lyrics are written while the other set only writes the chorus once.</iconp>
  <iconp type="question">Which of these ways of writing lyrics is shorter?</iconp>
  <iconp type="answer">The second one.</iconp>
  <iconp type="question">How is it shorter?</iconp>
  <iconp type="answer">Instead of rewriting the entire chorus each time, the writer writes ‘Chorus’. When people read the lyrics they can reference the chorus lyrics.</iconp>
  <iconp type="question">If you had to write the lyrics, which way of writing would you prefer? Why?</iconp>
  <iconp type="answer">Using Chorus because it is shorter and you don’t have to write as much.</iconp>

  >>“Let’s take a look at the last part of the song. We see that there are lines of lyrics that are reused. Someone decided to call these lines of lyrics ‘Chorus’. Keep these two sets of lyrics in mind as we go through our lesson today. ”  (click through slide during this script)



#### 2. Reusable Code (10 minutes)
- [ ] **Read Code:** Students individually read and step through each line of code in a program using omnifix cubes.

  >>“Now let’s read code. During this activity I want you to think about how rewriting lyrics can relate to code. Everyone needs 2 cube nets each for this activity. You are a robot that knows three function calls: pickUpNet(), fold(), and connectCubes(). Step through the program line by line to build the structure according to the code.”

- [ ] **Write Pair Share:** In their coding journals, students think of a way to refactor the program similar to the way the lyrics are written in the engage activity with ‘Chorus’. Then in pairs students share their ideas. Place hints on the table for students to use as a resource:
  - Hint 1: Think about the song lyrics.
  - Hint 2: What chunk of code/lines are reused.

  <iconp type="question">How could you rewrite this program? Here are hint cards if you need them. You can pull the black sheet down to reveal each hint. There are 2 hints total.</iconp>
  <iconp type="question">How are these two ways of writing code like the two versions of the song lyrics we saw earlier?</iconp>


#### 3. Explain Functions
- [ ] **Define & Identify** Functions. Students write definition of function in coding journals. Functions are a reusable chunk of code that performs a task. Students then identify what code is reused and what to name the function.
  - **Tip:** Collect the omnifix cubes


  <iconp type="question">What lines/chunk of code is reused in this program?</iconp>
  <iconp type="answer">pickUpNet(), fold(side1), fold(side2), fold(side3), fold(side4), fold(top)</iconp>
  >>“Programmers call this the function body”

  <iconp type="question">What task is this chunk of code performing/doing? This will be the name of our function.</iconp>
  <iconp type="answer">Building a cube, suggested function name can be buildCube.</iconp>
  >>“Programmers call this the function name. Function names need to be clear describe what the chunk of code is doing.”

  <iconp type="question">How would we rewrite our program using buildCube()</iconp>
  <iconp type="answer">buildCube(), buildCube(), connectCubes()</iconp>
  >>“When we use a function we defined/wrote in a program, we call it a function call. buildCube() is a function call.”                                                                

  >>“A function is a reusable chunk of code that performs a task. We can refactor our code and simplify our code by writing a function and using it.“

- [ ] **Call & Response:** Review parts of a function: function name, function body, function call. Point to parts of the function on slide and ask students to respond as a whole class.

  <iconp type="question">What is this called?</iconp>
  <iconp type="answer">Function Name</iconp>
  <iconp type="answer">Function Body</iconp>
  <iconp type="answer">Function Call</iconp>



#### 4. Elaborate: Line & Square Functions (30 minutes)
- [ ] **Guided Practice:** Show students PixelBots challenge and guide them through the thought process of refactoring code using functions.
  <iconp type="question">Here is a program that paints this picture. Can we use functions to refactor this code?</iconp>
  <iconp type="answer">Yes!</iconp>
  <iconp type="question">First we need to ask ourselves, what chunk of code is being reused?</iconp>
  <iconp type="answer">paint, forward, paint, forward, paint, forward, paint, forward</iconp>
  <iconp type="question">What is that chuck of code doing? This will be the name of our function.</iconp>
  <iconp type="answer">Painting a line. We can write a function named line. </iconp>
  <iconp type="question">Is there another way to rewrite our code to use less lines? Do we see a repeating pattern of code?</iconp>
  <iconp type="answer">We can use a loop to rewrite paint, forward, paint, forward, paint, forward, paint, forward.</iconp>

- [ ] **Code Along:** Together as a class, create a function called line in PixelBots and refactor the code in the challenge.
  >>“We can define a function named line and refactor the code using the function call line. Do these steps with me.”

		- Steps:
      1. Define a function and name it line. We do this by writing ‘function’ and then the name. In our cause it would be ‘function line()’. A function name is always followed by open and closed parentheses.
      1. Next, we write the body of the function: paint(), forward(),... We write the body of the code inside these curly braces. Like this. And that’s how how you define a function.
      1. Above the function definition, is where we write the program using line.

- [ ] **Independent Practice:** Students complete a PixelBot challenge by defining a function called square and calling the square function in a program.
  >> “Now it’s your turn. Define a function and complete the challenge using your function.”


#### 5. Evaluate: Exit Challenge (10  minutes)

- [ ] **Exit Challenge:** Students read a given program to refactor on PixelBots. Students will identify the reusable code, define a function named el(), and refactor the program calling the function el().
 >> “Okay coders, I have a challenge for you. *pause for students’ response*. I wrote a program and I need you to help me refactor my code. Use what we learned today to write a function named ‘el’.  Then call the el function to rewrite the code.”

- [ ] **Evaluate:** Check student’s solutions to determine student’s understanding of writing a function and calling that function in a program.





</notable>
[slides]: https://docs.google.com/presentation/d/15A2kU_vjDgCsFILC17912jBOrRCnm9i7ojkXdzqSXbo/edit?usp=sharing
[playlist]: http://www.pixelbots.io/OQ92Q
[dog]: http://www.pixelbots.io/5MR48
[lyrics]:https://docs.google.com/a/9-dots.org/document/d/1f2d6wwGzlskh8VYAssr5SnCYNCL6WfafAZIyQ5l1GgM/edit?usp=sharing
