# Cloze HTML builder

[Open Cloze HTML builder](http://htmlpreview.github.io/?https://github.com/picoral/cloze_html_builder/blob/master/index.html)

What is a cloze exercise? [Here's an answer.](https://en.wikipedia.org/wiki/Cloze_test) 

The Cloze HTML builder is a tool for language teachers. Enter your text on the area on the left of the interface to generate html code that allows students to self check their answers. You can either download the generated code as a standalone webpage, that you can then upload to your course management system or another web server, or you can copy and paste the code to a HTML editor in your course management system.

When you open the tool, an example in Portuguese is pre-loaded.

![alt text](screenshots/onload.png "screenshot of interface when first loaded")


Note that the first line in your text will always be the title (i.e., the instructions) in the HTML version. Add your cloze items starting from the second line.

```
Complete as frases abaixo com os tempos adequados do SUBJUNTIVO (presente, imperfeito ou futuro):
1. Vamos comprar um colchão novo quando _____________ (ter) dinheiro. [tivermos]
```

For each cloze item, use underscores to represent where the input text field should go:

```
2. É aconselhável que as pessoas _______________ (beber) muito líquido durante o verão. [bebam]
```

All underscores will be replaced by one textfield input in the HTML code.

The correct answers (i.e., the words that are acceptable to complete the blank) go between square brackets.

```
3. Foi importante que Rodney King ____________ (dar) uma entrevista na televisão na sexta-feira passada. [desse]
```

You can have a sentence with multiple blanks, but be sure to have as many groups of correct answers between angle brackets as blanks to be filled in your sentence. For example, here's a sentence with two blanks. Note there are two sets of angle brackets at the end of the line:

```
5. Esperaria na fila a fim de que _______________ (poder) comprar um ingresso para o show se ___________ (ter) paciência. [pudesse] [tivesse]
```

In some instances, there are multiple correct answers for one blank. Enter these options separated by comma withing the same square brackets to indicate multiple correct answers.

```
13. Ela lavará a roupa depois que ___________ (pôr) a mesa. [por, pôr]
```

If you are ready to start working on your cloze exercise, [open Cloze HTML builder](http://htmlpreview.github.io/?https://github.com/picoral/cloze_html_builder/blob/master/index.html)
