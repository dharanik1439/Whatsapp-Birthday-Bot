# Whatsapp-Birthday-Bot
The Project Is about Creating A whatsapp Birthday wishing Bot
Have you ever wished to automatically wish your friends on their birthdays, or send a set of messages to your friend ( or any Whastapp contact! ) automatically at a pre-set time, or send your friends by sending thousands of random text on whatsapp! Using Browser Automation you can do all of it and much more!
First you must install these:- 
1) Python Bindings for Selenium ( Browser Automation software ) 
 

pip install selenium

2) Chrome webdriver 
Download Chrome driver from here: Chromedriver download page( choose your specific version ) 

How the bot does it

The script uses PySelenium package to open a Chrome webdriver window on which all tasks are done. It checks if the current date and month matches the ones in a json file. If yes, the 'name' attribute of it is returned which is used to find the corresponding chat in Whatsapp web(finding by xpath). The script then simulates click on the chat, opens it, types the message in the chat box and simulates a click on the send button.
 

What is JSON?

JSON stands for JavaScript Object Notation. It is a very simple and light way of storing data. Though it's derived from JavaScript, it is language independent and is similar in looks to Python Dictionaries 
Check out this article for more on JSON.
Below is the implementation 


Code Explanation: 

1.The code begins by importing the necessary libraries.

2.It then imports the json module, which is used to store data in a JSON format.

3.Next, the code creates two global variables: eleNM and DoNotUseElsewhere.

4.The first variable, eleNM, will hold information about all of the elements on the webpage that are being analyzed.

5.The second variable will be used to keep track of whether or not any analysis should be performed on this particular page.

6.Next, the code begins to analyze the webpage.

7.First, it checks to see if there is an element with the id="ele" on the page.

8.If there is an element with that ID, then it sets up a delay so that all other elements on the page are loaded before proceeding with its analysis.

9.After checking for an element with the id="ele", the code proceeds to check for any input fields on this page.

10.If there are any input fields present, then it uses those fields as part of its analysis process.

11.For each input field, it checks to see if there is a value entered into it by either user or computer (depending on which type of field it is).

12.If there is a value entered into one of these fields, then that value is stored in eleNM

13.The code imports the necessary libraries and sets up a delay so that all elements on the webpage are loaded before proceeding.

14Next, it creates a global variable called eleNM which will store the name of the element on the webpage that has been selected by the user.

15.The next part of the code deals with the actual task at hand.

16.It uses Selenium to navigate to a specific element on the webpage and then calls a function named getDate().

17.This function will use the built-in datetime module to retrieve the current date in required format.

18.Finally, it stores this value in eleNM.

19.The code first opens the JSON file.

20.It then looks for a contact with the given name in the file.

21.If it finds that contact, it extracts the values of attr_ret and attr1 from that contact.

22.It also extracts the value of attr2 from that contact.

23.Finally, it assigns those values to the variables attr_val1 and attr_val2, respectively.

24.The code then uses these variables to return a list of strings containing information about all contacts in the file who have their birthday on or before today's date (inclusive).

25.The code will read the JSON file and extract the values for the two attributes, attr_ret and attr1.

26.It will then compare these values to the values of attr2.

27.If they match, it will return the value of attr_val1 for that contact.

28.If they don't match, it will return the value of attr_val2.

29.The code begins by loading the file's data into a variable named data.

30.The code then loops through each of the file's attributes, looking for pairs of values that match the conditions specified in the if statement.

31.If a matching pair is found, the value associated with that attribute is stored in the retv list and the loop ends.

32.Next, the code opens the JSON file in read-only mode so that it can access its data without interference from other programs running on your computer.

33.The code then creates an empty list named namev and stores a copy of each attribute's value in that list.

34.The code first initializes a list called retv.

35.This list will contain the names of all the attributes that have matching values for the two attributes specified in the code.

36.Next, the code checks to see if any of the attributes have been set to specific values.

37.If so, then those values are stored in the retv list and the loop continues.

38.If no matches are found, then an empty list is returned and the code terminates.

39.The code starts by getting the current date.

40.It uses the datetime module to get the date as a string.

41.The code then tries to get the data for the name and birth month from the JSON file.

42.If there is any data in the JSON file, it prints out that data.

43.If there is no data in the JSON file, the code checks to see if there are any values in namev .

44.If there are values, then it breaks out of while True and continues with else .

45.Otherwise, if namev is empty, then break exits from while True and execution resumes at try .

46.The code will keep rerunning the part of the code from 'while True' to 'break'.

47.This will keep waiting for the JSON function to return a non empty list.

48.In practice, this function will keep rerunning at 11:59pm a day before the birthday and break out at 12:00am.

49.The code first creates a ChromeOptions object.

50.This object allows us to control various aspects of the Chrome browser, such as which websites we can visit and how we should be navigated around them.

51.Next, we add an argument to the ChromeOptions object called user-data .

52.This argument is a location where we can store our user data.

53.We will use this argument later on in the code when we want to access our user data from within the Chrome webdriver.

54.Finally, we create a new Chrome webdriver object using the code above.

55.The webdriver object will allow us to interact with the Chrome browser and analyze its behavior.

56.The code will create a ChromeOptions object that will allow us to use the user data of Chrome.

57.This means that we won't have to sign in manually every time we want to use Chrome.

58.The code starts by getting the WhatsApp driver.

59.It then uses the get() method to request the web page for WhatsApp.

60.The code then adds a delay so that all of the elements on the web page can load before it starts to print out information about the contacts in your chat list.

61.Next, the code finds and prints out each element in the namev list using XPath.

62.If an exception is encountered, it prints out that information and continues with the rest of the code.

63.Next, using find_element_by_xpath(), the code tries to find and print out an element with a title attribute that matches one of the values in inp (the input variable).

64.If no such element is found, an exception is raised and processing stops.

65.If an element with that title attribute is found, however, processing continues by clicking on it.

66.This causes a mouse event to be sent to our program, which keeps looping until either an error occurs or all of our contacts have been printed out.

67.The output from running this program will look something like this: Name: John Doe Email: john@doe.com    Phone Number:

68.The code will first get the driver for WhatsApp.

69.Once it has been obtained, the code will delay for 10 seconds so that all of the elements on the page have loaded.

70.Next, the code will print out a list of all of the contacts in your chat.

71.Next, the code will find and click on an element with the class name _13mgZ .

72.This element is used as a chat box for WhatsApp.

73.If everything goes according to plan, this should open up your chat box and allow you to start typing in your messages!
