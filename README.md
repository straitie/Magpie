# Magpie Lab

## Activity 1

In this activity, you are going to explore some current chatbots. Go to [https://sites.google.com/site/webtoolsbox/bots](https://sites.google.com/site/webtoolsbox/bots) to see some examples of chatbots. Take notes of which ones you visited and how the chatbot responded to questions such as 

- "Where do you come from?"
- "asdfghkl;"
- "What is your name?"

Also, take note of
- The most interesting response
- Most peculiar response
- Keywords is seems to pick up on and the responses

## Activity 2

In this activity, you will work Magpie, with a simple implementation of a chatbot. You will see how it works with some keywords and add keywords of your own.

### Prepare
Have available:
- the code for the Magpie
- the code for the MagpieRunner
- a computer with your Java development tools

### Start
Get to know the Magpie class. Run it, using the instructions provided by your teacher.
How does it respond to:
- My mother and I talked last night.
- I said no!
- The weather is nice.
- Do you know my brother?

### Exploration
Look at the code. See how the if statement assigns a value to the response and returns that response. The method getRandomResponse picks a response from a group of String objects.

### Exercises
Alter the code:
- Have it respond “Tell me more about your pets” when the statement contains the word “dog” or “cat.” For example, a possible statement and response would be:
Statement: I like my cat Mittens.
Response: Tell me more about your pets.

- Have it respond favorably when it sees the name of your teacher. Be sure to use appropriate pronouns! For example, a possible statement and response would be:
Statement: Mr. Finkelstein is telling us about robotics.
Response: He sounds like a good teacher.

- Have the code check that the statement has at least one character. You can do this by using the trim method to remove spaces from the beginning and end, and then checking the length of the trimmed string. If there are no characters, the response should tell the user to enter something. For example, a possible statement and response would be:
Statement:
Response: Say something, please.

- Add two more noncommittal responses to the possible random responses.
- Pick three more keywords, such as “no” and “brother” and edit the getResponse method to respond to each of these. Enter the three keywords and responses in a table like the one shown below.

| Keyword       | Response      |
| ------------- | ------------- |
|               |               |
|               |               |

- What happens when more than one keyword appears in a string? Consider the string “My mother has a dog but no cat.” Explain how to prioritize responses in the reply method.

### Question
1. What happens when a keyword is included in another word? Consider statements like “I know all the state capitals” and “I like vegetables smothered in cheese.” Explain the problem with the responses to these statements.
