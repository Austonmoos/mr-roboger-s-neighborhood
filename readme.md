# Mr.Roboger's Neighborhood

#### By Auston Moos

#### _{Brief description of application}_

## Technologies Used

* Git
* HTML
* Java Script 
* CSS

## Description

_{This is a detailed description of your application. Give as much detail as needed to explain what the application does as well as any other information you want users or other developers to have.}_

## Setup/Installation Requirements

* 
* 
* 
* 
* 

_{Leave nothing to chance! You want it to be easy for potential users, employers and collaborators to run your app. Do I need to run a server? How should I set up my databases? Is there other code this application depends on? We recommend deleting the project from your desktop, re-cloning the project from GitHub, and writing down all the steps necessary to get the project working again.}_

## Known Bugs

* 
* 

## License

MIT License

Copyright (c) [2022] [Auston Henry Moos]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


TDD/Tests

Describe: mrRobogersNeighborhood()

Test:"It will return an array of numbers starting with 0 then ending with the users input." 
Code: mrRobogersNeighborhood("12")
Expected Output: [0,1,2,3,4,5,6,7,8,9,10,11,12]

Test:"It will return an array of numbers that have 3 with 'Won't you be my neighbor?'"
Code: mrRobogersNeighborhood("12")
Expected Output: [0,1,2,"Won't you be my neighbor?",4,5,6,7,8,9,10,11,12]

Test: "It will return an array with 2 replaced by 'Boop!'"
Code: mrRobogersNeighborhood("23")
Expected Output: [0,1,"Boop!","Won't you be my neighbor?",4,5,6,7,8,9,10,"Boop!","Won't you be my neighbor?"]

Test: "It will return an array with 1 replaced by 'Beep!'"
Code: mrRobogersNeighborhood("23")
Expected Output: [0,"Beep!","Boop!","Won't you be my neighbor?",4,5,6,7,8,9,10,11,12]

Test: "It will return an array as a comma-seperated string."
Code: mrRobogersNeighborhood("3")
Expected Output: [0,"Beep!",Boop!",Won't you be my neighbor?"]

Test: "It will return an error message if anything but a natural (i.e., counting) number has been entered." 
Code: mrRobogersNeighborhood("$23")
Expected Output: Error: '$23' is not a natural number.