<header title='Parameters' subtitle='Cubism: Lesson 3'/>

<notable>

<iconp src='/icons/activity.png'>### Overview</iconp>
Students learn to define functions with parameters to generalize bot’s actions with arguments. For example, students can define line() with a parameter called ‘length’ and ‘color’ so that the bot paints a line a specific length and color.



<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can define a function with parameters.
- I can use a function I have defined in my program.



<iconp src='/icons/agenda.png'>### Agenda</iconp>

#### Length: 60 minutes
1. Engage: ‘steps’ parameter (7 minutes)
1. Explore: Line Function (8 minutes)
1. Explain: Parameters & Arguments (10 minutes)
1. Elaborate: Rectangle Function (25 minutes)
1. Evaluate: Exit Ticket (10 minutes)


<note>

<iconp src='/icons/materials.png'>### Materials</iconp>

#### Teacher Materials
- Computer
- Projector
- PixelBots.io
- [Lesson 3 Slides][slides]



#### Student Materials
- Computer
- PixelBots Account
- Pencils
- [Cubism | Lesson 3 PixelBots playlist (code: 54YQ4)][playlist]


<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Parameter** - An extra piece of information that is passed to a function to customize it for a specific need.
- **Argument** - A specific value passed to a function call.

</note>
<pagebreak/>

#### 1. Engage: ‘steps’ Parameter (7 minutes)

- [ ] **Do Now:** Students complete challenges 1-3 on Cubism | Lesson 3 PixelBots playlist (code: 54YQ4)
	>>“Code the bot to complete the challenges, the first one is done for you. You will notice all three challenges paint the same pixel, in the upper right corner. I want you to focus on refactoring the program to use the least amount of lines as possible.”

- [ ] **Contrasting Cases:** Students compare code of the three PixelBots challenges.
  >>“All three programs paint the picture, but the codes looks different, let’s take a closer look at each program."

  <iconp type="question">How many lines are used to code challenge 1?</iconp>
  <iconp type="answer">22 lines of code</iconp>
  <iconp type="question">Who coded challenge 2 in the least amount of lines? How?</iconp>
  <iconp type="answer">6 lines, using 2 loops</iconp>
  <iconp type="question">Challenge 3 asks you to complete the challenge in 4 lines, so how did you code the bot?</iconp>
  <iconp type="answer">forward(10), turnRight(), forward(10), paint()</iconp>
  <iconp type="question">How did you know to put a number between the parenthesis of forward?</iconp>
  <iconp type="answer">API</iconp>
  <iconp type="question">What is the difference in API from Challenge 2 vs Challenge 3?</iconp>
  <iconp type="answer">Forward has ‘steps’ between the parenthesis</iconp>
  <iconp type="question">What does ‘steps’ mean? When you called the function up in your program, why didn’t you type the word ‘steps’? How did you know to use a number instead?</iconp>
  <iconp type="answer">Student answers will vary. Encourage students to explain their thoughts and answers about how ‘steps’ works.</iconp>

  >>“We have a name for this, we call them parameters. When we call the function forward() in our program, we don’t type the word ‘steps’ in the parenthesis, we type in the number 10 because we want our bot to move forward 10 steps. ‘Steps’ is a parameter.”

#### 2. Explain: Line Function (8 minutes)
- [ ] **Explore:** Review the line function students defined in previous class. Then show students a challenge that requires the bot to paint colorful lines. Students should see that the line function they defined is limited to only painting black lines of 4 pixels long. Facilitate a discussion to talk about how they can redefine function line to be able to paint any colored line of any length.
  >>“Now that we have an idea about parameters, let’s take a look at how it relates to functions. Here is the code for our line function from the previous lesson. And here is a new challenge for you, painting an image with colorful lines.”

  <iconp type="question">Can we use our line function to complete this challenge? Why or why not?</iconp>
  <iconp type="answer">Our line function will not work because it can only paint black lines of 4 squares long.</iconp>
  <iconp type="question">How do we want to change our line function to be able to complete this challenge? To paint a line what information do we need to know?</iconp>
  <iconp type="answer">Line function needs be able to paint any size line of any color. </iconp>
  <iconp type="answer">Redefine function line to take in a color and size.</iconp>
  <iconp type="question">Take a look at the API, what is in between the parentheses of forward and paint? What would it look like if we could do this for our line function?</iconp>

  >>“We want our line function to be able to paint any size line of any color and we can do this by using parameters.”


