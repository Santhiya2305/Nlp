import spacy
base = spacy.load("en_core_web_sm")
input="""
Wow!yesterday, Dr.Arun kumar announced that he will quickly launch
three innovative AI based projects.
In chennai beacuse they can significantly improve public safety.
it may not only reduce accidents but also improve lives.
There are 50 experts working on this field.
"""

doc = base(input)
for token in doc:
    print(token.text,"->", token.pos_)
