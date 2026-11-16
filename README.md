# math-concept-for-developers-project
# Birthday Paradox: A Learning Diary in Math Concepts for Developers

# The Birthday Paradox

How many people are needed in a room before a shared birthday becomes likely? This project starts from that one simple curiosity and follows it through mathematics, simulation, real data and an application in computer science. It is my final project for the SoftUni course *Math Concepts for Developers*.

## The central question

How many people are needed for at least a 50% chance that two of them share a birthday?

## Follow-up questions

1. How do we calculate the exact probability? (probability and counting pairs)
2. Does a simulation agree with the formula? (random groups, repeated 1,000 times)
3. How does the answer change with real birth data, where not all days are equally likely? (weekend effect, holidays, single years vs. all years combined)
4. Where does the same idea appear in practice? (hash functions: a collision is a shared birthday, and the group size needed grows like the square root of the number of possible values)

## What is in the notebook

- **Mathematics:** the probability of a shared birthday and the "counting pairs" explanation of why the answer is 23.
- **Simulation:** random groups of birthdays, compared with the formula.
- **Real data:** 21 years of US-looking birth counts (1994–2014), including the weekend effect and the lowest-birth days.
- **Hash functions:** the square-root rule, an experiment with SHA-256 cut to 8–40 bits, and a plot of how the running time grows.
- **Conclusion:** a summary and the next steps.

## Status

This project is not complete. The planned next step was a section on how the birthday attack has been used against real hash functions such as MD5 and SHA-1, and what has been done about it.

## Files

- `project.ipynb`: the notebook with the analysis, math and code
- `kaggle_birthdays_data.csv`: the dataset (see the source below)
