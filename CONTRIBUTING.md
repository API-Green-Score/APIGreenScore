# Contributing to the Best Practices Repository
Anyone who wishes to can propose contributions to the repository.

The rules of this document must be respected.

The project team in charge of this repository ensures compliance with these rules.

# Purpose of Contributions
Contributions aim to:

- Remove outdated, inapplicable, or ineffective best practices.
- Add relevant best practices based on practical experience.
- Associate compliance rules with new best practices.
- Verify and improve existing best practices and their compliance rules if necessary.
- Propose any ideas that could enhance the repository in general and, if appropriate, implement them.

# General Rules
- Everyone has a place, and everyone can contribute their experience.
- Friendliness, sharing, courtesy, and kindness are golden rules in interactions.
- Each best practice should be based on field feedback or scientific approaches.
- These best practices also serve as a memory aid, so even a simple, common-sense best practice can have its place.


## ProjectTeam

The project team consists of:

- [Yannick Tremblais](https://github.com/ytremblais)
- [Julien Brun] ()
- [Liliana Jena] ()
- [Christelle Ravaudet] ()
- [Julien Bichon] ()
- [David De Carvalho](https://github.com/dedece35)


The project team ensures that the established rules for contribution are respected.

In the event of disagreements among contributors, their role is to make final decisions.

The project team demonstrates transparency and strives for decisions to be as collective as possible.

The project team is responsible for the definitive validation of `Pull Requests` and the integration of proposed additions, modifications, or deletions into the repository.

A member of the project team can submit a proposal to the contributors but cannot be solely responsible for approving or rejecting it: a consensus from the project team is required.



## Proposal

Every proposal for adding, major modification, or deletion of best practices must go through [a discussion](https://github.com/ytremblais/APIGreenScore/discussions/categories/bonnes-pratiques).

The title of the discussion should be explicit and specify whether it is an addition, a major modification, or a deletion.

A major modification may include:

Significant changes to the priority level, i.e., implementation levels and ecological impacts.
- Addition or removal of elements in the rule definition.
- Addition or removal of examples.
- Modification of the compliance rule.

Any contributor can express their opinion on the proposal:

- In case of agreement, a contributor can click the "thumbs up" icon.
- In case of disagreement, a contributor can add a "thumbs down" icon and must provide an explanation in a comment.
- In case of confusion, a contributor can initiate a discussion to seek clarification.
- If there are ideas for improvement, they can be proposed.

When a proposal receives multiple positive votes, the project team is notified and evaluates the relevance of the best practice.

The following scenarios may occur:

- The proposal is approved, and the contributor can create an Issue referencing the discussion.
- The proposal is definitively rejected with justification.
- The proposal needs to be reworked before a final decision is made

The created `Issue` should include the tag `create`, `modify`, or `delete` depending on the type of proposal and should be linked to the [`Best Pratices project`](https://github.com/ytremblais/APIGreenScore/projects/1).

For additions, the file should be named following the pattern: `YYxx_en.md`, where ̀`YY` means category an `xx` is the number assigned to the rules by the project team.

The file should be copied from the [template](./resources/YYxx_en.md).

A `Pull Request` associated ton  `Issue` will be created and submitted to the project team for review.

The creation of a `Pull Request` follows the standard process within GitHub, which includes:

- Creating a personal `fork` by the person in charge of the `Pull Request`.
- Adding the original repository as a remote (`upstream`).
- Creating a branch on the personal fork.
- Creating a `Pull Request` from the fork, with the target branch set to the `main` branch of the target repository.


# Improvement

For improvements such as:

- Spelling, grammar, or conjugation corrections
- Alternative wording
- Formatting changes

There is no need to go through a discussion. The following steps should be taken:

- Create an `Issue` with a clear title and the tags `modify` and `minor`.
- Develop and create the associated PR, making sure to reference the `Issue`.

## Content of a Best Practice

Each best practice must include the following:

- Title
- Priority level (on a scale of 5, where 5 is highest priority and 1 is lowest)
- Implementation difficulty (on a scale of 5, where 5 is easiest and 1 is most difficult)
- Ecological impact level (on a scale of 5, where 5 has the highest impact and 1 has the lowest)
- Description
- Validation rule and compliance threshold

The following elements are optional:

- One or more examples
- Alternative solution

### Validation Rule and Compliance Threshold

The validation rule allows for testing the implementation of the best practice using an objective approach.
The compliance threshold associates a numeric value (threshold) with the validation rule, allowing for a binary decision (yes/no) on whether the best practice has been implemented or not.
The set of validation rules and compliance thresholds establishes the level of maturity achieved by the digital service.


### Definition of Levels

Three levels need to be defined for a best practice:

1. Implementation (ease or difficulty of implementing the best practice)
2. Environmental impacts (contribution to reducing environmental impacts)
3. Priority (this level is determined based on 1 and 2)

Each of these levels is defined by a rating from 1 to 5.

#### Implementation (higher is better)

The ease or difficulty of implementation can be evaluated as follows:

1. Implementation requires a high level of expertise and a major project overhaul.
2. Implementation requires a high level of expertise or a major project overhaul.
3. Implementation requires a specific skill without being rare (e.g., SEO, DBA, ...) and does not require a major project overhaul.
4. Implementation does not require a specific skill or have side effects on the rest of the project.
5. Implementation does not require a specific skill and has no side effects on the rest of the project.

#### Environmental Impact (higher is better)

The contribution can be evaluated as follows:

1. It reduces the impact of networks
2. It reduces the impact of compute
3. It reduces the impact of storage

#### Priority (higher is better)

The priority level is freely proposed by the contributor and is based on the Implementation and Environmental Impact.
