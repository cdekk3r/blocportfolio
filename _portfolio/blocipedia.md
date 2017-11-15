---
layout: post
title: Blocipedia
feature-img: "img/sample_feature_img.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/1686132/webflow_landingpage_1x.jpg"
short-description: An app that allows users to create public or private markdown-based wikis as well as collaborate with others.

---
<h2>Summary</h2>

Blocipedia is a application where users can submit markdown wikis and collaborate with others. Created with Ruby on Rails similar to my Bloccit project it showcases my progress in learning Backend development.

<h2>Explanation</h2>

Blocipedia is my first project after completing the Bloc backend foundations course. The Bloc curriculum provides very minimal instructions, if any, leaving me to decide what way I want to implement features.


<h2>Problem</h2>

Each checkpoint assignment requires a new feature be added. For the most part it involves using a new gem to complete the task. For example, using the Redcarpet gem for markdown formatting.

<h2>Solution</h2>

- The Devise gem is used for authentication. This handles sign-up, sign-in, and sign out functions. I have also added the comfirmable feature of Devise so users can have comfirmation e-emails resent upon sign-up.
- Authorization will be controlled with the Pundit gem. Users will have the ability to create public or private wikis depending on role on whether they are a standard or premium user respectively.
- To upgrade a user will need to make payment through the Stripe gem. When a user downgrades all created private wikis will revert to public. 
- Markdown formatting is available via Redcarpet.

<h2>Result</h2>

**Features**

- Users can create new account with email and password. 
- Confirmation e-mails are sent upon account creation.
- A standard user can edit any public wikis, but only delete their own.
- A standard user can upgrade to premium at which point they will gain the ability to create private wikis.
- A premium user can downgrade to standard making all private wikis public.
- Deleting a user account will delete all associated wikis.
- Users can also add collaborators to give access to private wikis.

<h2>Conclusion</h2>

Upon completion of the project I feel I've reinforced my knowledge of Backend development. After having to use multiple different gems I feel much more confident with the process. I have to admit taking on a project such as this with
minimal instruction is daunting and I hope to become more comfortable with the creative freedom I'm given on future projects.