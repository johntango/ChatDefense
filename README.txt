# This system sets up defenses against adversarial attacks on text generation models.
### We hide the system message from the user, so that they don't know that we are using a defense.
### We also transform the user message into a specially tagged format
### We can also check the LLM's response for potentially adversarial content eg python code or SQL queries
