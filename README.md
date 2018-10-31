# Seeking Help Like a Responsible Programmer

## Learning Goals

- Identify help request patterns of development

## Introduction

Many developers have written posts to Stack Overflow dozens of times, but only
submitted a few. Usually, in taking the time to be methodical and ask a Good
Question, they find the answer on their own. The trick that makes this work is
_being methodical_. Let's see how that method works, step by step.

### Identify Help Request Patterns of Development

When we developers come to a point in our programming where we need to ask for
help, we follow a process similar to the problem-solving process we've already
discussed. We:

1. Focus in on the relevant piece of code
2. Identify the inputs, outputs and expectations we hold
3. Theorize what should happen or what might be going wrong
4. Check documentation
5. Test small segments of our implementation in test programs / REPLs (like IRB)

If we're diligent in these steps, the problem usually popus up and we don't need 
to ask for help. If the reason still isn't forthcoming we have a
perfectly-formulated question to send out into a professional coding community
like Stack Overflow.

- **Begin with a focused section of code.** Avoid posting too much code. Professional
programmers have very little time. If you've not done any work to help yourself,
they won't bother to help. Show, by asking well-formulated questions,
that you tried to help yourself. When coding community visitors see screen
after screen of pasted code they usually reach for the "Close Tab" button.
If you struggle to narrow down the bit that causing you trouble, that
tells you that you might need to ask a larger, more fundamental question.

- **State your inputs.** What are specific values you are putting into your
code? Someone reading your question might not have your programming language
installed or they might be on a slow network. Make sure they have the facts handy
so they can mentally "play" your code.

Inputs are important factors you want to be able to identify and express,
because the error might be there.

- **State your outputs.** Similiarly, identifying what values you're getting as
a result will help pinpoint a potential error and help a programmer "trace" your code.

- **State your expectation.** What result did you think you would get? This
step is the best way to clarify your original goal, which will help both you and
whoever helps you make sure you work towards the correct solution.

- **State your theory for what should have happened.** This closely aligns with
the previous step, "state your expectation," but remember that not only do you
need to know _what_ result you want, you need to understand _why_ that result
should happen. That's how you can better spot errors and make corrections.

- **Check the documentation to make sure your implementation works as
expected.** All developers have been in a position where they thought
something worked a certain way, but in fact did not. Double-check all the
available documentation for whichever tool or technique you're using so that you
can eliminate that as a contributing factor to the current issue.

- **Test the implementation in IRB.** IRB is a great playground. Test parts of your
implementation there so that you can see how the pieces work in practice. Even
senior developers often find themselves entering:

```ruby
x = [1,2,3]
z = []
...
```

So that they can be sure they understand some method (in this case, probably an
`Enumerable` or some aspect of an `Array`).

- **Submit the question (if necessary).** As we said before, often going
through these steps will uncover any problems. But if you still need help, now
is the right time to ask for it.

- **Be polite.** Phrases such as "I'm new to..." or "I can get this to work in
(other language)" help your collaborator gauge their response. Always thank the person
who provides the winning response and mark their response as "correct." Keep in
mind that your questions will stay on the site long past your coding snag. Future
employers can decide a lot about how you present yourself and what kind of person
you are to work with from these questions. Leave your best impression, always.

## Conclusion

Generally, methodical description and documentation will help you see your bug.
If it doesn't, all of the information you gathered, tested and referenced will
help others know how to guide you to the answer you need.

## Resources

- [Stack Overflow: How to Ask](https://stackoverflow.com/help/how-to-ask)
