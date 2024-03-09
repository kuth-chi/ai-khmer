# AI Khmer Project

The AI Khmer Project is dedicated to advancing the understanding and utilization of the Khmer language through the power of artificial intelligence and natural language processing. Our project focuses on training models to analyze and process Khmer language text, including tasks such as part-of-speech tagging, sentiment analysis, and chatbot interaction.

## Project Goals

- **Language Understanding**: Our primary goal is to develop models that can accurately understand and interpret the nuances of the Khmer language.
- **Part-of-Speech Tagging**: We aim to build models capable of identifying and categorizing the parts of speech in Khmer text, facilitating deeper linguistic analysis.
- **Chatbot Interaction**: Through natural language processing techniques, we seek to create chatbots capable of engaging in meaningful conversations with users in Khmer text.
- **Language Support**: By developing tools and resources for Khmer language processing, we aim to support the broader Khmer-speaking community in various applications and domains.

## Features

- **Part-of-Speech Tagging**: Our models can automatically annotate Khmer text with part-of-speech tags, providing valuable linguistic insights.
- **Sentiment Analysis**: We offer sentiment analysis capabilities to assess the emotional tone and sentiment of Khmer language text.
- **Chatbot Interaction**: Our chatbots can interact with users in Khmer text, responding to inquiries, providing information, and engaging in conversation.
- **Training and Evaluation**: We provide tools and resources for training and evaluating language models on Khmer language data, fostering continuous improvement and development.

## How to Contribute

We welcome contributions from the community to help improve and expand the capabilities of the AI Khmer Project. Whether you're a linguist, data scientist, developer, or language enthusiast, there are many ways to get involved:

- **Contribute Code**: Help develop and improve our language processing models, algorithms, and chatbot functionality.
- **Provide Data**: Share annotated Khmer language datasets and corpora to enhance our training and evaluation efforts.
- **Report Issues**: Identify and report bugs, issues, or feature requests to help us improve the project.
- **Spread the Word**: Share our project with others and help grow our community of Khmer language enthusiasts and supporters.

## Start contribute
  #### If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```bash
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.


For example:

```bash
git clone git@github.com:your-username/ai-khmer.git
```

where `your-username` is your GitHub username. Here you're copying the contents of the khmer-ai repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```bash
cd ai-khmer
```

Now create a branch using the `git switch` command:

```bash
git switch -c your-new-branch-name
```

For example:

```bash
git switch -c add-sok-meanleap
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.


If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```bash
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```bash
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```bash
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier `add-sok-meanleap`.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
    fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/' </pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.


Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it.

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. 

### [Additional material](docs/additional-material/git_workflow_scenarios/additional-material.md)

## Get Started

To learn more about the AI Khmer Project and get involved, visit our [GitHub repository](https://github.com/kuth-chi/aikhmer.git) and explore our documentation, codebase, and contribution guidelines.

Let's work together to empower the Khmer language through artificial intelligence and natural language processing!
