<div>
  <p align="center">
    <img align="center" height="160" src="https://appinventor.mit.edu/explore/sites/explore.appinventor.mit.edu/files/blog/ai-bee-horiz.png" alt="app_inventor_logo">
    <img align="center" height="160" src="https://developers.google.com/open-source/gsoc/resources/downloads/GSoC-Horizontal.png" alt="gsoc_logo">

  </p>
</div>
<br><br>

# Functional Operators in the Blocks Editor

## Student Info

- Name: Siyao Li
- Email: siyaoli@g.harvard.edu
- GitHub Profile: https://github.com/siyaoL1

## Mentors Info

- Susan Lane
- Mark Friedman
- Lyn Turbak

## Project Abstract

Functional programming is a programming paradigm where programs are constructed by composing pure functions, avoiding shared state, mutable data, and side effects. Many operators in functional programming are commonly used to make code more concise, and less complex. This project hopes to expand the operations in the block editor of MIT App Inventor by implementing new blocks commonly found in functional programming, such as map, reduce, etc.

## Project Links
- #### [GSoC Project Proposal](https://docs.google.com/document/d/1tRz0RyFTDcBKOob6_pkPgNDJ0OIeh9T5OlHgtyPDXis/edit?usp=sharing)

- #### [GSoC Project Page](https://summerofcode.withgoogle.com/myprojects/details/HBUJwOG6)

- #### PRs Merged
  [Non-destructive Functional List Operator Blocks](https://github.com/mit-cml/appinventor-sources/pull/2699) <br>

- #### PRs Yet to be Merged
  [Destructive Functional List Operator Blocks](https://github.com/mit-cml/appinventor-sources/pull/2711) <br>
  
- #### GitHub Organization Repo
  [MIT App Inventor](https://github.com/mit-cml/appinventor-sources) 

- #### GitHub Forked Repo
  [MIT App Inventor](https://github.com/siyaoL1/appinventor-sources)

## Work Summary
  
### What's Done
* Debuged and merged 12 functional list operator blocks. (Map, Filter, Reduce, Sort, Sort with key, Sort with comparator, Minimum number, Maximum number, But first, But last, Slices)
* Implemented dropdown selection for procedures that enables the usage of higher order functions. This part is decided to not merged, but you can find the code [here](https://github.com/siyaoL1/appinventor-sources/tree/Siyao_GSoC2022_Functional_Blocks_with_Procedure_Selector).
* Created documentation and tutorials of new functional operator blocks for educational purposes. You can view the tutorial [here]().
  
### What left
* Create Minimum with comparator and Maximum with comparator blocks.
* Debug destructive mutator and integrate destructive vs. non-destructive switch for functional blocks.
