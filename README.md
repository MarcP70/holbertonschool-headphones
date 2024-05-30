      Project: Implement a design from scratch | Holberton Laval, France Intranet
      
### Concepts

_For this project, we expect you to look at this concept:_

*   [Implement a design](/concepts/963)

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.

Here the final result:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=842376fa82bef930392c8f861536deede9f90059cb530c9c2f99a08f72b36460)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip "here")

### Requirements

*   you are not allowed to import external CSS framework (like Bootstrap)
*   you are not to use Javascript

Tasks
-----

### 0\. Read and be familiar with Figma

mandatory

Create an account in [Figma](/rltoken/y6_o1T-HtCyTAGuOJqdA_g "Figma") and open this [project](/rltoken/SpYRV14tPxTZJSjU2Eoh4A "project") and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the [Figma file](/rltoken/tWEPFyHyXyNO9Xfi2Er2EA "Figma file")

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=073d2c027c598a116d86e9da364d87c050f1fba555c43f83463fb57c52a27f88)

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

Here an archive of all assets needed: [images\_.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=a01cb5d8a2931b99825be22a514c0249ba17d2ced96b386edc5800e759a1c8bb "images_.zip")

**Desktop:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d2a0a37c6727ecd73777ad276e3e59641f8e6f1ee9d92d4ddbe1ce80b0ea4b1f)

**Mobile:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a8ef369fb24e0979eb302728df0d6b421b20bb027e370ce8d31a0a0b306531fc)

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `0-index.html, 0-styles.css`

**0/25** pts

### 2\. "What we do..." section

mandatory

Copy files from the previous task.

For this second task: **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it: [holberton\_school-icon.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=d122941fc78e6bb9eec990dc3fb57efc0d9a2a230939556ed44a66118d8cbb9e "holberton_school-icon.zip") Inside you will find demo page of how to use it.

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

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ce9a1501049795d322d5e7e0bbaef5f0227ee79b031bdafc729601c7c6cd811a)

**Mobile:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240530%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240530T081954Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2ff617016679f2919337af70093609ee43f0b9c123f29ad096997f7eae3389a2)

And you are done!

**Good job!**

**Repo:**

*   GitHub repository: `holbertonschool-headphones`
*   File: `4-index.html, 4-styles.css`

**0/20** pts
