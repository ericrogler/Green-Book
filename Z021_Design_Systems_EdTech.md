---
title: 29. Design Systems and EdTech
layout: default
nav_order: 31
---
# Design Systems and EdTech

### [Previous Chapter](Z020_The_Use_Of_AI_And_Technology.html)

## **Short Answer**

**From Unknown**
> “Any idiot can build a bridge that stands, but it takes an engineer to build a bridge that barely stands.”
- *Finding the source for this quotation is a Herculean task, so if someone does know the original source, let me know.*

Everyone is a designer. Not everyone is a *good* designer.

Even if you can design well, you'll still deal with people management issues, managing upwards, and designing communication.

A complex design is always worse than a simple design if they perform at the same effectiveness/efficiency. Complex designs are more prone to failure compared to simple designs. 
- [Dr Richard Cook in *How Complex Systems Fail*](https://how.complexsystems.fail/) does a much better job than me succinctly describing complexity issues across multiple industries (2000).
- Keep it simple, stupid.

**Your most important question is "Why?"** Jumping straight into work is almost always a bad idea. Acquire information and context when able *before* working or you risk wasting time.
- What people actually do is worth more than what people say they do.
- Plus, sometimes all it takes is listening to or watching someone to find out nothing "fancy" was needed.

## **Long Answer**

There are two main things to cover in this chapter: design patterns and design systems. The latter is explained far more in-depth later here whereas the former can be summarized pretty neatly with an example.

Design patterns are reusable solutions to commonly occuring problems with specific contexts.

...You know. Math formulae. Algorithms. Lists of instructions. The fun stuff.

As an example: You want to make a cake.

Your problem is you need to make a cake. 

You have a recipe that *could* solve this problem; a method you can use to make a cake and many more cakes like it down the line. You recognize and recall that this recipe can make this cake, or solve the problem, and then reason through the steps to get from problem to solution.

The recipe, or design pattern alone, will get you most of the way through. 

*Most of the way.*

What may stop you are additional variables, such as elevation affecting baking time or substituting ingredients. They're a non-issue at best or a show-stopper (the bad kind) at worst. If you understand the pattern well enough and its underlaying mechanics, or *why* a recipe uses specific ingredients in specific ways, then you can also recognize where issues arise and what/how to adjust the recipe to still bake your cake.

When all is said and done, someone eating your cake evaluates based on the end result; taste, texture, appearance, etc. It could have the best process of all time, but that process doesn't mean anything if the cake tastes bad. This is why you want simplicity whenever possible because it saves you time and headaches, plus your consumer likely remembers the cake's taste far more than the cake's preparation.

That one recipe can make that one cake. You may reuse ingredients, but need a different recipe to make a different cake or another dessert altogether. Despite this, you still pull from recipes you know (the design patterns) to help solve problems.

If you're familiar with software, you may recognize the terms DSA, data structures, system design, and algorithms. Concepts from there are pretty close to what I'm getting at here!
- *And another reason you should learn math, like I said in earlier chapters!*

### **Things to Keep in Mind**

Understanding design systems translates directly into skills across multiple fields and helps with templating, creating reusable components and materials, and making it easy to change things. 

You're usually better off quickly pushing designs, testing (one at a time to save sanity), and iterating than remaining stuck on one perfect design. This means, when in doubt, stop overthinking and design something that just works and don't touch it again unless absolutely necessary. Sometimes the attempt to make it better actually makes it worse and sometimes a new piece of technology isn't the correct answer. 

For technical designs, like charts and graphs, you could save time and solve most of your business questions by asking if someone needs to import data to Excel (or another similar spreadsheet software).

No single breakthrough makes the work easier, as difficulty is often found in the *problem* instead of the *tools.*

Lastly, despite how well something is designed, human error and accidents will occur and you'll always have to make tradeoffs.

### **The Weird Complexity (and Simplicity) of Design Systems**

Per Chad Bergman on Figma’s blog (2024) ([Further Reading](https://www.figma.com/blog/design-systems-101-what-is-a-design-system/#what-exactly-is-a-design-system)):

> A design system is a set of building blocks and standards that help keep the look and feel of products and experiences consistent.

For those with less artistic backgrounds or lacking design skills, don't worry. You don't need to become a design expert to teach, instruct, or present, but I will ask you to see what a design system is and what it tries to accomplish.

If you've ever played with Legos, used power tools for construction, or questioned why you keep losing the 10mm socket for bolts and nuts used across various products, you're dealing with something akin to a design system: consistent and reusable parts.

Done correctly, **a design system accomplishes several goals**:
- A single source of truth
- Rules, standards, and styles definitions
- Libraries of reusable components
- Consistency across all products
- Reduced redundancy
- Increased accessibility

**Design systems are typically utilized in one of three ways: Adopting, Adapting, and Creating.**

**Adopting** takes a design system and adds it into your current system(s) without changes.
- Example: You copy and follow a cake recipe as is, step-by-step, exactly as written.

**Adapting** takes a design system and changes parts and pieces to fit it into existing system(s).
- Example: You follow the cake recipe, but have to substitute in gluten-free flour, vanilla for chocolate, or use a pan instead of a Dutch oven for part of the recipe..

**Creating** borrows from no design system and makes a new system from scratch.
- Example: You don't like the current cake recipe(s), so you made your own cake recipe.

Each option has benefits and drawbacks. Adoption is typically the cheapest, but least flexible and hardest to change. Creation is typically the most expensive, but most customizable. Adaption sits in between Adoption and Creation in cost and customization to suit your needs.

If you're unsure whether to adopt, adapt, or create, consider the amount of creative freedom or control you need over your system. Adopting suits low creative control, Adapting suits moderate creative control, and Creating suits high creative control.

### **How Design Systems Relate to Teaching**

Think of design systems as curricula. Let me draw some parallels they share:
- Defined Standards
- Libraries of resources
- Permits edits and updates
- Templates and reuseable materials
- Organizational Hierarchies
- Collaboration to create one
- Shared vocabulary
- Longetivity and reusability

**If you're starting fresh, here are some pointers. This applies to both curricula and design systems:**
- Do whatever makes the most sense for your use case(s) and audience.
  - If it doesn't make sense, then no one's going to want to stick with it.
- Look up actual design systems. Some examples are linked below:
  - [https://designsystem.digital.gov/](https://designsystem.digital.gov/)
  - [https://atlassian.design/](https://atlassian.design/)
  - [https://m3.material.io/](https://m3.material.io/)
  - [https://developer.apple.com/design/](https://developer.apple.com/design/)
  - [https://developer.apple.com/design/human-interface-guidelines/](https://developer.apple.com/design/human-interface-guidelines/)
  - [https://www.designsystems.com/](https://www.designsystems.com/)
- If you want to make good designs, you have to start designing.
- Learn not to fall in love with your work, because change is likely and sometimes forced.

### **Environmental Constraints**

There's two other constraints to design systems.

The first one is you may have to design something that accommodates *another* design. You may design a machine that looks amazing and does a great many things... but there's a catch. You have to use a specific set of screws, fasteners, and more, which are strictly defined and standardized to the point custom versions of these parts are extremely expensive. The environment may also restrict *how* you can design something, which is another cost.

A more practical example in 2025 may be smartphone applications. In the links above, there were various examples of design systems. If you were to make your own application on their software/hardware, you also have to obey the rules of their design systems. You may have to design menus a certain way, have animations function at specific timings, and have interactions be consistent with how the phone is normally utilized. That's only a few examples out of countless many, as compliance ensures your product functions as intended in the environment it is presented and utilized in.

Another environmental constraint I've experienced is when you need to do "field modifications." This may be issues with how a product looks on paper vs real life, it could be issues between professions like architects and engineers or designers and developers, and engineers and machinists, or just "the plan didn't cover this, what do we do?"

In cases like these, you may have to make an educated guess based on what is feasible and what is allowed. One example may be you received 2x6 planks when you need 2x4 planks, but you know you have a table saw around to cut down a 2x6 into a 2x4. Another example may be you need a tool or part to complete something, so you decide to peruse the environment and subsist on a potentially questionable, but surprisingly effective, "fix" to solve the problem at hand.

The general lesson is this: you can do a lot of things on paper, but not as many things in practice. When in doubt, try to create *practical* prototypes to ensure the theory is as close to practice/real-life as possible.

### **The Penthouse Software "Suite"**

Chances are you have purchased a product made by a particular company.

There's also a chance that same company has products compatible with what you currently have, but not compatible with similar products made by a different company.

If you're wondering why they aren't cross-compatible, it's because they want you, the consumer, to buy *their* products and not their competitor's products. Why should I let you buy 1 of my products and 1 of another company's products, when I can get you to buy *2* of my products so I can earn more income?
- *The answer is it also costs money, but I'll pretend I didn't answer it here.*

This can occur in software, hardware, a custom bed for man's best friend, the cardboard box, a stack of paper. You name it.

A company can do a lot of things to get you to buy their products: 
1. They can make one product exceptionally well you'll want for a long time. 
2. They can make one well-made product to get you into the door, then offer other items to keep your interest over time. 
3. They could offer a product which functions well, but also make a separate service tied to that specific product. 
4. They can also make a large variety of products to try and suit many needs so they become your one-stop-shop for goods.

A "suite" as the title implies mainly concerns software and items 2 and 3 in the list above. It's a set of software where each "software" in the set forms a "suite." You could purchase parts of a suite or the full suite, but you could be forced to buy the whole suite.

At the end of the day, a suite is an anchor to get you to use and purchase the companies products. The setup of a suite also makes it so as long as you really like at least one or more products in said suite, you might pay for a bundled price despite not utilizing part of a suite.

It's like a penthouse suite in real life. It comes with a lot of features you may or may not use during your stay, but you pay the price for the *opportunity* to have all these features bundled up nicely for you in case you *do* want to use them.

### **What about EdTech?**

Many rules and concepts you find in design systems, you'll find in EdTech and other digital and physical mediums. Some tools are well-designed and others are not. Quality typically improves over time, but gaps and deficiencies persist between iterations of new products.

Sometimes you're forced to use particular software to accomplish your goal. Software is a tool to achieve a task or solve a problem you have and you'll be better off knowing how to use a tool than not knowing how to use a tool. With tools, however, you won't get better with them unless you use them.

### **What if I cannot find problems with designs?**

*Alternatively: Heuristics and Heuristic Analysis*

You'll rarely, if ever, find something with *zero* issues in any way, shape, or form whatsoever. If something without *any* problems exists, then it'll probably stand the test of time for many years to come.

One common reference around for some time now is [Jakob Nielsen's *10 Usability Heuristics for User Interface Design*](https://www.nngroup.com/articles/ten-usability-heuristics/) (2025). They're rules, rather than guidelines, which is unlike what you might hear from pirates in the Caribbean. The intent of the rules is to make product easier to use and reduce cognitive load on users as they're utilizing products.

As for specific problems in general, there's countless amounts. To give a small set of examples:
- Functions without defined intents
- Readability issues
- Inconsistency
- Redundancies
- Help documentation is lacking
- Errors are permitted instead of prevented

The issues you'll find vary widely on the context and product they're located inside of. Some issues may have acceptable ranges (tolerances) which are wide or narrow depending on requirements.

### **How to Measure "Impact" (Metrics of Success) of Designs?**

This is a complicated question. 

The biggest thing is you don't want to lie about any impact and throw out random numbers. The lie quickly becomes apparent under scrutiny and you risk losing trust, influence, and even your position in a group.

A hidden reality is a lot of design work may not be "shipped" or available for use by customers or businesses. Because they are not readily available, collecting data for business metrics isn't easy, if even feasible, for someone below a director-level position or outside a data adjacent position (Scientist, Analyst, Engineer, etc.). This typically means many designers, or someone generating designs, may not have significant influence and impact at a company level.

The question shouldn't be how to provide business metrics to demonstrate success. It should be how to display the quality of decision making and problem solving and what you *should* use to prove your designs are good. While you could be in a position to acquire data to enforce decisions, if you're in an organization they may strictly limit who can access what data and manipulate it.

I'll go over what could still be answered while assuming you're in a position you cannot acquire hard data.

1. How would you measure success of the design (i.e. what you *would* use, not *did* use)?
2. What problems occurred during research into the design?
3. What are potential solutions we can implement?
4. What were the results from any tests you set up and ran on your designs?
    - Additionally, how did those tests influence decisions going forward? 
5. What processes worked and what processes didn't work?
6. What were the outcomes along the way during the design process?
7. What did you learn about?

Even for work that's never shipped, a project with sufficiently high quality design work is still a signal to show there's potential impact if it were shipped.

### **What if I Need to Find/Design Something?**

There's some questions you should ask beforehand.

1. Who is it for?
2. What problem does it solve?
3. Can it be used in your current setup, system, etc?
4. What benefits does it provide over another option?

If you don't know who is going to utilize what you provide, you risk them not using it, refunding it, or disliking the provider; you. If you cannot figure out what problem it's trying to solve, it's like using a band-aid for a non-existent wound and may not be that useful. If it cannot be used alongside your other products, or get buy-in from people to adopt it, it doesn't matter how good the solution is if it cannot be used. Lastly, if it doesn't provide benefits other another option, then why should someone use what you make?

### **I don't have much design experience though!**

Two things before you panic.
1. You can "design" in programs such as PowerPoint, Excel, and Microsoft Word or their equivalents in Google Documents, Google Sheets, and Google Slides as well. 
    - If you need advanced design programs, you'll need to look into dedicated design tools like Figma, ProtoPie, Photoshop, Illustrator, and Sketch.
2. You're likely focused more on content, the delivery of content, and the management of students rather than design anyway. If you lack time or resources, learn just enough to get by and supplement your teaching.

Some general rules of thumb you can quickly apply come from personal experience as well as reading through *Refactoring UI* by Wathan and Schoger (2025).

- Never rely on color alone
- Start simple and ensure functionality before adding complexity
- White space is easier to reduce than add
- Text needs sufficient contrast (e.g. WCAG "AA" rating or higher) against its background
- For colorblind people, it's easier to tell by lightness (light/dark) rather than color
- Most greys have tints of other colors mixed in

## **Bibliography**

1. Apple Inc. (n.d.). *Apple design*. [https://developer.apple.com/design/](https://developer.apple.com/design/)

2. Apple Inc. (n.d.). *Human interface guidelines*. [https://developer.apple.com/design/human-interface-guidelines/](https://developer.apple.com/design/human-interface-guidelines/)

3. Atlassian. (n.d.). *Atlassian design system*. [https://atlassian.design/](https://atlassian.design/)

4. Bergman, C. (2024, February 12). *Design systems 101: What is a design system?* [https://www.figma.com/blog/design-systems-101-what-is-a-design-system/](https://www.figma.com/blog/design-systems-101-what-is-a-design-system/)

5. Cook, R. (2000). *How Complex Systems Fail.* how.complexsystems.fail. [https://how.complexsystems.fail/](https://how.complexsystems.fail/)

5. Design Systems. (n.d.). *DesignSystems.com*. [https://www.designsystems.com/](https://www.designsystems.com/)

6. Fessenden, T. (2021, April 11). *Design systems 101*. Nielsen Norman Group. [https://www.nngroup.com/articles/design-systems-101/](https://www.nngroup.com/articles/design-systems-101/)

7. Google. (n.d.). *Material 3 design system*. [https://m3.material.io/](https://m3.material.io/)

8. TV Tropes. (n.d.). *Kansas City shuffle*. [https://tvtropes.org/pmwiki/pmwiki.php/Main/KansasCityShuffle](https://tvtropes.org/pmwiki/pmwiki.php/Main/KansasCityShuffle)

9. U.S. General Services Administration. (n.d.). *U.S. Web Design System*. [https://designsystem.digital.gov/](https://designsystem.digital.gov/)

10. Wathan, A., & Schoger, S. (2025). *Refactoring UI*. Tailwind Labs Inc. [https://www.refactoringui.com/](https://www.refactoringui.com/)


## **[Next Chapter](Z022_Action_Plan_Week_1.html)**