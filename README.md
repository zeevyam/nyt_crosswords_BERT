# nyt_crosswords_BERT
Trying to solve NYT famous crosswords using NLP tool , specifically BERT fine-tuned as a MLM task.

Crosswords are a type of word puzzle that many
people around the world solve as a pastime. Additionally,
crosswords are a great mental exercise and
you can find them in all shapes and sizes as well
as different themes. New York Times (NYT for
short) is probably the most well know crossword
producer globally. NYT crosswords are available
on many different platforms, such as application
for your mobile phone, a digital crossword from the
NYT website and newspaper publications. Since
the newspaper is printed each day, Sunday through
Saturday, the crosswords must be updated daily.
Crosswords differ in difficulty level through the
size of the grid, obscureness of the clue, prevalence
of the answer word and the number of words
that comprise the answer in some cases. The main
factor which determines the difficulty level of a
NYT crosswords is the day of the week they are
published at. Monday crossword is the easiest and
Saturday is the hardest, Sunday crosswords are
mid-week difficulty1.
For one to solve a crossword one needs to have
broad, but shallow, general knowledge of a variety
of disciplines such as: geography, world events,
literature, culture, music etc. For us this may seem
1Wikipedia’s page about the NYT crosswords NYT crossword’s
Wiki
like a very trivial matter because most of us acquire
this knowledge thorough out our life. We acquire
this knowledge in school, by traveling places, reading
book, watching movies etc. Unlike us, a computer
won’t find it that easy of a task Keim et. al
1999 [3].
In this article we will show the power-of stateof-
the-art NLP model named BERT, which stand
for Bidirectional Encoder Representations from
Transformer Devlin et. al 2018 [1]. BERT model
was trained using masked language modeling tasks,
MLM, and a next sentence prediction task, NSP.
BERT based models have been quite successful in
various natural language tasks such as Question
Answering Reddy et. al [7]. This article we show
that BERT has the lingual understanding and broad
general knowledge, allowing it to solve a complex
riddle in the form of a Clue in a crossword. We
show that although the average score of our model
is averaged around 87% on the training set and
about 41% on the test set, with enough training
data, transformers model such as BERT could be
used for a variety of different and not trivial task
that extend beyond the classical natural language
processing tasks.
