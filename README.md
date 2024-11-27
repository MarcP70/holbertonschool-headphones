      Project: Implement a design from scratch | Holberton Laval, France Intranet

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.

Here the final result:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b0e3ac8b0343e315e8074f95fabca6bc7b96951596db86983b115d32c2eb4311)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip "here")

### Requirements

*   you are not allowed to import external CSS framework (like Bootstrap)
*   you are not to use Javascript

_For this project, we expect you to look at this concept:_

*   [Implement a design](/concepts/963)

Tasks
-----

### 0\. Read and be familiar with Figma

mandatory

Create an account in [Figma](/rltoken/y6_o1T-HtCyTAGuOJqdA_g "Figma") and open this [project](/rltoken/SpYRV14tPxTZJSjU2Eoh4A "project") and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the [Figma file](/rltoken/tWEPFyHyXyNO9Xfi2Er2EA "Figma file")

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4e9cab55641b7535a78258b2fd7c5ff1250b953c20532326241e27084b7733d3)

Important notes with Figma:

*   if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](/rltoken/yvx4-XkjAQJgHlN6RAoKWQ "source-sans-pro") and [Spin-Cycle-OT](/rltoken/Jw0FKYKB6l5_2Koto0duTA "Spin-Cycle-OT")
*   some values are in float - feel free to round them

For this task, please write an amazing `README.md`

**Interactions note:**

*   the web page must switch to the mobile version when the screen width is 480px or less
*   links hover/active: `#FF6565`
*   button hover/active: `opacity: 0.9`
*   max width of the content: 1000px centered in the page

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `README.md`

**0/1** pt

### 1\. Header

mandatory

Building a web page the right way, is not easy - expect if you put in place strong foundations:

*   reset CSS styling
*   use variables
*   simple/“as generic as you can” CSS selectors
*   avoid using super specific CSS selectors as much as possible
*   simple HTML structure - `div` containers are your friend!

Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task: **create the header/hero piece**

Here an archive of all assets needed: [images\_.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=57c5acfbac6a6620eb700fc01e7703b939d39628667101527f9ae3ab70d47871 "images_.zip")

**Desktop:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a123e10cdf4dcf425aed7679387072ab4804fcfcf977ac471d705cd52ce1d4a3)

**Mobile:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1b483727684777acb3db453e868ef1a4db611a4b0185e2cc07c4d91dba552ceb)

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `0-index.html, 0-styles.css`

**0/25** pts

### 2\. "What we do..." section

mandatory

Copy files from the previous task.

For this second task: **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it: [holberton\_school-icon.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=bab2df15e7023bd83b7bc49d029c3dab678d8596405ccb9b48f502f89318022e "holberton_school-icon.zip") Inside you will find demo page of how to use it.

**Important:** try to build as generic as you can… you will probably need some components in next section.

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `1-index.html, 1-styles.css`

**0/26** pts

### 3\. "Our results" section

mandatory

Copy files from the previous task.

For this third task: **create the “Our results” section**

Now you can reuse components form the previous task!

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `2-index.html, 2-styles.css`

**0/25** pts

### 4\. Contact us

mandatory

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `3-index.html, 3-styles.css`

**0/19** pts

### 5\. Footer

mandatory

Copy files from the previous task.

Last piece of the page… the Footer!

When you are done, here the result:

**Desktop:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ff336923596a13e30e686ac4b8d39550fa4cb08f81f147feee0b435402f8b3df)

**Mobile:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20241127%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20241127T110745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=25ca6f58c03df7c8230b0d31425a4ccc84d7a3ff0cd52d9978dcc091b6fc9c3c)

And you are done!

**Good job!**

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `4-index.html, 4-styles.css`

**0/20** pts
