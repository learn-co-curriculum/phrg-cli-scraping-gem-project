# Build a CLI Application with External Data

## Overview

For this project, you are going to build an application that provides a Command Line Interface (CLI) to an external data source. The CLI will be composed of an Object Oriented Ruby application.

## Requirements

1. Provide a CLI.

2. Your CLI must provide access to data from a web page.

3. The data provided must go at least one level deep, generally by showing the user a list of available options and then drilling down into a specific item and showing info for that.

4. After a user enters input, your CLI should reach out to the web page again to scrape new data. Write your code in such a way that it outputs useful instructions if one submits invalid input.

5. The CLI application cannot be a Music CLI application as that is too similiar to the other OO Ruby final project. Also, please refrain from using Kickstarter since that was used for the scraping 'code along'. Look at the example domains below for inspiration. **Check off your domain with your instructor before starting your project.**

6. Use good Object Oriented design patterns. You should be creating a collection of objects that relate to one another. Attempt to make your code as "DRY" (Don't Repeat Yourself) as possible.

7. Your application should conform to Nitro's Ruby linting conventions. The `rubocop.yml` file included in this repo should be copied over to your application and named `.rubocop.yml`. Running `rubocop` from your application's root should return a `no offenses detected` message. (Notice you need to change the filename by adding a `.` to it.)

### Example Domains

- Movies opening soon - Enter your zip code and receive a list of movies and their details.
- Libraries near you -  Enter your zip code and receive a list of libraries and their details.
- Programming meetups near you, list details.
- News reader - List articles, read article.

### Link example repo here that was a project made by a PCA graduate.

## Instructions

1. Create a new repository on GitHub for your application, ie: `name-cli-app`.

2. Build your application. Make sure to commit early and commit often. Commit messages should be meaningful (clearly describe what you're doing in the commit) and accurate (there should be nothing in the commit that doesn't match the description in the commit message). Good rule of thumb is to commit every 3-7 mins of actual coding time. Most of your commits should have under 15 lines of code and a 2 line commit is perfectly acceptable. **This is important and you will be graded on it**.

3. Create a good README.md with a short description and installation instructions.

4. Add this [requirements.md](https://github.com/learn-co-curriculum/phrg-cli-scraping-gem-project/blob/master/requirements.md) in your project and address each requirement. Check each box (replace the space between the square braces with an x) and feel free to write next to an item on how you've met the requirement.

**While you will be writing code to scrape data from a website, what we are looking for is your capacity to effectively write good object oriented Ruby (objects, not hashes, separation of concerns, etc.)**

## Project Review:

Your project review will be with a Nitro System Architect.

### Be Prepared to:

1. Walk through your requirements.md a comment how you have fulfilled each criteria.
1. Explain your code from execution point to exit point.
1. Walk through your CLI tool. Be able to demonstrate multiple successful workflows and what happens when you enter invalid input.
1. Refactor your code.

If necessary, after your project review, be prepared to extend the application with a new feature and submit an improved version.

### What to expect in your Project Review

Project reviews are focused on preparing you for speaking technically with other Power developers. Treat Project Reviews as if they were technical interviews, in both attitude and technical presentation.

- If you make a mistake, correct yourself. We all make mistakes.
- Use the best technical vocabulary you can. We will help you with the words you cannot remember, or if you are unsure about how something is pronounced.
- Think on your feet. You are being asked to expand on concepts you have implemented and you should push yourself to the edge of your knowledge.
- Be proud of your project and your code, and show confidence in it.
- Be open to feedback.
- Ask questions! Curiosity and willingness to learn are hugely valued in our industry.

## Resources

- [How to build a ruby gem](http://guides.rubygems.org/make-your-own-gem/)
- [How to publish your gem](http://guides.rubygems.org/publishing/)
- [Environments, Requiring Files, Bundler, and Gems](https://www.youtube.com/watch?v=XBgZLm-sdl8)
- [Video- CLI Data Gem Walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI)
- [Video- CLI Data Gem Walkthrough: Creating a CLI Scraper Gem](https://www.youtube.com/watch?v=Y5X6NRQi0bU)
- [Video- Common Anti-Patterns in CLI Data Gem](https://www.youtube.com/watch?v=cbMa87oWv08)
- [Video- Student Example 1: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=JEL_PXr74qQ)
- [Video- Student Example 2: Refactoring CLI Data Gem](https://www.youtube.com/watch?v=Lt0oyHiKWIw)
