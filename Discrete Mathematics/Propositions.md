## Propositions

### Definition
A proposition is a declarative sentence that is either true, or false, but not both.

#### Examples

```
2 + 2 = 4
This is a proposition. 

2 + 2 = 5
This is a proposition. A proposition can be false.

The home page renders correctly in IE
This is a proposition. A proposition can be false.

Turn in your homework on Wednesday.
This is a command. This command doesn't have a truth value

Akjsdf!
This is not a proposition. This is gibberish.

Who are you?
This is a question which means it doesn't have a truth value

x + 1 = 2.
This is not a proposition. This statement is neither true or false. This statement can be turned into a proposition if we assign a value to x.

x + y = z.
This is not a proposition. This statement is neither true or false. This statement can be turned into a proposition if we assign values to the variables.

Every positive even integer can be written as the sum of two primes 
This is a proposition. We don't know if it is true or false, but we know it's either true or false.
```

## Logical Opporators 


- [Negation(not) | ¬p] (#negation-p)
- [Conjunction (and) | p ∧ q] (#conjunction-p--q")
- [Disjunction (or) | p ∨ q] (#disjunction-p--q)
- [Exclusive Or | p ⊕ q] (#exclusive-or-p--q) 
- [Implication | p → q] (#conditional-statements)
- [Biconditional | p ⟷ q] (#biconditionals)

### Compound Propositions

Propositions formed from existing propositions using logical opporators 

## Negation (¬p)

Let _p_ be a proposition. The _negation of p_, denoted by _¬p_, is the statement 
> "It is not the case that p."
The proposition _¬p_ is read "not _p_". The truth value of the negation of _p_, ¬p, is the opposite of the truth value of _p_

#### Examples

```
p: "Michael's PC runs Linux."
¬p: "It is not the case that Michael's PC runs Linux."

p: "Vandana's smartphone has at least 32GB of memory."
¬p: "It is not the case that Vandana's smartphone has at least 32GB of memory." or "Vandana's smartphone has less than 32GB of memory."
```

#### Truth Table

| p | ¬p|
|---|---|
| T | F |
| F | T |

## Conjunction (p ∧ q)

Let _p_ and _q_ be propositions. The _conjunction_ of _p_ and _q_, denoted by _p_ ∧ _q_, is the proposition "_p_ and _q_." The conjunction _p_ ∧ _q_ is true when both _p_ and _q_ are true and is false otherwise.

#### Example

```
p: Alex's PC has more than 16GB free hard disk space
q: The processor in Alex's PC runs faster than 1 GHz.
p ∧ q: Alex's PC has more than 16GB fre ehard disk space, and has a processor that runs faster than 1 GHz
```

#### Truth Table 

|  p  | q  | p ∧ q |
|-----|----|-------|
|  T  | T  |   T   |
|  T  | F  |   F   |
|  F  | T  |   F   |
|  F  | F  |   F   |

The conjunction of _p_ and _q_ exists if and only if both _p_ and _q_ are true.

## Disjunction (p ∨ q)

Let _p_ and _q_ be propositions. The disjunction of _p_ and _q_, denoted by _p_ ∨ _q_, is the proposition "_p_ or _q_." The disjunction _p_ ∨ _q_ is false when both _p_ and _q_ are false and true otherwise.

Disjunction is an _**inclusive or**_. Similar to how ```a || b``` works in programming languages.  If a is true, this statement is true. If b is true, this statement is true. If a and b are true, this statement returns true. If both a and b are false, this statement returns false.

#### Example

```
p: Alex's PC has more than 16GB free hard disk space
q: The processor in Alex's PC runs faster than 1 GHz.
p ∨ q: Alex's PC has at least 16GB free hard disk space, or the processor in Alex's PC runs faster than 1 GHz.

```

#### Truth Table 

|  p  | q  | p ∨ q |
|-----|----|-------|
|  T  | T  |   T   |
|  T  | F  |   T   |
|  F  | T  |   T   |
|  F  | F  |   F   |

### Exclusive or (p ⊕ q)

Let _p_ and _q_ be propositions. The _exclusive or_ of _p_ and _q_, denoted by _p_  ⊕ _q_, is the proposition that is true when exactly one of _p_ and _q- is true and is false otherwise.

#### Truth Table 

|  p  | q  | p ⊕ q |
|-----|----|-------|
|  T  | T  |   F   |
|  T  | F  |   T   |
|  F  | T  |   T   |
|  F  | F  |   F   |

## Conditional Statements

Let _p_ and _q_ be propositions. The conditional statement _p_ → _q_ is the proposition “if _p_, then _q_.” The conditional statement _p_ → _q_ is false when _p_ is true and _q_ is false, and true otherwise. In the conditional statement p → q, p is called the hypothesis (or antecedent or premise) and q is called the conclusion (or consequence).

This asserts that _q_ is true on the condition that p holds. This is also known as an **implication**. 

* “if p, then q”
* “if p, q”
* “p is sufficient for q”
* “q if p”
* “q when p”
* “a necessary condition for p is q” 
* “q unless ¬p”
* “p implies q”
* “p only if q”
* “a sufficient condition for q is p” * “q whenever p”
* “q is necessary for p”
* “q follows from p”

It's impossible to prove a theory, only possible to disprove it. 


The if-then construction used in many programming languages is different from that used in logic. Most programming languages contain statements such as if p then S, where p is a proposition and S is a program segment (one or more statements to be executed). When execution of a program encounters such a statement, S is executed if p is true, but S is not executed if p is false.

#### Examples 

> If you get 100% on the final, then you will get an A.

If you manage to get a 100% on the final, then you would expect to receive an A ( _p_ → _q_ ). If you do not get 100% on the final, you may or may not receive an A depending on other factors (p is false and q is true || p is false and q is false). However, if you get 100% but you do not get an A, you would feel cheated.

> If I am elected, then I will lower taxes.

If politician is elected, voters would expect the politition to lower taxes. If the politian is not elected, then voters do not have any expectation that this person will lower taxes, although the person may have sufficient influence to cause those in power to lower taxes. **It is only when the politician is not elected but does not lower taxes that voters can say the politician has broken the campaign pledge**.

> If Maria learns discrete mathematics, then she will find a good job.

This is only falsifiable if Maria learns discrete mathematics but does not find a good job. 

> Maria will find a good job when she learns discrete mathematics.

> For Maria to get a good job, it is sufficient for her to learn discrete mathematics.

These are the same as the first statement

#### Truth Table 

|  p  | q  | p → q |
|-----|----|-------|
|  T  | T  |   T   |
|  T  | F  |   F   |
|  F  | T  |   T   |
|  F  | F  |   T   |


## Converse, Contrapositive, and Inverse

> Implication:
> p → q

> Converse:
> q → q

> Contrapositive: 
> ¬q → ¬p

> Inverse:
> ¬p → ¬q

An implication and it's contrapositive  have the same truth value.

When two compound propositions always have the same truth value, they are **equivalent**.  An implication and its contrapositive are **equivalent**. An implication's inverse and the same implication's converse are **equivalent**.

>If it is raining, then the home team wins.

Contrapositive: If the home team does not win, then it is not raining.

Inverse: If it is not raining, then the home team loses.

Converse: If the home team wins, then it is raining.

## Biconditionals

Let _p_ and _q_ be propositions. The biconditional statement _p_ ⟷ _q_ is the proposition “_p_ if and only if _q_.” The biconditional statement is true when _p_ and _q_ have the same truth values, and is false otherwise. Biconditional statements are also called _bi-implications_.


#### Truth Table 

|  p  |  q  | p ⟷ q |
|-----|----|-------|
|  T  | T  |   T   |
|  T  | F  |   F   |
|  F  | T  |   F   |
|  F  | F  |   T   |


## Precedence of Logical Operators

| Operator      | Precedence |
|---------------|------------|
|      not      |      1     |
|      and      |      2     |
| inclusive or  |      3     |
|  implication  |      4     |
| biconditional |      5     |

