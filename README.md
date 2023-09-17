# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in Markdown make it _very easy_ for tech people to **copy, paste, and share** code.

A good **Cloud Engineer** uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replcate or research issues.

* In order to create Codeblocks in Markdown you need to use three backticks ( ` ).
* Not to be confused with single quotes ( ' ).
* Codeblock example:

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate and print the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

* When you can you should attempt to apply syntax highlighting to your Codeblocks:

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate and print the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- Make note of where the _backtick_ button is located.
- It should appear above the _tab_ key, but it may vary based on your keyboard layout.
  ![Backtick Key](https://i.stack.imgur.com/ETTnT.jpg)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
        1: from (irb):1
NameError (undefined local variable or method `undefined_variable' for main:Object)
```

> Here is an example of using a codeblock for an error that appears in _bash_.

## Step 3 - Use GitHub Flavored Task Lists

GitHub extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

* [x] Finish Step 1.
* [ ] Finish Step 2.
* [X] Finish Step 3.

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.

Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |

## Step 5 - How to Create a Table

You can use the following Markdown format to create tables:

```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
```

GitHub extends the functinality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

![Pipe Key](https://emleddin.github.io/comp-chem-website/images/UNIXguide/pipe.png)

## External References

* [GitHub Flavored Markdown spec](https://github.github.com/gfm)
* [Basic writign and formatting syntax (GFM)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
* [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
* [GFM - Tables (with extensions}](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>

:end:
