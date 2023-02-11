# Vim Motions

Personal Preference in moving around using vim which is also a text based editor. I personally use VScode Vim extension to get the functionality of Vim inside my VScode here is the few easy motion keys to move around

NOTE: Works both in Vim Editor and VScode Editior(VIM Extension must be installed)


## Modes:

* i: Insert
* jk/ESC: Command
* v: Visual


## Basics:

* j: Down
* k: Up
* h: Right
* l: Left
* 0: Beginning of the line
* $: move to the end of the line
* ^: Move to the first non blank character in the line

## Basic Insert:

* i: insert before the cursor
* a: append after the cursor
* I: insert at the beginning of the line
* A: append at the end of the line
* o: open a new line below the current one
* O: open a new line above the current one
* r: replace the one character under your cursor
* R: replace the character under your cursor, but just keep typing afterwards
* cm: change whatever you define as a movement, e.g. a word, or a sentence, or a paragraph.
* C: change the current line from where you're at
* ct?: change change up to the question mark
* s: substitute from where you are to the next command (noun)
* S: substitute the entire current line


## Basic Deletions:

* x: exterminate (delete) the character under the cursor
* X: exterminate (delete) the character before the cursor
* dm: delete whatever you define as a movement, e.g. a word, or a sentence, or a paragraph.
* dd: delete the current line
* dt.: delete delete from where you are to the period
* D: delete to the end of the line
* J: join the current line with the next one (delete what's between)

## Moving by word:

* w: Move forward one word
* b: Move backword one word
* e: Move to the end of the word
* W: Moves forward one big word
* B: Moves backward one big word

## Moving by sentence or paragraph:

* ): Move forward one sentence
* }: Move forward one paragraph

## Moving with the screen:

* H: Move to the TOP of the SCREEN
* M: Move to the MIDDLE of the SCREEN
* L: Move to the Low/BOTTOM of the SCREEN
* gg: Go to the TOP of the FILE
* G: Go to the BOTTOM of the FILE
* ^U: Move up half screen
* ^D: Move down half a screen

## Verbs:

* d: Delete
* c: Change
* y: Yank
* v: Visualize select

## Modifiers:

* a: Around
* i: Inside
* t: Seraches for something and stops before it
* f: Search for something and stops on it

## Nouns:

* w: Word
* p: Paragraph
* s: Sentence
* t: Tag
* b: Block

## Noun as motion:

* d2w: Deletes 2 words
* cis: Change inside Sentence
* yip: Yank inside a Paragraph
  

## Jumping to certain characters:

* f<: Jumps forward and lands on <
* t<: Jumps forward and lands right before <
* n: go to the next instance of the word looking for
* N: go to the previous instance of the word looking for
* ; : Go to the next instance to Jump
* , : Go to the previous instance to Jump


Above keybindings is preffered thourgh [this link](https://danielmiessler.com/study/vim/#language)