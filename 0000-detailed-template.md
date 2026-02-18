- Problem Name: (fill me in with a unique ident, `my_terrible_problem`)
- Start Date: (fill me in with today's date, YYYY-MM-DD)
- Problem Statement PR: [rust-lang/????#0000](https://github.com/rust-lang/????/pull/0000)
- Rust Issue: [rust-lang/rust#0000](https://github.com/rust-lang/rust/issues/0000)
- Rust RFC PR: [rust-lang/rfcs#0000](https://github.com/rust-lang/rfcs/pull/0000)
- C++ Standard Paper: [cplusplus/draft#0000](https://github.com/cplusplus/draft/pull/0000)

## Summary
[summary]: #summary

One paragraph explanation of the problem that users of Rust with C++ are having.

## Impact
[impact]: #impact

Focus on clearly defining the Rust and C++ interoperability problem, and its impact on developers.
This section should explain the problem in detail, including necessary background.
It should be factual, informative, and uncontroversial, supported by expert opinion.

It should also contain several specific use cases where users encounter this problem.
This can then be used to guide problem definitions and solution properties.

This section is one of the most important sections of the problem statement, and can be lengthy.

It should *not* propose specific solutions, that is the role of Rust / C++ change proposals.

## Related Problems
[related-problems]: #related-problems

Does this problem depend on any other prpblems being solved first? Do other problems depend on it?
Is it part of a larger group of problems?
Does solving this problem conflict with other problems?

## Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

Explain the problem as it is typically encountered by Rust / C++ programmers. That generally means:

- Introducing existing language, library, or toolchain concepts.
- Explaining the problem largely in terms of examples.
- Explaining how Rust and C++ programmers should *think* about the problem. It should explain the impact as concretely as possible.
- If applicable, provide sample language, tool or execution error messages.
- If applicable, describe the differences between the experiences of Rust programmers and C++ programmers.
- Discuss how this impacts the ability to read, understand, and maintain Rust / C++ code. Code is read and modified far more often than written; does the problem make code harder to maintain?

This section should focus on how compiler contributors should think about the problem, and give examples of its concrete impact.

## Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC. Explain the problem in sufficient detail that:

- Its interactions with other interoperability problems and existing language/library features is clear.
- Corner cases are dissected by example.
- Performance, compatibility, and usability issues are highlighted where relevant. 

The section should return to the examples given in the previous section, and explain more fully how the problem manifests in each example.

## Acceptance Criteria
[acceptance-criteria]: #acceptance-criteria

List the necessary and desirable solution constraints, without committing to any one solution.
If possible, they should be categorised by Rust or C++, and by language, library, or tooling.

Is are there any solution properties that are out of scope?

## Drawbacks
[drawbacks]: #drawbacks

What kinds of drawbacks are acceptable in any solution?
- Are there any unacceptable drawbacks?
- Which residual issues are acceptable after the problem is solved?

## Prior art
[prior-art]: #prior-art

Discuss prior art in relation to this problem.
A few examples of what this can include are:

- What previous solutions have been tried for this Rust / C++ problem?
- Does a similar interoperability problem exist in other programming languages, and how have they tried to fix it?

## Further Background
[further-background]: #further-background

- Papers: Are there any published papers or great posts that discuss this? If you have some relevant papers to refer to, this can serve as a more detailed theoretical background.
- Is there any other useful background information, that will help understand the problem?

## Experts & Champions
[experts-champions]: #experts-champions

Which experts understand the fine details of this problem?
Who is able to drive solutions on the Rust and C++ sides? (This can be an individual or a team.)

Link to documents and discussions that demonstrate community consensus on the problem: that it is current, important, and practical.

## Unresolved questions
[unresolved-questions]: #unresolved-questions

- What parts of the problem do you expect to resolve through the problem statement process before this gets merged?
- What parts of the problem do you expect to resolve through further analysis, expert consultation, or experiments?
- What related issues do you consider out of scope for this problem statement, that could be addressed in the future?
