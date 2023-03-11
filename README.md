# `Information`
This should be a fun exercise.

## Router Protocol

<!-- <p align="center" >

<img src="https://user-images.githubusercontent.com/124175970/224509096-12e4864a-6819-4c8c-8998-41c7a96ba026.jpg" />
  </p> -->

<!-- ![router-protocol-crypto-ninjas](https://user-images.githubusercontent.com/124175970/224509096-12e4864a-6819-4c8c-8998-41c7a96ba026.jpg) -->

<img src="https://user-images.githubusercontent.com/124175970/224509096-12e4864a-6819-4c8c-8998-41c7a96ba026.jpg" width="8000000em" height="400em" />


# `Company Information`

Router Protocol is a solution introduced to address the issues hindering the usability of cross-chain liquidity migration in the DeFi ecosystem. It acts as a bridge connecting various layer 1 and layer 2 blockchains, allowing for the flow of contract-level data across them. The Router Protocol can either transfer tokens between chains or initiate operations on one chain and execute them on another.

Please check the [official documentation of Router Protocol](https://www.routerprotocol.com/)

# `Why participate in Router Student Expert Program`

We reward 🏅 badges to individuals who complete our Open Source assignments!

The journey is divided into multiple stages, each with its own set of points. As you complete Assignment 1, you'll earn a certain number of points, and the same goes for Assignment 2, all the way up to the Final Assignment. Once you've earned a certain benchmark points, you'll receive an NFT badge as a token of your achievement.

Each assignment has its own unique set of points. For every 100 points earned, you'll receive a 🥉 Bronze Router Expert badge, for 500 points, you'll get a 🥈 Silver badge, and for 1000 points, you'll receive a coveted 🥇 Gold badge. These badges will add an extra shine to your resume and can be a golden ticket to working with us.

This initiative is perfect for those interested in pursuing a career in the web 3 space, and the badges can serve as a glowing recommendation for future opportunities. So what are you waiting for? Let's get started on the path to becoming a Router Expert! 🚀

# `Assignment description`

1. Give the NFT a name - "Your name" and symbol - "Your Name's first and 2nd name first letter used as abbreviation".

2. Use Mumbai Testnet as the source chain and Fuji Testnet as the destination chain.

3. Mint the NFT with id = 450 on the source chain.

4. Transfer the NFT from the source chain to the destination chain.

5. Copy the transaction hash from the Router Explorer and submit in this ![form](https://docs.google.com/forms/d/e/1FAIpQLSd8Xuiuw32kOqGsWmT5s7GLjLVZ_rHXw9bAJbdbr0XzrVG6RA/viewform?embedded=true) 


**Key Responsibilities:**

- Building features for the browser extension
- Building reusable UI components using our existing the [design system](https://design.opensauced.pizza/) 
- Building interactions to communicate with with GitHub and our API
- Participate in design and engineering reviews to provide feedback during team meetings
- Monitor application performance
- Provide solutions to various solutions based on complexity and tradeoffs.

### Recommended qualifications

**Desired Skills:**

- Strong proficiency in React, Next.JS, and Tailwind
- Familiarity with general backend APIs
- Strong proficiency in HTML, CSS, JavaScript
- Proficiency in TypeScript

**Bonus Skills?:**

- Familiarity with the GitHub API
- Familiarity with backend APIs such as NestJS with Swagger

### Eligibility

To participate, you must be:

* A [verified student](https://education.github.com/discount_requests/pack_application) on Global Campus

* 18 years or older

* Active contributor on GitHub (monthly)

* Ability to work overlap US hours (at least 4 hours within the 7am-12pm PT timeframe) 

# Assignment

## Create browser extension that connects [api.opensauced.pizza](https://api.opensauced.pizza/) to a github.com profile.

### Task instructions

1. Create an OpenSauced account by connecting your GitHub to [opensauced.pizza](https://insights.opensauced.pizza)
1. Generate a [vite](https://vitejs.dev/) powered browser extension using the [CRXJS](https://crxjs.dev/vite-plugin/getting-started/vanilla-js/create-project) guide. Note there are two versions, vite@3 is in beta but both will work fine for this assignment. You can also leverage this [DEV post](https://dev.to/jacksteamdev/create-a-vite-react-chrome-extension-in-90-seconds-3df7) and the projects GitHub Discussion for additional help. This project is an open book assignment, so google as much as you'd like.
1. Connect your localhost power extension to your browser. You should not be deploying this to production or any browser store. 
1. Write a function that validates if an OpenSauced user account exists (using the OpenSauced API) for a GitHub user profile while viewing them on github.com. 

The final solution should only show a button if the GitHub user profile if the GitHub user is signed up for OpenSauced.

<img width="245" alt="Screen Shot 2023-03-04 at 2 27 39 PM" src="https://user-images.githubusercontent.com/5713670/222931380-bc824441-abc8-46f9-af4b-8adf4b3ef373.png">

API example:

When viewing [bdougie](https://github.com/bdougie) you will check his handle using the users service in api.opensauced.pizza to confirm he is an OpenSauced user. When checking [defunkt](https://github.com/defunkt) you will confirm he is not an OpenSauced user.

```
https://api.opensauced.pizza/v1/users/bdougie // returns 200
https://api.opensauced.pizza/v1/users/defunkt // return 404
```

Things to consider:

1. You can leverage the extension's popup to test the API by replace the Vite boilerplate.
1. Limit this extension to only work on github.com profile pages. hint: the project will default to google.com, you will need to change that.
1. Adding a button can be done using React, Vue, HTMl, what you prefer. The button should actually link to the OpenSauced profile if it exists.
1. What else? How can you make this better? Auth to OpenSauced? Other Features?

### Task Expectations

Expectation is your extension only works when the user is on GitHub and can interact with the page. This interaction is to add a button that links to the users profile. 

- If there is missing documentation for OpenSauced, a contribution or open issue to the [docs](https://docs.opensauced.pizza/) repository is expected.
- If you are blocked longer than 2-3 hours, [ask in the Discussions](https://github.com/open-sauced-craftwork/browser-extension/discussions). Linking errors messages or StackOverflow questions is the preferred way to provide context when asking for help.
- To better understand the OpenSauced, join the [Discord Community](https://discord.gg/opensauced).

### Task submission

Students are expected to use the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) when working on their project. 

1. Creating a new branch
2. Making changes on the new branch to complete the task
4. Using GitHub Discussions to ask any relevant questions regarding the project

### Resources

- [api.opensauced.pizza](https://api.opensauced.pizza/)
- [docs.opensauced.pizza](https://docs.opensauced.pizza/)
- https://github.com/open-sauced/assets
- [crxjs](https://crxjs.dev/) 
- [vite](https://vitejs.dev/)
