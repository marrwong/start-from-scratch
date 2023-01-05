# Web Development Starter Checklist

**Actionable first steps towards being a web developer in 2023**

If you're interested to learn web development in 2023, this may be a useful repository to get you started.

## Install Tools

In MacOS, search for and open the "terminal" application before installing the tools below. To install, **click on the dropdown at each step to reveal the respective command to run, then copy and paste the command in the terminal, and press Enter on the keyboard**:

### Steps

<details><summary>(Mac users only) Install brew</summary>This tool will help to manage the other tools that we will install in future
<br />`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`</details>

<details><summary>Install git</summary>This tool will help track our code changes and allow us to collaborate on code with others
<br />`brew install git`</details>

<details><summary>Install node</summary>This tool allows us to develop JavaScript applications
<br />`brew install node`</details>

<details><summary>Install visual studio code</summary>This is for viewing and editing code files
<br />`brew install --cask visual-studio-code`</details>

In Windows, you can use `winget` on the command prompt (Windows 11 onwards), or download and install the tools manually.

## Setup Starter Project from Template

(Refer to https://vitejs.dev/guide/ for more detail)

### Commands to Run

<details><summary>Create a directory called workspace and navigate to it</summary>
<br />`mkdir ~/workspace && cd ~/workspace`</details>
<details><summary>Create a new web application (called 'hello-world') based on an existing React & Typescript template</summary>
<br />`npm create vite@latest hello-world --template react-ts`</details>
<details><summary>Navigate to the newly created hello-world project folder</summary>
<br />`cd hello-world`</details>
<details><summary>Install required dependencies for the application to run</summary>
<br />`npm install`</details>
<details><summary>Start the local dev server</summary>
<br />`npm run dev`</details>

Now you will be able to view the project locally your web browser (Chrome, Edge, Safari, Firefox etc), as per the instructions in the `npm run dev` command). You will also be able to open the files in Visual Studio Code to view the code.

## Create and Setup GitHub Account

GitHub is an online platform that lets you upload your git repositories for backup and collaboration purposes.

### Steps

<details><summary>Create account on GitHub</summary>
https://github.com/join</details>

<details><summary>Create token on GitHub</summary>
Refer to https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token</details>

## Commit Changes and Push to GitHub

This will allow you to backup and track code changes and more.

### Commands to run

<details><summary>Initialize a new git repository</summary>
<br />`git init`</details>
<details><summary>Stage all newly created files</summary>
<br />`git add .`</details>
<details><summary>Commit the staged files to the local git repository</summary>
<br />`git commit -m "initial commit"`</details>
<details><summary>Configure a remote git repository destination</summary>
<br />`git remote add origin https://github.com/<your-github-username>/hello-world.git`</details>
<details><summary>Sync the local git repository with GitHub</summary>
<br />`git push --set-upstream origin main`</details>

Congrats! You have just setup your first repository on GitHub.
