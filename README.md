ButtonColour
============

This will help you to create a basic button as well as put a function into it!
void Draw(){
//Button
    fill(0); // this will fill a shape/section to a specific colour
    noStroke(); // this will not allow thick lines around the shape
    ellipse(0,0,0,0); // this will create a circle, where you have to set (X,Y,width,height)
//Function
    if (mousePressed && dist(0, 0, mouseX, mouseY) < 20) {
      myPenStroke = color(0); //if mouse pressed at "x" place then set "x colour to my pen
      }
