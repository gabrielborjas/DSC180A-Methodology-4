---
layout: default
---

# Gabriel Borjas-Perez

- **UCSD email:** gborjasperez@ucsd.edu
- **Section:** D40
- **Mentor:** Jun-Kun Wang

## Quarter 2 Reflection

**What is the most interesting topic covered in your domain this quarter?**

I thought it was interesting that we could use a betting method to check
for differences in how a model performs across groups as new predictions
come in. In our project, that means checking whether the income model
correctly identifies people who earn over $50,000 at similar rates for
men and women.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to see how quickly the audit picks up a gap in recall that
lasts compared with one that only shows up for a short time. We could
simulate both cases using the Adult Census Income dataset and compare
how many records the audit needs before it flags a difference.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

I would run the audit several times with the same records in different
random orders. That would help us see how much the detection time
depends on which records come in first.

**What other techniques would you be interested in using in your project?**

I would like to try a permutation test that checks for a difference in
recall after a fixed number of records. It would give us a baseline to
compare with the betting method when both have seen the same amount
of data.
