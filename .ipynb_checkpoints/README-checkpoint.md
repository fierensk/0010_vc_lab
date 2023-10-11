Welcome to hello-world. If you wish to contribute, please read the Contribution section below. We are an age collecting database for online surveys. A user inputs their name and the year they were born, and the software reports their age based on the year alone.

**Installation**
To access our software, you need a JupyterHub account and terminal. From there, run the command: git clone https://github.com/fierensk/0010_vc_lab
Open program.ipynb and run it.

**Usage**
Upon running, your output should look like this:

Please enter your name: (input field)

The program should have three lines, the first two requiring input and hitting enter to move to the next. The last two lines will resemble:

What year were you born: (user input)
You are (output) or (output) years old.

**Implementation**
Essentially, we take a name input and year input from the user here:

```python
name_inp = input("Please enter your name: ")
us_input = input("What year were you born: ")
```

Then we calculate the age of the person, with allowance for where in the year we are:

```python
age = 2023 - int(us_input)
age2 = 2022 - int(us_input)
```

Finally, we output the result of the calculations:

```python
print("You are " + str(age2) + " or " + str(age) + " years old.")
```

**Contribution**
Hello! Thank you for checking us out. As a team of two unpaid students, we work on hello-world solely out of passion. We're always looking for fellow tinkerers to join our community. Currently, we are working hello-world v1.5. Our goals are to implement allowances for a date of birth to make our software more accurate. If we could get this implemented, we could improve online surveying and support the scientific community as a whole. 
If these ideals resonate with you, please consider contributing. Our license and code of conduct can be found in the same file as this README. If you have accessed and installed the program as above, all you need to do is directly submit pull/push/merge requests directly using Git. You're also invited to join our Discord with the code: sjdajdhk to discuss further. We hope to see you soon!

Thanks,
Kate and Feyza at hello-world co.

**Rationale for license and CoC choices**
For our license, we looked over the multiple that are available online. Given we have little stock in the product but what to preserve the heart of the project, we chose GNU GPLv3. This license allows pretty much any changes to be made to the project. However, this license prohibits distributing closed source version, making sure that it carries the priciple of open exchange no matter the situation.

For the code of conduct, we were stuck between the Django code of conduct and the Contributor Covenant CoC. While the Django code was more concise (more likely for people to read it), it didn't cover actions that could occur in bad faith as much, as is common in online spaces, like trolling. There is an arbitrary line between harassment and trolling in some peoples' minds, so its really good to include that. The more fleshed out terms of the Contributor Covenant allow for more protection for community members, so we chose that one.