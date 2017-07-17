<header title='Variables, Operators, and Random' subtitle='Lesson 2'/>

<notable>

<iconp src='/icons/activity.png'>### Overview</iconp>
Students learn and use variables, operators, and random to create interesting sketches in Processing.

<iconp src='/icons/objectives.png'>### Objectives</iconp>
- Students will be able to declare variables and use them to manipulate objects.
- Students will be able to use operators to manipulate variables.
- Students will be able to use random to create random sized shapes in random locations.

<iconp src='/icons/agenda.png'>### Agenda</iconp>
###### Length: 65 minutes
1. **Review:** Drawing A Shape (5 minutes)
1. **Engage:** mouseX & mouseY (5 minutes)
1. **Explain:** Variables, operators & random (25 minutes)
1. **Explore:** Coding with variables, operators & random (25 minutes)
1. **Evaluate:** Share sketches (5 minutes)

<note>

<iconp src='/icons/materials.png'>### Materials</iconp>

###### Teacher materials
- [ ] Projector
- [ ] Computer
- [ ] [Lesson 2 Slideshow][slides]
- [ ] [Print Out for Box Activity][print]
- [ ] Boxes

###### Student materials
- [ ] Computer
- [ ] [Grid Paper][gridpaper]
- [ ] pencil
- [ ] coding journal

<iconp src='/icons/vocab.png'>### Vocabulary</iconp>



</note>
<pagebreak/>

#### Review: Drawing A Shape (8 minutes)
- [ ] **Guided Practice:** Review creating a canvas, setting the background color, and drawing a shape by choosing one from the zine and using fill. Ask the class questions, students give a response, and then code together as a class.
  <iconp type='question'> Let's start a new sketch. How do we set the background color to blue?</iconp>
  <iconp type='answer'> Change the three numbers in background() </iconp>
  <iconp type='question'> How do we draw a rectangle with the top left corner at x = 250 and y = 250 of width 200 and height 300? </iconp>
  <iconp type='answer'> Use the rect() function call. Pass four numbers to the rect function call, rect(250,250,200,300) </iconp>
  <iconp type='question'> How do we color the rectangle yellow? </iconp>
  <iconp type='answer'> How can we change our sketch to have the rectangle draw at the mouse pointer?</iconp>
  <iconp type='answer'> change the first 250 to mouseX and the other 250 to mouseY </iconp>
  <iconp type='question'> What happens if we place the background function in draw instead of setup? </iconp>
  <iconp type='answer'> The a new background is placed and then an ellipse is drawn and this repeats in a loop. We don't see a trail of rectangles following the mouse.</iconp>

#### Engage/Explore: Box Activity (7 minutes)
- [ ] **Explore:** In this activity, students will learn how variables, operators, and random works through an unplugged activity. Code will be displayed on the board and boxes will be in the front that act at variables, 'named storage for data'. The code expressions will use operators and students will do arithmetic with variables. For each program read line by line and update variables. For the 2nd program, place a dice in box a for random(1,6).
  >> "We are going to read code and act out how information is stored in a computer's memory. Let's read this first program together. 'var a' this creates a box of storage name 'a' and the same for 'var b' and 'var c'. Next line, 'a = 100'. This looks like a = 100, but in code we read it as store the number 100 in the variable box 'a' *Place paper with 100 in box a*"

  - Continue reading code and placing correct values in each variable box.

#### Explain: Variables, Operators & Random (15 minutes)
- [ ] **Define** Variable: Named storage for data.
  >> "A variable stores a value in memory so that you can use it later in a program."

  <iconp type='question'>Why do we use variables?</iconp>
  <iconp type='answer'>To avoid repeating ourselves in our code.</iconp>
  <iconp type='answer'>So that we can easily change values.</iconp>
  <iconp type='answer'>To write clear and effective code.</iconp>

- [ ] **Demonstrate** using variables. Create a new sketch and type the following code. Then change the value of a and b to see how the sketch is altered.

      var a = 60
      var b = 80
      ellipse (75, a, b, b)
      ellipse (175, a, b, b)
      ellipse (275, a, b, b)


- [ ] **Define** Operator: a character that represents an action.
  >> "An operator are symbols like +, -, and * are operators. When an operator is placed between two values, an expression is created."

- [ ] **Demonstrate** using operators in the example from above and change size of ellipses.

- [ ] **Demonstrate** random in the example from above. Explain how to use the random function call: for example, random(width) returns a random x-coordinate and random(height) returns a random y-coordinate.

      var a = random(width)
      var b = random(height)
      ellipse (a, b, b, b)
      ellipse (a, b, b, b)
      ellipse (a, b, b, b)

  >> “We can use random to draw things in random locations, which will be useful in our beat machine project.”


#### Elaborate: Coding with variables, operators & random (25 minutes)
- [ ] **Independent Practice:** Students create their own sketch using variables, operators, and random.

#### Evaluate: Share Sketches (5 minutes)
- [ ] **Turn and Talk:** Students turn in pairs and share their project for the day.
- [ ] **Share Out:** 3-4 students share their project to the whole class over projector.



</notable>
[zine]:https://docs.google.com/document/d/1_S-nlYJVSYOe-gK_cARrc4L6jT_rAmfIuofJ0rvoQpY/edit
[mouseX&Y]: https://www.openprocessing.org/sketch/398856
[gridpaper]: ../../worksheets/gridworksheet.pdf
[examplecode]: https://docs.google.com/document/d/15q7Fc4VpcTd--i7clFKvmVy3GBWp6B8cfGgEZm1w-2w/edit
[sketch1]:https://www.openprocessing.org/sketch/400530
[sketch2]: https://www.openprocessing.org/sketch/400531
[print]: https://docs.google.com/document/d/1NJwGG_D-wPXyZLP0GGBJkGj9R8M_DVtiGrX6YUFA788/edit?usp=sharing
[slides]: https://docs.google.com/presentation/d/1oa7TFJV8VybztwuhC2jlXXqTXI6jWkKbX7wCfu3jHIg/edit?usp=sharing
