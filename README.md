# Codeclause_Random_Password_Generator_in_Python
Having a weak password is not good for a system that demands high confidentiality and security of user credentials. It turns out that people find it difficult to make up a strong password that is strong enough to prevent unauthorized users from memorizing it. I will create a mixture of numbers, alphabets, and other symbols found on the computer keyboard to form a 8-character password which is unpredictable and cannot easily be memorized.
# Requirements
For developing a random password generator in Python, we will need a good understanding of Python programming like the working of loops, operators, and functions. Along with that, we will be using some data structures like lists, strings, etc. Apart from these, we need to use the random module of Python. The random module in Python provides us with various functions that help us to randomly choose among various values. Some of the most important functions of the random module are randint(), sample(), choice(), seed(), sample(), etc.In this random password generator program, we will be using some of the functions of the random module. 
# choice() :
The choice() method is one of the most important methods of the random module. The choice() method selects a random value (or element) from the provided sequence. Now this sequence can be any sequential data type like strings, lists, tuples, or any other sequence of numbers or objects.
# sample() :
The sample() method is used to obtain a sequence of randomly selected values from the provided input sequence. The sample() method returns a list of unique choices. The sample() method takes two parameters. The first parameter is the original sequence from which the output random sequence has to be generated. The second parameter is the length of the random sample that needs to be generated.
# Generate a Password Using All Alphanumeric Characters
# Before getting into the implementation of generating random passwords using all alphanumeric characters.
# At the very start, we need to import the random module.
# Create a function generatePassword() that will return a randomly generated password. The generatePassword() function takes one argument i.e. n which denotes the length of the password to be generated.
# Create a string or list consisting of all the alphabets (both small alphabets and capital alphabets), numbers, and symbols.
# Initialize an empty string that will store the randomly selected password.
# At last, we will run a loop from 0 to n. In each iteration, we will randomly choose a character from the list of characters (using the random.choice() method) and add the selected character to the password string. Finally, we will return the password string at the end of the loop.
