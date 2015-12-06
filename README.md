# Dataset of Developer-Labeled Commit Messages In SQL
This has been shamelessly taken from https://github.com/flobrosch/msr-data and converted to SQL
so that SQLite does not have to be used to analyze the data. Also I realized after I did all this
work that I should have just submitted a pull request so I did that. Use the `msr-data` repo instead!!

All credits for doing the actual work should go to the authors of the dataset Andreas Mauczka, Florian Brosch, Christian Schanes, Thomas Grechenig
and their paper "Dataset of Developer-Labeled Commit Messages." I had nothing to do with its creation I am only someone with a dislike of SQLite.

## Getting Started
It's easy.

    cd msr-survey-data-sql
    mysql -u user -p password < schema.sql

Edit bootstap.sh for your mysql username and password

    ./bootstrap.sh

You're done. Enjoy
