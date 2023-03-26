Hello, I am Pratiksha Sankhe from VJTI, Mumbai. This is the first time I’ll be applying for GSoC. After going through a vast array of Organisations and learning about their projects, I finally found the "*Modularization of Components*" project of **caMicroscope** quite interesting.

## Getting Started

I joined Slack and began digging deeper into the projects. I completed the setup locally and began with the code challenge task mentioned under my project as well. I'm creating this blog to summarise my path of completing the code challenge task, as well as the hurdles I encountered and how I overcame them.

## Getting Warmed up
Code challenge tasks were provided under each project for new contributors to demonstrate their creativity, understanding of the project, and ability to execute on a project proposal. I too started understanding and implementing it.

### 1. Building caMicroscope and running it locally
- First I followed the [Getting Started](https://github.com/camicroscope/caMicroscope#hosted-setup) section on caMicroscope's repository, which involved installing it using docker. I was able to successfully build and test its working on my PC.
- Then, I started exploring the different pages and finding bugs in the pages of [caMicroscope](https://github.com/camicroscope/caMicroscope) repository and [camicroscope.github.io](https://github.com/camicroscope/camicroscope.github.io) repository.
-  Following are the PRs that I have raised to date:

     In [camicroscope.github.io](https://github.com/camicroscope/camicroscope.github.io):<br/>
    ● [Scroll to top feature added](https://github.com/camicroscope/camicroscope.github.io/pull/22)<br/>
    ● [Improved the Index and the Community Page](https://github.com/camicroscope/camicroscope.github.io/pull/23)<br/>
    ● [Changed link of navbar](https://github.com/camicroscope/camicroscope.github.io/pull/27)<br/>
    ● [Created README](https://github.com/camicroscope/camicroscope.github.io/pull/28)<br/><br/>

    In [caMicroscope](https://github.com/camicroscope/caMicroscope):<br/>
    ● [Landing page UI modified](https://github.com/camicroscope/caMicroscope/pull/619)<br/>
    ● [Fixed UI of admin page](https://github.com/camicroscope/caMicroscope/pull/620)<br/><br/>

### 2. A simple webapp demonstrating Web Components using storybook.
- I started by going through the [Getting Started](https://storybook.js.org/docs/react/get-started/install/) section on storybook's website, which included installing dependencies and documentation. I read through all of the documentation on the website and became acquainted with it.
-  To use the storybook in a react application, I created a react-app and then installed the dependencies required for creating stories.
  ```
  npx storybook init
  ```
- I decided to develop stories for 3 basic components namely Button, Input and Subscription components.
- My next target was to build a story for buttons. I decided to do it similarly to bootstrap. In bootstrap, by assigning some class, the button color changes, while the other CSS remains the same.
- I considered variant which is given the value like primary, secondary, success, danger.
- Finally I got a good hand on it and created similar stories for input and subscription components.
  Eg:
  ```
  () => <Button variant='primary'>;Primary</Button>;
  ```
- [GitHub](https://github.com/psankhe28/react-storybook-eg)
- [Hosted application](https://storybook2023.netlify.app)

<p align="center">
  <img width="100%" src="https://user-images.githubusercontent.com/84843461/227114898-147ea4e6-ae66-42ef-a1d7-2645dcafbcbc.gif" alt="storybook" />
</p>

<br>

### 3. Creating Web Components Using HTML, CSS and JavaScript
- First, I searched numerous blogs for alternatives to storybooks, and some of the blogs listed below were really helpful.<br/>
    ● [A Complete Introduction to Web Components in 2023](https://kinsta.com/blog/web-components/)<br/>
    ● [Web Components Introduction](https://www.grapecity.com/blogs/web-components-introduction-creating-custom-html-elements-2018)<br/>
    ● [All the Ways to Make a Web Component](https://www.grapecity.com/blogs/web-components-introduction-creating-custom-html-elements-2018)<br/>
- After reading about web components, I started working on Feather UI and initially creating button and navbar components and experimenting using utility classes.
- I began working on the other components after I was able to develop the above components.
- Feather UI makes building experience effortless with collection of 97+ components and 33+ utility classes that cater to a wide variety of use-cases.
- The library is built using HTML, CSS and JavaScript only.
- The components are easy to use and customize, with ready-made HTML-CSS components available.
- Among the 16 components included are Alerts, Avatars, Badges, Buttons, Cards, Chips, Drawers, Grids, Images, Inputs, Lists, Modals, Navbars, Ratings, Sliders, and Toasts. These components can be used for various use cases and are designed to be easy to use and customize.
- In addition to wide range of UI components, the toolkit also includes 33+ utility classes that makes building UIs effortless. These utility classes are grouped into three main categories: Colors, Typography, and Utilities.
- The Colors category includes classes for text and background colors, while the Typography category includes classes for font styles and sizes. The Utilities category includes various classes for positioning, spacing, and layout, as well as responsive classes that adapt to different screen sizes. 
- [GitHub](https://github.com/psankhe28/feather-ui)
- [Hosted application](https://feather-ui-dev.netlify.app/)

<p align="center">
  <img width="100%" src="https://user-images.githubusercontent.com/84843461/227113389-fea89597-15ac-48c8-b2f1-0fbcc13899ec.gif" alt="feather-ui" />
</p>

<br>
 
