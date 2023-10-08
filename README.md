# Madlibs Program

## Description

This is a simple Python program that allows you to play Madlibs! You'll be prompted to input various types of words, and then the program will plug them into a sentence template to create a wacky story.

## How to Run

1. Ensure you have Python installed on your system.
2. Download or clone this repository.
3. Run the program by executing `python madlibs.py` in the terminal.

## Code Overview

The story template is:

```
"The {noun} {adjective} {verb} over the {place}."
```

You'll be asked to input:

- A noun
- An adjective
- A verb
- A place

Here is the main code snippet:

```python
story_template = "The {noun} {adjective} {verb} over the {place}."

noun = input("Please Enter a Noun: ")
adjective = input("Please Enter an Adjective: ")
verb = input("Please Enter a Verb: ")
place = input("Please Enter a Place ")

completed_story = f"The {noun} {adjective} {verb} over the {place}."
print("Here is your madlibs story: ")
print(completed_story)
```

## How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin new-feature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License.
