# causal-ML

This topic really intrigued me while I was working on a marketing usecase last summer at a real estate company. 

What is Causal ML and how is it different from traditional ML?
With traditional machine learning we predict targets, but Casual ML helps us understand *why* those targets occur. This is extremely useful in various domains such as a real estate company(to increase conversion rates), healthcare company(to treat patients effectively) and more.

I'll use the example of a real estate company targeting to increase prospect conversion rates to explain the concepts of Causal ML.

**Example of Causal ML**
If a prospect ends up signing lease and moving into an apartment, Causal ML helps us understand whether it was because they received a phone call, an email, or something else.

### Some Key Terminologies in Causal ML

- **Treatment**
A treatment is any specific action taken to influence behavior. In our example, treatments include personalized calls, offers or targeted email campaigns. Prospects who receive the action are called treated group.

- **Control Group**
These are prospects who *do not* receive the treatment. They might wanted to checkout the property as its in their neighborhood. This group helps us understand what would have happened without any action.

- **Causal Inference**
This helps us understand what actually caused a change in behavior, was it a specific treatment? Answers the most important question - "Did this really make a difference?"

- **Propensity Modeling**
This gives us the probability that a specific prospect will be chosen for a treatment.

- **Uplift Modeling**
Uplift modeling predicts *who* is likely to change their behavior - either positively or negatively because of the treatment.

### The Four Response Groups
In industry practice, in Causal ML there are four response groups which is classified based on how they react to treatments:
- **Persuadables**
Convert *only* if treated (e.g., they signed a lease only because they got a call).
- **Sure Things**
Convert *irrespective* of being treated (e.g., highly interested buyers, we need not do anything about them).
- **Lost Causes**
They *will not* convert, regardless of any treatment (e.g., not interested at all, there is nothing we could do about these group either).
- **DND**
They convert *only if not treated* (e.g., not very likely but sometimes people get irritated by outreach and decide not to buy).


This method helps us to go beyond simple prediction to actually influencing the outcomes, thereby making marketing and sales efforts more impactful and efficient.
