# Build a CLI Application with External Data

## Overview

For this project, you are going to build an application that provides a Command Line Interface (CLI) to an external data source. The CLI will be composed of an Object Oriented Ruby application.

## Requirements

1. Provide a CLI that exposes data scraped from a web page.

2. The application must allow the user to learn more based on their input. This will be done by showing the user a list of options, allowing them to choose a specific option, and then showing them more info based on their choice.

3. After the user enters input, your CLI should reach out to the web page again to scrape additional data. Write your code in such a way that it outputs useful instructions if one submits invalid input.

4. Refrain from using Kickstarter since that was used for the scraping 'code along'. Look at the example domains below for inspiration, but the webpage you choose will guide how your CLI can be built. **Check your domain with your instructor before starting your project.**

5. Use Object Oriented design patterns. You should be creating instances of objects that relate to one another. Attempt to make your code as "DRY" (Don't Repeat Yourself) as possible.

6. The application should conform to Nitro's Ruby linting conventions. The `rubocop.yml` file included in this repo should be copied over to your application and named `.rubocop.yml`. Running `rubocop` from your application's root should return a `no offenses detected` message. (Notice you need to change the filename by adding a `.` to it.)


## Instructions

1. Create a new repository on GitHub for your application with a descriptive name that communicates the domain of the application.

2. As you build your application, make sure to commit early and often. Commit messages should be meaningful and accurate. Clearly describe what you're doing in the commit and note that there should be nothing in it that doesn't match the commit subject and description. A good rule of thumb is to commit every 3-7 mins of actual coding time. **This is important and you will be graded on it**.

3. Create a README.md with a short description and installation instructions.

4. Add the [requirements.md](https://github.com/learn-co-curriculum/phrg-cli-scraping-gem-project/blob/master/requirements.md) file to your project. Address all items by describing how you have met that requirement under each line and by checking each box. **USE CORRECT TECHNICAL VOCABULARY**


## Project Review:

Your project review will be with a Nitro System Architect. If necessary, after the review, you may need to extend the application and submit an improved version.

Project reviews are focused on preparing you for speaking technically with other Power developers. Treat Project Reviews as if they were technical interviews, in both attitude and technical presentation. The only way to get better at using new vocabulary is practicing. Practice presenting your application before the review.

### Be Prepared to:

1. Walk through your requirements.md and comment how you have fulfilled each of the criteria.
1. Explain your code from execution point to exit point.
1. Demonstrate multiple successful workflows and what happens when you enter invalid input.
1. Refactor your code.

### Final advice:

- If you make a mistake, correct yourself. We all make mistakes.
- Be open to feedback.
- Ask questions! Curiosity and willingness to learn are hugely valued in our industry.

---

## Example Domains

- Movies opening soon - Enter your zip code and receive a list of movies and their details.
- Libraries near you -  Enter your zip code and receive a list of libraries and their details.
- Programming meetups near you, list details.
- News reader - List articles, read article.


## Link example repo here that was a project made by a PCA graduate.


## Resources

- [How to build a ruby gem](http://guides.rubygems.org/make-your-own-gem/)
- [How to publish your gem](http://guides.rubygems.org/publishing/)
- [Environments, Requiring Files, Bundler, and Gems](https://www.youtube.com/watch?v=XBgZLm-sdl8)
- [Video- CLI Data Gem Walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI)
- [Video- CLI Data Gem Walkthrough: Creating a CLI Scraper Gem](https://www.youtube.com/watch?v=Y5X6NRQi0bU)
- [Video- Common Anti-Patterns in CLI Data Gem](https://www.youtube.com/watch?v=cbMa87oWv08)
- [Video- Student Example 1: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=JEL_PXr74qQ)
- [Video- Student Example 2: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=Lt0oyHiKWIw)
