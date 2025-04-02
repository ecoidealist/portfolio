# README #
BIMD233 Midterm Instruction Sheet

# Overview #
Our BIMD233 Midterm Objective is a sprucing up of your individual UW Website. This project will modernize and showcase your learning experience while increasing your level of skill as a web front end developer and user experience designer.

# Concept of Operation #
As we discovered, the main URL of your UW student web site will fetch the index.html file as the default HTML document that is rendered. While this was initially useful for verifying that your student website was provisioned correctly, it's time for an upgrade! That's precisely what we'll do in this exercise and you can be proud of the accomplishment. This will also help organize and showcase your labs and other projects. In short, we will design a new web page to replace the plain ole default index.html with a new one that will link to your BIMD233 dashboard.

# Statement of Work #
Design a simple, clean intuitive UX website that will mock up how to log into your **primary BIMD233** dashboard:

1. Start by creating a BitBucket repository called **dashboard**. Clone this repository to your local **GIT_REPOS** working folder of repositories.

2. Working within the **dashboard REPO** folder created from the cloning process, create an index.html and dashboard.html as a temporary stand-ins for the files you will design in CodePen.io (to work most efficiently). Create a primary CSS file styles.css for controlling the PRESENTATION for your new custom web site (for best "separation of concerns").

3. Do a **test deployment** to your UW Website by:

    *  Copy the wireframe template created in Lab 10 to your dashboard REPO
	*  Save a copy of the default index.html (the one from your UW Website provisioning)
	*  Clone the dashboard REPO to your public_html folder on your UW Website
	*  Copy the index.html and styles.css files from your dashboard repo to the root of your UW Website
	*  Link the log in button to your dashboard.html (found in the dashboard REPO)

4. Create a new "Pen" in CodePen.io and also name it **login**.

5. Create a new "Pen" in CodePen.io and also name it **dashboard**.

