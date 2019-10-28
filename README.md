# Hosting your Resume through GitHub Pages 

## AUDIENCE PROFILE

#### Audience:
- Technical Background:
	- No experience with Markdown
	- Some experience with GitHub
	- No experience with Jekyll
	- No experience with VS-code

#### Venue:
- README file within GitHub Pages

#### Purpose:
- Write a resume using Markdown, Format with Jekyll Theme, and host resume on GitHub Pages

#### Additional Purpose:
- Gain experience and confidence in technical writing tools: Markdown, Jekyll and GitHub Pages

#### Desired Reaction: 
- Informative and helpful

#### Vocabulary: 
- Technical and simple words to allow for understanding for people with a minimal background knowledge

#### Tone: 
- Respectful and formal

## PREREQUISITES 

Prerequisites to using this are having a complete resume.

## INSTRUCTIONS
	
Hello, these instructions can help a user host their resume on Git and change the layout to a pre-set theme.

> The user first has to convert their resume document into a Markdown file. To create a Markdown file, a Markdown editor can be used to write it. Some Markdown editors that can be used are Atom and VSCode. Any Markdown editor can be used, it just depends on what your comfortable with. The editor used for this assignment specifically was VSCode. 

> VSCode has nice features where you can see live previews and preview it with the GitHub Flavoured Markdown Plugin, so it fit very well with our assignment details. It is also an editor that is free to download online.

> You can create your new Markdown file (extension .md) in your Markdown editor of choice and convert your resume using Markdown syntax. Below are some basic features in Markdown. 

#### HOW TO USE BASIC FEATURES IN MARKDOWN

1. **EMPTY LINES**. A empy new line is used to separate text. If there is no empty line in between, the texts will be beside each other.

2. **HEADERS.** Headers are used to separate text and to show different sizes of text. The Number of " # " placed in front of the text will change the size and separation with 1 " # " being the largest.

	# HEADER1 
	`Markdown # Header1`
	## HEADER2 
	`Markdown ## Header2`
	### HEADER3 
	`Markdown ### Header3`

3. **BOLD and _ITALICED_ TEXT**. Bold and italiced text can be use to differentiate between different text for importance. Bold text is implemented by placing 2 " * " at the before and after the text wanted to bold. Italiced text is implemented by placing 1 " _ " before and after text wanted. 

	**HELLO** 
	`Markdown **HELLO**`
	
	_BYE_ 
	`Markdown _BYE_`

4. **TABLES**. Tables can be used to display information. Tables are made through the use of " | " and " --- " in specifc places. " | " is used to determine the number of rows and colums needed. A separate row is added and filled with " --- " in each column; it is placed as the second row. This row is not included as part of visible table, but is required in your markdown text. 

	`Markdown
	|    | 1  | 2  |  3 |
	|--- |--- |--- |--- |
	| 1  |    |    |    |
	| 2  |    |    |    |
	| 3  |	  |    |    |
	`

	|    | 1  | 2  |  3 |
	|--- |--- |--- |--- |
	| 1  |    |    |    |
	| 2  |    |    |    |
	| 3  |	  |    |    |	

