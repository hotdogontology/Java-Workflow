# GitHub Workflow for Students

This guide will walk you through the steps to create a GitHub account, accept an assignment on GitHub Classroom, clone the repository using GitHub Desktop, and add the project to IntelliJ.
To learn more about these tools, head to the [Getting Started Repo](https://github.com/hotdogontology/Java-Getting-Started)

## 1. Creating a GitHub Account

1. Go to [GitHub](https://github.com/).
2. Click on **Sign up** in the upper-right corner. (If you already have an account, click on **Sign In** instead.)
3. Enter your email address, create a password, and choose a username.
4. Follow the on-screen instructions to complete the setup. You might need to verify your email address.
5. After setting up your account, sign in to GitHub.

## 2. Accepting an Assignment on GitHub Classroom

1. Your instructor will provide a link to the GitHub Classroom assignment.
2. Click on the link to open the assignment in your browser.
3. If prompted, authorize GitHub Classroom to access your GitHub account.
4. Click **Accept this assignment**. GitHub Classroom will create a repository for you with the assignment files.
5. Once the repository is created, you’ll see a link to your personal assignment repository. Click on it to view your repo.

## 3. Working In The Browser with GitHub Codespaces

1. GitHub Classroom provides virtual machines for students to develop their code. These are called Codespaces. The interface will look like VS Code.
2. Follow the [directions here](https://docs.github.com/en/education/manage-coursework-with-github-classroom/integrate-github-classroom-with-an-ide/using-github-codespaces-with-github-classroom#launching-an-assignment-using-github-codespaces) if you want to use Codespaces.
3. If you have difficulty with Codespaces or want to work locally on your machine, follow the directions below.

## 4. Cloning the Repository Using GitHub Desktop

1. Download and install [GitHub Desktop](https://desktop.github.com/) if you haven't already.
2. Open GitHub Desktop and sign in with your GitHub account.
3. In GitHub Desktop, click on **File** > **Clone Repository**.
4. In the pop-up window, select the **URL** tab and paste the URL of your assignment repository (found on GitHub after accepting the assignment).
5. Choose a local path (the folder) where you want to save the repository on your computer, then click **Clone**.
6. The repository will be cloned to your computer, and you can now see the files in GitHub Desktop.

## 5. Adding the Project to IntelliJ IDEA

1. Open IntelliJ IDEA on your computer.
2. On the Welcome screen, click Open near the top of the window. **Do not click New Project or Clone Repository. The repository has already been cloned using GitHub Desktop.**
3. Navigate to the folder where GitHub Desktop cloned your repository.
4. Select the root folder of the repository (the folder that contains src, README.md, etc.), then click OK.
5. If prompted, choose Open as Project.
6. If IntelliJ asks whether to trust the project, select Trust Project.
7. If this is a Java project:
   -IntelliJ will usually detect and configure it automatically.
   -If it does not, go to File > Project Structure > Project, and set the Project SDK to the Java version specified by your instructor.
8. Wait for IntelliJ to finish indexing the project.

Your project is now ready to be worked on in IntelliJ IDEA.

---

## Troubleshooting Tips

- **Can't find the cloned repository in GitHub Desktop?** Make sure you copied the correct URL from GitHub and that you're logged into the correct GitHub account in GitHub Desktop.
- **IntelliJ doesn't show the project correctly?** Check if your project files are correctly placed in the repository and try importing the project again using the correct import settings.
