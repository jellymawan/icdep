# Extension: How can we add additional features to the protocol without breaking previous functionality?

## Send to any individual on the whole UW campus
### Solution 1:
- The person sending the message will say: "are you [recipient]?"
- If the answer is no, then the person (node) will take the message and pass it on. They will also ask: "are you [recipient]?" This process is repeated until the message reaches the recipient
- If the answer is yes, the recipient will read the message.

### Solution 2:
- The person sending the message will give the index card to someone who has relation to the recipient (i.e. is in their class, is their friend, etc)
- If the person does not know anyone who knows the recipient, they will randomly give the index card to a random person
- The random person will then repeat the two above steps
- This process is repeated until the recipient receives the index card

## Specify whether contents are ASCII text, Unicode text, or binary values
- Write down the type of content in human-readable form (ASCII) on the corner of the index card. The receivers will be able to read what type of message is written in the index card without actually seeing the message.

## Keep a record of what nodes the card has passed through.
- On the index card, write down a unique identifier of each node (person) that has received the card. This can be name, student ID, etc.
