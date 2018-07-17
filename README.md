# direct-docker-golang
This is an example of a wercker pipeline that uses a direct docker daemon.

## How to run the example

You will need a GitHub account, a Wercker account and a DockerHub account.

In Github:

* Login to GitHub if you have not already done so.
* Fork this repository to your GitHub account by clicking on the "Fork" button at the top-right corner of this page.

In Wercker:

* Goto [app.wercker.com](https://app.wercker.com/) and login if you have not already done so.
* Create an application by clicking on the + icon at the top-right of the page and choosing "add application"
* In the page that opens, select your username (if necessary), select "GitHub" from the list and press "Next". 
* If prompted, follow the instructions to give Wercker access to your GitHub repository
* Wercker will then display a list of repositories in GitHub. Select your fork of direct-docker-golang and click "Next"
* On the next page "Setup SSH key" accept the defaults and click "Next"
* On the next page "Review" review the information displayed and click "Create"

You have now created an application in Wercker which refers to your forked repository in GitHub.

* Click on the "Environment" tab and create two environment variables 
  * `USERNAME` - Your Docker Hub username 
  * `PASSWORD` - Your Docker Hub password

* Click on the "Runs" tab, scroll to the bottom of the page and click on "trigger a build now". You will then see your build running in Wercker.


 
