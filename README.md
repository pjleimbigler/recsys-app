# recsys-app
Azure-based proof of concept for recommendations in a consumer app.

# Introduction
I've read about recommender systems and experimented with model fitting and evaluation using simulated data and popular datasets (e.g., MovieLens). To help bring the concepts to life for myself and learn through direct experience, I'll build a simple consumer-facing application that lets real users create an account, set up some preferences, browse a catalog of items, and "purchase" sets of items.

# The App

To give myself a concrete domain to learn in, I'll go with something that practically everyone has experience with: **groceries**. Let's build an app that simulates a grocery purchasing portal. The recommendation module suggests groceries to users based on their past purchases, stated preferences (e.g., dietary restrictions, special nutritional needs, health or fitness goals, favourite foods or flavours), and what similar users buy.

# Goals

- Architect and build a simple, proof-of-concept web application
  - authentication
  - user profiles
  - dummy items in a domain amenable to recommendations
- Choose an initial baseline system to compute, store, and serve user-to-item recommendations
- Learn enough frontend development to be dangerous
- Implement and/or learn best practices for how to instrument web app with analytics to support both recommendations and reporting of recommendation performance to non-technical stakeholders
- Learn about Azure-specific implementation choices

# Process

- Track features in [GitHub Projects](https://github.com/users/pjleimbigler/projects/1)
- Architecture diagram in diagrams.net