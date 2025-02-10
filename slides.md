---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev 
background: /assets/intro.jpg
# some information about your slides (markdown enabled)
title: Software Development | Foundations
info: |
  ## Software Development | Foundations
# apply unocss classes to the current slide
class: text-left
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# Software Development Bootcamp
Circuit Stream
- [ ] Setup a development environment (install VS Code)
- [ ] Recognize HTML and how it works
- [ ] Use HTML to create a simple document


<div class="abs-br m-6 text-xl">
  <a href="" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
TODO: fill in anchor href above to point to github repo for these slides
-->

---
transition: slide-left
---

# Intro | About Me
(1 min)
- 📺 **Commodore 64** - first time I coded was 5 lines of BASIC - Guess the number game
- 🏫 **Seneca College** - Computer Programming & Analysis | Library & Information Technician
- 📚 **Library Technician** - 16 year career in libraries, coded in VBA, XML, HTML/CSS/JS
- 👨🏽‍🏫 **Web Development Instructor** - for Georgian College IMDW program PHP/mySQL/Vue/Node/Express
- 💻 **FrontEnd Developer** - 3 years at [AgencyAnalytics](https://agencyanalytics.pinpointhq.com/en/postings/ac05e149-714f-411a-8352-96db586f6c8d) React/JS/TS/Docker/CSS Modules/PHP/mySQL

Now I'm a 👨🏽‍🏫 **Software Development Instructor** for CircuitStream #forYou


<!--
00:00 - START

Introduction

01:00 - END

-->

---
transition: slide-left
---

# Intro | About You
Icebreaker Activity (4 min)

- 🍿 **What is your go-to comfort food?**
- 🏀 **What is your favourite hobby/sports?**
- 🎞️ **List 1 favourite movie or book**
- 🍏 **What kind of computer are you using?** (Mac / PC / Linux)
- 🌐 **List one website you wish you knew how they made that?**
- 💻 **Why do you wish to get into Software Development (in 1 sentence)?**

<!--
01:00 - START

05:00 - END
-->

---
transition: slide-left
---

# Bootcamp Objectives
(5 min)
- 🥾 End of Bootcamp, you will be able to build software
- 🔀 Not easy, requires learning of many different skills
- 🏆 **Bootcamp will be hard work**
   - 5 assignments that are worth 20% of final grade
   - 1 midterm worth 30%
   - 1 Capstone worth 50%
- 🏅 You need to get **more than 70%** to get the certificate

*Questions so far?*

<!--
05:00 - START

10:00 - END
-->

---
transition: slide-left
---

# LMS (Learning Management System)
(5 min)
- 📎 Login to [courses.circuitstream.com](https://courses.circuitstream.com)
- Tour the following:
   - 🏠 Course Home (announcements)
   - ✏️ [Content tab and Class Recordings](https://courses.circuitstream.com/d2l/le/lessons/9514)
   - 🎥 how to find live [sessions](https://courses.circuitstream.com/d2l/common/dialogs/quickLink/quickLink.d2l?ou=9514&type=lti&rcode=6C9E5966-CBB5-4BA4-BD1A-5D627729924B-13290&srcou=6606&launchFramed=1&framedName=Zoom)
   - 💯 how to find [assignments](https://courses.circuitstream.com/d2l/lms/dropbox/dropbox.d2l?ou=9514)
   - 🏢 Career one-on-one (geared towards portfolio, strategies with jobs)
   - ℹ️ [Help Center](https://help.circuitstream.com/)

*Questions so far?*

<!--
10:00 - START

15:00 - END
-->

---
layout: image-left
transition: slide-left
image: /assets/danny02.png
backgroundSize: 500px 180px
class: text-left
---

# Intro to Software Development
(10 min)
- [ ] What is software development? 
- [ ] Software Development Process
- [ ] See Course Outline and unit [description](https://courses.circuitstream.com/d2l/le/lessons/9514/units/49644)
<v-click>
   <br />
   <li><a href="https://www.loom.com/share/c0571f737f8841388124be71266690c9?sid=602f827d-6dfa-4771-a3a9-8b426253a2ec">work demo video 1 (3 min)</a></li>
   <li>
   <a href="https://www.loom.com/share/28f8719138b044ea84a3496aa5472d94?sid=871950d7-7e58-41c8-b601-fd11e8857fd5">work demo video 2 (1 min)</a>
   </li>
</v-click>   


<!--
15:00 - START

1. Reveal work vids; explain industry, what devs do (5 min)
2. use chatgpt to see SDLC (4 min)
3. Where to find more info (1 min)

25:00 - END
-->

---
layout: image-right
transition: slide-left
image: /assets/danny01.png
backgroundSize: 500px 300px
class: text-left
---

# 5 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- 🎧 Dev podcast [Syntax.fm](https://syntax.fm/)
- 📖 Resource for Devs = [MDN](https://developer.mozilla.org/en-US/docs/Web#web_technology_references) 
- 📊 StackOverflow [Survey Results 2024](https://survey.stackoverflow.co/2024/technology#most-popular-technologies-language)


<!--
25:00 - START

30:00 - END
-->

---
transition: slide-left
---

# Environment Setup
Foundations (30 min)
- [ ] Software Development Environment (hw / sw)
- [ ] Install VS Code
- [ ] Install Git
- [ ] Create GitHub account
- [ ] Setting up GitHub Copilot

<div class="abs-br m-6 text-xl">
  <a href="" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
TODO: fill in anchor href above to point to github repo for these slides

30:00 START 

1. (10 min)
- what sw/hw needed? 

2. (5 min)
- also VS Code Insiders ed.
 

3. (5 min)
- free for Win/Mac/Lnx
- but your choice
- other editors, but I may not be familiar when troubleshooting

4. (5 min)
- Why create GitHub account?

5. (5 min)
- Show how to set up Copilot

60:00 END
-->

---
transition: slide-left
---

# 10 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- 🗺️ Dev [roadmaps](https://roadmap.sh/)
- 📝 Learning how to code [advice](https://www.reddit.com/r/learnprogramming/comments/16b1czl/what_is_your_best_advice_for_learning_how_to_code/)
- 🎭 The Fastest way to [learn](https://www.swyx.io/learn-in-public)


<!--
60:00 - START

70:00 - END
-->

---
transition: slide-left
---

# HTML = Hypertext Markup Language
(30 min)

in index.html

````md magic-move {lines: true}
```html {1|2-3|4|5|6|7|all}
<h1>Hello World</h1>
<h2>SubTitle 2</h2>
<h3>Project 1</h3>
<input>
<button>Click me</button>
Will <mark>this</mark> highlight?
<a href="https://www.google.ca">Click me</a>
```
````

<!--
Alternate: codepen.io

70:00 START

1. (20 min) Uses of markup language
- have them follow along in VS Code while I use TextEdit
- .txt vs .html
- Compare Network tab Response: Content-Type
- Compare View Source vs. Inspect
- URL = request (give me resource; see Request Method = GET)
- index.html could be sitting halfway around world
- open directory example: http://www.mixed-up.com/cs/community/
- try eliminating index.html from url path (what do you see?)
- what if we changed the filename?
- try opening index.html in Safari
- SUMMARY: you're getting a document

2. Leave markdown for later until we reach Github

3. (10 min) open IDE create index.html
- Type code one line at a time to see effect
- Why don't see see a change right away upon save?
- Observations? (Why line 6 on same line?)

100:00 END
-->

---
layout: image-right
transition: slide-left
image: /assets/florin01.png
backgroundSize: 500px 480px
class: text-left
---

# 5 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- 👩‍⚖️ W3C Markup Validation [Service](https://validator.w3.org/)
- 🛜 How does the Internet [work](https://www.youtube.com/watch?v=x3c1ih2NJEg) 
- 📋 an HTML Scratchpad [Codepen.io](https://codepen.io/)


<!--
100:00 - START

105:00 - END
-->

---
transition: slide-left
---

# Recognize HTML + Exercise
(30 min) In groups of 4:

1. Open up [this wikipedia page](https://en.wikipedia.org/wiki/National_Basketball_Association)
2. Try to spot a particular area on the page that intrigues you (how'd they make that using HTML)
3. Right click that area > View Source > Can you recognize the HTML that made that particular area?
4. Right click that area > Inspect > Can you recognize the HTML that particular area? 
5. How many `h1` tags are there? Hint: Inspect using devtools and Ctrl/Cmd + F to find `<h1`
6. What happens on the page if you hover your mouse cursor over that `h1` tag in devtools?
7. Find one of the many `p` tags; To the left of it is a triangle, click it -- what happens?  
8. Try double clicking then changing the text inside one of the `p` tags, does it change the webpage?
*Does your change also affect your classmate's viewing of that webpage?*
9. What seems to be the purpose of the `div` tag?
10. The structural pattern of "title followed by paragraphs" is created by what pattern of particular HTML tags?
11. Finally open up your fav website you mentioned during the icebreaker and repeat steps 2 to 4 only.  

<!--
105:00 START

- Moana 2 kakamora story telling scene is like the DOM https://www.youtube.com/watch?v=Kspt-12xjg8#t=4m52s

135:00 END
-->

---
transition: slide-left
---

# 5 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- ⌨️ [Scrimba](https://scrimba.com/html-css-crash-course-c02l)
- 🔥 [FreeCodeCamp](https://www.freecodecamp.org/) 
- ▶️ [LinkedIn Learning](https://www.linkedin.com/learning/) (might be freely available thru your local public library website)


<!--
135:00 - START

140:00 - END
-->

---
transition: slide-left
---

# Basic HTML document
(10 min)

```html
<!DOCTYPE html>
<html lang="en"> <!-- Inspect https://horecamenu.pl/ -->
<head>
    <meta charset="UTF-8"> <!-- Try "ISO-8859-1" -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Try removing content with  circuitstream.com -->
    <title>Document</title>
</head>
<body>
    <p>This page contains special characters: ñ, é, ü</p>
</body>
</html>
```

<!--
140:00 - START
- HTML = element or individual component
- Where is the one and only p element?  Purpose of p element?
- elements have opening and closing tags (usually).  between = content
- Body tag contains all visible content on page.  Does the body tag have content?
- What happens if I place the ending tag on a new line?
- What happens if I forget to put ending tag?
- Comment tag has 2 purposes.  Comment out a tag.
- Indent all nested elements

150:00 - END
-->

---
transition: slide-left
---

# Menu Exercise
(20 min) in groups of 4

1. Ask ChatGPT: "Why is semantic HTML important?"
2. Create in VS Code index.html (Press `!` followed by the tab key)
3. Come up with a way to structure a menu (see next slide for menu) using all the necessary above tags plus whatever tags you think is most appropriate to build a semantic document 

Tip: there's no one absolute correct answer; there may be more than one way to achieve same goal.  
On the other hand, try to use the correct tag it was designed for.

<!--
150:00 - START

210:00 - END
-->

---
transition: slide-left
---

```
Menu

Plates
Plate 1: Grilled Chicken - Tender chicken breast seasoned and grilled to perfection. 
 Price: $12.99
Plate 2: Spaghetti Bolognese - Classic Italian dish with hearty meat sauce served over spaghetti.
 Price: $14.99
Plate 3: Vegetarian Stir-Fry - Fresh mixed vegetables stir-fried in a savory sauce.
 Price: $10.99

Drinks
Drink 1: Fresh Orange Juice - Refreshing and freshly squeezed orange juice.
 Price: $4.99
Drink 2: Classic Mojito - A refreshing blend of mint, lime, and soda with a touch of sweetness.
 Price: $8.99
Drink 3: Iced Cappuccino - Chilled cappuccino with a shot of espresso, milk, and ice.
 Price: $6.99

Desserts
Dessert 1: Chocolate Cake - Rich and moist chocolate cake topped with velvety chocolate frosting.
 Price: $7.99
Dessert 2: Tiramisu - Classic Italian dessert with layers of coffee-soaked ladyfingers and mascarpone cream.
 Price: $9.99
Dessert 3: Fruit Tart - Fresh fruit medley on a delicate pastry crust with a light glaze.
 Price: $8.99
```

<!--
140:00 - START

210:00 - END
-->

---
transition: slide-left
---

# 5 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- 🙏 [caniuse.com](https://caniuse.com)
- 🎒 [Khan Academy](https://www.khanacademy.org/search?page_search_query=html) 
- 🥷🏻 [FrontendMasters.com](https://frontendmasters.com/)

---
transition: slide-left
---

# HTML Creation
(10 min)

1. Why was HTML invented?
2. HTML5 philosophy
3. How do browsers work?
   - See [caniuse.com](https://caniuse.com/)
   - To find out more about any HTML tag, CSS property, or JS concept type: `MDN [whatever]`

<!--
210:00 - START 

1. In 1990s, To help scientists share documents via hyperlinking.  Before HTML, sharing was hard to do and not easily accessible across different types of computer systems.  Before HTML there was not standardized way or declaring what was a heading, paragraph, image etc.  HTML5 was the fifth version of HTML
2. emphasizes open standards, making the web more accessible and future-proof.  Away from proprietary tech like Flash.  "Don't break the web" mantra promotes backward compability
3. W3C, WHATWG, ECMA ensure open standards that define how to render HTML/CSS.  It's up to Chrome/Safari/FF to implement those open standards 

220:00 - END

-->
---
transition: slide-left
---

# Homework
(10 min)

- Browse through the list of all HTML tags found on [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- Ask yourself: any weird ones? any useful ones?
- Be curious: Try displaying various tags that intrigue you (I wonder how this tag will render?)
- Get started on your portfolio project

*Questions?*

<!--
220:00 - START

230:00 - END
-->