6. Carefully set up your [Bootstrap 5.1](https://getbootstrap.com/docs/5.1/getting-started/download/) CSS and JS in Settings as well as check the Behavior for automatic continuous rendering (Auto-Updating Preview).

7. Use the Dashboard login image below, design your simple login screen:

	*  Replace the personalized round picture with your picture, avatar or a logo
	*  Design the form with a username, and password login capability as shown
	*  Use a button just like shown, but wrap it in an anchor tag to provide a way to link to dashboard
	*  Test the Link to your Dashboard


8. Utilizing the template you designed in **Lab10** continue to finish the details such as:

	*  Link the BitBucket entry to your BitBucket URL
	*  Link the Bootstrap entry to your Bootstrap 5.1 URL
	*  Link each of the Labs in the dropdown list
	*  Link to your Lavender Site
	*  Provision for a Capstone (future site to be developed)
	*  Add some pictures to your Carousel and/or Cards as desired
	*  Tidy up your presentation of all of the above to sell your creativity
	*  Log into your UW Website command line and deploy your updated dashboard (e.g. git pull)

# LINKS TO LECTURE NOTES #

| Description | Zoom Link | Lecture Notes Link |
| --- | --- | --- |
| Link to 6B - Midterm zoom, discussing the midterm specs | [Week 6B-ZOOM](https://washington.zoom.us/rec/play/eavXKCxKVYjgyZjMBK-jZam-Jfg-0oOSYHIoOXBwAdqruBB6mJt-Dg6s2duEiyF25mNX7YwAb0eYfxow.GrqW9cNd8MoWMnRm?continueMode=true) | [Week 6B-BIMD233 Midterm Instruction Sheet](https://courses.washington.edu/bimd233/midterm_spec_c/) |
| Link to Week 6A, Module 10 zoom, create a Bootstrap wireframe template to be used for Midterm | [Week 6A-ZOOM](https://washington.zoom.us/rec/play/oPq1HRxl0FGfxkzGt62Y2wK6oG_16bnmeVP1yjbnsqgqTW_XGS4QZrLn1mz873P0H9OCzLy9AvTw_yE.kNrhbldbBxa7Jyyr?continueMode=true) | [Link to 6A - Module 10 Powerpoint](https://res.cloudinary.com/dnsjrjyv3/raw/upload/v1636278395/B_IMD233_Module_10_6_qmpwuh.pptx) |
| Link to Week 5A, Module 8 zoom, creating and deploying a new BitBucket repository into vergil | [Week 5A-ZOOM](https://washington.zoom.us/rec/play/4Bycw9jJSv_WCMgExqefqcjeb9bCJskuPthNc9XeFjUObM1PG5Ya_TW5sXmRTqlrnYbtoj2mUAIYpEWA.f1c_narnX447mZ9L?continueMode=true) | [Link to 5A - Module 8 Powerpoint](https://res.cloudinary.com/dnsjrjyv3/raw/upload/v1636278464/B_IMD233_Module_8_wnny89.pptx) |

# Midterm Example Files #

### Dashboard Login Examples ###

![Dashboard Login](https://res.cloudinary.com/dnsjrjyv3/image/upload/v1636276672/Site_Login_zvgqla.png)

### Wireframe Design from Lab 10 Example ###

![Dashboard Login](https://res.cloudinary.com/dnsjrjyv3/image/upload/v1636276672/Dashboard_Wireframe_yynxv5.png)

# BITBUCKET / VERGIL DEPLOY STEPS #

### GIT BASH TERMINAL - PUSH FILES TO LOCAL "REPO FOLDER-2" ###

 **Git Clone**
```
$ ssh %unetid%@vergil.u.washington.edu
$ cd public_HTML
$ git clone git@bitbucket.org:%GITUSERNAME%/%gitreponame%.git
	"EXAMPLE: git clone git@bitbucket.org:ksteve3/dashboard.git..."
$ Pull/Delpoy to website https://students.washington.edu/ksteve3/fall2021-dashboard/
```

| **Step #** | **Terminal indicator** | **Command** |
| --- | --- | --- |
| 1) | $ | cd C:/ |
| 2) | $ | cd C:/Users/ |
| 3) | $ | cd C:/Users/%USERPROFILE%/ |
| 4) | $ | cd C:/Users/%USERPROFILE%/%GIT-WORKSPACE-FOLDER%/ |
| 5) | $ | cd C:/Users/%USERPROFILE%/%GIT-WORKSPACE-FOLDER%/%GIT-REPO-FOLDER-2%/ |
| 6) | $ | ls |
| 7) | $ | git status |
| 8) | $ | git add -A |
| 9) | $ | git status |
| 10) | $ | git add -A |
| 12) | $ | git commit -m "Checking in ..." |
| 13) | $ | git status |
| 14) | $ | git push |
| 15) | $ | ssh %uwnetid%@vergil.u.washington.edu |
| 16) | vergil11$ | cd public_html/%GIT-REPO-FOLDER-2%/ |
| 17) | vergil11$ | git pull |
| 18) | vergil11$ | exit |


# MIDTERM Grading Rubric  #

| Grading Rubric |  |  |
| --- | --- | --- |
| Category | Evaluation Criteria | Weight(%) |
| General Organization | Understanding how to plan a website project, use web technology oriented tools such as editors and browsers to code static web pages, layout of files and directories, use repository for capture and deployment to a real website on the public internet. | 20 |
| Separation of Concerns | Designs should not mix content and style within the same file. Clear understanding and layout of content in the HTML documents and style in the CSS documents should be demonstrated. | 20 |
| Design Style | Demonstration and creative use of background images, textures, gradients, color and leveraging of advanced CSS libraries such as bootstrap components to enhance and simplify the design style. | 20 |
| Technical Competence | Clarity in understanding how to create static web site pages use of HTML elements and CSS selectors and declarations to style respective HTML elements. | 20 |
| Testing and Deployment | Applied use of tools, such as GIT to check in source files into stand-alone respositories that are deployment to a production web site environment. Understanding of how to log into UW-NEDID account, traverse through folders using basic linux commands (e.g. ls, cd). | 20 |
| TOTAL |  | 1 |

