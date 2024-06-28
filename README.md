A quick MVP of comparing religious text corpora using semantic chunking and openAI embedding. Current approach:

1. Uses a single ipython notebook
2. Has low code quality, poor naming, repeated code, unused code, bad conventions, inverted abstractions, etc.
3. Does not contain visualizations or tests
4. Uses cached data or pulls from gutenburg if not all three compared texts are there
5. Will leave texts in whatever folder run
6. Does not clean data

A future approach may:
1. Clean data
2. Have tests
3. Allow for different translations
4. Be better tuned
5. Contain visualizations
6. Ideally, run each against every and form a graph. Tinkerpop would be nice.
7. Potentially have a topic layer as an entry point in a graph. That is, support graph workflows following: topic -> concept -> related concept in other texts
