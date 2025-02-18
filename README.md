# Assign Python Variables

<h1>Introduction</h1>
Variables help security analysts to keep track of a variety of security-related information. For example, analysts may need to create Python variables for the users who are allowed to log in, the number of login attempts that they're permitted, and the current number of attempts that a user has made.

In this lab, you'll practice assigning values to variables and determining their data types.

<h1>Scenario</h1>
You are a security analyst who is responsible for writing code that will automate analysis of login attempts made to a specific device. As the first step, you'll need to create variables to keep track of information relevant to the login process. This information includes the device ID, list of approved usernames, maximum login attempts allowed per user, current login attempts made by a user, and login status.

Throughout this lab, you'll assign these variables and check the data types of the variables.

<h1>Task 1</h1>
In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is "72e08x0".

In the following code cell, assign this value to a variable named device_id. Then, display the contents of the variable and observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/0f9a75ba-041d-485a-8346-14b12e2c5f66)

<h1>Task 2</h1>
Now that the variable device_id is defined, you can return its data type.

In this task, use a Python function to find the data type of the variable device_id. Store the data type in another variable called device_id_type. Then, display device_id_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/6984f1b9-e3b9-4171-8491-c24b6de494c8)

<h1>Question 1</h1>
Based on the output above, what do you observe about the data type of device_id?

The output above shows that the data type of device_id is str, which means that device_id stores a string value.

<h1>Task 3</h1>
As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are "madebowa", "jnguyen", "tbecker", "nhersh", and "redwards".

In this task, create a variable called username_list. Assign a list with the approved usernames to this variable. Then, display the value of the username_list variable.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/36085c1c-1581-442a-8282-903ec54672e3)

<h1>Task 4</h1>
In this task, find the data type of the username_list. Store the type in a variable called username_list_type. Then, display username_list_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/8fd0a422-02f4-4f49-a253-5341c5fb7ebb)

<h1>Question 2</h1>
Based on the output above, what do you observe about the data type of username_list?

The output above shows that the data type of username_list is list, which means that username_list stores a list.

<h1>Task 5</h1>
Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: "madebowa", "jnguyen", "tbecker", "nhersh", "redwards", and "lpope".

In this task, reassign the variable username_list to the new list. Run the code to display the list before and after it's been updated to observe the difference.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/18a7edf0-e382-41c6-9753-b7ae2ad2973c)

<h1>Question 3</h1>
Based on the output above, what do you observe about the contents of username_list?

The output above shows that the contents of username_list were updated after the variable was reassigned to the new list.

The first print() call output the original contents of the list. The second print() call output the updated contents, which includes the newly added username, "lpope".

<h1>Task 6</h1>
In this task, define a variable called max_logins that represents the maximum number of login attempts allowed per user. Store the value 3 in this variable. Then, store its data type in another variable called max_logins_type. Display max_logins_type to examine the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/102503db-81c0-4ca5-81f6-cc1f68d6f830)

<h1>Question 4</h1>
Based on the output above, what do you observe about the data type of max_logins?

The output above shows that the data type of max_logins is int, which means that max_logins stores an integer value.

<h1>Task 7</h1>
In this task, define a variable called login_attempts that represents the current number of login attempts made by a user. Store the value 2 in this variable. Then, store login_attempts data type in a variable called login_attempts_type. Display login_attempts_type to observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/488fda62-f11a-40b0-978f-37b24a63f79a)

<h1>Question 5</h1>
Based on the output above, what do you observe about the data type of login_attempts?

The output above shows that the data type of login_attempts is int, which means that login_attempts stores an integer value.

<h1>Task 8</h1>
In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/b2ffe44c-6849-4f33-8aa0-aa911f91eb28)

<h1>Question 6</h1>
What is the output? What does this mean?

The output above is True, which indicates that login_attempts is less than or equal to max_logins. In other words, the current number of attempts the user has made to log in has not yet exceeded the maximum number of attempts allowed.

<h1>Task 9</h1>
This code continues to check for the Boolean value of whether max_logins is less than or equal to login_attempts. In this task, reassign other values to login_attempts. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/06f8ca6f-bf85-4399-8910-f7388652031b)

<h1>Question 7</h1>
Based on the different values you assigned to login_attempts, what did you observe about the output?

The Boolean value in the output changes depending on the value assigned to login_attempts. For example, when login_attempts is assigned to 4, the output is False, which indicates that login_attempts is not less than or equal to max_logins. In other words, the current number of log in attempts the user has made has exceeded the maximum number of attempts allowed.

<h1>Task 10</h1>
Finally, you can also assign a Boolean value of True or False to a variable.

In this task, you'll create a variable called login_status, which is a Boolean that represents whether a user is logged in. Assign False to this variable and store its data type in a variable called login_status_type and display it.

Be sure to replace each ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/18b665fe-429c-4dc7-9c4f-eaa3d9dfb5ba)

<h1>Question 8</h1>
Based on the output above, what do you observe about the data type of login_status?

The output above shows that the data type of the login_status is bool, which means that login_status stores a Boolean value.

<h1>Conclusion</h1>
What are your key takeaways from this lab?

- There are many useful operators in Python that help you work with variables.
- The = assignment operator allows you to assign or reassign a specific value to a variable.
- The <= comparison operator allows you to compare the value of one variable to the value of another.
- The type() function in Python helps you to determine the data type of an object.
- If you pass in a variable to type(), it will output the data type of the value stored in the variable.
- The print() function in Python allows you to display information.
- It can take in a value directly, a variable that stores a value, or a comparison between variables that evaluates to a Boolean value.
