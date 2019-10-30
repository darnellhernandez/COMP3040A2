# Hosting your Resume through GitHub Pages 

## INTENDED AUDIENCE

The instructions below are a helpful guide to how to host your resume through GitHub Pages. A user no background with Markdown and Jekyll and little background to Git can follow these instructions to host their resume.

## PREREQUISITES 

Prerequisite to using this is having a complete resume.

## INSTRUCTIONS
	
Hello, these instructions can help a user host their resume on GitHub and change the layout to a pre-set Jekyll theme from GitHub.

> The user first has to convert their resume document into a Markdown file. To create a Markdown file, a Markdown editor can be used to write it. Some well-known Markdown editors are Atom and VSCode. Any Markdown editor can be used, it just depends on what your comfortable with. The editor used for this assignment specifically was VSCode. 

> VSCode has nice features where you can see live previews and preview it with the GitHub Flavoured Markdown Plugin, so it fit very well with our assignment details. It is also an editor that is free to download online.

> You can create your Markdown file of your resume in your Markdown editor of choice. Below are the Markdown syntax that were used in the resume markdown file. 

### QUICK MARKDOWN TUTORIAL

1. **EMPTY LINES**. A empy new line is used to separate text. If there is no empty line in between, the texts will be beside each other.

2. **HEADERS.** Headers are used to separate text and to show different sizes of text. 

	# HEADER1 
	`Markdown # Header1`
	## HEADER2 
	`Markdown ## Header2`
	### HEADER3 
	`Markdown ### Header3`

3. **BOLD and _ITALICED_ TEXT**. Bold and italiced text can be use to differentiate between different text for importance. 

	**HELLO** 
	`Markdown **HELLO**`
	
	_BYE_ 
	`Markdown _BYE_`

4. **TABLES**. Tables can be used to display information. <br />
<img width="175" height="100" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/TABLE.png"/><div> <br />
	
	|    | 1  | 2  |  3 |
	|--- |--- |--- |--- |
	| 1  |    |    |    |
	| 2  |    |    |    |
	| 3  |	  |    |    |	

5. **LINKS**. Links can be used to attach a link to text.

	GitHub: [darnellhernandez](https://github.com/darnellhernandez)

	`Markdown
	[darnellhernandez](https://github.com/darnellhernandez)`

> If you are wanting to learn more about Markdown or curious about what more you can do. There are links to more resources in the resource section below. 

> Once the resume is made into a Markdown file, a user can put it on Git. Git is essentially a version control system that is free to use, and it is where we will host the markdown file.

> In order to start, a user must make a Git account to use the system. Below are instruction to create an account, but if you have an account already, you may skip this step.

### SIGNING UP FOR A GIT ACCOUNT

1. Go to the [Git Website](https://github.com/git)

2. Once on the website, click on the SignUp Icon.

The SignUp icon is outlined in **RED** in the example picture below. <br />
<img width="500" height="300" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/SignUp.png"/><div> <br />

3. A new page will load, where you can create an account, by entering your preferred information. <br />
<img width="500" height="300" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/CreateAccount.png"/><div> <br />

4. Once account completed, an email confirmation will be sent to the selected email. The email is used for verification, so please click on the verify email address in your email to finish confirmation. <br />
<img width="150" height="50" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/VERIFY.png"/><div> <br />
Once completed you may login to your account through the SignIn Icon on the [Git Website](https://github.com/git).

The SignIn icon is outlined in **RED** in the example picture below. <br />
<img width="500" height="300" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/SignIn.png"/><div> <br />

> Now that you have an account, you can create a repository on your profile. Below are instructions to create a repository.

### CREATING A REPOSITORY ON GIT

1. First, login to your Git Account 

2. On the top right corner there will an icon that looks like this <br />
<img width="25" height="25" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/ICON.png"/><div> <br />
Click the icon and a drop down menu will appear. In that menu, click the **"Your repositories"** option.

The icon and option have been outlined in **RED** in the example picture below. <br />
<img width="500" height="200" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Repositories.png"/><div> <br />

3. Once in the repositories page, click on **"NEW"** to create a new repository. Afterwards, a new page will load to enter details about your new repository like repository name and additional details.

The **"NEW"** option has been outlined in **RED** in the example picture below. <br />
<img width="500" height="100" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/NewRepository.png"/><div> <br />
Example for **Create Repository Page**.<br />
<img width="500" height="400" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Create%20Repository.png"/><div> <br />

**NOTE: if you select _PRIVATE_ for your repository, you will not be able to use the preset templates in Git. You will have to change the settings of your repository later to use the templates.**

> Your new repository will be created and found in the **"Your Repository"** section of your account. You can access it and place your Markdown file of your resume in the repository. Once added, you can start change your setting of your GitHub Page. Below are instructions to change of your jekyl theme.

### CHANGING SETTING OF JEKYL THEME

1. Go the the **SETTINGS** section of your repository.

	The **SETTINGS** section has been outlined in **RED** in the example picture below. <br />
<img width="800" height="250" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Settings.png"/><div> <br />

2. In the **SETTINGS** section, there will be a _GitHub Pages section_. In this section, there will be an option to select your a Jekyll Theme. The selected theme for this assignment is "Midnight Theme".

	The **Theme** section has been outlined in **RED** in the example picture below. <br />
<img width="500" height="250" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Theme.png"/><div> <br />

3. Once theme is selected, two new files will be added to your repository; **Index.md** and **_ config.yml**. 

	**_ config.yml** is a configuration file that contains the selected Jekyll theme and **Index.md** is a markdown file 	       of their example. 

### HOSTING IN GIT PAGES

1. Select the Index.md file created and delete it. The **Index.md** is the name of the file that will be hosted once you go to your GitHub Pages.

2. Rename your resume file to **Index.md**.

3. (OPTIONAL) In the **_ config.yml**, you can add a different title to your GitHub Page, if you do not want to default name (respository name). By adding a new line of code: "title: Resume". <br />
<img width="400" height="250" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/TitleRename.png"/><div> <br />

4. Once completed, you can access your GitHub Page through the **Setting** section of your repository. In the **Sectting** section, the GitHub Page will have a link to your site. <br />
<img width="700" height="150" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Website.png"/><div> <br />

## More Resources 
-	A tutorial on [Markdown Tutorial](https://www.markdowntutorial.com/)
-	An introduction to [GitHub Flavored Markdown](https://github.github.com/gfm/)
-	An introduction to [GitHub Pages](https://help.github.com/en/categories/working-with-github-pages)

## Authors and Acknowledgements
-	Wilson from GROUP #20 
-	Harry from GROUP #20
- 	[Lin from GROUP #11](http:github.com/zelin-qiu)
- 	[Swetul from GROUP#11](http://github.com/swetul)
- 	mattgraham (Theme Template Author)

## FAQs 
### How can I use the preset Jekyll templates on GitHub?
- Your repository must be set as public to use them.  If you go to the **SETTINGS** section of your repository, at the bottom of the page there is a danger zone. You can change your repository to public to allow use of template. <br />
<img width="500" height="300" src="https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Private.png"/><div> <br />

### Why does my new Jekyll template not change on my "GitHub Page"?
- The page on GitHub Pages needs time for the settings to update.
