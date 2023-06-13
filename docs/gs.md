# **Getting Started...** {: style="text-align: center"}

## Forking the repository

![git-fork](images/git-fork.png)

-  Visit the [repository](https://github.com/smaranjitghose/awesome-portfolio-websites.git)

- Fork the repository by clicking on the **Fork** button

## Cloning the repository

- Visit the [repository](https://github.com/smaranjitghose/awesome-portfolio-websites.git)
- Copy the link the of the repository by clicking on the clone button

![git clone](images/git-clone.png)

- Open terminal
- Type `git clone https://github.com/smaranjitghose/awesome-portfolio-websites.git`

## Changing the details

### Home Page

![Home](images/home.png)

- To add your image on the home page :
    1. Add your image to assets -> images folder
    2. Open _index.html_
    3. Change the `<img src="">` to your image path

- To change the name on home page :
    1. Open _index.html_
    2. Change the name from **John Doe** to **Your Name**

- To change the interests displayed : 
    1. Open _index.html_
    2. Inside `span` tag, change the `data-words` with your interests

- To add your social media links :
    1. Open _index.html_
    2. Inside `<div class="social-icons">` fill up the link to your social media accounts inside `href`

---

### Navbar

![Navbar](images/Navbar.png)

- To change the name :
    1. Open _app.js_
    2. Under `let header`, inside `<a class="navbar-brand" href="index.html">`, change the name from **John Doe** to **Your Name**

---

### Footer

![Footer](images/footer.png)

- To change the quote :
    1. Open _app.js_
    2. Go to `let footer`, inside `<div class="container-fluid quote-container">`, change the quote inside`<p class="tag" >` from "**Develop a passion for learning. If you do, you will never cease to grow.**" to your quote

- To add your social media links :
    1. Open _app.js_
    2. Inside `<div class="rounded-social-buttons tag">`, under ` <a class="social-button"` fill up the link to your social media accounts inside `href="#"` by replacing `#`.
     [ For example: `<a class="social-button twitter" href="#" target="_blank">` Here, replace `#` with twitter account link]


---

### Contact Form

- We will use [FormCarry](https://formcarry.com/) to collect the feedback of the visitors on the page. 

- First, create a FormCarry account if you do not have one
    1. Go to [https://formcarry.com/register](https://formcarry.com/register)
    2. Enter your Email and password
    3. Click on Sign Up

- Create a FormCarry Form
    1. Click on the **Add New** button
    <br>
    Give it a name such as _Portfolio_
    <video width="100%" autoplay loop controls >
    <source src="https://formcarry.com/assets/documentation/create-form.mp4" type="video/mp4">
    </video>
    3. Copy the form endpoint given to you. example: `https://formcarry.com/s/KljL8nJiRf`
    ![FormCarry Endpoint](images/FormCarry/Endpoint.PNG)

- To replace the demo form link with your endpoint
    1. Open _app.js_
    2. Go to `let footer`, inside `<form name="form1" action="https://formcarry.com/s/BywEPAJNb" method="POST" accept-charset="UTF-8">`, change the action attribute from "`BywEPAJNb`" to your FormCarry endpoint e.g. `KljL8nJiRf`

- To Test if the form works, send a submission and if you see this, it works!
    ![FormCarry Send Form](images/FormCarry/SendMessage.gif)
    And, inside your submissions, you should see the email
    ![FormCarry Submissions](images/FormCarry/Submissions.PNG)

### Experience Page

![Experience](images/work-exp.png)

- To change the **work experience** details :

    1. Add your work experience images to assets -> images -> experience-page folder
    2. Open _experience.js_
    3. Under **Work Experience Cards** heading,
        1. Change the current **title** to your position inside `title`
        2. Change the current **image path** to your image path inside `cardImage`
        3. Change the current **place** to your industry/company name inside `place`
        4. Change the current **time** to your duration of work inside `time`
        5. Change the current **description** to your job description inside `desp`. [ Let `<li>` remain]

![Volunteership](images/opensource.png)

- To change the **volunteership** details :

    1. Add your volunteership work images to assets -> images -> experience-page folder
    2. Open _experience.js_
    3. Under **Volunteership Cards** heading,
        1. Change the current **title** to your organisation name inside `title`
        2. Change the current **image path** to your image path inside `cardImage`
        3. Change the current **description** to your job description inside `description`

![Hackathons](images/hackathon.png)

- To change the **hackathon** details :

    1. Add your hackathon work images to assets -> images -> experience-page folder
    2. Open _experience.js_
    3. Under **Hackathon Section** heading, in `const mentor`
        1. Change the current **title** to your organisation name inside `title`
        2. Change the current **designation** to the designation under which you participated as, i.e., mentor, judge, team-leader etc, inside `subtitle`
        3. Change the current **image path** to your image path inside `image`
        4. Change the current **description** to your work description inside `desp`

---

### Projects Page

![Projects](images/project.png)

- To change the **projects** details :

    1. Add your projects images to assets -> images -> project-page folder
    2. Open _project.js_
    3. Under **Project Cards** heading,
        1. Change the current **title** to your project name inside `title`
        2. Change the current **image path** to your project image path inside `cardImage`
        3. Change the current **description** to your project description inside `description`
        4. Add the links to images of **language or framework** used inside `tagimg`
        5. Add the **preview link** inside `Previewlink`
        6. Add the **github link** inside `Githublink`

---

### Research Page

![Research](images/research.png)

- To change the **research** details :

    1. Add your research work images to assets -> images -> research-page folder
    2. Open _research.js_
    3. Under **Research Details Table** heading,
        1. Change the current **title** to your research paper title inside `title`
        2. Change the current **authors** to your research paper authors inside `authors`
        3. Change the current **conferences** to your research conferences inside `authors`
        4. Change the current **research year** to your research year inside `researchYr`
        5. Change the current **image path** to your image path inside `image`
        6. Change the current **vancouver** to yours inside `vancouver`
        7. Change the current **abstract** to yours inside `abstract`

---

### Education Page

![Education](images/edu.png)

- To change the **formal education** details :

    1. Add your institute images to assets -> images -> education-page folder
    2. Open _education.html_
    3. Under **Dynamic Education Timeline Cards** heading,
        1. Change the current **title** to your institute name inside `<h2>` tag. [ Example: `<h2>Columbia University</h2>` replace `Columbia University` with your institute name]
        2. Change the current **date** to the years range studied in the institute inside `<div class="date">`
        3. Change the current **specialization or education stream** to yours inside `<h6>` tag
        4. Change the current list of  **activities** to yours inside `<li>` tags

![mooc](images/mooc.png)

- To change the **mooc section** details :

    1. Add your MOOCs images to assets -> images -> education-page folder
    2. Open _education.js_
    3. Under **MOOCs Cards** heading,
        1. Change the current **title** to your course name inside `title`
        2. Change the current **image path** to your course image path inside `cardImage`
        3. Change the current **MOOC link** to yours inside `moocLink`


## SEO and Miscellaneous

- Search for `site_name` and update it to the link to your portfolio

- Search for `title` and update it from `John Doe | Home` to `Your Name | Home`

- Search for `description` and update by writing something about yourself

- Search for `url` and update it to the link to your portfolio

- Search for `site` and again update it to the link to your portfolio

- Search for `application-name` and update it from `John Doe | Home` to `Your Name | Home`

- Search for `apple-mobile-web-app-title` and update it from `John Doe | Home` to `Your Name | Home`

- Search for `summary` and update it by writing somthing about yourself

## Final Steps

- After making all the changes, now it's time to push these changes to your local repository. For this, steps to be followed are :

    - Save the changes you have made till now

    - Open terminal in the file you made the changes

    - Type `git add .`

    - Then type `git commit -m "Your commit message"`

    - Then finally, `git push origin master`
