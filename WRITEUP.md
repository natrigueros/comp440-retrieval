# COMP 440: Representing and Retrieving Knowledge

Claude writes your answers here as you say them. A sentence or two is enough for each. Your
Part 0 predictions stay as you first wrote them; Part 5 asks what you would change.

**Name:** Nayla Trigueros
**Date:** October 20, 2026

## Part 0: Predictions

### Questions that name a character, place or thing: which method will do better, and why?

I think keyword search will do better, probably on a character, especially if it's unique to the movie and not a common name, because it will look for a match for that specific word.

### Vague descriptions: which method will do better, and why?

since embedding search can give more of a general context i think it would do better

## Part 1: Build the TF-IDF model

### The settings you chose, and why

- `REMOVE_STOP_WORDS = True`: to make sure identifying words like "ghost" or "sailor" matter more.
- `MIN_MOVIES = 2`: making it = 2 could help with typos.
- `REPEATS_COUNT_LESS = True`: to make sure a common word is not getting more weight than an identifying one.

## Part 2: Top terms

### Your movies: what do the top terms get right and wrong about what makes each one distinctive?

percy: its pretty good terms, with percy being the top 1 (makes sense). pride & prejudice: there's more "sentence" words and not description terms, but still gets the hang of the movie plot.

## Part 3: Your own searches

### Your questions, as you typed them

1. There's this movie about a woman who has a car crash and suddenly gets this disease that makes her unable to age. She falls in love with this boy but has to move because after years she doesn't age, and then decades after falls in love with that boy's son.
2. Small town, rich girl poor guy, separation, cheating, white house, blue shutters, dementia
3. the world is ending because of climate and a group of scientists send people into space to figure out if other planets are viable for life

### Did the movies you meant come up? What did TF-IDF get right and wrong?

None of my movies showed up. I think it just takes a few words and considers it enough for a match and by doing so misses some context.

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

Seems like detail questions did best, and both reworded and vague did pretty bad, like literally 0 of them right.

### The misses you looked at: what do they have in common?

It just seems like the TF-IDF used mostly super common words like "rich" or "park" to identify movies.

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

XXXX

### Where does each method do better, and why?

XXXX

### Your Part 0 predictions: which held, and which would you change?

XXXX

### How might you combine the two methods?

XXXX
