# Investment-personalProject
This personal projects uses Java GUI's to allow user to easily navigate and manage Stocks and Mutual Funds
README - Shaan Saharan
-----------------------------------------------------------------------------------------------------

1. The program uses the investment function as well as stocks and mutual funds functions extensions to execute the portfolio code.
It allows users to buy, sell, update, be updated, and search from a menu prompt. Each function
execute a unique
set of code.
    i. buy: Allows the user to purchase shares
    ii. sell: Allows the user to sell shares
    iii. update: Allows the user to update the prices of the investments
    iv. getGains: Outputs the loss or gain of the stocks and/or mutual funds
    v. search: Allows the user to search through and filter the stock and mutual funds list

2. Testing & Assumptions: To test the ePortfolio, ensure that all codes are included in the same folder under the same package name.
Then, using the 'javac' command, we can compile, test, run and use the program. The screen is set to size 800 x 800 so assume that the
size of the GUI fits the users layout

3. Test Plan: The program allows the user to choose from a list of tasks to complete. The options let the user buy/sell as many stocks 
and/or mutual funds as they wish. They are allowed to update the price of each investment and the computer will calculate the gain of 
each bought investment. A HashMap is also used to search for the searched items.

Test plan in detail:
    - empty textfields will provide a message error to the user
    - incorrect datatypes in textfields will through a message error to the user
    - negative price will through a message error to the user 
    - negative quantity will through a message error to the user
    - trying to buy an object that already exists will not be bought
    - trying to sell more shares than that are available
    - updating the investmentList
    - gives the correct hashMap search
4. Future Improvements: Given more time, I would have liked to experiment with making a more colourful and eye appealing GUI. It would
allow for better user interface and overall better outcome. Playing around with this would allow me to further enhance my GUI coding
abilities
