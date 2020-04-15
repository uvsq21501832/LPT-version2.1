# LPT-version2.1

## LPT-version2.0 + added banner picture; added navigation barre 
## navigation barre design with bootstrap in separate jsp (barNavigation.jsp)
## Index.html repladced by index.jsp which includes barNavigation.jsp
## Java Dynamic web project (converted to maven project[1])
## NB: no JSP, no servlet, no database
## Heroku deployment Configured


## [1] Maven advantage
The convertion to a maven project is needed as the project is deployed on Heroku. Heroku scripts automaticaly look for a file that describes the laguage of the project. In java project maven provides the pom.xml file that plays this role when deploying on Heroku. Wihout this file the deployment process will present error message "Could not find a pom.xml file" or " No default language could be detected for this app" then "Push failed". With pom.xml in the project, heroku will show message "Java app detected" at the first line on the deployment process.


Previous versions
=================
## LPT-version2.0 (no code update) changed deployment project on heroku
# LPT-version1.4 added picture
## LPT-version1.3 Updated to responsive
## LPT-version1.2 added Heroku deployment Configured (ProcFile); One Servlet and one JSP page
# LPT-version1.1 Converted to maven project
# LPT-version1.0 Java Dynamic web project  (Not a maven project)
