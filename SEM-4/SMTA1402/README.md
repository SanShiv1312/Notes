<p align = center>
<img src="https://miro.medium.com/max/501/1*bn6QG4Vemv5Pgnhfx9b21Q.jpeg" width="45%" />
</p>

# Unit-1 `Probability Concepts and Random Variable`

### ->**Experiment** :
- In Probability, Experiment or Trail is an attempt that can be `infinitely repeated` and has a well defined `set of possible outcomes`(Sample space).
- The experiment will always results in something.
  * _**Example** :_
**Event or Trail** : "Tossing TWO coins"
then,
- _(Sample space)_ S = {HH, HT, TH, TT} and also "n" = 2(number of coins)
- |S| = _number of possible elements_ = `2^n`

### ->**Event** :
A probability event can be defined as a `set of outcomes` of an experiment
- A sub-set of Sample space(S) consisting of possible outcomes.
- * _**Example** :_
"Getting one tail" (From the above given example)
- "E1" = { HT, TH, TT}
- n(E1) = 3


Based on number of possible results in an experiment, we can classify  the experiments as two types
- **Deterministic**
- **Probabilistic**

#### -->**Deterministic Experiment** :
The Experiments which have only one possible result or outcome i.e. whose result is certain or unique.
- Also known as "Predictable Experiments"
- Result can be predicted with certainty and is known prior to its conduct.

<p align = center>
<img src="https://img.brainkart.com/imagebk37/whzSlIA.jpg" width="350"/>
</p>  

#### -->**Probabilistic Experiment** :
Experiments whose result is uncertain or unpredictable.
- Also known as "Indeterministic Experiments"
- The different possible outcomes can be known or assessed and the outcomes cannot be predicted prior to it's conduct.
- This can have more than one possible outcome.   

### ->**Random Experiment** :
An experiment is random if although it is repeated in the same manner every time, can `result in different outcomes`
- The set of all possible outcomes is completely determined before carrying it out.
- But before we carry it out, we cannot predict its outcome.
- No preference or priority is given to any of the cases i.e. without any bias for any case.
  * _**Example** :_ Tossing a coin (or) Rolling a die

### ->**Mathematical definition of Probability** :
Let S be the sample space and A be an event associated with a random
experiment. Let n(S) and n(A) be the number of elements of S and A. then
the probability of event 'A' occurring is denoted as P(A), is denoted by
- **`P(A) = n(A)/n(S)`**
- (number of likely occurring outcomes for the event **A**) / (Total possible outcomes of the experiment)  

#### ->**Statistical definition** :
<p align = center>
<img src="https://www.wisdomjobs.com/tutorials/definition-rdot-von-mises.png"/>
</p>

### ->**Axiomatic definition of Probability** :
Let S be the sample space and A be an event associated with a random
experiment. Then the probability of the event E, P(E) is defined as a real
number satisfying the following axioms.
- p(Ei) >= 0
- 0 <= P(E) <= 1
- P(S) = 1 and p(Φ) = 0
- If A and B are mutually exclusive events or disjoint then, `P(A U B) = P(A) + P(B)`

### ->**Basic types of events**

#### -->**Disjoint events** :
Two events are Disjoint, if they `cannot occur at the same time`.
- Another word that means disjoint is `mutual exclusivity`.
- If two events are disjoint, then the probability of them both occurring at the same time is '0'.  

<p align = center>
<img src="https://www.statology.org/wp-content/uploads/2021/02/disjoint1.png" width="220"/>
</p>

- we have, `P(A or B) = P(A) + P(B)` from the above.

#### -->**Equally likely events** :
Events that have equal chance of occurrence in a trail of an experiment.
- If each outcome of an event has `same probability of occurring`.
- Getting a head or tail when a coin was tossed (or) getting even or odd number when a dice was thrown can be stated as examples for Equally likely events.
- `Unbiased` conditions should be there for their occurrence.

<p align = center>
<img src="https://3.bp.blogspot.com/-11S-ach8wd8/WH8mfaPOG_I/AAAAAAAAEKY/s2rXtK8MboQU6S-lBTbAYlr0bqku3uglgCLcB/s1600/1%25252F6.jpg"/>
</p>

#### -->**Exhaustive events** :
Events are called as Exhaustive, if at least one of them necessarily occurs whenever the experiment is performed.
- All the possible events in a sample space of an experiment constitute the exhaustive events.
- Exhaustive events may or may not be equally likely Events.
   * consider,  Ai be a possible event for all i ∈ {1, 2, 3, 4, ..., n} in S then [ "U(from i = 1 to n) Ai = S" ].

<p align = center>
<img src="https://www.w3spoint.com/wp-content/uploads/2019/11/Pasted-into-Exhaustive-events-in-Probability.png" width="250"/>
</p>

- where E1, E2, E3 are the "Exhaustive events".

#### ->**`Important Theorems`** :
