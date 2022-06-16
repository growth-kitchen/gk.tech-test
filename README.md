# Growth Kitchen's Full-Stack Test

Welcome to Growth Kitchen and thanks for showing an interest in applying for one of our roles. 

## Goal

The objective of this challenge is to assess a tiny bit of each thing you'd have to do while developing a feature for a full-stack application. On a normal day at work, you'd probably have to _at the bare minimum_, modify an API, fiddle with some frontend code, do some magic in HTML and CSS, and write some tests. So, that's what we want to see on this challenge, and it's why we don't ask you to traverse a tree or implement Dijkstra's algorithm.

## Languages, technologies and libraries

Ideally, we'd like you to use React, TypeScript, HTML and CSS because those are some of the technologies we're using at Growth Kitchen at the moment. We've provided you with a basic [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), in case you want to use it and save some time.

However, you don't need to use the project provided, if you feel more comfortable with, for instance, [`create-react-app`](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app) or Vue.js/Svelte/Angular instead of React.

You can use as many libraries and tools as you need to get the job done. Do you prefer to write your styles in plain CSS? That's fine. Do you feel more comfortable using SASS, or a framework like Tailwind or Ant? That's totally fine too. All we ask is that you explain _why_ you've chosen a certain library or tool.

## What we'll be paying attention to

We want to be as transparent as possible to set you up for success, so here are the things that we'll be paying attention to:

**1. Adherence to instructions** – Does your solution do everything we've asked you to do? Have any requirements been ignored? Do your tests run (and pass)?

**2. Overall structure and cleanliness** – Can you organise the project cleanly and tidily? Is your code easy-to-read and structured in a cohesive manner? 

**3. Language features** – Are you correctly using the features of the languages you're using for the test?

**4. Correct use of technologies and tools** – Are you using the right tools for each task? 

**5. Naming conventions and consistency** – Do you stick to naming conventions? Does your code look consistent throughout your solution?

**6. Clarifications and assumptions** – Have you written clear clarifications to explain why you've decided to do (or not to do) a part of the solution in that specific way? If something wasn't obvious from the task description, have you documented it and explained your assumptions?

## The task

We'd like you to create a simple menu page for a restaurant.

Using the data provided in `public/menu.json`:

1. Create an API endpoint that returns the menu data from said file.

2. Create a menu page that renders the necessary information provided by the API endpoint. We don't want to display menu items without stock. Information we need to display on the menu page:
- Restaurant's name.
- Restaurant's description.
- Each menu item with its name, description, image, unit price and a button to add it to the basket.

3. Create a button that, when clicking it, will log to the `console` a JavaScript `object` including–but not limited to–all the items in the basket. It's up to you to decide what data you should include when "placing an order" and how to structure it.

4. Create an `EXPLANATION.md` file explaining your solution and decisions that you had to make, including, at least:
- How to run the solution and the tests, and any pre-requisites.
- Assumptions.
- Libraries used (and why).
- Types of tests written.
- Any problems you faced.
- Any things you'd have done differently if you had more time or if this was a feature that you'd be deploying to real customers in Production.
- How long you've spent on the test – This won't have an impact on the outcome of the interview process. We want to monitor how long do people tend to spend on the challenge.

## Additional Tips

- Try to make this simple page look nice, clean and professional for mobile devices up to `480px`. Ignore other screen sizes. It's entirely up to you how this page should be presented, but make sure you do style it (once again, feel free to use libraries or frameworks to achieve this, if you wished to do so).

- Write some sort of automated tests. Again, you choose what type(s) of tests to write and how.

## How long should I spend on this test?

We are very conscious of people's personal time, so we didn't want to create a test that would take up too much time. Ideally, you should be able to complete this task in more or less 2-3 hours.

## Feedback

This is the first version of our technical test because we're just starting our journey towards building our in-house team! If you have any feedback in terms of how we can make it a better test, please, let your interviewer know! 🙏

## Submission

Create a zip file named `{yourfullname}.zip` including your whole submission and send it to the recruiter who's been in contact with you. Please, be mindful of not including any unnecessary files and folders.

## Running The Application

### Prerequisites

- `node >= 12.22.0` (more details [here](https://nextjs.org/docs/upgrading)).

### Running the dev server

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000/menu](http://localhost:3000/menu) with your browser to see the result.

You can start editing the page by modifying `pages/menu.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/menu](http://localhost:3000/api/menu). This endpoint can be edited in `pages/api/menu.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.