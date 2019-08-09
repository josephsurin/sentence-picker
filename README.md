```bash
usage: pick [-h] [-i INP] [-w WORDS] [-n NUMBER] [-t THRESHOLD] [-o OUT]
            [--no-score]

tool to find the sentences with the most occurences of particular words

optional arguments:
  -h, --help            show this help message and exit
  -i INP, --inp INP     Input text; either a filename or - to read from stdin
  -w WORDS, --words WORDS
                        Target words to be used for scoring; either a filename
                        (for a file with a word on each line) or - to read
                        from stdin. If both the input text and word list are
                        being read from stdin, place the token ==WORDS== on a
                        line before the first word to indicate the start of
                        the word list
  -n NUMBER, --number NUMBER
                        Number of sentences to show (shows all by default)
  -t THRESHOLD, --threshold THRESHOLD
                        Minimum score required for a sentence to be shown
  -o OUT, --out OUT     File to print output to
  --no-score            Only show the sentences
```
