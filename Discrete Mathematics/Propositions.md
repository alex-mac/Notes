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

### Logical Opporators 

```
Negation(not) | ¬p
Conjunction (and) | p ∧ q
Disjunction (or) | p ∨ q
Exclusive Or | p ⊕ q
Implication | p ⟶ q 
Biconditional | p ⟷ q
```

### Compound Propositions

Propositions formed from existing propositions using logical opporators 

### Negation (¬p)

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

### Conjunction (p ∧ q)

Let _p_ and _q_ be propositions. The _conjunction_ of _p_ and _q_, denoted by _p_ ∧ _q_, is the proposition "_p_ and _q_." The conjunction _p_ ∧ _q_ is true when both _p_ and _q_ are true and is false otherwise.

#### Example

```
p: Alex's PC has more than 16GB free hard disk space
q: The processor in Alex's PC runs faster than 1 GHz.
p ∧ q: Alex's PC has more than 16GB fre ehard disk space, and has a processor that runs faster than 1 GHz
```

#### Truth Table 

|  p    q  | p ∧ q |
|----------|-------|
|  T    T  |   T   |
|  T    F  |   F   |
|  F    T  |   F   |
|  F    F  |   F   |

The conjunction of _p_ and _q_ exists if and only if both _p_ and _q_ are true.

### Disjunction (p ∨ q)

Let _p_ and _q_ be propositions. The disjunction of _p_ and _q_, denoted by _p_ ∨ _q_, is the proposition "_p_ or _q_." The disjunction _p_ ∨ _q_ is false when both _p_ and _q_ are false and true otherwise.

Disjunction is an _**inclusive or**_. Similar to how ```a || b``` works in programming languages.  If a is true, this statement is true. If b is true, this statement is true. If a and b are true, this statement returns true. If both a and b are false, this statement returns false.

#### Example

```
p: Alex's PC has more than 16GB free hard disk space
q: The processor in Alex's PC runs faster than 1 GHz.
p ∨ q: Alex's PC has at least 16GB free hard disk space, or the processor in Alex's PC runs faster than 1 GHz.

```

#### Truth Table 

|  p    q  | p ∨ q |
|----------|-------|
|  T    T  |   T   |
|  T    F  |   T   |
|  F    T  |   T   |
|  F    F  |   F   |

### Exclusive or (p ⊕ q)

Let _p_ and _q_ be propositions. The _exclusive or_ of _p_ and _q_, denoted by _p_  ⊕ _q_, is the proposition that is true when exactly one of _p_ and _q- is true and is false otherwise.

#### Truth Table 

|  p    q  | p ⊕ q |
|----------|-------|
|  T    T  |   F   |
|  T    F  |   T   |
|  F    T  |   T   |
|  F    F  |   F   |

