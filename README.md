# Writing Good Documentation


## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. A good __Cloud Engineer__ uses Codeblocks whenever possible because it allows others to copy and paste their code to replicate or reasearch issues.

- In order to create codeblocks in markdown you need to use three backticks \`\`\`
- Not to be confused with single quotations \'\'\'
```
print('Hello, world!')
```
- When you can you should attempt to apply syntax highlighting to your codeblocks
```python
print('Hello, world!')
```

Make note of where the backtick character is located. It should appear below the Esc key, but it may vary based on your keyboard layout.

- Standard Image
  - ![backtick-key](https://github.com/ATP-kperia/github-docs-example/assets/90066284/d7e63f9c-9017-42b6-bd1d-b2b1a2fd811e)
- Resized Image (HTML)
  - <img width="300px" src="https://github.com/ATP-kperia/github-docs-example/assets/90066284/d7e63f9c-9017-42b6-bd1d-b2b1a2fd811e" />

Good Cloud Engineers use codeblocks for both code and errors that appear in the console. 
```bash
Traceback (most recent call last):
  File "/path/to/example.py", line 4, in <module>
    greet('Chad')
  File "/path/to/example.py", line 2, in greet
    print('Hello, ' + someon)
NameError: name 'someon' is not defined
```
> Here is an example of using a codeblock for an error that appears in bash.

When you can, always provide a codeblock instead of a screenshot.

If you need to take a screenshot, make sure it's not a photo from your phone

> There are certain cases where it's okay to take photos with your phone. This is when you are showing something like a keyboard, which does not appear on a computer screen
> If it is rendered on your computer screen it should be a screenshot.


## Step 2 - How to take screenshots

A screenshot is when you capture a part of your screen via your computer or phone. This is **not** to be confused with taking a photo with your phone or camera.


## Step 3 - Use GitHub Flavored Markdown Task Lists

GitHub extends Markdown to have a list where you can check off items. [^3]

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3


## Step 4 - Use Emojis _(optional)_

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️ |


## Step 5 - How to create a table

You can use the following markdown format to create tables:
```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️ |
```

Github extends the functionality of Markdown tables to provide more aligntment and table cell formatting options. [<sup>[5]</sup>](#external-references)

Make note of where the pipe character is located. It should appear below the Backspace key, but it may vary based on your keyboard layout.

<img width="400" src="https://github.com/ATP-kperia/github-docs-example/assets/90066284/0a418ec0-3e09-4ef7-90cf-5a3fb3cdfc2e">


## External References
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>[1]</sup>
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[2]</sup>
[^3]: [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet) <sup>[4]</sup>
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[5]</sup>


