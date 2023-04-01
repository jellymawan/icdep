# How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, rather than treat them as pass-through intermediaries?
- The sender specifies which node they want to reach. (If the message is in the index card, then this would be like the envelope the index card would be in).
- The envelope is passed around until it reaches the specific node
- The node returns the envelope back to the sender with a note saying that the command is executed, and then actually executes the command.
