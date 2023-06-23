---
title: How we style our dbt projects
id: 0-how-we-style-our-dbt-projects
---

## Why does style matter?

Style might seem like a trivial, surface-level issue, but in fact it's a deeply material aspect of a well-built project. Consistent, clear style enhances readability, which in turn makes it easier to understand and maintain your project. Highly readable code will make it easier for you to build clear mental models of your project, which will make it easier for you to debug and extend your project. It's not just a favor to yourself though, equally importantly, it makes it easier for others to understand and contribute to your project, essential for peer collaboration, open source work, and onboarding new team members.

## What's important about style?

There are two crucial tenets of code style:

- Clarity
- Consistency

Style your code in such a way that you can read your code quickly and understand it. It's also important to consider code review and git diffs. If you're making a change to a model, you want reviewers to be able to see just the material changes your making clearly.

Once you've established a clear style, stay consistent. This is the most important thing. Everybody on your team needs to have a unified style, which is why having a style guide is so crucial. If you're writing a model, you should be able to look at other models in the project that your teammates have written and read the same style. If you're writing a macro or a test, you should see the same style as your models. Consistency is key.

## How should I style?

You should style the project in the way you and your teammates or collaborators agree on. The most important thing is that you have a style guide and that you stick to it. This guide is just a suggestion to get you started and to give you a sense of what a style guide might look like. It covers various areas you may want to consider, with suggested rules. It emphasizes lots of whitespace, clarity, clear naming, and comments. We belive one of the strengths of SQL is that it reads like English, so we lean into that declarative nature throughout our projects. Even within dbt Labs though, there are differing opinions on how to style, even a small but passionate contingent of leading comma enthusiasts! So again, the important thing is not to follow this style guide, it's to make _your_ style guide and follow it. Lastly, be sure to include rules, tools, _and_ examples in your style guide to make it as easy as possible for your team to follow.

## Automation

Use formatters and linters as much as possible. We're all human, we make mistakes. Not only that, but we all have different preferences and opinions while writing code. Automation is a great way to ensure that your project is styled consistently and correctly and that people can write in a way that's quick and comfortable for them, while still getting perfectly consistent output.