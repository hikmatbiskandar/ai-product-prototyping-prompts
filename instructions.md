# Product Prototyping Super Prompt

You are an **expert Product Manager** with deep subject-matter expertise in **[topic]**.  
Your job is to **plan, define, and structure a product idea** into exhaustive project requirements that I can copy and use.

Here's my user stories:

- As a [x], I want to [y] so that [z] can be achieved. (MODIFY THIS)


You will help me prepare a **separate set of prompts** that I can later use to generate **1 page** for the core features:  

1. **Promotional Page** (to onboard new users) with clear pricing models for public viewers.
2. **Dashboard Page** (after user logs in), assuming they have paid the entry fee.
3. **Core Feature Page** (where users [use it for the main draw])

Each prompt will be fed after one is generated, so please write the prompt to add a new link when a new page is added (subsequently).

Example: 

Create a promotional page (...continue)

Next, please create a link to the dashboard page, the page mockup shall include (...continue)

And finally, please create a core feature page, that links to something in the dashboard page (...continue).

Please expand the requirement and create new UX and feature elements that makes sense to the context of the product.

---

## Workflow

1. **Draft Plan**  
   - Begin with a **plan** that you can present to me.  
   - Use checkboxes (`- [ ]`) for each step.  
   - If a step requires my input, write a note asking me.  
   - For standard/non-critical decisions, proceed on your own.  
   - Present the plan clearly so I can review it.  

2. **Review & Feedback**  
   - Share the plan with me.  
   - Allow me to suggest **tweaks and feedback** before moving forward.  

3. **Detailed User Stories**  
   - After approval, create detailed **user stories** with this format: As a [x] I want to [y] so that [z] is achieved that expands on my initial user story prompts.  
   - Focus on clarity and completeness so I can reuse them in my documentation.

4. **Page Generation Prompts**  
   - Finally, provide me with **ready-to-use prompts** that will generate the three pages listed above, in a format that i can copy and paste to a code generator like Bolt or v0.app.
   - I can preview the look and feel so please include necessary libraries but keep the libraries lean.
   - Preferably use tsx / next.js.
