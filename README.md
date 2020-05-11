# Build a CLI Application with External Data

## Overview

For this project, you are going to build an application that provides a Command Line Interface (CLI) to an external data source. The CLI will be composed of an Object Oriented Ruby application.

## Requirements

1. Provide a CLI that exposes data scraped from a web page.

2. The application must allow the user to learn more based on their input. This will be done by showing the user a list of options, allowing them to choose a specific option, and then showing them more info based on their choice.

3. After the user enters input, your CLI should reach out to the web page again to scrape additional data. Write your code in such a way that it outputs useful instructions if one submits invalid input.

4. Use the example domains below for inspiration, but the web page you choose to scrape will guide how your CLI can be built. **Check your domain with your instructor before starting your project.**

5. Use Object Oriented design patterns. You should be creating instances of objects that relate to one another. Attempt to make your code as "DRY" (Don't Repeat Yourself) as possible.

6. The application should conform to Nitro's Ruby linting conventions. The `.rubocop.yml` file included in this repo must be copied over to your application, it is not exactly the same as the generic file copied over to your system from the Ruby Linting lesson. Running `rubocop` from your application's root should return a `no offenses detected` message.

## Instructions

1. Create a new repository on GitHub for your application with a descriptive name that communicates the subject matter of the application.

2. As you build your application, make sure to commit early and often. Commit messages should be meaningful and accurate. Clearly describe what you're doing in the commit and note that there should be nothing in it that doesn't match the commit subject and description. A good rule of thumb is to commit every 3-7 mins of actual coding time. **This is important and you will be graded on it**.

3. Create a `README.md` with a short description and installation instructions.

4. Add the [requirements.md](https://github.com/learn-co-curriculum/phrg-cli-scraping-gem-project/blob/master/requirements.md) file to your project. Address all items by describing how you have met that requirement under each line and by checking each box. **USE CORRECT TECHNICAL VOCABULARY**

## Project Review

Your project review will be with a Nitro System Architect. If necessary, after the review, you may need to extend the application and submit an improved version.

Project reviews are focused on preparing you for speaking technically with other Power developers. Treat Project Reviews as if they were technical interviews, in both attitude and technical presentation. The only way to get better at using new vocabulary is practicing. Practice presenting your application before the review.

### Be Prepared to

1. Walk through your `requirements.md` and comment on how you have fulfilled each criterion.
1. Explain your code from execution point to exit point.
1. Demonstrate multiple successful workflows and what happens when you enter invalid input.
1. Refactor your code.

### Final Advice

- If you make a mistake, correct yourself. We all make mistakes.
- Be open to feedback.
- Ask questions! Curiosity and willingness to learn are hugely valued in our industry.

---

## Example Domains

Refrain from using Kickstarter since that was used for the scraping 'code along'. Some other possibilities include:

- Movies opening soon - Enter your zip code and receive a list of movies and their details.
- Libraries near you -  Enter your zip code and receive a list of libraries and their details.
- Programming meetups near you, list details.
- News reader - List articles, read article.

## Example repos by PCA graduates

- [Top 50 Movies](https://github.com/eabousaif/top50movielist_cli_app)
- [Pennsylvania Disc Golf Tournament Tracker](https://github.com/KFad11/DGTournament-cli-app)
