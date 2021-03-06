<header title='PixelBots' subtitle='Emoji: Lesson 1'/>

<notable>

<iconp src='/icons/activity.png'>### Overview</iconp>
Students learn the fundamental coding concept of sequencing to program a bot to paint a given picture on PixelBots.io. Using function calls forward, turnRight, turnLeft, and paint, students will write sequential lines of code to move the bot and to paint.

<iconp src='/icons/objectives.png'>### Objectives</iconp>
- I can read, write, and execute code in a sequence on PixelBots Challenges.
- I can navigate and use the PixelBots editor to write programs using JavaScript.


<iconp src='/icons/agenda.png'>### Agenda</iconp>

#### Length: 60 minutes

1. Engage: What is Code? (5 minutes)
1. Explore: PixelBots (15 minutes)
1. Explain: Sequence & Function Calls (10 minutes)
1. Elaborate: PixelBots Challenges (20 minutes)
1. Evaluate: Exit Challenge (10  minutes)

<note>

<iconp src='/icons/materials.png'>### Materials</iconp>

#### Teacher Materials
- Computer
- Projector
- PixelBots.io
- [Lesson 1 Slides][slides]
- [Icon Playlists & Slides][icons]


#### Student Materials
- Computer
- PixelBots Account
- [Emoji | Sequence PixelBots playlist (code: WN5BN)][playlist]


<iconp src='/icons/vocab.png'>### Vocabulary</iconp>
- **Sequence** - The idea that statements must be performed in the order they are written.
- **Function call** - A programming element that tells the computer to do something. In the beginning, most function calls will cause the computer to perform an action.
- **API** - stands for application program interface, API defines the correct way for a developer to write a program
- **Code** - instructions in a computer program

</note>
<pagebreak/>

#### 1. Engage: What is Code? (5 minutes)
- [ ] **Define** code and present each of the examples on “Code is Everywhere” slide.
  <iconp type='question'>What is code?</iconp>
  <iconp type='answer'>A set of instructions designed to be carried out by a computer. It is the instructions someone wrote to make your website, app, game, etc. run.</iconp>

  >>“Code is everywhere. Everywhere we look computer programs are running code to run our world. Code is what creates the website or computer programs we use. Being a coder is about producing, not just consuming.”

<note>**Slides**
![slides](./images/engage1.png)
![slides](./images/engage2.png)
</note>

