# BookMatch AI - Final Project for the Building AI Course

## Summary
BookMatch AI is an interactive conversational agent designed to recommend personalized book suggestions based on the user's current mood, preferences, and answers to a few targeted questions.

## Background
* **The Problem:** Many readers struggle to find a book that matches their exact current mood or interests.
* **Personal Motivation:** I wanted to build an intelligent solution that makes book discovery fun and personalized.

## How is it used?
* **The Process:** Users answer a few short questions about their current mood and interests, and the AI suggests a matching book.
* **Example Code:**
```python
def recommend_book(user_mood):
    if user_mood == "happy":
        return "The Alchemist"
    else:
        return "Atomic Habits"
