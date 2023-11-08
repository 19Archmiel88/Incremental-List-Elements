Adding Elements to a List with a Sum Increasing by 5
This is a simple HTML project that creates a list of elements. By clicking the "Add an element to the list, and the sum increases by 5" button, you add a new element to the list. If the number of the element is divisible by 3, its font size is increased to 40px.

Running
To run this project, follow these steps:

Download the HTML file to your computer.

shell
Copy code
git clone https://github.com/19Archmiel88/Incremental-List-Elements/blob/master/index.html
Open the HTML file in any web browser.

The project will run, and you can add elements to the list by clicking the button.

Installation Instructions
To download the HTML file to your computer, follow these steps:

Open a terminal or command prompt on your computer.

Use the git clone command to download the HTML file to a chosen directory on your computer.

shell
Copy code
git clone https://github.com/19Archmiel88/Incremental-List-Elements/blob/master/index.html
After cloning the repository, open the HTML file in any web browser.

The project will run, and you can add elements to the list by clicking the button.

Script Details
The JavaScript script performs the following actions:

Initializes the number variable to 1.
Retrieves the button and the unordered list (ul) from the HTML elements.
Listens for a click event on the button.
Upon clicking the button, it creates a new list item (li) and assigns it the current value of number.
If the value of number is divisible by 3, the script adds the "big" class to the list item, increasing its font size to 40px.
Then, it increments the number by 5.
This is a simple project illustrating the addition of elements to a list with the font size increasing when the number is divisible by 3.
