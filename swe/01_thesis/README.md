# Thesis

## Software Engineering

- **Time and Change**: How code will need to adapt over the length of its life
- **Scale and Growth**: How an organization will need to adapt as it evolves
- **Trade-offs and Costs**: How an organization makes decisions, based on the lessons of _Time and Change_ and _Scale and Growth_

### _Sustainable_ for software

What is the expected life span of your code?

**Life = maintenance lifetime**

#### technical debt

for either technical or business reasons,

- choose not to perform a given upgrade, either for lack of value or other priorities.
- things that "should" be done, but aren't yet
  - the delta between **our code** and **what we wish it was**.


### Team play

The multiperson development of multiversion programs.

book: _Mythical Man Month_

### Rational decisions

the complexity of decisions that need to be made and their stakes.

---

## Time and Change

<img src="https://abseil.io/resources/swe-book/html/images/seag_0101.png" width="400px">

### Painful transition

- what we hid and covered are revealed
- lack of experience
- many overdue tasks

### Hyrum’s Law

_With a sufficient number of users of an API, it does not matter what you promise in the contract: all observable behaviors of your system will be depended on by somebody._

## Scale and Growth

**scalable**: _sublinear scaling with regard to human interactions._

- codebase
- human cost
- compute cost
- everything: overall cost and resource

### _Flexibility_ of a codebase

Release more regularly:

- Expertise
- Stability
- Conformity
- Familiarity
- Policy

### Shifting Left

a defense-in-depth approach.

<img src="https://abseil.io/resources/swe-book/html/images/seag_0102.png" width="400px">

## Trade-offs and Costs

### Cost

- Financial costs
- Resource costs
- Personnel costs
- Transaction costs
- Opportunity costs
- Societal costs
- biases
  - status quo bias
  - loss aversion

### Jevons Paradox, Jevons Effect

Wikipedia: [Jevons Paradox](https://en.wikipedia.org/wiki/Jevons_paradox)

consumption of a resource may increase as a response to greater efficiency in its use.

### Data informing decisions

- Based on the available data
- Making Mistakes
- Revisiting Decisions
