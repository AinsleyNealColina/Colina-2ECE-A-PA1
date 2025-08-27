# Colina-2ECE-A-PA1

# Problem 1
For the 1st problem we are tasked to create a function that takes a string and returns a string with its letters in alphabetical order.
Example # "hello" -> ehllo

1st we are going to create the function: alphabet_soup(word)
return ''.join(sorted(word)).This function takes a string and returns its letters sorted alphabetically that is what the sort is for.

2nd we are going to create a loop: def main():
    while True:
    user_input = input("Enter a word (or type 'exit' to quit): ") This allows the user to type any word they want

3rd we are going to create the break,this is to stop the loop and to stop it we need to type "exit"

4th we are going to call back and show the function, to do this we are gonna name it result and it is equal to our (user input),then print the result.

Lastly the last part:if name = main:main() it is to start our function

# Problem 2
For the second problem we are tasked to create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad and mad with their corresponding emoticon:
Example # "smile"=':)'

1st we are going to create the name of the function emotify(sentence)after that  we are gonna write emoticon_dict to store our words and turn them into emoticons

2nd we are gonna add the split function to seperate the sentence into words

3rd we are gonna create an interactive loop that asks us a sentence, using the while loop.Then to break the loop or end the code we must type 'exit'.

4th we are going to convert the sentence then show the result, we need to assign the result as the emotify(user_input) then print(and call back the result )

Lastly the last part:if name = main:main() it is to start our function
