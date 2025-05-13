# Process Automation - Sainsbury’s Shop
![Sainos Logo as banner](./Sainsburys-Emblem.png)

In the modern world, almost every job has one or two regular, repetitive digital tasks. These are often essential but equally often very simple; routine.

Automation, for example with Python and Selenium, grants us efficiency gains. Delegating these routine tasks to code can give us this time back to spend more complex tasks.

In this project, I’m taking a regular task that many people are familiar with - the weekly food shop - and sharing the code required to automate it.

The script logs in, takes an ingredients.txt file and works through the list, adding each item to the shopping basket. The list uses tuples to store the English-language ingredient name along with the product ID code - this gives us precise selection of our favourite items. Once completed, it’ll print a summary of all the items successfully added and any that it failed to find/weren’t available. Ready for the user to hit checkout.

Milage may vary on your personal time-saves with this one. But this script acts as a great demonstration of what can be achieved through Python automation. 