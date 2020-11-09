# Elsevier

A one page web app for use at conferences, to demo medical study learning environment and collect emails for newsletter.

3 multiple choice questions and a sign-up form for the Elsevier newsletter.
 
## UX
 
Client requests: 
- Duplicate the 3 questions from the companies learning environment.

- After Q3 answer is shown, pressing 'next' goes to the email sign up form.

- Add embedded form for collecting contact details for prize draw.

- Web app is used on an iPad and/or a lower/mid resolution laptop. Mobile responsiveness is not necessary.

- Brand colours, images, fonts etc that need replicating provided by the client.
    - [Client Logo](assets/img/elsevier_logo.png)
    - Main font - NexusSansPro
    - Start page header font - Elsevier Display BoldCondensed
    - Brand colours
        - Orange: #FF8200
        - Blue: #007398
        - Grey: #808080
    - Terms and conditions PDF provided to replicate on terms.html page
    - Favicon
    
### Images provided by client to replicate: 

![](https://i.ibb.co/njW7WKS/Clipboard01.jpg)

![](https://i.ibb.co/4ZnfZVx/Clipboard02.jpg)

![](https://i.ibb.co/Kjvd8S4/Clipboard03.jpg)

## Features
 
### Existing Features

#### Start page
- **Client logo** in top left corner, links to the index.html page.
- **Heading** in client's custom brand font.
- **Start button** in brand color to begin the quiz.

#### Questions page

- **Progress bar** shows the user where they are in their progress through the quiz. Updates every time they submit an answer.

- **Question** and 5 **multiple choice answers** to choose from.

- Custom **radio inputs**, colored the brand colour on hover and selection. 

- **Confident button** and **not sure B]button** are displayed at the bottom of the page for the user to submit their answer. Which is clicked is recorded for their results.

- When an answer is submitted the user is given feedback if their answer was correct or not. The correct answer is displayed for them. And notes on each of the options is displayed under their corresponding answer choice.

- **Side info bar** displays the **key concept** for the question, the **percentage** of students who got this question right, and the number of **seconds** it took the user to answer. 

- A **next button** is available to start the next question.

- The **restart quiz button** reloads the entire quiz from any point within it. 

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

#### Email signup page

- **Sign-up form** Embedded form provided by client.
- **Test scores on right hand side**

## Technologies Used

- This project uses HTML, CSS and JavaScript programming languages.
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Visual Studio Code](https://code.visualstudio.com/) 
    - Developer used **VSCode** for their IDE while building the website.
- [Bootstrap](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap** to simplify the structure of the website and make the website responsive easily.
    - The project also uses Bootstrap to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [Adobe Fonts](https://fonts.adobe.com/fonts)
    - The project uses **Adobe fonts** to style the website fonts.
- [Imgbb](https://imgbb.com)
- [GitHub](https://github.com/)
    - This project uses **GitHub** to store and share all project code remotely. 
    - The new GitHub Projects planner was utilised to plan and keep track of this project. This project plan can be viewed [here](https://github.com/AJGreaves/picflip/projects/1).
- [Photoshop](www.adobe.com/Photoshop)
    - This project used tools in **Photohshop** to edit, crop and save images as well as ulitizing the colour picker to ensure color consistency over the entire project.

## Deployment

To deploy this project to GitHub Pages from its [GitHub repository](https://github.com/AJGreaves/elsevier), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **AJGreaves/elsevier**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
6. On selecting Master Branch the page is automatically refreshed, the project is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.

### How to run this project locally

To clone this project from GitHub:
1. Follow this link to the [Elsevier GitHub repository](https://github.com/AJGreaves/elsevier).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

## Credits

### Code
- Custom radio code from [triss90 on codepen](https://codepen.io/triss90/pen/XNEdRe/)

### Images and animations
- Spinner aquired from [icons8](https://icons8.com/preloaders/en/circular)

### Content
- All content provided by the client

### Media
- All media provided by the client