#### 3. Explain: Parameters & Arguments (10 minutes)

- [ ] **Define & Summarize** parameters and arguments. Students write the definition of parameter & arguments in their coding journals. Then have students come up to point to their answers on the board of challenge 3.
  >>“When defining a function, you can specify additional information to customize what the function does, we call this a parameter. A parameter stores and uses information that is passed to a function. Let’s take a look back at our pixelBots code and point out the parameters. Remember not to confuse parameters and arguments. When we give a specific value to a function call, we call this an argument.”

  <iconp type="question">What are the parameters here?</iconp>
  <iconp type="answer">‘steps’ and ‘color’</iconp>
  <iconp type="question">What are the arguments?</iconp>
  <iconp type="answer">10 and black</iconp>
  <iconp type="question">What are the functions here?</iconp>
  <iconp type="answer">forward(), turnRight(), turnLeft()</iconp>

- [ ] **Model** defining line function with a parameter called color and length.
	>>“Here is how we define function line with a color and a length parameter.”

  - Steps:
    1. First, define a function using the word function.
    1. Next name the function. The function name is always followed by open and close parentheses.
    1. Then we write the instructions of the  function in between open and close curly braces.
    1. Write the parameters in between the parentheses of the function name. We will create a color parameter. Color will store information that will need to be used in the body of our instructions.
    1. We can use color in place of a specific color name when we use paint().
    1. We can also create another parameter, called length. We write this in the parentheses and separate it from the other parameters with a comma.
    1. If we repeat paint and forward four times, we get a line of 4 squares, if we repeat paint and forward 10 times, we get a line of 10 squares. If we want a line if any length, we can put the word length instead of an exact number.
    1. Together as a class, rewrite main function to use function line with parameters.

  >>“When we call line in a program, we can pass arguments in the order we wrote the parameters in our function definition. For example, to draw a blue line that is 7 squares long, we would write line(‘blue’, 7). In our definition if we wrote length then color, we would write line(7, ‘blue’). Let's go back to the main program and call our line function with parameters."


#### 4. Elaborate: Functions with Multiple Parameters (25 minutes)

- [ ] **Discuss** what other functions students should create. Facilitate a discussion about simple shapes and what information is needed to create each shape. The information needed to create a certain shape will be the parameters of the function.

  <iconp type="question">Now that we have a line function, what other functions would be useful to have? What simple shape can we code?</iconp>
  <iconp type="answer">Square, rectangle, circle, triangle</iconp>
  <iconp type="question">What shape can we easily code using our line function?</iconp>
  <iconp type="answer">Rectangle</iconp>
  <iconp type="question">What information do we need to paint a rectangle on PixelBots?</iconp>
  <iconp type="answer">Height, width, and color</iconp>
  <iconp type="question">How will this information help us when defining our function?</iconp>
  <iconp type="answer">Height, width, and color will be the parameters for the rectangle function</iconp>

  >>“Rectangles are fundamental shapes in coding art. Let’s create a rectangle function in PixelBots with a height, width, and color parameter.”


- [ ] **Guided Practice:** Guide students to Cubism | Lesson 3 playlist, challenge Rectangle and together as a class create a function for a rectangle.
  >>“The first challenge is to create a rectangle function, and then to solve the following challenges calling the rectangle function we defined.”

- [ ] **Extension:** Students who finish early can write a function for triangles.
<pagebreak/>
#### 5. Evaluate: Exit Ticket (10)

- [ ] **Exit Challenge:** Students debug a program with the rectangle function. Students will need to correct the definition of rectangle by adding parameters.
  >>“Okay coders, I have a challenge for you. *pause for students’ response*. I wrote a program and I need you to help me debug my code. Use what we learned today find and fix my bugs. ”



</notable>
[slides]: https://docs.google.com/presentation/d/1MJ8fQ_Ay0mvL20nKWKuzB3GNBDlyP-b3dcjLQvm87VI/edit?usp=sharing
[playlist]: http://www.pixelbots.io/54YQ4
[dog]: http://www.pixelbots.io/5MR48
[lyrics]:https://docs.google.com/a/9-dots.org/document/d/1f2d6wwGzlskh8VYAssr5SnCYNCL6WfafAZIyQ5l1GgM/edit?usp=sharing
