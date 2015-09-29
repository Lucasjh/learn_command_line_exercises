The `|` commands takes the output of the command on the left and puts it into the input of the command on the right.

The `<` command will send the text from the file on the right to the program on the left.

The `>` takes the output of the command on the left, then puts it into the file on the right

The `>>` takes the the output of the command on the left and adds it to the file on the right.


Can you put "This class is fun" into bar.txt?

`echo "this class is fun" >> bar.txt`

Can you put "Oh so much fun" into foo.txt?

`echo "Oh so much fun" >> foo.txt`

