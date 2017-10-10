# Overview

This repository contains basic info on the goals and findings of Team Sibyl.
If you're new or unsure of what you should be doing, you're in the right place.

## About us
Team Sibyl is an ad-hoc research group operating under the Cloud Computing and Big Data center in PES University.

Our focus is on binary analysis techniques, specifically on ways to automatically understand their function.

## Contributing
If you are a member of the team (or wish to be one), you should:
1. Apply to this GitHub organization, if you are not already a member(contact one of the members for an invite).
2. Go through the fuzzing-research repo, and understand all of our prior research.
The angr paper is of particular importance.
Read the paper, or at least the summary of it, before you do anything else.
3. Go through the issue tracker on this repository.
Feel free to weigh in on anything listed there.

If you are one of our supervisors/faculty, you can see our current status, as well as our general progress through the issue tracker on this and other projects.

If you are neither of those, you're probably not in the right place.
Though if you have an idea, an issue/PR is always welcome.

## Isuue tracking
All of our progress is tracked through the Github issue tracker.
Discussions and debates should take place either face-to-face, or in the issue tracker.
We do not use Zenhub boards yet, though we plan to.

## Tools
All of our work is done on the angr frameworks, written in Python.
Setting up should be as simple as:
```
pip install angr
```

This will work in 99% of cases on any Linux system.
If you're running Windows/Mac OS, you're on your own.
If you have any trouble, consult the [docs](https://docs.angr.io)

In addition, all of our ML work(if any) will be done in Tensorflow/Keras.
Setup should once again be as simple as:
```
pip install tensorflow keras
```
All of our code is written in Python 2.
We are unable to utilize Python 3, since angr lacks support for it.
Any requests to change languages will be ignored with impunity.
We are on a tight time budget, and we cannot afford the time to code in any lower-level language.
