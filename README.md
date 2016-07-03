# Inlcusion toolkit game

This is a game which may serve as a tool for fostering empathy and anti-oppressive practice. It is intended for community organizations and work groups to self-evaluate their practices from the perspective of an anti-oppression framework.

## Why use this?

- It can spark discussions in your group by providing starting points for improvement.
- Using this as a group may overcome one of the key challenges to initiating change: gaining a collective awareness of current needs.
- It can simply be a learning experience if you are unfamiliar or still learning about the anti-oppression framework.
- It's free, costs you only as much time and effort as you are willing to invest into it.

## How to use this?

* Prepare by setting up **a space for trust and safety** among the group. Either use trust exercises, or see some suggestions in the instructions around framing the toolkit.
* Approach it with **common purpose**, but ensure that the group invited to use the toolkit has a shared understanding of what they're about to embark on.
* Be **permissive of mistakes** as it takes experience and openness to learn about difference.
* Encourage **time-outs for constructive discussion** provided they are about personal experiences related to what was said, or reactions people want to share constructively.
* If possible, involve people with different levels or domains of decisional power when using the toolkit as a group.

## Getting practical

* Print the instructions.pdf file.
* Print the png files in the folder 'cards' and cut them out. They are formatted as poker-sized cards.

# Building the deck

The instructions are built using [pandoc](http://pandoc.org):

    pandoc instructions.md -o instructions.pdf --latex-engine=xelatex

The YAML header block includes commented options for letter ouptut, default is tarot-sized booklet. It can be subsequently converted to png using imagemagick:

    convert -density 300 -quality 85 instructions.pdf instructions.png 

The cards are built using illustrator external files for variables and the Variable Importer from Silly-V, [https://github.com/Silly-V/Adobe-Illustrator/tree/master/Variable%20Importer](https://github.com/Silly-V/Adobe-Illustrator/tree/master/Variable%20Importer).
An excellent tutorial is available at [http://hypertransitory.com/blog/2015/04/26/illustrator-variable-data/](http://hypertransitory.com/blog/2015/04/26/illustrator-variable-data/).