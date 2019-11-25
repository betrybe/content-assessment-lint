# How to create Content Pages

Before you start describing the content page for a given day, you must **first study** the contents that will fit this day.

So, before you start typing on each section of the content, your main concern is to lookup references for the content of the day. These references may be internal or external, but be careful to select only those that fit into the day's scope.

This _research/thinking_ process may be the hardest part of producing a content page. So watch yourself not to lose it in the middle of all of your thinking and waste hours away of your focus.

---

## Content Page Sections

To keep some level of consistency between content pages, below there is a detailed explanation about all the sections that must be present on each page.

Some sections are optional, so choose wisely which one fits your content page better.

Also, to get a grip of what a content page looks like, you can always peek on other content pages that are already specified:


* [Multiple Quizes / Custom Section](https://course.betrybe.com/intro/internet/)

* [Single Quiz](https://course.betrybe.com/intro/unix/unix-part-1/)

* [Single Exercise](https://course.betrybe.com/intro/html-css/html-css-part-1/)

* [Multiple Exercises](https://course.betrybe.com/intro/git/git-part-2/)

Usually, your content page will have the following sections:

1. **Aquecimento** _(section - optonal)_
2. **O que vamos aprender?** _(section)_
    * **1.1 Você será capaz de:** _(subsection)_
3. **Por que isso é importante?** _(section)_
4. **Conteúdo** _(section)_
5. **Quiz** _(section - optional)_
6. **Vamos fazer juntos!** _(section)_
7. **Exercícios** _(section)_
    * **7.1 Antes de começar: versionando seu código** _(subsection - optional)_
8. **Recursos Adicionais (opcional)** _(section)_
9. **Próximo** _(section)_

###### _sections are created in our markdown pages using ##, and subsections using ###_

Feel free to _add/remove_ other _sections/subsections_ to your page if it makes sense within your current content.

Specially between different contents/weeks, the sections may vary a lot, and it's OK. Your main concern when describing a content page shall be creating a logical step by step section definition that basically covers the following:

* Give the student context about what he's going to learn;

* Expose the skills he'll learn objectively;

* Guide the student through the content with our comprehension exercises/quizes;

* Provide the student exercises that will stretch his knowledge, always inside the scope of the current content;

* Give the student additional content/exercises that may be optional, in order to light up his curiosity and enhance his knowledge within the current content.

---

## Aquecimento
##### _section - optional_

This section's goal is to instigate the curiosity of the student by placing a question or challenge about the content.

You must define the question with the appropriate details and guide the student to answer it on Slack in the proper thread.

It is useful to put this section in your page when you want to ask something to the student that he'll not know, and your content will cover. Because if so, after studying your content he may realize the knowledge he acquired, _a.k.a. aha! momment_.

---

## O que vamos aprender?
##### _section_

This section's goal is to provide an overview of what the student will learn with your content page.

Also, spare some paragraphs for a motivational quote, that highlights the importance of that content in the scope of the _week/module/course/career_.

---

## Você será capaz de:
##### _subsection_

In this subsection, you must provide a bullet list of skills _(capabilities)_ that the student will train (or acquire) after studying your content page.

_Be aware that the skills you put in here must fit into the scope of the current content page._

You must provide at least two, and at most five skills, with **three** being your magic number.

---

## Por que isso é importante?
##### _section_

This section's goal is to provide information to the students about the relevance of studying your content page.

You can link your contents with market needs, professional skills, desired skills a developer should have, etc.

It's good to include articles, quotes, and another external contents to stand by your arguments.

But be careful not to run out of scope, or flood your section with a lot of external references making the student lose himself in the content path. Your main concern is to create a straight line of progress for the students. Creating a sense that he must overcome this content in order to keep going in the course.

##### Obs: if your content page is splitted between multiple parts (_i.e.: "JavaScript Part I", "JavaScript Part II", etc_) this section **may be** optional, depending on the context of the content.

---

## Vamos fazer juntos!
##### _section_

This section's goal is to provide the student the necessary information about the live class regarding your content.

Depending on your content, the live class shall appear before/after the exercises, or before/after the content. Pick the one that fits better to your planning.

Basically, include a paragraph that calls off the students to a live class, and say that the video chat link will be available in the class Slack channel.

We use Zoom video chats in order to perform live lectures. For each live lecture you must use a previously defined script.

---

## Quiz
##### _section - optional_

This section's goal is to provide the student with an exercise that is not covered within your content.

Usually you'll have to create the Quiz yourself and, for now, using Google Forms.

_Keep in mind that the questions used in the Quiz are meant to be used as comprehension exercises for the student, and they should be able to see their answers and the quiz feedback._

If any doubt arise when creating a Quiz, refer to another previously created for an accurate reference.

Remember to always use multiple choice or checkbox questions, because they allow you to put the feedback (answer) on the form directly, eliminating the need for you to correct the quiz by yourself.

---

## Conteúdos
##### _section_

This section is where you will detail the content for the student. Depending on the shape of your content, you may have several variances of content organization here.

The guideline is to cover all the scope of the content, using as much interactivity as you can, mixing theory and practice as much as possible... in other words:

_**The funnier you make it, the less boring you make it, the better!**_

Some examples:

  * You can have video tutorials and guide the student to code along;
  * You can have short theory videos with exercises/quizes;
  * You can use interactive tutorials;
  * You can use articles with exercises of your own;
  * _... and always put your creativity to work!_

#### Obs: Depending of the nature of your content, you may want to mix this section with the _Exercícios_ section (below), in order to give the student a more consistent and practical approach. It may look like **_Conteúdos & Exercícios_** for example.

---

## Antes de começar: versionando seu código
##### _subsection - optional_

This section aims to provide detailed instructions for the students on how to organize their exercises using Git and GitHub.

Typically this section will cover:

* Creating a branch for the _week/day_ exercises;

* Within that branch, creating a folder to store the _week/day_ exercises files;

* Instructions on `committing` and `pushing` the branch to remote repository.

---

## Exercícios
##### _section_

The goal of this section is to provide extension exercises for the student to put the knowledge acquired in the previous section to work.

The main difference between the exercises defined here and the ones you may put inside the _Conteúdos_ section is that here you have the freedom to stretch the problems/exercises difficulty, requirements, and/or time the student will spent developing it.

If your content allows you to ask students to put their codes into GitHub, it's _highly recommended_ to do so.

Always prefer exercises that are deliverable in some way. Despite we'll not assess them on those exercises, they'll train their deliverability and we can watch out which students are missing exercises. This may fire up an alert for a possible outlier on the learning path.

#### Obs: Depending of the nature of your content, you may want to mix this section with the _Conteúdos_ section (above), in order to give the student a more consistent and practical approach. It may look like **_Conteúdos & Exercícios_** for example.

---

## Recursos Adicionais (opcional)
##### _section_

This section's goal is to provide other resources for the students to research, read, and obviously, learn.

You must state that this section is optional because the contents of it are not required to be inside the scope of the course.

You could include links for external courses _(free)_, articles, podcasts, videos, playlists, and so on. Anything that you find cool enough and want the students to see can be a good candidate here.

Also, if your content exercises has some kind of **bonus features/requirements**, it is recommended that you fill in the necessary content that the students will need to achieve it here.

---

## Próximo
##### _section_

This is the default final section of each page.

It must contain a button to the next day's content page.

You can provide an optional paragraph before the button to give a bit of a tease to what is coming. ;)

---

## Tips and Tricks

* Review your content and keep it consistent with the scope;

* Always keep in mind that we prefer practice over theory. Try to describe your content page using a 1 to 3 proportion of theory and practice, _.i.e. for each hour of theory, three hours of practice_;

* Remember that your content page almost always will be preceeded by another content, and also there will be another content page after it. **So, be aware of how you connect your content with the ones before and after it!**

---

> _First, think._
>
> _Second, write._
>
> _Third, review._
>
> _And finally, ship it!_
