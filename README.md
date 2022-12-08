# My Portfolio
My portfolio is a site dedicated to promoting my skills to future employers or clients. I detail my experience in the communication field and my future technical skills as a Full Stack Software Developer. It is possible to contact me via a contact form or via other ways (email and phone).

![Responsive Website](/assets/screenshots/responsive-website.png)

## Wireframes
From the beginning, I have a clear idea of what I want on my website and how to organize it. I would like something easy and sober.

![Wireframe Home Page 1](/assets/screenshots/home-page1.jpg)

![Wireframe Home Page 2](/assets/screenshots/home-page2.jpg)

![Wireframe Home Page 3](/assets/screenshots/home-page3.jpg)

## Features

My portfolio has three pages: Home Page, Services, About.

The home page allows the user to have a general vision of my work and my skills. It is divided into 4 parts.

- __My Experiences Section__
The user can quickly get acquainted with my knowledge, listed in two parts, website conception and digital communication strategy.

- __Services__
This is a section with a text explaining why it is essential to define a communication strategy when creating a website. This text aims to inform the user on the important things to take into account when creating his website.

- __Contact Me__
This section is accessible from the navigation bar on the different pages of my portfolio.

- __The Footer__
The footer of my portfolio lists my copyright as well as the year of update of the website. The user can also click on one of the two icons before going to my LinkedIn or Instagram accounts.

![Footer](/assets/screenshots/footer.png)

- __Services Page__
This is a page that lists what I can provide to a client. This page can replace an information brochure.

- __Take up the Challenge__
This section aims to convince the user that it is important to take care of his communication. And therefore that he should call on me! I explain why it is essential to have a graphic charter, a website, social networks in order to communicate better with its target. 

- __What I can do for you__
In this section, like a catalog, I detail the different services I offer, in terms of website creation, visual identity, communication consulting and other important features.

- __About Page__
This is a page where I talk more specifically about myself.

- __My Background__
This section briefly lists the Experiences part of my resume. I write here how long I have been working in this field and what has been my path.

- __My Skills__
Here, I list my skills and my area of expertise in each of them. 
A portrait allows you to get to know me before discovering some of my hobbies and a playlist of music that I like.
This section allows to create a link with the user. The latter may or may not have the feeling to want to work with me.

### Existing Features

- __Navigation Bar__

The navigation bar is present on all pages, in order to facilitate the navigation through the website. The logo is clickable, the link points to the home page

![Nav Bar](/assets/screenshots/header.png)

- __Contact Section__

The contact form allows the user to contact me directly via the website without having to go to an email account. The user just has to fill in his name, his email and the content of the message before clicking on the send button. The different fields are required to make sure that the informations are correctly filled in. If it is not the case, the message cannot be sent.

- __Spotify Player__

The music player doesn't launch automatically when the user arrives on the page. It is up to the user to launch or not the player, according to his wishes. It is possible to open the playlist directly on Spotify in order to consult the titles on the platform, share some of them, etc.

![Spotify Player](/assets/screenshots/spotify-reader.png)

- __Background Images__
I make the choice to display my top page pictures in background directly in the style sheet. I make this choice because I really like the transparent insert with the title on the photo of the Love Running project. So I copy the css code. Moreover, these photos are not essential to the good understanding of the site, so it is not too bad if they don't have an "alt" attribute. They don't give additional informations, they are purely decorative. 

### Features Left to Implement

I would like to continue to enrich this portfolio, first of all with the future skills I will acquire during the training, but also by posting or putting links to my future projects and works.

The website will then be proposed in French and maybe in German.

I would like a sticky navigation bar in the future. I read some articles about it on Google, it seems that I have to use JavaScript. So soon, when the user scrolls on a page to view the content, the navigation bar remains fixed at the top of the screen. 

## Testing

- I try a lot of things when making this portfolio. Many attributes but also values are not completely clear to me at the moment. I test several options and check if it works correctly or not. I am very inspired by the courses and examples of the w3schools.com website.

- When validating my html code by Validator Testing, I have errors with the h2 child of spans. So I delete the span and I replace them by a div.

- The site, its different pages and sections are adapted to different screen sizes. Two points are created with the help of @media 768px for tablets and 992px for screens. I decide to make a third point for extra small devices (below 576px) because my logo doesn't display well with such a small size.

- I have a problem with the blocks of the Services page. Thanks to the "align-items: center" property, the blocks are now center by default. In tablet view, it works too. But in desktop view, the blocks are not the same size and it's not pretty. After several unsuccessful attempts, the value "align-items : normal" fixes things.

![Align Items](/assets/screenshots/align-items.png)

- I have a horizontaly scroolbar whereas all my sections are with "width:100%". I add the attribute "max-width:100%" to the nav and footer.

- In the About page, in desktop view and only in this view, I have a problem with a span tag with text that is displayed on two lines. To fix it, I reduce the padding of the span and add the attribute display with the value inline-block.

![Skills line](/assets/screenshots/skills-line.png)

### Validator Testing

- HTML
No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/)
- CSS
No errors were found when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/)

### Unfixed Bugs

After sending the message via the contact form, the user leaves the site to go to the Code Institute page. I use the URL given during the course on contact forms. I would like the user to stay on my site after sending his message, with a congratulations message. I look on Google, it seems that we have to use php or javascript for this function. Si I will fix it soon.

## Deployment

- The website has been deployed on GitHub pages. The steps of the deployment are as follows:
    - On the project on GitHub, go to Settings
    - And then on GitHub Pages. Select the "Main" branch and save the settings.

The site is live here : https://cecilegaudron.github.io/my-portfolio/

## Credits

### Content

- The icons in the footer and the About page come from [Font Awesome](https://fontawesome.com/)
- The instructions and the code to display and position the transparent color blocks on the images at the top of the pages come from the Love Running Project
- The instructions "how to center vertically and horizontaly" and "How to add a favicon" come from [W3schools.com](https://www.w3schools.com/) 
- To maintain the center elements on different views, like in About page, Services page and contact ways, I use the flexblock attributes flex-direction and display. These combinaisons come from [W3schools.com](https://www.w3schools.com/)

### Media

All pictures and the logo are from me.