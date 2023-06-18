# recsys-app
Azure-based proof of concept for recommendations in a consumer app.

# Abstract
I've read about recommender systems and experimented with model fitting and evaluation using simulated data and popular datasets (e.g., MovieLens). To help bring the concepts to life for myself and learn through direct experience, I'll build a simple consumer-facing application that lets real users create an account, set preferences, browse a catalog of items, and "purchase" sets of items.

# Goals

- Architect and build a (simple, proof-of-concept scale) web application
  - authentication
  - user profiles
  - dummy items, e.g., grocery items with representative metadata 
- Choose an initial baseline system to compute, store, and serve user-to-item recommendations
- Implement and/or learn best practices for how to instrument the web app with enough analytics to support both recommendations and reporting of recommendation performance to non-technical stakeholders

# Architecture

