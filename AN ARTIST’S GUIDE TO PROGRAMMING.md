# AN ARTIST’S GUIDE TO PROGRAMMING
>A Graphical Introduction
>Jim Parker
# AUTHOR’S NOTE
Processing is:

- A programming language

- ==Designed== by Casey Reas and Ben Fry
- Used by artists creating ==generative== art
- ==Based== on Java
  
- ==Extends== Java in many useful ways:

  - ==Read==, ==display==, and ==write== image files

  - ==Drawing== elementary shapes and curves

  - ==Manipulating== colors

  - It opens a window into which the programmer/artist will ==draw==

  - All Processing programs are intended to ==create an image==, a ==visual output==
# INTRODUCTION
## The Basics of a Programming Language: Processing
  - When someone ==programs== a computer => they are really ==communicating== with it:
    - **Imperative**
      - Because the computer has no choice
      - It is being told what to do
      - It will do exactly that
    - **Precise**
      - Does ==not apply== any interpretation to what it is being told.
      - Computers do ==not think== and so ==can’t evaluate== a command that would amount to “expose the patient to a fatal dose of radiation” with any skepticism.
      - So we, as programmers, must be ==careful and precise== in what we instruct the machine to do.

- When humans ==communicate== with each other, we use a ==language==.
  - Similarly, humans use ==languages== to ==communicate== with computers, but these ==languages== are
    - _artificial_ (humans invented them for this purpose),
    - _terse_ (there are few if any modifiers—no way to express emotions or gradations of any feeling),
    - _precise_ (each item in the language means one thing), and
    - _written_ (we do not yet speak to computers in a programming language).
- The ==process== of programming begins with a problem to be solved, and the first step is to ==state== the problem as clearly as possible.
  - Then we ==analyze== the problem and ==determine== methods by which it may be solved.
  - A ==sketch== of the ==solution==, perhaps on paper in a human language and math, is created.
    - This is then ==translated== into computer language and ==typed== into the computer using a keyboard.
    - The ==resulting== text file is called a script, source code, or more commonly the computer program.
- Next, another program called a ==compiler== takes the program and converts it into a form that can be ==executed== on the computer.
  - Computers can only directly ==manipulate== numbers, so it is common for solutions discussed at this stage to be numerical or mathematical.
- Basically, all programs are converted into ==machine code==, which consists of numbers, and which the computer can ==execute==.
- Use Processing
  - It was developed for use by artists, but it’s pretty good for lots of things.
  - It’s good for teaching because it makes a lot of things easy.
  - It always has graphical visual output.
## The Beginning
>All ==sketches== have the same basic structure.
>
>There is something called ==setup()== (a predefined name) that gets executed just ==once==, when the program ==begins==.
>
>This is where we will do ==initializations==, such as ==defining== the size of the output window. If we need to ==read== a bunch of images or sounds from files, this is where we might do it.

The syntax of setup() is as follows:
```Java
void setup () { your code goes here }
```
## The Middle
>The second part of a sketch is another function, one named ==draw()==.
>This function is called ==many times== each second (the default is 60 times, but this can be changed), and its purpose is to ==update== the drawing being made by the program.
>Processing assumes that the programmer is writing a program to draw a picture of some kind.

The syntax of draw (a predefined name) is as follows:
```Java
void draw () { your code goes here }
```
## The Rest
>The programmer writes code that is ==inside== either of the ==functions== ==setup()== and ==draw()== or that is ==executed== by those ==functions==.
>
>Any part of the program that cannot be ==reached== from ==setup()== or ==draw()== will never be ==executed== (except for some of the mouse and keyboard ==functions==).
>
>The programmer can name and provide code for other ==functions==, and these can be ==executed== by (called from) ==draw()== or ==setup()==.
>
>These ==functions== are usually placed after the ==draw()== ==function== in the program.
>
>For example, if the programmer wanted to define a ==function== named doSomething(), it might look like this:
```Java
void doSomething () { your code goes here }
````
## Variables
> Essentially, a ==variable== is a ==place== to put a ==result==, usually a number.
> 
>A ==variable== is represented by a ==name==.
>
> we “==declare==” variable, and we specify a ==type==.
>
> The ==type== defines the set of ==values== that can be ==assigned== to the ==variable==.
> 
>Connection between the ==name== and the ==value== is established by a statement in the language called an _assignment statement_: it assigns a value to a variable.
## How to Write a Program
```Java
void setup () {
  size(400,300);
}

void draw () {
  ellipse(200,100,50,50);
}
```
