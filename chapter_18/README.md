Show me the lines in foo.txt that have "ERROR" in them.

- I would run `grep "ERROR" foo.txt` and it will return `ERROR`

Show me the lines in bar.txt that have "davinci" in them.

- I would run `grep "davinci" bar.txt` and it will return `davinci`

Can you print all the lines in text files that have your first and last name in them?

I would run `grep "Lucas Henderson" *.txt` and it will return:

    bar.txt:Lucas Henderson
    foo.txt:Lucas Henderson
