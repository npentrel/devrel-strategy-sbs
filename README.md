Developer Relations Strategy - *Step By Step*
----------------------------------------------

You have stumbled upon the guide to creating a strategy for your (team's) developer relations work.

## The summary
A strategy is a framework for understanding what the right thing to do is and a tool for knowing roughly how you are going to achieve your goals.
In this guide I will take you through multiple steps. The first step will be the creation of an **analysis of your current situation**. From there we will discuss what your **overarching goals** and themes for the upcoming quarter(s) will be. Finally we will guide you through **setting SMART goals**.

## What will I get out of it?
You will get a concise set of documents that document your team's focus areas, strategy, and goals. These documents will be a valuable resource for the team and other stakeholders.

- **Written assessments of your products.** This includes target audiences, the product landscape, competitors etc.
- **Written documentation and analysis of your current initiatives.** This includes short summaries, goals, who is involved and responsible, and how well things are going.
- **Defined themes for the upcoming months.**
- **Defined strategies and goals on a per initiative level.**
- **A written overview of where your team sits in the company.** This will detail stakeholders as well as teams that you closely work with along with their goals.
- [optional] **Better knowledge of how your team likes to work together.**

## Structure

This guide is set up for the person leading the training. Within each step you will find a readme that contains outcomes, an introduction, preparation todos, the tasks, as well as some helpful notes. Below you will find a brief overview of each section. You can also find helpful notes on the schedule, ideas for energizers etc. in the [Schedule, Energizers, etc. folder](/Schedule%2C%20Energizers%2C%20etc.).

##### [Step 0: Communicate well 🎤 [30 min] [_optional_]](/Step%200:%20Communicate%20well)
_While this is optional it is strongly recommended, especially if you have new people on the team!_

This exercise focuses on the team getting to know one another and outlining how they like to be communicated with. Each team member will create an instruction manual for themselves outlining preferred communication platforms, languages, project types, etc. This aims to help the team effectively work with one another and to give you a better idea what work your team members enjoy doing.

##### [Step 1: Know your org & products 🧐 [30 min + 60 min * number of products]](/Step%201:%20Know%20your%20org%20&%20products)
To start, your team will examine the org and teams around you, including their target areas. This will allow you to see and avoid overlaps in the following steps. Next, you will get to know your products more intimately. You will perform segmentation exercises for each product. Finally, you will document the findings to ensure a common understanding of each products target audience. You may find during this step that you start having ideas around new initiatives for certain products - write these down!

##### [Step 2: Know your team & initiatives 🙌 [180 min + 45 min * number of initiatives]](/Step%202:%20Know%20your%20team%20&%20initiatives)
In the previous step you got to know your org and products. Now, you will focus on the team. As part of this you will review _all_ current initiatives. These current initiatives will be documented to ensure a common understanding of current initiatives. You will also do a retrospective for each initiative and for the team's work as a whole.

##### [Step 3: Define themes 🧞‍♀️ [160 min]](/Step%203:%20Define%20themes)
You may have many current initiatives or many ideas for new initiatives. In this section you will define overarching goals or themes. These will in the next steps allow you to set more concrete goals. Best of all, this will give you a framework to decide whether you should spend time on X or not!

##### [Step 4: Define an event strategy 💃 [80 min]](/Step%204:%20Define%20an%20event%20strategy)
If your team does a lot of event work, it is advisable to create an event strategy. In this section you will analyze some events across different criteria and then work towards identifying the selection criteria that make sense for your team.

##### [Step 5: Set SMART goals 🏃‍♀️ [15 min * number of initiatives]](/Step%205:%20Set%20SMART%20goals)
Specific, Measurable, Achievable, Relevant, Timely. Those are the keywords that you need to keep in mind for this section. These SMART goals will describe what your team is planning to do in the coming quarter(s). Each project/initiative the team is undertaking should have some goals attached to it. You will also consider metrics in this section.

##### [Step 6: Documentation 📜 [2h]](/Step%206:%20Documentation)
Pull everything together. This is the last task for the person leading this workshop. In this, you will create an overall reference document/folder where your team's strategy is clearly defined. This will be invaluable throughout the next quarter's in keeping you goal-oriented. It will also be a good resource to have at hand when doing your yearly review!

### Preparation 👈

If you are planning to use this for a team planning workshop, I suggest you go through the entire step by step guide _before_ you start the workshop.

I suggest creating a team repository or a Google Drive folder for this session. This will allow you to keep all materials/documentation that you produce in one place.

##### Materials 🗝
- post-its & felt pens
- tape
- print outs of the materials for each section
- a small plush animal

### FAQ 🤔
**⏳ How long does the entire step by step process take?**
Here's a nifty formula that should give you an idea:

**`Time in hours = 8h + 1h * Number of Products + 1 * Number of Initiatives + break time + lunch time`**

**`break time = for every 4h calculate 1h as break time or buffer`**

**`lunch time = for every 7h add 1h for lunch`**

Or if you prefer a python 🐍 program:
```python
import math

def time_to_complete(num_products, num_initiatives):
  time_in_hours = 8.0 + 1.0 * num_products + 1.0 * num_initiatives
  # for every 4h calculate 1h as break time or buffer
  time_in_hours += time_in_hours/4
  # for every 7h add 1h for lunch
  time_in_hours += math.ceil(time_in_hours/7.0)+1
  return "{} days, {} hours".format(time_in_hours//8, time_in_hours % 8)

> time_to_complete(3, 9)
'3.0 days, 5.75 hours'
```

**👋 Can I contribute?**
Yes! Contributions are very welcome. Please create an issue to discuss what you would like to contribute first and then create a PR.

**💼 Can I use this in my company?**
Yes! Please note the `license.md` file. If you would like a professional dev rel consultant to help you I suggest you reach out to the fantastic [Matthew Revell](https://matthewrevell.com/), [Cristiano Betta](https://betta.io/), or [Mary Thengvall](https://www.marythengvall.com/about/).

**Is this for me?**
This guide features information and multiple exercises designed to help you define your (team's) strategy. You may find that some exercises fit better than others and that you need to add/change content for your team's needs.

**😳 Do we really need this?** Yes. Defining your strategy will help your team and your stakeholders understand what you are doing. It will give you the tools to see whether you are reaching goals and having the impact you want to see. On top of that, it gives your superiors a chance to understand what you are doing and why you are doing it. Hopefully this will ensure your team's value will be obvious (and avoid people thinking of dev rel as a sinkhole for monetary resources).

**👩🏼‍💻 Who are you?**
I'm [Naomi](https://twitter.com/naomi_pen) and I love thinking about processes and strategy. Personally, I think I do my best work when I see how my work aligns with strategic goals and when I can justify to myself and others why I am spending time doing X. To help with that, I created this guide for my team and for other teams to create a methodical approach to defining your developer relations strategy. Strategy is, of course, not the only thing I love. I also _love_ ✨ emoji ✨, [samoyeds](https://weheartit.com/entry/307342706), my niblings, and [writing](http://blog.naomi.codes/).

**Credits**
A lot of this content is drawn from resources the phenomenal DevRel community has provided. The training is based on training I received from [hoopy](http://hoopy.io) during DevRelCon.