5. **LINKS**. Links can be used to attach a link to text.Through the syntax [text](link), a user can attach a link to text.  For example, if the link was used to show other work or more resources. 

	GitHub: [darnellhernandez](https://github.com/darnellhernandez)

	`Markdown
	[darnellhernandez](https://github.com/darnellhernandez)`

> If you are wanting to learn more about Markdown or curious about what more you can do. There are links to more resources in the resource section. 

> Once the resume is made into a Markdown file, a user can put it on Git. Git is a version control system that is free to use, and it is where we can host the markdown file.

> In order to start, a user must make a Git account to use the system. Below are instruction to create an account, but if you have an account already, you may skip this step.

#### HOW TO SIGNUP FOR GIT ACCOUNT

1. Go to the [Git Website](https://github.com/git)

2. Once on the website, click on the SignUp Icon.

The SignUp icon is outlined in **RED** in the example picture below.
![SignUp Screen](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/SignUp.png)

3. A new page will load, where you can create an account, by entering your preferred information.
![Enter Information](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/CreateAccount.png)

4. Once account completed, an email confirmation will be sent to the selected email. The email is used for verification, so please click on the verify email address in your email to finish confirmation.

![Verify Icon In Email](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/VERIFY.png)

Once completed you may login to your account through the SignIn Icon on the [Git Website](https://github.com/git).

The SignIn icon is outlined in **RED** in the example picture below.
![SignIn](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/SignIn.png)

> Now that you are now an account user on Git, you may create a repository on your Git account for hosting your resume. Below are instructions on how to create a repositiory. 

#### HOW TO CREATE A REPOSITORY ON GIT

1. First, login to your Git Account 

2. On the top right corner there will an icon that looks like this 

![icon](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/ICON.png).

Click the icon and a drop down menu will appear. In that menu, there will be a **"Your repositories"** option. Please select that option.

The icon and option have been outlined in **RED** in the example picture below.

![Repositories](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Repositories.png)

3. Once in the repositories page, click on **"NEW"** to create a new repository. 

The **"NEW"** option has been outlined in **RED** in the example picture below.

![NewRepository](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/NewRepository.png)

4. A new page will be seen and fill out the page to create a new repository. You will need a repository name and make the repository public. Click "Create repository" once finished.

**NOTE: if you select _PRIVATE_ for your repository, you will not be able to use the preset templates in Git. You will have to change the settings of your repository later to use the templates.**

![CreateRepository](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Create%20Repository.png)

> Your new repository will be created and found in the **"Your Repository"** section of your account. Your can access it and place your Markdown file of your resume in the repository.

> Below are some basic features on how to use the repository

#### HOW TO USE BASIC FEATURES OF THE REPOSITORY

1. **Create a file**. Creating a file in the respository is simple, click the **"Create new file"** icon and it will lead you to a make a new document in the git editor. In this editor, you can name the document and enter in text. 

The **"Create new file"** option has been outlined in **RED** in the example picture below.

![CreateFile](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/CreateFile.png)

For example, we can name the document "RESUME.md" and copy our content from our Markdown editor into this editor. This will allow us to save the resume in the repository. 

![NewFile](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/NewFile.png)

2. **Editing/Saving/Deleting**. In Git, they are icons in files to start editing. Additionally, once the edit option is selected, there is a trash-can icon for deleting files. In Git, saves are referred to as **"commits"**. In the file being editted, once the wanted changes are made, you can commit the changes to the document through the **commit changes""** icon at the bottom of the page. 

The edit icon is outlined in **RED** and the trash-can icon is outlined in **BLUE** in the example picture below.

![EDIT/DELETE](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/EDIT:DELETE.png)

Example of COMMIT SECTION
![COMMIT](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/COMMIT.png)

> Once, the you have your resume on Git, they can host they resume on Git Pages. Git Pages is essential a public repository. Below are instructions on how to change your Jekyll template and host your resume on Git Pages.

#### HOW TO CHANGE TEMPLATE FOR MARKDOWN FILE AND HOST IN GIT PAGES

1. Go the the **SETTINGS** section of your repository.

The **SETTINGS** section has been outlined in **RED** in the example picture below.

![Settings](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Settings.png)

2. In the **SETTINGS** section, there will be a _GitHub Pages section_. In this section, there will be an option to select your a Jekyll Theme. The selected theme for this assignment is "Midnight Theme". The theme can be any option as long as it supports markdown tables. In the preset themes, not all themes support markdown tables.

The **Theme** section has been outlined in **RED** in the example picture below.
![Theme](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Theme.png)

3. Once theme is selected, two new files will be added to your repository; **Index.md** and **_ config.yml**. 

**_ config.yml** is a configuration file that contains the selected Jekyll theme and **Index.md** is a markdown file of their example. 

4. Select the Index.md file and delete it through the trash can icon. Commit the changes to actually delete the file. The **Index.md** is the name of the file that will be hosted once you go to your GitHub Pages.

5. Rename your resume file to **Index.md** through editting, so it can be used to host.

6. Once completed, you can access your GitHub Page through the **Setting** section of your repository. In the **Sectting** section, the GitHub Page will have a link to your site.

![Website](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Website.png)

Finally, your resume is now hosted on GitHub Pages. 

## More Resources 
-	A tutorial on [Markdown Tutorial](https://www.markdowntutorial.com/)
-	An introduction to [GitHub Flavored Markdown](https://github.github.com/gfm/)
-	An introduction to [GitHub Pages](https://help.github.com/en/categories/working-with-github-pages)

## Authors and Acknowledgements
-	Wilson
-	Harry
-	mattgraham (Theme Template Author)

## FAQs 
### Why can I not use the pre-set Jekyll templates on GitHub?
- Your repository may be on private as it must be set as public to use.  If you go to the **SETTINGS** section of your repository, at the bottom of the page there is a danger zone. You can change your repository to public to allow use of template.

![private](https://github.com/darnellhernandez/COMP3040A2/blob/master/pictures/Private.png)

### Why does my template on change my "GitHub Page"?
- The page on GitHub Pages needs time for the settings to update.
