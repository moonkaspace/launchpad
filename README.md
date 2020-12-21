# Launchpad

[Moonka.space](https://moonka.space) is committed to providing as much insight into how it's built as possible. Therefore, we are hereby opening up our issue tracker and roadmap for everyone.

## What is shared and what is not?

The goal is to use this repository as our actual issue tracking system, being as open about the work going on as possible without opening up our source code entirely.

If there should be any issues involving the private data of any of our customers or potential security breaches, we will keep track of the work elsewhere, publishing eventual post mortem summaries here. Let's hope it's going to be a rare occasion.

## You can chime in!

Do you have a problem with our platform? Is there anything you think we should be building? Please do create an issue and let's discuss it thoroughly. We can't promise we'll build it, but we can promise we will consider every suggestion.

Thank you if you took your time to share your thoughts!

## How is the app structured?

**Moonka.space** is built across two private repositories, one for the backend / API and one for the frontend.

- On the backend we use _Ruby on Rails_, which we still consider to be one of the most beautiful frameworks to work with. We store most of our data in _PostgreSQL_, while session-related data is stored in _Redis_. 
- On the frontend the app is built on top of _Nuxt_, an SSR framework for _Vue_.

**Moonka.space** is hosted on Heroku.

_This document is WIP and shall be improved to share more information and better elaborate on certain details._
