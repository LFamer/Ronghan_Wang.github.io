# **How to Host and Format an Online Resume (and learn some fundamentals of Tech Comm along the way)**

## **Purpose**

This README will describe the instructions of host an excellent resume on GitHub Pages. During the processes, the Markdown, Jekyll and GitHub are needed, which are free. At the same time, this README will also relate the instructions of host a resume with the concept of Modern Technical Writing, which the author is Andrew Etter. This README wants to help you get the skill of hosting an excellent resume and learn knowledge about documentation.

## **Prerequisites**

- This should include a resume formatted in Markdown. 
- You also need a GitHub account for hosting your online resume.

## **Instructions**

### **Building a Repository**

1. Login into your GitHub

2. Click &quot;**New**&quot; button

3. Click the box under &quot;**Repository name**&quot;, enter the name you want to create. The format is your\_name.github.io, e.g.: wangr317.github.io.

4. Click the box which is before the &quot;**Add a README file**&quot; for creating a README.md in your repository.

5. Click &quot;**Create repository**&quot;, then you will get into your repository page.

![Building a Repository](https://github.com/LFamer/LFamer.github.io/blob/main/GIF/Building_a_Repository.gif "Building a Repository")

Developers prefer DVCS much more than centralized systems because the distributed version control systems (DVCS) have better performance and allow offline work. DVCS also supplies that developers work on the same file simultaneously, which makes it more convenient for them to cooperate in development. As developers prefer DVCS, it is the most crucial reason why technical writers choose to use it.

Wherever you decide to store your files, you need to build a README.md at the root branch (e.g. main) in your repository. This file&#39;s purposes are providing a quick summary of the product, describing instructions on how to run the projection, and instructions on how to contribute.

### **Setting up Jekyll Theme**

1. Click the &quot;**Settings**&quot; button which is on the top of the web page.

2. Scroll down and find the &quot;**GitHub Pages**&quot;.

3. Click the &quot;**Choose a theme**&quot; button.

4. Choose a Jekyll flavor which you want by click, such as, Slate. Then, you click the &quot;**Select theme**&quot; button.

5. Scroll down and click &quot;**Commit changes**&quot; button.

6. Click the repository name which is on the top and left on the web page for getting back the main page.

![Setting up Jekyll Theme](https://github.com/LFamer/LFamer.github.io/blob/main/GIF/Setting_Up_Jekyll_Theme.gif "Setting up Jekyll Theme")

We choose to host a static website for the resume because it is simple, portability, and security. The second reason is that we do not need the database and server-side application dependencies. You will choose to use a generator (e.g. Jekyll), because it is complex if you create the website manually.

In this case, we choose to use the default theme (Slate) because it is an example for showing instructions. However, it is not enough for a wonderful static website. If you want to create a successful online resume, you need to spend time choosing colors, typefaces, font sizes, page width, and spacing. You can hire a designer if you are not good at it.

You can find the Jekyll tutorial under [More Resources](More_Resources).

### **Setting up your Resume**

1. Click the &quot;**main**&quot; button and choose the branch which name is &quot;**gh-page**&quot;.

2. Click the index.md to open it.

3. Click the button which is an icon as a pencil. You could see &quot;Edit this file&quot; when your mouse arrow moves on it.

4. Remove all the things in this file. Then, you copy and paste your resume which is written by markdown into this file.

5. Click &quot;**Preview changes**&quot; for checking. If there are some format problems, you can click &quot;**Edit file**&quot; and fix them.

6. Scroll down and Click &quot;**Commit changes**&quot; for saving the change.

7. Click the repository name which is on the top and left on the web page for getting back the main page.

![Setting up your Resume](https://github.com/LFamer/LFamer.github.io/blob/main/GIF/Setting_up_your_Resume.gif "Setting up your Resume")

The purpose of modern technical writing is that everyone is a contributor. Writing XML by hand is difficult, and this conflicts with the purpose of modern technical writing because it limits people&#39;s ability to contribute. Therefore, we choose to use lightweight markup (e.g. Markdown), which is easy for learning and free.

In this case, we choose to use Markdown to edit the resume because Markdown files can be covert to HTML easily. You do not need to spend time learning XML. If you want more information about Markdown, you can check under [More Resources](#More_Resources).

### **View the Resume Web Page**

1. Click the &quot;**Settings**&quot; button.

2. Scroll down and find the &quot;**GitHub Pages**&quot;

3. Find the website link under the &quot;**GitHub Pages**&quot; and click it. The website format is like [http://Your_Name.github.io/](http://Your_Name.github.io/)

4. View your online resume online page.

![View the Resume Web Page](https://github.com/LFamer/LFamer.github.io/blob/main/GIF/View_the_Resume_Web_Page.gif "View the Resume Web Page")

Finally, the resume website page is built successfully which follows the principles of Andrew Etter&#39;s book. If you want to get more information about modern technical writing principles, you can read this book which you can find under [More Resources](#More_Resources).

### **More Resources**
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Jekyll tutorial](https://jekyllrb.com/tutorials/home/)

## **Authors and Acknowledgment**

Andrew Etter

Kurt Hanel

Matt Cameron

Nabeel Saeed

## **FAQs**

### **1. Why is Markdown better than a word processor?**

Markdown is a syntax language designed to read and write structured text easily, which is free. Markdown is easy to work with others. The changes on the Markdown file can be merged together on version control such as GitHub. The most important reason is that the writer can edit Markdown files on any platform with the editor. It will not mess up the formatting of the text file. But the Word document will break in sometimes. Therefore, Markdown is better than a word processor.

### **2. Why is my resume not showing up?**

If your resume not showing up and you followed all the instructions which are discussed on the top, you need to wait several minutes because GitHub need time to refresh the content in sometimes. Then, you can refresh the web page and check it again. If it still not work, you may connect to GitHub sever community or go to GitHub help page for more information.
