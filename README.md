![basic](https://github.com/user-attachments/assets/72d9ef7c-9766-4dcb-b7bb-3803b10418cc)

# Sweet Sidenotes

Sweet Sidenotes is a css snippet that allows you to get, via callouts, notes alongside the main text.

**Table of content**
1. [Introduction](#Introduction)
2. [How to install](#How-to-install)
3. [How to use](#How-to-use)
4. [License](#License)

## Introduction

After doing some research, I found out about the existence of sidenotes, particularly tufte. I looked to see if there might already be a snippet for Obsidian somewhere, but I couldn't find it, so I decided to create it myself. Thus was born Sweet Sidenotes, a snippet that through callouts allows you to get an aesthetically beautiful sidenote.

## How to install

1. Download the CSS file from the css folder inside `<vault name>/.obsidian/snippets`.
2. Enable the snippets under the **Appearance** section in the settings.
3. Download the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin in order to customize the snippet and also to make it work.

## How to use

1. To create a sidenote callout you have to write [!sidenote] to the first line of a blockquote. To reverse their position you just put the left adjustment ([!sidenote|left]).

```
>[!sidenote]
>Ut consectetur diam lorem, ac consectetur eros imperdiet nec. Nunc quam sem, posuere at est nec, congue condimentum arcu.
```

or reversed

```
>[!sidenote|left]
>Quisque sodales mollis sodales. Morbi sem erat, gravida in velit in, fermentum consectetur neque.
```

What it would look like:

![sidenotes](https://github.com/user-attachments/assets/e7eaae6b-5d27-48cd-bbee-44808b3923c7)


2. You can use adjustment to modify the width of the sidenote. There are 4 adjustment: small, medium, large, larger.

```
>[!sidenote|large]
>Sed ultrices aliquet nunc a bibendum. Quisque sodales mollis sodales. Morbi sem erat, gravida in velit in, fermentum consectetur neque.
```

or

```
>[!sidenote|left small]
>Donec laoreet ex mi, quis interdum velit tempus nec. Phasellus vitae tincidunt mauris. In efficitur consectetur eros, ac imperdiet ante euismod nec. Nunc elementum malesuada luctus.
```

What it would look like:

![another](https://github.com/user-attachments/assets/8e73f362-125d-4ca3-b361-20768fefd255)


3. To further customize the sidenote you can use [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.

Style Settings panel:

![style settings](https://github.com/user-attachments/assets/91cd6b86-235f-42a4-8416-684df1b25956)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
