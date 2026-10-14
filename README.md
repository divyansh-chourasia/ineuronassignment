# Pattern programs

Five Java files. Each one is its own program, with a `main`, a fixed size, and no input. They print asterisks, or digits, to the terminal.

`Pattern_INEURON.java` prints the word INEURON. Each letter is 10 rows tall, drawn with `*`, and a tab separates the letters. I is a vertical line. N is the two sides and the diagonal. E is the left side plus the top, middle, and bottom. U is a cup. R is the upper bowl and a diagonal leg. O is a hollow box. The last letter is N again.

`Pattern_K.java` prints 14 rows. The first and last rows are solid. The rows between them fill a wedge on the left. Stars are printed as `* ` and empty cells as a single space, so the columns do not line up.

`Pattern_hut.java` prints 14 rows of a hut: the outline of a square, plus a roof across the top. Stars are `* ` and empty cells are two spaces.

`Pattern_lVl.java` prints 14 rows of a V. Stars fill the lower left and the lower right. The top rows are blank, and the bottom row is solid.

`Pattern_num.java` prints four lines. Each line is that row's digit, four times:

```
1111
2222
3333
4444
```

## Run

From this folder, compile and run one file:

```bash
javac Pattern_INEURON.java
java Pattern_INEURON
```

Use the same commands for `Pattern_K`, `Pattern_hut`, `Pattern_lVl`, and `Pattern_num`.
