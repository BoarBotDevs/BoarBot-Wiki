## Setting up the Wiki Locally
This wiki does not work like most wikis you've seen such as Wikipedia or Fandom wikis. Instead, this wiki uses docusaurus to run. This makes it a little more complex to contribute, but it should be relatively easy after following some simple steps. First, we recommend that you give yourself the Wiki Writer role in the Boar Central Discord. This will allow you to talk to other writers to help to stylize pages or to help with any problems that may occur during the contributing process. 

If you are not in the Boar Central discord server, you can join it [here.](https://discord.boarbot.dev/)

Next, go to the [Wiki Github](https://github.com/BoarBotDevs/BoarBot-Wiki) for instructions on how to get the BoarBot Wiki running locally. This will allow you to preview pages you made without affecting the live wiki.

If you can go to the website shown on the setup section of the github page and see the wiki, you've correctly set up the wiki and can start to make changes.

## File Structure
All work to the wiki pages should be done in the docs folder. Creating a new folder in the docs folder will create a new catagory, and creating a new file will create a new page. All files should have the extension ".md"

Adding an image to the static/img folder will allow you to link that picture on a page, and changing src will change the styling of the wiki. (Generally this should never be changed.)

## Getting Changes Pushed to Live Wiki

When you're done with making your changes locally, you can submit a pull request to the Wiki Github and then 2 verified reviewers will review your push shortly. Keep an eye on this pull request, you may be asked to change it.

## Markdown
The rest of this page will focus on markdown and how to use it. The general structure of this section will be that it shows what it looks like normally, then showing the text you need to make it look like that. If you've ever used discord markdown, this works very similarly.

### Headings
By using hashes, you can turn part of a line into a heading. There are 5 different levels of headings, each using more hashes. These are useful for seperating different parts of an article. The following lines will display how each heading looks and how to write them in the Markdown file.

# Heading 1
\# Heading 1

## Heading 2
\#\# Heading 2

### Heading 3
\#\#\# Heading 3

#### Heading 4
\#\#\#\# Heading 4

##### Heading 5
\#\#\#\#\# Heading 5

If you look at the right sidebar, you can see that Headings 2 and 3 show up as catagories.

### Bullet Points and Numbering
Bullet Points and Numbering can be done in markdown automatically. To use bullet points, simply use a - before a line. For example, the list:
- This is a list
- using bullet points.

would be written as:

\- This is a list

\- using bullet points.

The same applies for numbering, except that instead of using the - character, you simply put the numbers before the line. For example, the list:
1. This is 
2. a list using
3. numbering.

would be written as it looks.

### Code Blocks

There are two types of code blocks, small and large. To use the small version, surround the text you want to be in the block with `.

`Small Code Block`

\`Small Code Block\`

The large code block is the same except it is surrounded by three \` and there must be a line break between the \` symbols and the content.

```
Large Code Block
```

\`\`\`

Large Code Block

\`\`\`

Generally, the large code block is used for multiple lines, while the small block is used for single lines. Addionally, remember that the \` symbol is the grave, not the apostrophe or quotation marks.

### Quotation Boxes

By putting the > symbol before a line, that line will be a quote box.

>This is a Quote Box.

\> This is a Quote Box.

### Hyperlinks

By using the format \[Text\]\(Link\) you can link to other pages on the web. 

[I am linking to the "How to Contribute" page.](https://wiki.boarbot.dev/How%20to%20Contribute)

\[I am linking to the "How to Contribute page.\]\(https://wiki.boarbot.dev/How%20to%20Contribute\)

Keep in mind that that when linking internally to the wiki itself, the localhost link will have to be charged to a wiki.boarbot.dev link.

### Warning Boxes

By using the phrases :::tip[name] or :::danger[name] at the start of a line you can create either a tip or danger box.

:::tip[This is a tip box.]

This is the contents of the tip box.

:::

‎:::tip[This is a tip box.]

This is the contents of the tip box.

:::

:::danger[This is a danger box.]

This is the contents of the danger box.

:::

‎:::danger[This is a danger box.]

This is the contents of the danger box.

:::

### Images
You can link to any images that are in the static\img folder. You can link to the images by using the phrase !\[Image\](\img\IMAGE_FILE_LOCATION)

![Normal Boar](\img\boars\NormalBoar.png)

\!\[Normal Boar\]\(\img\boars\NormalBoar.png\)

Keep in mind that you must keep the file extension.

#### Escaping Markdown

Should you ever need to, you can use the character "\\" before a character to escape the markdown. Note that aside from this page, this should be used either never, or very sparingly.