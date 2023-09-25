---
title: "Next.js App Tutorial"
date: "2023-09-22"
---

Welcome to the Next.js App Tutorial. This is a blog template from the official [Nextjs.org website](https://nextjs.org). This blog template uses the Page Router, which was superseded by the App Router in Spring 2023. Next.js plans to upgrade this tutorial documentation to the App Router in future. You can learn a lot about Next.js, but just be aware that the App Router is now the preferred method for building apps. The [Docs section](https://nextjs.org/docs) of the website does have plenty of information on the App Rounter. Make sure you select Using App Router at the top left.

To learn the basics of Next.js you can go to the [Next.js Foundations Course](https://nextjs.org/learn/foundations/about-nextjs). The explanation of how to build this blog website is at [Create a Next.js App](https://nextjs.org/learn/basics/create-nextjs-app). Here is an example of the final result of the [Next.js blog template](https://next-learn-starter.vercel.app) and here is the [GitHub source code](https://github.com/vercel/next-learn/tree/main/basics/demo).

### Download the GutHub Repository

When you are ready to download the complete code to your local computer use this Terminal command:

**npx create-next-app@latest nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/main/basics/basics-final"**

Open your code editor, then start the develoment server with the Terminal command:

**npm run dev**

### Customize the Website

To customize the website with your own information you should update the following files:

In the directory, **public/images/**, replace the **profile.jpg** file with your own photo (recommended: 400px width/height).

In the **components/layout.js** file, at about line 9, replace the line: const name = '[Your Name]' in components/layout.js with your name, without the brackets.

In the **pages/index.js** file at about line 15 update this self introduction with your own information.

That is a good start, but you can make further changes. When you are ready, you can upload the project to your own GitHub repository and then deploy it on Vercel.

### Upload to Your Github Repository

If you have been following along with this tutorial you downloaded the repository from the GitHub Vercel repository. Now you can upload the project to your own repository. Log in to GitHub or [sign up for a new GitHub account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account). To upload to GitHub follow the instructions, [Adding Locally Hosted Code to GitHub](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github).

### Deploy to Vercel

Vercel offers free hosting of your website, with some limitations. Now you are ready to deploy to Vercel. Log in to Vercel or create an account with these instructions, [Get started with Vercel](https://vercel.com/docs/getting-started-with-vercel). Then to create your Project and Deployment follow these instuctions, [Deploying Git Repositories with Vercel](https://vercel.com/docs/deployments/git#deploying-a-git-repository).
