# canvas-boucing-balls

This example is written to practice OOJS style in code.

As you see in the code

Creating ball object with some constructor.
function Ball(x,y,velX,velY,color,size){
	this.x = x;
  this.y = y;
  this.velX = velX;
  this.velY = velY;
  this.color = color;
  this.size = size;
}

In ES6 there is class and constructor keyword. Yo can follow es6 style as well.
And with .prototype keyword we just make function member of Ball

Ball.prototype.draw = function()
Ball.prototype.update = function(){

There is loop function that handles the drawing ball issue and creating random coordinate issue. At the end of function we add all information to the Ball array. Those information comes from Ball object.

lastly requestanimationframe calls the function many times it never ends. It is for writing something in Object Oriented Style.

![alt text](https://i.itsosticky.com/1ysr6hf.png)

some extra things like make the balls grow smaller and larger
