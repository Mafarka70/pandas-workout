# Pandas Workout

Notebooks and solutions for [Pandas Workout](https://www.bambooweekly.com/pandas-workout/),
my book of 200 exercises for becoming fluent in Pandas.

Reading about Pandas teaches you what `groupby` does. It doesn't give you the
reflex to reach for it at the moment you need it. That only comes from writing
enough Pandas that the syntax stops being the hard part, and you can spend your
attention on the question you are actually asking of the data.

## What's here

One directory per chapter. Each exercise has two notebooks:

- `Exercise NN — Title.ipynb` — the exercise and my solution, with an
  explanation of why the solution works the way it does.
- `Exercise NNb — Beyond the exercise.ipynb` — the follow-up questions, for
  when you want to push a bit harder on the same data.

Chapters 8 and 13 are projects rather than exercise sets: longer problems that
pull together everything up to that point.

## Getting the data

The exercises work on real data sets, which live outside this repository
because of their size:

    https://files.lerner.co.il/pandas-workout-data.zip

Heads up: that download is about 865 MB. Unzip it wherever you like, then adjust
the paths at the top of each notebook to point at it.

## Running the notebooks

With uv:

    uv add pandas jupyter
    uv run jupyter notebook

Or with pip, if that is what you already have set up:

    pip install pandas jupyter
    jupyter notebook

JupyterLab works just as well, if you prefer it. Any recent version of Pandas
will do; where an exercise depends on behavior that changed between versions,
the notebook says so.

## Getting the book

- [Manning](https://www.manning.com/books/pandas-workout) — print and ebook,
  including access to liveBook
- [Amazon](https://www.amazon.com/Pandas-Workout-Reuven-Lerner/dp/1617299723)
- [O'Reilly](https://learning.oreilly.com/library/view/pandas-workout/9781617299728/)
  — included with a Learning Platform subscription

If the book helped you, an Amazon review genuinely does more for it than
anything else you could do.

## Keep practicing after the last exercise

Two hundred exercises is a lot, and it still ends. If you want to keep going:

- [Bamboo Weekly](https://www.bambooweekly.com/) — a new Pandas problem every
  week, built on real public data. Two of each week's questions and answers are
  free, as are hundreds of problems in the archive.
- [Better Developers](https://lernerpython.com/become-a-better-developer/) — a
  free Python article in your inbox every week.
- [Python Workout](https://lernerpython.com/python-workout/) — the same
  treatment for Python itself, if your Python needs the same work.
- [LernerPython](https://lernerpython.com/) — my courses, live sessions, and
  office hours.

## Elsewhere

- [YouTube](https://youtube.com/reuvenlerner)
- [Bluesky](https://bsky.app/profile/lernerpython.com)
- [Twitter/X](https://x.com/reuvenmlerner)
- [LinkedIn](https://linkedin.com/in/reuven)

Questions, corrections, or a solution you like better than mine?
reuven@lernerpython.com — I read everything.
