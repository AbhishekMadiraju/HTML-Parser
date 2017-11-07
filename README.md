# HTML-Parser
A  HTML parser written using lex and yacc which takes as input any number of files and returns a CSV with required content in minimal time.

Wrote a YACC grammar which analyses the input HTML file with over 2000 lines and extracts only the options table and other data within selected tag.

Wrote a Lexical Analyzer which analyzes the incoming input and extract only the specified text which are passed onto the Yacc Grammar.

I have provided the sample dataset for J.P Morgan taken from NASDAQ. But, the program can be run on options table of any company in NASDAQ.
With just a few modification to the grammar, we will be able to get data from various other website HTML pages as well.
