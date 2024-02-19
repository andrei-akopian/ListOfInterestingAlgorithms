# A List of Good Algorithms

The modern education system is unacceptably terrible at teaching Computer Science. You are tested on how well you know the syntax of your programming language, which is fundamentally wrong.

I think people who made the modern education system do not understand what Programming is about whatsoever.

There are many skills that I would expect to learn in a CS class. Not all of them but at least some.
- Debugging complex issues
- Searching online and searching for documentation
- Making a well designed website
- Writing simulations (for eg. physics)
- Processing large amounts of data quickly (file conversion and parsing)
- Learn algorithms and the beautiful math behind them

Somehow none of them are taught in school:
- Debugging is mostly fighting with the stupid IDE, that doesn't support something everybody online uses.
- You learn to use 1 graphics library with drag and drop instructions on how to use it.
- A Highschool CS student can't even make a creative looking quiz website.
- You don't learn how to write anything that can help you in a math class.
- Converting data and automatic manual work is the purpose of an average person knowing how to code. It is never mentioned. What can and should be done in a Jupyter Notebook in 5 minutes, is outside the skillset of a computer science student in highschool.
- The best way to understand something, is to teach it. So why not explain the math you learned the day before to the computer?

Instead you learn the syntax of the language, or buzzword vocab.

# Algorithms

Unfortunetly most tutorials focus on the implementation of the algorithms, and not on the math behind them. So lets make a list of problems that put the math before the code.

## Template

Name (with wikipedia link): the general name of the algorithm
- Problems: the most best problems (from eg. Project Euler) that are solved using this algorithm
- Math Tags: Mathematical Concepts it is related to
- Related: related programming topics
- Description: comes last, because the mathematical and related concepts are the goal
- Videos: videos with the explanation of the algorithm (not the code and not the implementation)
  - videos could be either miminalist and entertaining. Decent sources:
    - [Tom Scott](https://www.youtube.com/@TomScottGo): has a series of short code videos
    - [Fireship](https://www.youtube.com/@Fireship): fast paced with jokes
    - [Computerphile](https://www.youtube.com/@Computerphile): Explained on paper, has some vibes of the terrible education system we are trying to avoid.
    - [Free Code Camp](https://www.freecodecamp.org/): More step by step tutorials than indepth explanations.
    - [Khan Academy](https://www.khanacademy.org): Worst among the good learning resources available
  - or more professional lecture by a professor
- Implementation: The cleanest most clear implementation of the algorithm
  - Use Python or JavaScript to eleminate complex syntax.
  - Use C for if a low level language is truly necessary.
  - Should have as few langauge specific operations as possible (eg. memory menagement)
- Other resources: other resources you consider important to include.

## The List

[Binary Search](https://en.wikipedia.org/wiki/Binary_search_algorithm):
- Problem:  
  - You have a bag of 1 cent coins (2 grams each) and one fake coin (with a mass of 3 grams) mixed in. You also have a balance, and you can put multiple coins on it at once. Using the balance as few times as possible, find the fake coin.
- Math Topics: Logarithms, [Numeral Systems](https://en.wikipedia.org/wiki/Numeral_system) 
- Related:
  - binary trees
- Description:
  - The fastest way of figuring out a number from yes/no questions is to literally ask what each digit is. This is how the trick where you find one's birthday using 5 cards works.
- Videos:
  - by [Fireship](https://www.youtube.com/watch?v=MFhxShGxHWc)
  - by [Tom Scott](https://www.youtube.com/watch?v=KXJSjte_OAI)
  - by [Computerphile](https://www.youtube.com/watch?v=hDn8iOc30Tk)
- Other resources:
  - [Khan Academy](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)

[Wagner-Fisher](https://en.wikipedia.org/wiki/Wagner%E2%80%93Fischer_algorithm)
- Problem:
  - Given two words, find how many insert, delete, or substitute operations you need to change one word into the other. (Used for spellchecking suggestions)
- Videos:
  - by [b001](https://www.youtube.com/watch?v=d-Eq6x1yssU)

