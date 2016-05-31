
# Bash, Git, and GitHub setup instructions

In this class you will use **bash** (also known as terminal or shell) to submit certain commands using text via the "command line". You will also use **Git** to manage code versions and **GitHub** to share and access code online. This card details installation instructions.

Before starting the process below, if you do not have a GitHub account you should sign up for one. Go to the [GitHub Homepage](https://www.continuum.io/downloads) and select "Sign Up". If you sign up with academic credentials, you can gain access to paid features by requesting a [free student account](https://education.github.com/) (not required for this course).

* Windows users should install "Git Shell" along with Git and GitHub via the installer below. If you do not use this method, you will run into technical problems.
* Linux and Mac OS users already have "bash" (called "terminal" on a Mac) installed by default. Mac users can access Terminal via their Spotlight search, and pin it to the dock for easy access.


## Windows users: Installing Git Shell and Linking to GitHub

Windows users should install Git Shell by installing the [GitHub Desktop](https://desktop.github.com/) program. 

1. Download the installer and click "install". Once the installation completes, wait for the program to automatically launch.
2. Once GitHub Desktop launches, you will be prompted for your GitHub email and password. Provide these, then click "Log In".
3. The next screen prompts you for your GitHub username and email address. Provide these to configure *Git* so that it can connect to *GitHub*.  The email you specify should be the same one found in your GitHub email settings. To keep your email address hidden, see "[Keeping your email address private](https://help.github.com/articles/keeping-your-email-address-private/)". Finally, click "Continue".

You have now installed GitHub Desktop, which we will not use in this course. However, in the process GitHub Desktop has successfully installed Git Shell and connected your Shell account session to GitHub.

To access Git Shell, close out of GitHub Desktop and use the Start Menu or Desktop Shortcut to launch Git Shell. You will use this program whenever you need to enter command line commands in this course.



## Mac/Linux users: Installing Git and Linking to GitHub

The instructions below replicate those found online through [GitHub](https://help.github.com/articles/set-up-git/).

1. Download and install the latest version of [Git](https://git-scm.com/downloads).
2. On your computer, open the Terminal application.
3. Tell Git your name so your commits will be properly labeled. Type everything after the $ here:

		git config --global user.name "YOUR NAME"

4. Tell Git the email address that will be associated with your Git commits. The email you specify should be the same one found in your GitHub email settings. To keep your email address hidden, see "[Keeping your email address private](https://help.github.com/articles/keeping-your-email-address-private/)".

		git config --global user.email "YOUR EMAIL ADDRESS"

You can now use Git and access GitHub via the Terminal. You will use this program whenever you need to enter command line commands in this course.
