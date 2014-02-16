# Gabs Automator Workflows
A collection of Automator workflows that I created to speed up repetitive tasks.

## Installation
Paste the following code at a Terminal prompt:

```shell
bash <(curl -fsSL https://raw.github.com/gabstv/automator-workflows/go/install)
```

The script explains what it will do and then pauses before it does it. If you don’t trust it, [download the zip package](https://github.com/gabstv/automator-workflows/releases) and manually copy the workflows to `~/Library/Services/`.

## Available Workflows

### Count Chars
![Count Chars](https://s3.amazonaws.com/gabstv-github/automator-workflows/count-chars.jpg)

### Count Words
![Count Words](https://s3.amazonaws.com/gabstv-github/automator-workflows/count-words.jpg)

### Preencher Boleto
![Preencher Boleto](https://s3.amazonaws.com/gabstv-github/automator-workflows/preencher-boleto.jpg)

This task automatically types [boleto](http://en.wikipedia.org/wiki/Boleto) numers (from a digital boleto) for you. Here is how it works:

1. It copies the selected text;
2. Formats the text by removing dots and spaces;
3. After 10 seconds, it will type the formatted text;

Please make sure to set the focus to your desired form input before the automator starts typing (you have 10 seconds!).

This might be renamed later (since it's also useful to fill other numeric data to online forms).

## Author
**Gabriel Ochsenhofer**
