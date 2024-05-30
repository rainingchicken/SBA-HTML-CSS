# SBA 307 - HTML and CSS
https://rainingchicken.github.io/SBA-HTML-CSS/pages/index.html

## Purpose
This is product landing website intended to statisfy the Skill Based Assessment (SBA) project for Perscholas coding bootcamp 2024. 

## Inspiration
The chosen product is teleporter. Marketed towards the introverts, the lazy, and okay drivers, a teleporter is one of the most wishlisted item since forever ago. This idea was inspired by the teleporter in the game Lethal Company. This made the project more enjoyable to develope due to the silliness factor of it being a fictional object. The teleporters are for personal use and would replace cars. I am uncreative with names and so WYA (Where You At) Company was born. Since there is no javascript, none of the buttons worked. Some buttons were disguised anchors which led to different pages. This project is as completed as it could be using just HTML and CSS.

## SBA Requirements
### HTML Requirements
- Have at least three pages.
  - **There are 7 .html files**
- Keep the grid system consistent between pages as much as possible.
  - **Ok**
- Use at least ten different HTML tags.
  - **Used more than 10.**
  - **Examples in the body in index.html alone include: header, nav, div, a, button, span, ul, li, section, h1, h5, img, h2, p, h3, form, input, footer**
- Include at least one table.
  - **Table about CO2 emission in info.html** 
- Include at least two forms.
  - **Login form, signup form, subscribe to newsletter form**
- Include at least one dropdown menu.
  - **In shop.html as color selector for product**
- Include at least one of each of the following forms of content: 
  - Text.
    - **There is lorem text in info.html**
  - Images.
    - **There are images in index.html**
  - GIFs.
    - **A gif in about.html** 
  - (See resource links above for some free content of each of these types.)
### CSS Requirements
- Make use of inline, internal, and external styling.
  - **Examples of each**
  -  **Inline in index.html page**
```
<h1 style="padding-bottom: .5em;">No CO2 emission!!!
</h1>
```
  -  **Internal in index.html page**
```
 <style>
      footer {
          text-align: center;
          padding: 2em 0;
          background-color: #212529;
      }
  </style>
```
  -  **External**
  - **shop-style.css**
- Use five different CSS selectors.
  - **Used different CSS selectors in all pages but as example of 5 are**
  -  **Type selectors** in index.html
```
main {
    background-color: rgb(8, 10, 14);
    color: var(--fontColor);
}
```
  -  **Class selector**
```
.item {
    justify-content: center;
    align-items: center;
    background-color: var(--bootstrapdark);
    border-radius: 20px;
    padding: 1em;
    text-align: left;
    transition-duration: .5s;
}
```      
  -  **ID selectors**
```
#subbtn {
    height: 3em;
    border-radius: 6em;
    padding: 0 1em;
}
```    
  -  **Pseudo-classes selectors**
 ```
.buybtn:hover {
    background-color: white;
    box-shadow: .1em .1em .1em var(--bg);
}
```   
  -  **Multiple selectors**
```
#featured>h1,
#shop>h1 {
    padding-top: 2em;
}
```    
- Use colors that complement each other.
  - Coolors is one of many resources that can help you find a color palette.
  - **Dark gray and white colors used for contrast** 
  
- Use Flexbox and/or the Bootstrap Grid.
  - **display:flex is used in all html pages except info.html**   
- Use at least two CSS animations.
  - **Product div boxes gets bigger when hover in index.html and shop.html**
  - **Rotates gif when hover in about.html**

## The Website Itself
### Home (index.html)
This page is heavily inspired by samsung landing page for the Galaxy S24 Ultra. User will be greeted by a huge promotion for the Premium Teleporter that has 'recent' launched. Under that are buy options for the Premium Teleporter which includes a Premium+ version that supposedly better, faster, and more luxurious. Under that, a section talks about the benefits of using a teleporter. There is a section dedicated to credibility of the company and product. So under this section is the link to the About Us page. The next section is the a recommended products section where user can choose other teleporter options. Under this, if the user is interested in newsletter from this company, they can sign up.

### Shop (shop.html)
This page shows the products available for purchase. Each card includes image of teleporter, its name, its specifications, color option and purchase button.

### Information (info.html)
Gives 'additional' information about the benefits of the teleporter, most noteably, the 0% CO2 emmission.

### About Us (about.html)
This page introduced the company's motive, values, and missions.

### Contact (contact.html)
This is a contact page for users to ask or send comments to the company.

### Login page (login.html)
This is here users can log into the company's website to make purchases.

### Sign Up page (signup.html)
Users can use the sign form to sign up for the company's website.

## Process

1. created wireframe for teleporter landing page during in class activity
2. liked the login form created during in class which reminded me of cotton candy
3. wanted to create product landing page for cotton candy
4. hate it immediately because I had to scavange for copyright free cotton candy pictures
5. changed product to teleporter
6. use Samsung and Top of the Morning websites as reference
7. 2d drawings of teleporters looked off against the professional feeling of website so 3D modelling it is
8. can't find free 3D teleporter online
9. forgot how to use blender. relearned a little bit
10. modeled on 3D models of teleporter
11. waste 5 hours modeling
12. get told that doing the bare mimumim is the way to go
13. disagree
14. hate the premium telelporter model used for promotion. too lazy to change so remains unhappy
15. a week later, completed project limited to using only HTML and CSS
16. pushing to github took a hour due to errors
17. troubleshoot using
```# To get all the ref 
git show-ref

# replace with your branch name according to ref 
git push origin HEAD:<branch>
```
18. it works. thanks DharmanBot and Lindsey https://stackoverflow.com/questions/71936452/github-error-failed-to-push-some-refs-to-github-com. might have to do again
 
## Image Sources
- https://www.pexels.com/photo/time-lapse-photography-of-stars-in-sky-at-night-1048081/
- https://www.pexels.com/photo/person-holding-a-green-plant-1072824/
- https://www.pexels.com/photo/green-and-grey-circuit-board-57007/
- https://www.pexels.com/photo/american-astronaut-in-space-2156/
- https://pixabay.com/gifs/cat-cute-emoji-6939/
