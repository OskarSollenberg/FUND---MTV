# fed25-fundamentals-mtv
Final website for the **fundamentals**-module at Hyper Island

Hi, This is a beginner project i did at Hyper Island where im currently studiying to become a Front End Developer. This was about a 2 week project were we were assigned to create a 90s-styled webpage from scratch. For this project i put alot of effort into structuring my code, making sure its very readable with styles that are easily interchangeable by the use of Css and Sass variables.  




  <img align="right" alt="GIF" src="https://github.com/OskarSollenberg/fed25-fundamentals-mtv/assets/122973984/e5992fcb-1e75-4a48-8aa0-dd0afd1329b8" width="400"/>




### Languages and Tools:


<img align="left" alt="HTML5" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" style="padding-right:10px;" />
<img align="left" alt="CSS3" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" style="padding-right:10px;" />
<img align="left" alt="Sass" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" style="padding-right:10px;" />
<img align="left" alt="Figma" width="26px" src="https://i.pinimg.com/originals/66/8c/cc/668cccb3f734f342e07c0185e6d9a975.png" style="padding-right:10px;" />
<img align="left" alt="Git" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" style="padding-right:10px;" />
<img align="left" alt="GitHub" width="26px" src="https://user-images.githubusercontent.com/3369400/139448065-39a229ba-4b06-434b-bc67-616e2ed80c8f.png" style="padding-right:10px;" />
<img align="left" alt="GitHub" width="26px" src="https://seeklogo.com/images/N/netlify-logo-758722CDF4-seeklogo.com.png" style="padding-right:10px;" />
<img align="left" alt="Visual Studio Code" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" style="padding-right:10px;" />

<br />

---
### What I learned:

- Grid and Flex-box.

- Sass variables, nesting, @imports and mixins.

- BEM naming convention.

- Mobile-first workflow

- Responsiveness using fluid units. 

- Intergrating Parcel for better optimisation.


<!--STRAT_SECTION:code-->

<br>

**A bit of code using:**

BEM naming-convention for class-names.
  
Sass-variables in nested @media-queries  
  set to the (Bootrap breakpoints-values).

Costum css-properties for easy accessibility
  and dry code.
  
```scss

//* Header
.site-header {
    width: 100%;
    z-index: 100;
    position: sticky;
    top: 0;
    padding: 2rem 0;
    background: var(--clr-blue);
}
.site-header__nav {
    display: flex;
    justify-content: end;
}
.site-header__menu {
    display: none;
    gap: var(--gap-md);

    &--visable {
        @media (min-width: variables.$breakpoint-md) {
            display: flex;
        }
    }
}
```

<br>
<br>
<br>



**💬 ask me about anything, i am happy to help**

<p>
<a href="https://github.com/thmsgbrt" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a> 
<a href="https://www.linkedin.com/in/thomas-guibert" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://www.instagram.com/mokkapps/"><img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
</p>


