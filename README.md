# Build a CLI Application with External Data

## Overview

In this lesson you're going to build an application that provides a Command Line Interface (CLI) to an external data source. The CLI will be composed of an Object Oriented Ruby application.

**Please note that while you will be writing code to scrape data from a public website, what we're looking for is your capacity to effectively write good object oriented Ruby (objects, not hashes, separation of concerns, etc.) - we're less interested in the details of the regex's or selector you're using to parse the web pages that you're scraping.**

## Requirements

1. Provide a CLI
1. CLI must provide access to data from a web page.
1. The data provided must go at least one level deep, generally by showing the user a list of available data and then being able to drill down into a specific item.
1. The CLI application can not be a Music CLI application as that is too similiar to the other OO Ruby final project. Also please refrain from using Kickstarter as that was used for the scraping 'code along'. Look at the example domains below for inspiration.
1. Use good OO design patterns. You should be creating a collection of objects - not hashes.

*For bonus points, instead of just creating an application, create a gem and for extra bonus points try publishing it to RubyGems.*

### Example Domains

- Movies opening soon - Enter your zip code and receive a list of movies and their details.
- Libraries near you -  Enter your zip code and receive a list of libraries and their details.
- Programming meetups near you, list details.
- News reader - List articles, read article.

[now-playing](https://github.com/learn-co-curriculum/now-playing-cli-gem) is an example of a gem that would meet these requirements.
[worlds best restaurants](https://github.com/cjbrock/worlds-best-restaurants-cli-gem) was built by a Learn student, maintained by Flatiron School staff, meets these requirements, and is well coded.
Take the time to clone, run and look through the code for both of these in detail - it will help.

## Instructions

1. Watch this [video walkthrough](https://www.youtube.com/watch?v=_lDExWIhYKI) of building a CLI Gem called [Daily Deal](https://github.com/learn-co-curriculum/daily_deal) before you begin.
1. Create a new repository on GitHub for your application, ie: `name-cli-app`.
1. Build your application. Make sure to commit early and commit often. Commit messages should be meaningful (clearly describe what you're doing in the commit) and accurate (there should be nothing in the commit that doesn't match the description in the commit message). Good rule of thumb is to commit every 3-7 mins of actual coding time. Most of your commits should have under 15 lines of code and a 2 line commit is perfectly acceptable. **This is important and you'll be graded on this**.
1. Create a good README.md with a short description, installation instructions, a contributors guide and a link to the license for your code.
1. Use [this checklist](https://docs.google.com/forms/d/1ItDHkNbtHJP8T2G28Nqc3Ad8MppbPDpqv9AijAOCFDA/) as a guide but do NOT submit it.

## Project Review:

Your project review will be with a Nitro Developer.

### Be Prepared to:

1. Explain your code from execution point to exit point.
1. Walkthrough the CLI tool. Be able to demonstrate multiple successful workflows. **Write your code in such a way that it outputs useful instructions if a user submits invalid input. And demonstate that too.**
1. Refactor your code.

If necessary, after your project review, be prepared to:

1. Extend the application with a new feature, more data, a different domain etc.
1. Submit an improved version.

### What to expect

Project reviews are focused on preparing you for speaking technically with other Power developers. Treat project reviews as if they were technical interviews, in both attitude and technical presentation.

- If you make a mistake, correct yourself! We all make mistakes. No worries :).
- Think on your feet. You are being asked to expand on concepts you have implemented and you should push yourself to the edge of your knowledge.
- Don’t worry if your code isn’t perfect the first time - focus on getting something working, then refactor to improve it.
- Be proud of your project and your code, and show confidence in it.
- Be open to feedback, both positive and constructive.

#### Work Together.
- Trust yourself.
- Trust us - our goal is to help you be successful in achieving your goals.
- We understand that this process can be stressful. We’re here to help you through.

#### Pursue mastery.
- Use the best technical vocabulary you can. We will help you with the words you can’t remember, or if you’re unsure about how something is pronounced.
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
