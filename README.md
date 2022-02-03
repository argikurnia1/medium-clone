# Medium Clone

![](https://res.cloudinary.com/di3zoiucb/image/upload/v1643857567/clone/medium-cover_zaqivr.png)

## 📌 Overview

### /pages

✔️ `pages/index.tsx` = Homepage and list all Blogs <br/>
✔️ `pages/post/[slug].tsx` = Details Blog

### /pages/api

✔️ `pages/api/createComment.ts` = API createComment that store data to sanity studio

## 🛠 Get started

### Getting the API Keys

Create an `.env.local` and follow the name `.env.example` and get the API Keys based on the steps below

<details>
<summary>Sanity API KEYS</summary>
<p>
<br>
1. Create a <a href="https://www.contentful.com/sign-up/">Sanity</a> account <br>
2. Create new project  <br>
3. npm install -g @sanity/cli && sanity init  <br>
4. After you create new project, Go to your project, you will see the PROJECT ID at the top  <br>
   
![](https://res.cloudinary.com/di3zoiucb/image/upload/v1643897288/clone/sanity-projectid_mmrn57.png)
5. After that you need to go to -> API -> TOKENS -> ADD API TOKEN -> ENTER YOUR PROJECT NAME
   -> CHOOSE THE ACCESS PRIVILEGES FOR THE TOKEN(PERMISSIONS) -> CHANGE PERMISSIONS TO EDITOR
   
![](https://res.cloudinary.com/di3zoiucb/image/upload/v1643897298/clone/sanity-api-tokens_1_xac809.png)

![](https://res.cloudinary.com/di3zoiucb/image/upload/v1643897311/clone/sanity-api-tokens_2_jsqfam.png)

6. Put it into the environment variables according to `.env.example` and you're all set! <br>

</p>
</details>

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss&project-name=with-tailwindcss&repository-name=with-tailwindcss)

## ⚙ Tech Stack

- ReactJS
- NextJS
- Typescript
- TailwindCSS
- Sanity

### Starting the Project

Install the dependencies with `npm i` or `yarn`  
Start the project by `npm run dev` or `yarn dev`

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
# or
yarn create next-app --example with-tailwindcss with-tailwindcss-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
