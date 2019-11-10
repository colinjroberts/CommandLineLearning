# Command Line Learning
A project for experimenting with learning tools at the command line.

## Purpose
Ultimately, the goal of this project is to experiment with implementing learning tools to be used form the command line. It is part programming exercise and part experiential learning of pedagogy. 

## Direction
This project is likely to change direction quickly depending on what I'm working on and thinking about. A current focus is C++, so both the implementation and content will focus on getting a working product using content I am learning. Though questions and answers are abstract and could potentially be used for anything, it is really my personal learning tool and will be built to suit my current needs. The current goal is to practice C++ concepts and syntax using a question consisting of one to a few lines of C++ and one of two questions: "What does this do?" and "What, if anything, is wrong with this code?" 

## Roadmap
### V0.1 - C++ Flashcards <- current
- A CLI for reviewing flashcards
- System presents random flashcards of C++ Syntax
- Cards are question/answer, front/back
- Questions are hand written and hard coded into the source

### V0.2 - Card Management and Control
- System employs some ordering of flashcards in addition to randomness to reduce repeating too soon
- Cards can be marked as complete and stop showing up in reviews
- Questions are saved in a txt file and parsed

### V1 - Question Spacing, Randomization, and Combination
- Cards use some kind of some variant of spaced repetition.
- Questions can have multiple variants to avoid the trap of learning the card not the content
- Questions become components that can be randomly mixed such that a question might have 1-3 errors in it
- Configuration file allows user to set features like min and max # of errors a question can have and what topics to show

## Why?
The current direction is inspired by a class at the University of Washington Bothell in which some exam questions involved looking at code snippets and determining whether anything was wrong with them. Despite the widespread use of IDEs with syntax checking, I believe it is good practice to hone the skills of quickly spotting errors. 
