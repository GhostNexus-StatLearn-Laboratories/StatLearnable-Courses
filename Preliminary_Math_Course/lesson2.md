# Hi folks
Welcome to this course! Feel free to mess around with the docs and graphs! This is the beginning of the journey in StatLearn Labs.

## So, what exactly is a vector?
We are going to think about vectors from two perspectives: the Computer Science perspective and the Mathematical perspective.

To a maths person, a vector is an object that has both **magnitude** and **direction**.

For example, if you walk 5 meters to the east, that movement can be represented as a vector. It is not just "5 meters" — the direction matters too.

Vectors are usually written like this:

$$
\vec{v} = \begin{bmatrix} x \\ y \end{bmatrix}
$$

Here, the vector tells us how much movement happens along each axis. (x-y coordinate plane)

For example:

$$
\begin{bmatrix} 3 \\ 2 \end{bmatrix}
$$

means:
- Move 3 units on the x-axis
- Move 2 units on the y-axis


<div class="sl-plot" data-x="0,3" data-y="0,2"></div>

You can imagine it as an arrow pointing from one position to another.

In Computer Science, vectors are everywhere. Vector is just a fancy word for List or Array!

Graphics engines use vectors to move objects around the screen. Machine Learning models use vectors to represent data. Game engines use vectors for physics, velocity, and camera movement. Even images, sounds, and text can eventually become vectors inside a computer.

In AI and Machine Learning, vectors become extremely important because they let computers represent information numerically.

A single vector might represent:
- A photo
- A sentence
- A song
- A person's preferences
- Or even an entire document

This idea is one of the foundations of modern AI and Statistics.


## Quiz time
<quiz>
<question id=1 > Vector is just a fancy word for _ </question>
<choice id=1 name=A> Numbers </choice>
<choice id=1 name=B> Array </choice>
<answer id=1 choice=B></answer>

<question id=2 > In the co-ordinate plane, What units does the given vector below  move on the y axis? $$  \begin{bmatrix} 4 \\ 9 \end{bmatrix} $$</question>
<choice id=2 name=A> 4</choice>
<choice id=2 name=B> 9 </choice>
<answer id=2 choice=B></answer>

</quiz>
