# **A Simple Guide to Post Your Resume On Github Pages**
##### This guide is created for people who have no experience with markdown, no experience in Github, and no experience in Jekyll, to create a Resume in markdown and upload it to Github Pages using a Jekyll theme.

## **Prerequisite**
* basic understanding of website interactions
* basic understanding of any operating systems
* familiar with creating text files
* familiar with accessing e-mails

## **Introducing markdown**

#### The Resume needs to created in a mark up language called markdown, below are some guides and tools to help you learn the mark up language

### Creating a markdown file
1. Create a new file called index.md. (*why it is called index will be explained later*)  
2. Now you can open this file in any of your favourite text editor and start creating your resume.

### Syntax guide
* You can format your resume in a variety of ways using markdown, it is a powerful language that is easy to learn. But you need to first understand the syntax.  
* Some basic mark down syntax is shown below:
> ||Syntax|Display|
> |---|---|---|
> |bold|`**text**`|**text**|
> |italics|`*text*`|*text*|
> |strikethroughs|`~~text~~`|~~text~~|
> |Links|`[Google](www.google.com)`|[Google](www.google.com)|

* Some header syntax is shown below:
>`# Header 1`  
>`## Header 2`  
>`### Header 3`   
>`#### Header 4`   
>`##### Header 5`  
>`###### Header 6`  

* What the above syntax displays when parsed:  
># Header 1  
>## Header 2  
>### Header 3   
>#### Header 4   
>##### Header 5  
>###### Header 6

* You can create lists by using the follow syntax:
> `* list item 1`  
> `* list item 2`

* What the above syntax displays when parsed:
> * list item 1  
> * list item 2

* you can use it to display pictures in markdown files as well:
> `![symobl](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)`  
* What the above syntax displays when parsed:
> ![symobl](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

### Additional Resources
* [Markdown Overview](https://www.markdownguide.org/getting-started)
* [Complete Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown Tutorial](https://www.markdowntutorial.com)

## **Using Atom to create your resume**
##### While I do mention to use any text editor of your choice, Atom is a very popular text editor for markdown editing. So I will provide a more detailed guide on creating the resume on Atom.

### Installing Atom on Windows
1.  Go to the [Atom Website](https://atom.io/)
2.  Click the *Download* button.
3.  After it finishes up downloading, follow the steps on the installation wizard on complete your installation.

### Creating your resume
1.  Open up Atom, click on the *File* tab on the top left corner and click *New File*
2.  After the file have been opened, it should be called *untitled*. Go to the *File* tab again and click *Save*, Then name the file index.md and store it in any path.
3.  Now you can start writing your resume in Markdown.
4.  To access a preview for your markdown text, click on the *Packages* tab in the same row as the *File* tab. you then click *Markdown Preview* and then click *Toggle Preview*. Now you can see how your markdown file will look like after it's parse.

### Additional Resources
* [Atom Installation and File Creation For Windows and Mac](https://www.portent.com/blog/copywriting/content-strategy/atom-markdown.htm)
* [Atom GitHub Package](https://flight-manual.atom.io/using-atom/sections/github-package/)

## **Setting up Github Pages**
##### Github pages is where you will host your resume on a personal web-page, but to access Github pages, you must first create a Github account.

### Create an account on Github
1. Go to [Github](https://github.com).
2. Click the *Sign up* button at the top right corner.
3. Enter the required information.
4. Verify your e-mail account.

### Create a repository
1. After you have logged on to your account, click the *New* button on the repository panel on the leftmost side of the web page.
2. The Repository name must be (Ownername).github.io. E.g. Wilsonzha.github.io.
3. Then set the repository to public and click *create repository*.

### Upload your Resume
1. Open your repository page, you will see a list of files. Since the repository is newly created, you should only see a README file.
2. Above the file list, you will see a *Upload files* button. Click that button and a new page opens.
3. Now you will be prompted to drag a file for upload, drag the index.md file that you created onto the web page and click commit changes.

### Select a Jekyll Theme
1. Now that your resume is uploaded to your repository, you can select a Jekyll theme for your web page.
2. Locate the text (Ownername)/(Ownername).github.io near the top of your repository page.
3. You will see that the tab *Code* is selected, on the same row, select the *Settings* tab.
4. Scroll all the way down to the header *GitHub Pages*, you will see a *Change theme* button. Click that button.
5. You will now be able to see a list of themes that are available to you from GitHub Pages. Select one that suits you and click the *Select theme* button.
6. Now you can visit (Ownername).github.io on any browser and view your resume.

### Additional Resources
* [Jekyll Guide](https://jekyllrb.com/resources/)
* [Github Pages](https://help.github.com/en/categories/working-with-github-pages)

## **Authors and Acknowledgement**
* Thank you to both Darnell H. and Hoang Huy P. for helping me edit my README file.
* I want to also thank Adam P. for his markdown cheat sheet and the picture I used from his Github repository.

## **FAQ**
***Question:*** How do I add additional spaces in markdown?  
***Answer:*** Use the symbol `&nbsp` to represent a space in markdown

***Question:*** How do I escape characters in markdown?  
***Answer:*** Use `` to enclose the characters that needs to be escaped. E.g. ```` `*hello*` ```` will show up as `*hello*`