- [ ] **Motivate:** Reveal the Emoji project over the projector. Show students the code and the bot painting the example emoji, [Math Eye Smiley (code:E6BJ9][mathemoji].
  >>“In this class you are going to design and create an Emoji with code! Using a coding language called JavaScript,  you will code a bot to paint your emoji on a platform called PixelBots. Here is an example of an emoji and the program. *Show emoji and code* Before you can design and code our own emoji, you will first need to learn a few fundamental coding concepts. Today we will be learning about sequencing.”

<note>
![slides](./images/engage3.png)
</note>

#### 2. Explore: PixelBots (15 minutes)
- [ ] **Code Along:** Students follow along on their own computer as you walk through each step of logging onto PixelBots.
  >> “Open your computers and follow along as we walk through the steps of going to PixelBots.io and logging in to our accounts.”

  - **Steps:**
    1. Open Chrome and type ‘www.pixelbots.io’ in the address bar
    1. Click on ‘Log In’  and ‘Sign in with Google’
    1. Type in email and password.
      - Email: firstlaststudent@9-dots.org
      - Password: student5 or student6
    1. Navigate to playlist: click ‘Code’, type playlist code: ‘WN5BN’, then click ‘go’ and ‘play’

  - **Tip:** Uphold good classroom management on computers. When you give each step, students should have eyes on you and hands off computers.

<note>
![slides](./images/explore1.png)
![slides](./images/explore2.png)
![slides](./images/explore3.png)
![slides](./images/explore4.png)
</note>

- [ ] **Group Exploration:** Together as a class explore the PixelBots.io interface by doing the first two challenges in the [Emoji | Sequence PixelBots playlist (code: WN5BN)][playlist]. For the Write Challenge, students will write instructions to move the bot and paint a picture. For the Read Challenge, students will be given code to read and will paint the picture the code produces. Ask guiding questions to get students thinking about how to use the interface.

  - **Write Challenge:**
    >> “We want to code the bot to paint this picture. We can do this by typing instructions the bot can understand.”  

    <iconp type='question'>What do you see in the pixelBots editor?</iconp>
    <iconp type='answer'>Allow students to make their observations about the parts of the editor and predict what they think is the function of each part.</iconp>
    <iconp type='question'>What do you suggest we do first? Why?</iconp>
    <iconp type='answer'>Let students guide the exploration by asking guiding questions.</iconp>
    <iconp type='question'>What instructions can we write to guide the bot?</iconp>
    <iconp type='answer'>Students should learn that computers only understand certain instructions. For PixelBots the instructions can be found by referencing the API. Students can hover over the API to read what each function call does. </iconp>
    <iconp type='question'>Where do we write our instructions/code?</iconp>
    <iconp type='answer'>Students will point to the editor or the right side. Refer to is as the editor. “Yes, we write our code here on the right, this is called the editor.”</iconp>
    <iconp type='question'>What specific instructions do we want to write?</iconp>
    <iconp type='answer'>Students suggest function calls in a particular order. </iconp>

  - Possible Solutions:
  ![write solution](./images/writesol.png)

<note>
![slides](./images/write.png)
![slides](./images/read.png)
</note>

  - **Read Challenge:**
    >> “Reading code is just as important as writing code. In Read Challenges, we are given code and we paint the picture that this program would produce. For each line of code we read, the bot does an action.”  

    <iconp type='question'>What should we do first when reading a program?</iconp>
    <iconp type='answer'>Read the first line of code.</iconp>
    <iconp type='question'>The first line of code says ‘forward()’, what does forward mean? </iconp>
    <iconp type='answer'>The pixelbot will move forward one square in the direction it is facing. </iconp>
    <iconp type='question'>How do make the bot act out forward?</iconp>
    <iconp type='answer'>Click on the square the bot moves to.</iconp>
    <iconp type='question'>What do we do next?</iconp>
    <iconp type='answer'>Together as a class, read and enact more lines of code.</iconp>
    <iconp type='question'>What happens if we try to paint an incorrect square? Try it.</iconp>
    <iconp type='answer'>The bot shakes and a ‘Wrong Location’ error message appears.</iconp>

<pagebreak/>
#### 3. Explain: Sequence & Function Calls (15 minutes)
- [ ] **Discuss & Define Sequence.** Guide students through a discussion of how code is performed in order using the previous write challenge as an example.

  <iconp type='question'>Here is our code for the write challenge. What would happen if the code was rearranged? Would it still create the same picture?</iconp>
  <iconp type='answer'>Students compare the two codes. The program would be different, the code would no longer paint the correct picture.</iconp>
  <iconp type='question'>The program still uses the same function calls, so why does switching the order of the lines of code matter?</iconp>
  <iconp type='answer'>Students come to the conclusion that order matters when you write code. The pixelbot will perform the function calls in the order that it is written in.</iconp>

  >>“In computer science, this is called sequencing. The code is performed in the order it is in. This means that line will be performed first then line two and, so on.”

<note> **Slides:**
![slides](./images/explain1.png)
![slides](./images/explain2.png)
</note>

- [ ] **Identify & Define Function calls.** Students identify forward(), turnRight(), turnLeft(), and paint() as function calls and a definition of function calls is given.

  <iconp type='question'>What did we use to code the bot? And what do they have in common? Hint: It’s how it is written.</iconp>
  <iconp type='answer'>forward, turnRight, turnLeft, and paint, they all have ‘()’ parenthesis at the end</iconp>
  <iconp type='question'>What would you call these?</iconp>
  <iconp type='answer'>Students answers will vary. </iconp>

  >>“In computer science, these instructions with parenthesis at the end are called function calls. Function calls are programming elements that tell the computer to do something.”

<note>
![slides](./images/explain3.png)
![slides](./images/explain4.png)
</note>

#### 4. Elaborate: PixelBots Challenges (20 minutes)
- [ ] **Independent Practice:** Students work to complete challenges in Emoji| Sequence playlist.
  - Playlist consists of three types of challenges:
    1. Read - Students read given code and paint the picture the code would produce.
    1. Write - Students use code to move a bot to paint a given image.
    1. Debug - Students are given code to fix to paint a given image.
  >>“We’ve learned about sequences and function calls and now we can code the bot to paint simple pictures. In these next challenges, we will continue to practice reading and writing code. There are also challenges where code is written for you, but there are a few mistakes, we call these bugs. I want you to debug the code, to find the mistakes and fix them.”

#### 5. Evaluate: Exit Challenge (10  minutes)
- [ ] **Call and Response:** teach students the call and response. Teacher says: “I have a challenge for you.” Students say: “Bring it, bring it.”
  >>“I’m going to teach you a call and response. Whenever you hear me say ‘I have a challenge for you’, you will respond as a class and say ‘Bring it, bring it’. Let’s try it. ‘I have a challenge for you’ … (students respond ‘Bring it, bring it.’)”

<note>**Slides:**
![slides](./images/evaluate1.png)
</note>

- [ ] **Exit Challenge:** Students work independently to write a program to complete the Exit Challenge on the playlist.
  >>“Okay coders, I have a challenge for you. *pause for students’ response*   Use what we learned today to debug the Exit Challenge at the end of the playlist! You will work on this challenge independently to show me and yourself what you learned this lesson.”

<note>
![slides](./images/evaluate2.png)
</note>

- [ ] **Evaluate:** Circulate and check code to determine student’s understanding of sequences and debugging and writing code in PixelBots to paint a picture.


</notable>
[icons]: https://docs.google.com/document/d/1ZE99zvzel6p8Q2DCoZUVXHnNSeB9ZCEiJlKeHWUtY4E/edit?usp=sharing
[slides]: https://docs.google.com/presentation/d/1czhFgQIY2PxMHuMXXJ8VDN_ptlAiKKyuZ5dY5m0tL8s/edit?usp=sharing
[playlist]: http://www.pixelbots.io/WN5BN
[mathemoji]: http://wwww.pixelbots.io/E6BJ9
