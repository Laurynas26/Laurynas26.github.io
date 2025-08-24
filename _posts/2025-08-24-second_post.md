# Kickoff - Planning the Funda Price Range Prediction App

When you’re learning data science, the best projects are the ones you actually care about. For me, that project starts with a simple but exciting question: can I predict the price range of houses in Amsterdam?

With so much data out there and countless questions to explore, choosing the right one doesn’t just spark curiosity - it fuels motivation and helps you build real, lasting skills.
For me, that question is:

“Can I predict the price range of a house listing based on its features?”

My motivation is twofold:

Personal interest: I’m genuinely curious about house prices, especially as someone who might buy again in the future.
Living in Amsterdam, where the housing market is famously wild, I wanted to find ways to cut through the clutter and understand what really drives asking prices.

Skill growth: at the same time, I see this as the perfect opportunity to stretch myself as a data scientist.
Instead of focusing on one narrow part of the process, I want to build an end-to-end product: from scraping raw data to cleaning and modeling, and then serving predictions via an app.

Since I’m based in the Netherlands, and most housing listings live on Funda.nl
, I’ll be collecting data from there.

## What I Hope to Learn (and Share)

![Project Pipeline](/assets/project_pipeline.png)


This project isn’t just about predicting prices - it’s about practicing the full lifecycle of a data product. Along the way, I hope to sharpen (and share!) skills in areas like:

+ Project planning & scoping - breaking a big idea into smaller, manageable phases.

+ Data collection & web scraping - navigating HTML, extracting the right fields, and making a scraper that’s respectful and robust (rate limits, retries, logging, etc.).

+ Data cleaning & exploration - handling messy real-world data, filling in missing values, and doing exploratory analysis to understand housing price patterns.

+ Machine learning modeling - experimenting with regression algorithms, tuning models, and predicting price ranges instead of just single values.

+ Backend development - serving the model via a REST API built with FastAPI.

+ Frontend development - building a simple UI (Streamlit or React) so users can try the model themselves.

+ DevOps & deployment - containerizing with Docker, setting up CI/CD, and deploying to the cloud so it’s usable outside my laptop.

+ Documentation & communication - writing things down clearly (README, blog posts, slides) so others can follow along or build on it.

## The Project Plan

To stay organized (and avoid letting this spiral into a never-ending side project), I broke the work into seven phases. Each phase builds on the previous one, taking the project from an idea to a deployable app others can try.

+ Phase 1 - Define & Prep (1 week)

Lay the foundation: clarify the scope, explore the data source, and set up the development environment. This includes choosing the tech stack (Python, FastAPI, Streamlit/React), identifying which Funda pages to scrape, and setting up version control + virtual environments.

+ Phase 2 - Data Collection & Cleaning (1-2 weeks)

Build a scraper that plays nicely with Funda’s rules, collect at least 1000 listings to start with, and clean the dataset. That means handling missing values, normalizing formats, and doing exploratory data analysis (EDA) to understand distributions and correlations.

+ Phase 3 - Modeling & Evaluation (1-2 weeks)

Train machine learning models to estimate a property’s asking price range. I’ll start with regression algorithms like Linear Regression, Random Forest, and Gradient Boosting, and compare them using cross-validation and hyperparameter tuning.

+  Phase 4 - API & Backend (1 week)

Expose the trained model via a FastAPI backend. This includes endpoints like /predict (price range prediction) and /scrape (on-demand scraping). I’ll also containerize the backend with Docker for easier deployment.

+ Phase 5 - Frontend & User Interface (1 week)

Build a simple interface so users can input property details (or a Funda URL) and get predictions. I’ll either use Streamlit (for speed) or React (for more flexibility).

+ Phase 6 - Testing, Logging & Deployment (1 week)

Make the app production-ready: add tests, error logging, and deploy the backend + frontend to the cloud. Ideally this includes CI/CD, domain setup, and SSL.

+  Phase 7 - Documentation & Portfolio Prep (1 week)

Wrap things up by polishing the GitHub repo, writing clear documentation, and preparing portfolio materials, like this blog series, a demo video, or a slide deck.

## Final Thoughts (for Now)

Of course, new ideas or unexpected challenges will come up and that’s part of the fun. When they do, I’ll adapt the plan as needed.

For now, this feels like a solid kickoff point. If you’ve made it this far: thank you for reading! I hope this series is valuable not just for me, but also for you; whether you’re curious about house prices, end-to-end data science projects, or just like watching a good build-in-public story.

In the next post, I’ll share how I set up my environment and explored Funda’s site structure, the very first step in turning this idea into something real.
See you there! 👋
