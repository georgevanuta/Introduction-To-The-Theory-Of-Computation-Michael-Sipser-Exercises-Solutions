# Exercises - Chapter 1

[Exercises - Chapter 1](#exercises-chapter-1)
- [1.01](#11)
- [1.02](#12)
- [1.03](#13)
- [1.04](#14)
- [1.05](#15)
- [1.06](#16)
- [1.07](#17)
- [1.08](#18)
- [1.09](#19)
- [1.10](#110)
- [1.11](#111)
- [1.12](#112)
- [1.13](#113)
- [1.14](#114)
- [1.15](#115)
- [1.16](#116)
- [1.17](#117)
- [1.18](#118)
- [1.19](#119)
- [1.20](#120)
- [1.21](#121)
- [1.22](#122)
- [1.23](#123)
- [1.24](#124)
- [1.25](#125)
- [1.26](#126)
- [1.27](#127)
- [1.28](#128)
- [1.29](#129)
- [1.30](#130)
- [1.31](#131)
- [1.32](#132)
- [1.33](#133)
- [1.34](#134)
- [1.35](#135)
- [1.36](#136)
- [1.37](#137)
- [1.38](#138)
  
## $1.1$

### $a.)$

$M_1: q_1$ \
$M_2: q_1$

### $b.)$

$M_1: \{q_2\}$ \
$M_2: \{q_1, q_4\}$

### $c.)$

$M_1: q_1 \rarr q_2 \rarr q_3 \rarr q_1 \rarr q_1$
$M_2: q_1 \rarr q_1 \rarr q_1 \rarr q_2 \rarr q_4$

### $d.)$

$M_1:$ because the process ends in $q_1$, \
 which is not an accept state, this machine does not accept the string "aabb".

$M_2:$ because the process ends in $q_4$, \
which is an accept state, this machine accepts the string "aabb".

### $e.)$

In order for a machine to accept the empty string, the start state needs to be \
an accept state.

$M_1:$ doesn't accept the empty string $(q1 \notin AcceptStates)$.
$M_2:$ accepts the empty string $(q1 \in AcceptStates)$.

## $1.2$

### $M_1$

$States = \{q_1,q_2,q_3\}$
$Alphabet = \{a,b\}$
$StartState = q_1$
$AcceptStates = \{q_2\}$
$Delta:$
|     |$a$  |$b$  |
|:---:|:---:|:---:|
|$q_1$|$q_2$|$q_1$|
|$q_2$|$q_3$|$q_3$|
|$q_3$|$q_2$|$q_1$|

### $M_2$

$States: \{q_1,q_2,q_3,q_4\}$
$Alphabet = \{a,b\}$
$StartState = q_1$
$AcceptStates = \{q_1,q_4\}$
$Delta:$
|     |$a$  |$b$  |
|:---:|:---:|:---:|
|$q_1$|$q_1$|$q_2$|
|$q_2$|$q_3$|$q_4$|
|$q_3$|$q_2$|$q_1$|
|$q_4$|$q_3$|$q_4$|

## $1.3$

<img src="https://user-images.githubusercontent.com/74255152/178842376-b8315805-30e3-4155-9c39-b2036d249d8e.png">

## $1.4$

### $a.)$

#### $\{w | w\ has\ at\ least\ 3\ a's\}$

<img src="https://user-images.githubusercontent.com/74255152/178844823-d0f1cd7c-119b-4d93-822c-93a5e9dad7cf.png">

#### $\{w | w\ has\ at\ least\ 2\ b's\}$

<img src="https://user-images.githubusercontent.com/74255152/178844849-0bcbc7cd-3395-430f-9ab0-8adcae4990b0.png">

#### $\{w | w\ has\ at\ least\ 3\ a's\ \mathbf{and}\ at\ least\ 2\ b's\}$

<img src="https://user-images.githubusercontent.com/74255152/178849275-34dfe23a-1703-46d2-80fd-54f8231e2013.png">

### $b.)$

#### $\{w | w\ has\ exactly\ 2\ a's\}$

<img src="https://user-images.githubusercontent.com/74255152/178853083-9df2917f-3138-473c-b1a1-7d97965e0652.png">

#### $\{w | w\ has\ exactly\ 2\ a's\ \mathbf{and}\ at\ least\ 2\ b's\}$

<img src="https://user-images.githubusercontent.com/74255152/178854164-13a849b2-1463-4ced-8557-a27ee0d82f71.png">

### $c.)$

#### $\{w | w\ has\ an\ even\ number\ of\ a's\}$

<img src="https://user-images.githubusercontent.com/74255152/178855277-5881ac79-46bf-4c44-a90c-2dbd002d93aa.png">

#### $\{w | w\ has\ 1\ or\ 2\ b's\}$

<img src="https://user-images.githubusercontent.com/74255152/178855314-cc1d7925-8925-40db-babe-1aa7e5957054.png">

#### $\{w | w\ has\ an\ even\ number\ of\ a's\ \mathbf{and}\ 1\ or\ 2\ b's\}$

<img src="https://user-images.githubusercontent.com/74255152/178856141-20c79267-0495-4a91-b62a-957fb324778c.png">

### $d.)$

#### $\{w | w\ where\ each\ a\ is\ followed\ by\ at\ least\ 1\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178857121-64a48047-1a3b-4ad6-ab44-4e654af4fd32.png">

#### $\{w | w\ has\ an\ even\ number\ of\ a's\ \mathbf{and}\ where\ each\ a\ is\ followed\ by\ at\ least\ 1\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178858067-18e20d52-d26c-44c8-939c-5d19ce047920.png">

### $e.)$

#### $\{w | w\ starts\ with\ an\ a\}$

<img src="https://user-images.githubusercontent.com/74255152/178859699-0c2a73b3-22d1-4512-aac7-b0ea2efaac7b.png">

#### $\{w | w\ has\ at\ most\ 1\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178859841-0adc8b03-e8cd-42f0-af00-9bf9d9ee60c2.png">

#### $\{w | w\ starts\ with\ an\ a\ \mathbf{and}\ w\ has\ at\ most\ 1\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178859887-64a0f2aa-49d0-4018-a080-eb9f8a865a15.png">

### $f.)$

#### $\{w | w\ has\ an\ odd\ number\ of\ a's\}$

<img src="https://user-images.githubusercontent.com/74255152/178861776-519d2602-32f3-477f-8d0a-f630fa52e7e7.png">

#### $\{w | w\ ends\ with\ a\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178861798-13418676-f1f1-4086-a4bd-81bb05706349.png">

#### $\{w | w\ has\ an\ odd\ number\ of\ a's\ \mathbf{and}\ ends\ with\ 1\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178861810-1bc5f964-ee29-4b61-b210-07d5a509ab76.png">

### $g.)$

#### $\{w | w\ has\ an\ even\ length\}$

<img src="https://user-images.githubusercontent.com/74255152/178863872-e9af28ef-4bfc-43a6-8d17-ed18969313d5.png">

#### $\{w | w\ has\ an\ even\ length\ \mathbf{and}\ an\ odd\ number\ of\ a's\}$

<img src="https://user-images.githubusercontent.com/74255152/178863893-dd73ae01-a30c-413f-a5d8-430970d04343.png">

## $1.5$

To build a DFA that accepts the complement of a language, \
we simply need to swap the accepts states with the other states.

### $a.)$

$\{w\ |\ "ab" \notin w\}$

<img src="https://user-images.githubusercontent.com/74255152/178875181-9ea4f41a-4be8-4ab1-82ba-5828e7f10aa3.png">

### $b.)$

$\{w\ |\ "baba" \notin w\}$

<img src="https://user-images.githubusercontent.com/74255152/178881164-1c991d9d-00bb-4145-9bde-e9388d6ae8e6.png">

### $c.)$

$\{w\ |\ "ab" \notin w\ \mathbf{and}\ "ba" \notin w\}$

<img src="https://user-images.githubusercontent.com/74255152/178881251-00fca14d-5750-43ca-9574-57d9cd62233e.png">

### $d.)$

$\{w\ |\ w \notin (a^*b^*)\}$

<img src="https://user-images.githubusercontent.com/74255152/178881368-c4042c5c-4905-4da0-b479-9e23ba026a1e.png">

### $e.)$

$\{w\ |\ w \notin ((ab^+)^*)\}$

<img src="https://user-images.githubusercontent.com/74255152/178881474-8efb4b74-1b44-4b89-a388-ceb55e166dfe.png">

### $f.)$

$\{w\ |\ w \notin (a^* \cup b^*)\}$

<img src="https://user-images.githubusercontent.com/74255152/178881607-1811b4b7-35a5-4216-bac5-36b3ef547c5d.png">

### $g.)$

$\{w\ |\ w\ doesn't\ contain\ exactly\ 2\ a's\}$

<img src="https://user-images.githubusercontent.com/74255152/178881854-65e64c87-47ac-49cc-94dc-b47660f5e261.png">

### $h.)$

$\{w\ |\ w\ is\ any\ string\ except\ a\ and\ b\}$

<img src="https://user-images.githubusercontent.com/74255152/178881975-8cb34b6d-e4fc-40c2-867b-4eaf178ff011.png">

## $1.6$

### $a.)$

$\{w\ |\ w\ begins\ with\ a\ 1\ and\ ends\ with\ a\ 0\}$

<img src="https://user-images.githubusercontent.com/74255152/179010060-1b4eccfd-614c-456e-8e09-76e0cc3e186a.png">

### $b.)$

$\{w\ |\ w\ contains\ at\ least\ three\ 1's\}$

<img src="https://user-images.githubusercontent.com/74255152/179010095-5b0f6510-e08a-4915-b514-b229ce956108.png">


### $c.)$

$\{w\ |\ w\ contains\ the\ substring\ 0101\}$

<img src="https://user-images.githubusercontent.com/74255152/179010107-fb6573ab-cef7-4f86-8ff4-192d3cf20fac.png">

### $d.)$

$\{w\ |\ w\ has\ length\ at\ least\ 3\ and\ its\ third\ symbol\ is\ a\ 0\}$

<img src="https://user-images.githubusercontent.com/74255152/179010245-0c0e647b-894c-46ac-a170-04c88fc8cf47.png">

### $e.)$

$\{w\ |\ w\ starts\ with\ a\ 0\ and\ has\ odd\ length\ or\ starts\ with\ a\ 1\ and\ has\ even\ length\}$

<img src="https://user-images.githubusercontent.com/74255152/179010254-ffc9d39e-e6d4-47cd-96b1-16e664834a5a.png">

### $f.)$

$\{w\ |\ w\ doesn't\ contain\ the\ substring\ 110\}$

<img src="https://user-images.githubusercontent.com/74255152/179010266-ec870d41-8d1c-4113-8fe2-8aeffbaa546e.png">

### $g.)$

$\{w\ |\ the\ length\ of\ w\ is\ at\ most\ 5\}$

<img src="https://user-images.githubusercontent.com/74255152/179010481-7f2a5b60-8e85-48a9-8a04-7304ab408b59.png">

### $h.)$

$\{w\ |\ w\ is\ any\ string\ except\ 11\ and\ 111\}$

<img src="https://user-images.githubusercontent.com/74255152/179010486-8719f9f2-ca38-4148-af56-96cea28905e8.png">

### $i.)$

$\{w\ |\ every\ odd\ position\ of\ w\ is\ a\ 1\}$

<img src="https://user-images.githubusercontent.com/74255152/179010499-0902d7d3-660c-4931-81b0-db0394a398b4.png">

### $j.)$

$\{w\ |\ w\ contains\ at\ least\ two\ 0's\ and\ at\ most\ one\ 1\}$

<img src="https://user-images.githubusercontent.com/74255152/179010717-b9206e73-fa93-415d-b58b-f2c5184cda90.png">

### $k.)$

$\{\epsilon,\ 0\}$

<img src="https://user-images.githubusercontent.com/74255152/179010729-be3ad984-883a-498f-8959-75416ef6e293.png">

### $l.)$

$\{w\ |\ w\ contains\ an\ even\ number\ of\ 0's,\ or\ contains\ exactly\ two\ 1's\}$

<img src="https://user-images.githubusercontent.com/74255152/179010748-0a863f42-a0d6-47e3-b1e3-8ddb25f7f6c5.png">

### $m.)$

$\{\}$ (the empty set)

<img src="https://user-images.githubusercontent.com/74255152/179014674-e7b021a2-5006-4f81-a110-0690efac2c39.png">

### $n.)$

$\Sigma^* - \epsilon$

<img src="https://user-images.githubusercontent.com/74255152/179010984-612881dc-425e-4170-992c-1235d2e1f35f.png">

## $1.7$

### $a.)$

$\{w\ |\ w\ ends\ in\ 00\}\ with\ \mathbf{three}\ states$

<img src="https://user-images.githubusercontent.com/74255152/179289521-0eb40a89-5cf5-43e5-a945-c2bb6c99b31f.png">

### $b.)$

$1.6.\ c)\ with\ \mathbf{five}\ states $

<img src="https://user-images.githubusercontent.com/74255152/179289576-6bc87cb4-3148-4c58-8311-f630381fad93.png">

### $c.)$

$1.6.\ l)\ with\ \mathbf{six}\ states$

<img src="https://user-images.githubusercontent.com/74255152/179289584-3726b74b-a87f-4cb9-906e-66fba008e509.png">

### $d.)$

$\{0\}\ with\ \mathbf{two}\ states$

<img src="https://user-images.githubusercontent.com/74255152/179289594-7f385da1-af9b-4cdc-93c7-c70a6029c042.png">

### $e.)$

$0^*1^*0^+\ with\ \mathbf{three}\ states$

<img src="https://user-images.githubusercontent.com/74255152/179289600-b6df07cc-722a-41ec-aa2d-675816f03512.png">

### $f.)$

$1^*(001^+)^*\ with\ \mathbf{three}\ states$

<img src="https://user-images.githubusercontent.com/74255152/179289607-b42de1aa-3edc-4158-9801-de833c720354.png">

### $g.)$

$\{\epsilon\}\ with\ \mathbf{one}\ state$

<img src="https://user-images.githubusercontent.com/74255152/179289621-82a82a8a-a1fb-43c8-8a41-bd4bb11c6b14.png">

### $h.)$

$0^*\ with\ \mathbf{one}\ state$

<img src="https://user-images.githubusercontent.com/74255152/179289633-6a996040-c8dd-4616-af44-cebc7c3a3ba7.png">

## $1.8$

### $a.)$

$1.6\ a.)\ \cup\ 1.6\ b.)$

<img src="https://user-images.githubusercontent.com/74255152/179292932-35d64c93-65e1-4b03-9e2e-34f36dfbebff.png">

### $b.)$

$1.6\ c.)\ \cup\ 1.6\ f.)$

<img src="https://user-images.githubusercontent.com/74255152/179292944-a8038a0a-3a44-4023-b55c-d93c79e51440.png">

## $1.9$

### $a.)$

$1.6\ g.)\ \circ\ 1.6\ i.)$

<img src="https://user-images.githubusercontent.com/74255152/179296752-3bf68c33-99b1-4505-b574-8c1ef0f579f4.png">

### $b.)$

$1.6\ b.)\ \circ\ 1.6\ m.)$

<img src="https://user-images.githubusercontent.com/74255152/179296761-05374006-68e3-4b41-9e50-85939a4703d2.png">

## $1.10$

### $a.)$

$1.6\ b.)^*$

<img src="https://user-images.githubusercontent.com/74255152/179300571-ffd6c0d5-ac1a-4fcd-ab7b-eedcdb39eeff.png">

**Obs:** the only thing the star changes is the set of the accept states, \
adding the empty string to it.

### $b.)$

$1.6\ j.)^*$

<img src="https://user-images.githubusercontent.com/74255152/179300577-a61a812a-133c-4ca1-ae68-ef0d33173673.png">

**Obs:** same as $1.10\ a.)$

### $c.)$

$1.6\ m.)^*$

<img src="https://user-images.githubusercontent.com/74255152/179300582-4c8523a2-ffb4-4481-b7c3-a743def8bc84.png">

**Obs:** the star changes nothing here, \
because:
 - *zero* appearances of *empty* **MEAN** *empty*.
 - *multiple* appearances of *empty* **MEAN** *empty*.

## $1.11$

**Statement**:
`Every NFA can be converted to an equivalent one that has a single accept state.`
**Proof**:
Draw empty arrows from all accept states to a single, newly created state. \
This state will be the new, only accept state.

**Example**:

*From:*

<img src="https://user-images.githubusercontent.com/74255152/179292944-a8038a0a-3a44-4023-b55c-d93c79e51440.png">

*To:*

<img src="https://user-images.githubusercontent.com/74255152/179322669-4387cd27-ebe9-426b-bbf0-e746a024ca33.png">

## $1.12$

 - Because $D$ doesn't contain the substring *ab*,\
it means that D is of the form $b^*a^*$.
 - An even number of b's is described by $(bb)^*$.
 - An odd number of a's is descrived by $a(aa)^*$

$\mathbf{Regex}:\ (bb)^*a(aa)^*$

$\mathbf{DFA}:$

<img src="https://user-images.githubusercontent.com/74255152/179325835-7c7795b9-7818-4900-a505-d69366dc0f84.png">

## $1.13$

**Description:**
$Alphabet=\{0,1\} (*)$
$F=\{w\ |\ w\ over\ Alphabet(*),\ w\ doesn't\ contain\ a\ pair\\
of\ 1s\ with\ an\ odd\ number\ of\ symbols\ between\ them\}$

**Proof:**
Let's assume we have a string with $>=3\ 1s$. The first and the second $1$ have\
$2n, n \in N$ number of 0s between them, and the second and third one have\
$2m, m \in N$ number of 0s between them. Based on this assumption, we can\
conclude that the number of symbols between the first and the third 1 is\
$2n+2m+1 = 2(m+m)+1$ (the $2n$ and $2m$ are the number of 0s between the\
first and second $1$, respectively between the second and third $1$, and the\
$+1$ is the symbol 1 between them (the second $1$)).\
Thus, there is an odd number of symbols between the first and third $1$.\
The conclusion is that there can't be $>=3\ 1s$ in our language $F$.

**Construction:**
Because there can't be $>=3\ 1s$ in F, there can only be 0, 1 or 2 $1s$ in F.\
Let's take all the possible cases:
 - 0 number of $1s\ \rarr\ 0^*$
 - 1 occurance of $1\ \rarr\ 0^*10^*$
 - 2 number of $1s\ \rarr\ 0^*1(00)^*10^*$

$\mathbf{Regex}:$
Combining all possible cases, we come across this regex:\
$0^*\ \cup\ 0^*10^*\ \cup\ 0^*1(00)^*10^*$

$\mathbf{NFA}\ with\ four\ states:$

<img src="https://user-images.githubusercontent.com/74255152/179361598-fbd8da73-ef26-4ed8-9bb0-ba11cac4e276.png">

$\mathbf{DFA}\ with\ five\ states:$

<img src="https://user-images.githubusercontent.com/74255152/179361629-5dbdfe01-481b-4e4d-9453-e3f9c30d9064.png">

## $1.14$

### $a.)$

**Notations:**

$D\ =\ initial\ DFA$
$\dot{D}\ =\ complement\ of\ D$


**Proof**:

$\dot{D}$ accepts whevenever $D$ doesn't accept. This means that $\dot{D}$ accepts only\
the strings which $D$ doesn't.

**Closure under Complement (*):**

*Proof idea* $\rarr$ We have regular language $A$ and want to show that $\dot{A}$ is also regular.\
Because $A$ is regular, we know that some finite automaton $M$ recognizes $A$.\
To prove that $\dot{A}$ is regular we demonstrate a finite automaton, call it $\dot{M}$, that recognizes $\dot{A}$.

This is a proof by construction. We construct $\dot{M}$ from $M$. Machine $\dot{M}$ must accept its input exactly when $M$ wouldn't accept it.\
Thus, the construction is simple. Build $M$, and swap its accept states with its non-accepting states.

**Proof of (*)**:

$Let\ M\ recognize\ A,\ where\ M\ =\ (Q,\Sigma,\delta,q_0, F)$.
$Construct\ \dot{M}\ =\ (Q, \Sigma, \delta, q_0,\dot{F}),\ which\ regonizes\ \dot{A}$.
$\mathbf{1.}\ \dot{M}\ has\ the\ same\ Q, \Sigma, \delta, q_0\ as\ M$.
$\mathbf{2.}\ \dot{F}\ =\ Q\ -\ F$
$The\ accept\ states\ of\ M\ (F)\ are\ the\ nonaccepting\ states\ of\ M\ (Q\ -\ F).$

### $b.)$

**Counterexample:**

 - $Initial\ \mathbf{NFA}(recognizes\ 1^*):$


     <img src="https://user-images.githubusercontent.com/74255152/180047514-554214a9-51aa-4451-a375-c9e6a9d82b7a.png">

 - $Complement\ \mathbf{NFA}(constructed\ from\ the\ previous\ \mathbf{DFA}\ theorem\ from\ a.)):$
  
     <img src="https://user-images.githubusercontent.com/74255152/180047525-6d33fc26-9649-48b3-aeef-55796f16b758.png">

     $This\ machine\ recognizes\ the\ empty\ set.$

 - $Actual\ complement\ \mathbf{NFA},\ recognizes\ 0^+:$

     <img src="https://user-images.githubusercontent.com/74255152/180047533-1c887507-f4c2-443b-98f2-0a095577609a.png">

**Conclusion:**
$The\ class\ of\ languages\ regognized\ by\ \mathbf{NFAs}$
$is\ not\ closed\ under\ complement\ because\ an\ \mathbf{NFA}$
$doesn't\ have\ transitions\ for\ all\ letters\ of\ the\ alphabet.$

## $1.15$

TODO.

## $1.16$

$N\ =\ (Q,\Sigma,\delta,q_0,F)$
$D\ =\ (Q',\Sigma,\delta',q_0',F')$

### $a.)$

$Q'\ =\ P(Q)\ (the\ powerset\ of\ Q)$
$Q'\ =\ \{{\empty,\{1\},\{2\},\{1,2\}}$\}

$F'\ =\ \{\{1\},\{1,2\}$\}

$q_0'\ =\ E(\{q_0\})$
$q_0'\ =\ \{1\}$

$Now,\ let's\ build\ \delta':$
$\{1\}$ on $a$ goes to $\{1,2\}$ and, on $b$, goes to $\{2\}$.
$\{2\}$ on $a$ goes to $\empty$ and, on $b$ goes to $\{1\}$.
$\{1,2\}$ on $a$ goes to $\{1\}$ and, on $b$ goes to $\{1,2\}$.
$\empty$, as always, goes for all letters of $\Sigma$ to itself.

<img src="https://user-images.githubusercontent.com/74255152/180070007-66258ae4-a650-4bd5-8c6a-097760560457.png">

### $b.)$

$Q'\ =\ P(Q)$
$Q'\ =\ \{\empty,\{1\},\{2\},\{3\},\{1,2\},\{2,3\},\{1,3\},\{1,2,3\}\}$

$F'\ =\ \{2\},\{1,2\},\{2,3\},\{1,2,3\}$

$q_0'\ =\ E(\{q_0\})$
$q_0'\ =\ \{1,2\}$

$\delta':$
$\{1\}$ on $a$ goes to $\{3\}$ and, on $b$, goes to $\empty$.
$\{2\}$ on $a$ goes to $\{1,2\}$ and, on $b$, goes to $\empty$.
$\{3\}$ on $a$ goes to $\{2\}$ and, on $b$, goes to $\{2,3\}$.
$\{1,2\}$ on $a$ goes to $\{1,2,3\}$ and, on $b$, goes to $\empty$.
$\{2,3\}$ on $a$ goes to $\{1,2\}$ and, on $b$, goes to $\{2,3\}$.
$\{1,3\}$ on $a$ goes to $\{2,3\}$ and, on $b$, goes to $\{2,3\}$.
$\{1,2,3\}$ on $a$ goes to $\{1,2,3\}$ and, on $b$, goes to $\{2,3\}$.
$\empty$, as always, goes for all letters of $\Sigma$ to itself.

**initial:**

<img src="https://user-images.githubusercontent.com/74255152/180074468-b9aa1dfc-fdd9-482c-8b30-e700ff10ed84.png">

**simplified (removed useless states $\mathbf{\{\{1\},\{1,3\},\{3\},\{2\}\})}$:**

<img src="https://user-images.githubusercontent.com/74255152/180075580-b0e064e7-1d6f-47df-ae20-355ba3a798b5.png">

## $1.17$

### $a.)$

$\mathbf{NFA}\ for\ 01:$

<img src="https://user-images.githubusercontent.com/74255152/180079705-6ae19658-b2fa-4dc2-9bf4-f6c002207284.png">

$\mathbf{NFA}\ for\ 001:$

<img src="https://user-images.githubusercontent.com/74255152/180080211-77df493f-3264-4a86-a3cb-b734891be7f9.png">

$\mathbf{NFA}\ for\ 010:$

<img src="https://user-images.githubusercontent.com/74255152/180079720-9abc0028-1890-47a8-a58d-634f90b891e0.png">

$\mathbf{NFA}\ for\ (01\ \cup\ 001\ \cup\ 010):$

<img src="https://user-images.githubusercontent.com/74255152/180079727-d10861be-fd76-4df7-95a1-80c2584a60b6.png">

$\mathbf{NFA}\ for\ (01\ \cup\ 001\ \cup\ 010)^*:$

<img src="https://user-images.githubusercontent.com/74255152/180079737-5fb895dd-b7eb-4242-b250-9dd0c22a7285.png">

### $b.)\ \mathbf{DFA}\ for\ (01\ \cup\ 001\ \cup\ 010)^*:$

<img src="https://user-images.githubusercontent.com/74255152/180084536-cccd9253-e026-4dbc-b15c-0ee26cbc85ed.png">

## $1.18$

$a.)\ 1\Sigma^*0$
$b.)\ \Sigma^*1\Sigma^*1\Sigma^*1\Sigma^*$
$c.)\ \Sigma^*0101\Sigma^*$
$d.)\ (0 \cup 1)^20\Sigma^*$
$e.)\ (0((0 \cup 1)(0 \cup 1))^+) \cup (1(0 \cup 1)((0 \cup 1)(0 \cup 1))^+)$
$f.)\ (0^*10^+1110^+1110^+1) \cup (0^*10^+1110^+11) \cup (0^*10^+1)$
$g.)\ (0 \cup 1)^n, n \in \{0,1,2,3,4,5\}$
$h.)\ \empty \cup \{1\} \cup (0 \cup 10 \cup 110 \cup 1110 \cup 1111)(\Sigma^*)$
$i.)\ (1(0 \cup 1))^*$
$j.)\ 00^+ \cup 100^+ \cup 00^+1 \cup 0^+10^+$
$k.)\ \empty \cup \{0\}$
$l.)\ 1^* \cup 1^*0(01^*0)^*01^* \cup 0^*10^*10^*$
$m.)\ \{\}$
$n.)\ \Sigma^+$

## $1.19$

### $a.)\ (0 \cup 1)^*000(0 \cup 1)^*$

<img src="https://user-images.githubusercontent.com/74255152/180600883-9c19ac4f-7c18-408a-9b5d-4ef432d0df3e.png">

### $b.)\ (((00)^*11) \cup 01)^*$

<img src="https://user-images.githubusercontent.com/74255152/180600885-ef38e345-064e-4f34-ae5c-764d3045ce15.png">

### $c.)\ \empty^*\ = \ \{\epsilon\}$

$\empty^*\ = \ \{\epsilon\}$

<img src="https://user-images.githubusercontent.com/74255152/180601034-92da4c95-5aaf-4bbb-812c-321f55c219b6.png">

## $1.20$

### $a.)\ a^*b^*$

**members:**

- $bbbbbbbb$
- $aaab$
 
**not members:**

- $baaa$
- $aabbba$

### $b.)\ a(ba)^*b$

**members:**

- $ab$
- $ababab$

**not members:**

- $b$
- $aba$

### $c.)\ a^* \cup b^*$

**members:**

- $\epsilon$
- $aaaaa$

**not members:**

- $ab$
- $aaba$

### $d.)\ (aaa)^*$

**members:**

- $\epsilon$
- $aaaaaa$

**not members:**

- $a$
- $aaabbaaa$

### $e.)\ \Sigma^*a\Sigma^*b\Sigma^*a\Sigma^*$

**members:**

- $aba$
- $bbabb\mathbf{a}abababab\mathbf{b}ababbbbbba\mathbf{a}bababababa$

**not members:**

- $\epsilon$
- $bbbbbbabbbbbbb$

### $f.)\ aba \cup bab$

**members:**

- $aba$
- $bab$

**not members:**

- $aab$
- $baba$

### $g.)\ (\epsilon \cup a)b$

**members:**

- $ab$
- $b$

**not members:**

- $a$
- $\epsilon$

### $h.)\ (a \cup ba \cup bb)\Sigma^*$

**members:**

- $\mathbf{ba}ababababaaaaba$
- $a$

**not members:**

- $\epsilon$
- $b$

## $1.21$

### $a.)\ a^*b(ba^*b \cup a)^*$

### $b.)\ \epsilon \cup (a \cup b)a^*b(((a(a \cup b)) \cup b)a^*b)^*a$

## $1.22$

$\Sigma\ =\ \{a,\ b,\ /,\ \#\}$

### $a.)$

<img src="https://user-images.githubusercontent.com/74255152/180603105-f70cd7cc-1321-4d89-bab4-e8d4066fbef2.png">

### $b.)\ /\#(a \cup b \cup /)^*\#(\# \cup ((a \cup b)(a \cup b \cup /)^*\#))^*/$

## $1.23$

$Let\ B\ be\ any\ language\ over\ the\ alphabet\ \Sigma.\ Prove\ that\ B\ =\ B^+\ iff\ BB \subseteq B.$ 

### $\mathbf{1.}\ B\ =\ B^+ \rArr BB \subseteq B$

$B\ =\ B^+ \rArr B\ =\ BB\ (*)$
$B \subseteq B\ (**)$
$(*),(**) \rArr BB \subseteq B$

### $\mathbf{2.}\ B\ =\ B^+ \lArr BB \subseteq B$

$BB \subseteq B\ (***)$
$w \in B^+ \rArr w\ =\ x_1x_2...x_k, x_i \in B,\ k \ge 1$
$x_1,\ x_2 \in B,\ (***) \rArr x_1x_2 \in B$
$x_1x_2,\ x_3 \in B,\ (***) \rArr x_1x_2x_3 \in B \rArr BBB \subseteq B$
$If\ we\ continue:\ x_1x_2...x_k \in B \rArr B^+ \subseteq B$

## $1.24$

<img src="https://user-images.githubusercontent.com/74255152/180610801-c753f604-da13-489d-bf64-3d2bf2d4770b.png">

### $a.)\ T_1\ on\ input\ 011$

$000$

### $b.)\ T_1\ on\ input\ 211$

$111$

### $c.)\ T_1\ on\ input\ 121$

$011$

### $d.)\ T_1\ on\ input\ 0202$

$0101$

### $e.)\ T_2\ on\ input\ b$

$1$

### $f.)\ T_2\ on\ input\ bbab$

$1111$

### $g.)\ T_2\ on\ input\ bbbbbb$

$110110$

### $h.)\ T_2\ on\ input\ \epsilon$

$\epsilon\ (the\ empty\ string)$

## $1.25$

### $Formal\ definition\ of\ \mathbf{FST}$

$A\ \mathbf{finite\ state\ transducer}\ is\ a\ 5-tuple\ (Q,\ \Sigma,\ \delta,\ q_0,\ \Gamma),\ where:$

$\mathbf{1.}\ Q\ is\ a\ finite\ set\ called\ the\ \mathbf{states},$
$\mathbf{2.}\ \Sigma\ is\ a\ finite\ set\ called\ the\ \mathbf{input\ alphabet},$
$\mathbf{3.}\ \delta:\ Q\ \times\ \Sigma \rarr\ Q\ \times\ \Gamma\ is\ the\ \mathbf{transducer\ function},$
$\mathbf{4.}\ q_0 \in Q\ is\ the\ \mathbf{start\ state},\ and$
$\mathbf{5.}\ \Gamma\ is\ the\ \mathbf{output\ alphabet}.$

## $1.26$

### $T_1$

$\mathbf{1.}\ Q\ =\ \{q_1,\ q_2\},$
$\mathbf{2.}\ \Sigma\ =\ \{0,\ 1,\ 2\},$
$\mathbf{3.}\ \delta\ is\ described\ as:$

|     |$0$  |$1$  |$2$  |
|:---:|:---:|:---:|:---:|
|$q_1$|$q_1 \times 0$|$q_1 \times 0$|$q_2 \times 1$     |
|$q_2$|$q_1 \times 0$|$q_2 \times 1$|$q_2 \times 1$     |


$\mathbf{4.}\ q_1\ is\ the\ start\ state, and$
$\mathbf{5.}\ \Gamma\ =\ \{0,1\}$

### $T_2$

$\mathbf{1.}\ Q\ =\ \{q_1,\ q_2,\ q_3\},$
$\mathbf{2.}\ \Sigma\ =\ \{a,\ b\},$
$\mathbf{3.}\ \delta\ is\ described\ as:$

|     |$a$  |$b$  |
|:---:|:---:|:---:|:---:|
|$q_1$|$q_2 \times 1$|$q_3 \times 1$ |
|$q_2$|$q_3 \times 1$|$q_1 \times 0$ |
|$q_3$|$q_1 \times 0$|$q_2 \times 1$ |


$\mathbf{4.}\ q_1\ is\ the\ start\ state, and$
$\mathbf{5.}\ \Gamma\ =\ \{0,1\}$


## $1.27$

$Give\ the\ state\ diagram\ of\ an\ \mathbf{FST}\ the\ following\ behavior:$
$\Sigma\ =\ \Gamma\ =\ \{0,\ 1\}$
$Its\ output\ string\ is\ identical\ to\ the\ input\ string\ on\ the\ even\ positions$
$but\ inverted\ on\ the\ odd\ positions$

<img src="https://user-images.githubusercontent.com/74255152/180613188-1ff85e3a-429e-4a03-8b6a-9b2a760ecaf9.png">

## $1.28$

$\Sigma\ =\ \{a,\ b\}$

### $a.)\ a(abb)^* \cup b$

<img src="https://user-images.githubusercontent.com/74255152/180613832-022d51e8-0d1a-4a02-be94-f94559b98719.png">

### $b.)\ a^+ \cup (ab)^+$

<img src="https://user-images.githubusercontent.com/74255152/180613833-c093a827-96cc-4d10-ae84-ec1649caa2b3.png">

### $c.)\ (a \cup b^+)a^+b^+$

<img src="https://user-images.githubusercontent.com/74255152/180613835-ac1dc4dc-58e3-4194-b401-363a2e2803b8.png">

## $1.29$

### $a.)\ A_1 = \{0^n1^n2^n\ |\ n \geq 0\}$

$\mathbf{Assumption:}$
$Assume\ that\ A_1\ is\ regular.\ Let\ p\ be\ the\ pumping\ length.$
$Choose\ s\ to\ be\ the\ string\ 0^p1^p2^p.\ Because\ s\in A_1\ and\ |s| \ge p,$
$the\ pumping\ lemma\ guarantees\ that\ s\ can\ be\ split\ into\ three\ pieces,$
$s = xyz,\ where\ for\ any\ i \ge 0\ the\ string\ xy^iz \in A_1$. 

$\mathbf{Contradiction:}$
$y\ consists\ only\ of\ 0s\ and\ 1s.\ In\ this\ case$
$xyyz\ may\ have\ the\ same\ number\ of\ 0s\ and\ 1s\,\ but\ they\ will\ be$
$out\ of\ order\ and\ be\ twice\ as\ many\ as\ the\ number\ of\ 2s.$

$\mathbf{Conclusion:}$
$Thus,\ we\ have\ a\ contradiction\ and\ our\ initial\ assumption\ is\ false,$
$so\ A_1\ is\ not\ regular\ (\mathbf{qed}).$

### $b.)\ A_2 = \{www\ |\ w \in \{a,\ b\}^*\}$

$\mathbf{Assumption:}$
$Assume\ that\ A_2\ is\ regular.\ Let\ p\ be\ the\ pumping\ length.$
$Also,\ given\ the\ definition\ of\ A_2,\ we\ can\ deduce\ that\ any\ string$
$from\ A_2\ has\ length\ in\ M_3\ (multiples\ of\ 3)\ (*).$
$Choose\ s\ to\ be\ the\ string\ www,\ where\ w\ has\ length\ p.$
$Because\ s \in A_2\ and\ |s| \geq A_2,\ the\ pumping\ lemma\ guarantees\ that$
$s\ can\ be\ split\ into\ three\ pieces,\ s = xyz,\ where\ for\ any\ i \ge 0$
$the\ string\ xy^iz\ \in A_2.$

$\mathbf{Contradiction:}$
$x = \epsilon,\ y= ww\ and\ z = w.\ In\ this\ case\ xyyz\ has\  length\ in\ M_5\ (multiples\ of\ 5),$
$which\ contradicts\ (*).$

$\mathbf{Conclusion:}$
$Thus,\ we\ have\ a\ contradiction\ and\ our\ initial\ assumption\ is\ false,$
$so\ A_2\ is\ not\ regular\ (\mathbf{qed}).$

### $c.)\ A_3 = \{a^{2^n}\ |\ n \geq 0\}$

$\mathbf{Assumption:}$
$Assume\ that\ A_3\ is\ regular.\ Let\ p\ be\ the\ pumping\ length.$
$Choose\ s\ to\ be\ the\ string\ a^{2^p}.\ Because\ s \in A_3\ and\ s \geq p,$
$the\ pumping\ lemma\ guarantees\ that\ s\ can\ be\ split\ into\ three\ pieces,$
$s = xyz,\ where\ for\ any\ i \geq 0\ the\ string\ xy^iz \in A_3.$
$Given\ the\ definition\ of\ A_3,\ any\ string\ in\ A_3\ contains\ 2^n\ a's, n \ge 0.$
$This\ results\ in\ an\ even\ number\ of\ a's\ for\ any\ string\ in\ A_3\ (*).$

$\mathbf{Contradiction:}$
$x = \epsilon,\ y = a^{2^p - 1}\ and\ z = a.\ In\ this\ case\ xyyz = a^{2^p - 1}a^{2^p - 1}a = a^{2^{p + 1} - 1},$
$which\ means\ s\ has\ an\ odd\ number\ of\ a's,\ which\ contradicts\ (*).$

$\mathbf{Conclusion:}$
$Thus,\ we\ have\ a\ contradiction\ and\ our\ initial\ assumption\ is\ false,$
$so\ A_3\ is\ not\ regular\ (\mathbf{qed}).$

## $1.30$

$The\ error\ lies\ in\ the\ choosing\ of\ s = 0^p1^p.\ The\ chosen\ string\ needs\ to$
$cover\ all\ strings\ in\ 0^*1^*\ which\ are\ of\ length\ at\ least\ p.\ s\ only\ covers\ a$
$general\ subset\ of\ those,\ so\ the\ proof\ is\ faulty.$

## $1.31$

$Because\ A\ is\ regular,\ it\ means\ it\ can\ be\ pumped.\ Let\ p\ be\ the\ pumping\ length,$
$and\ s \in A,\ |s| \geq p.\ This\ means\ s\ can\ be\ split\ into\ three\ pieces,\ s = xyz,\ where\ for$
$any\ i \geq 0\ the\ string\ xy^iz \in A.$
$s^R = zy^ix,\ s \in A^R,\ |s^R| = |s| \geq p \rArr Any\ string\ in\ A^R\ of\ length\ at\ least\ p\ can\ be\ pumped$
$\rArr A^R\ is\ regular\ (\mathbf{qed}).$

## $1.32$

$\mathbf{Show\ that\ B\ is\ regular.}$

$In\ order\ to\ prove\ that\ B\ is\ regular,\ we\ can\ prove\ that\ B^R\ is\ regular\ (ex.\ 1.31).$

$So,\ we\ construct\ an\ NFA\ for\ B^R:$

<img src="https://user-images.githubusercontent.com/74255152/180668939-6b9f3739-ea44-489b-afae-9383508a0282.png">

$B^R\ can\ be\ simulated\ by\ an\ NFA \rArr B^R\ is\ regular \rArr B\ is\ regular\ (\mathbf{qed}).$

## $1.33$

$\mathbf{Show\ that\ C\ is\ regular.}$

$\mathbf{Remark:}\ the\ triple\ of\ a\ number\ in\ binary\ is\ the\ sum$
$of\ the\ number\ itself\ with\ its\ 1\ bit\ left-shifted\ value\ (its\ double).$

$Also,\ we\ are\ going\ to\ prove\ that\ C^R\ is\ regular,\ because\ it's\ simpler.$

$So,\ we\ construct\ an\ NFA\ for\ C^R:$

<img src="https://user-images.githubusercontent.com/74255152/180669285-1799e2f6-c468-4fb0-ac1b-4e65ee47961f.png">

$C^R\ can\ be\ simulated\ by\ an\ NFA \rArr C^R\ is\ regular \rArr C\ is\ regular\ (\mathbf{qed}).$

## $1.34$

$\mathbf{Show\ that\ D\ is\ regular.}$

$We\ are\ going\ to\ prove\ that\ D^R\ is\ regular,\ because\ it's\ simpler.$

$So,\ we\ construct\ an\ NFA\ for\ D^R:$

<img src="https://user-images.githubusercontent.com/74255152/180669491-c468d722-2e8d-49f4-a12e-41deedd62682.png">

$D^R\ can\ be\ simulated\ by\ an\ NFA \rArr D^R\ is\ regular \rArr D\ is\ regular\ (\mathbf{qed}).$

## $1.35$

$\mathbf{Show\ that\ E\ is\ not\ regular.}$

$\mathbf{Assumption:}$
$Assume\ that\ E\ is\ regular.\ Let\ p\ be\ the\ pumping\ length.$
$Choose\ s\ to\ be\ a\ string\ from\ E\ of\ length\ bigger\ than\ p.\ Because\ s \in E\ and\ s \geq p,$
$the\ pumping\ lemma\ guarantees\ that\ s\ can\ be\ split\ into\ three\ pieces,$
$s = xyz,\ where\ for\ any\ i \geq 0\ the\ string\ xy^iz \in E.$

$\mathbf{Contradiction:}$
$s\ is\ of\ the\ form\ zs',\ where\ z\ is\ the\ first\ character$
$in\ s,\ and\ s'\ is\ the\ tail\ of\ s.$
$x = z,\ y = s',\ z = \epsilon$
$Let's\ assume\ that\ the\ top\ row\ is\ formed\ of\ alternating\ 1s\ and\ 0s,$
$with\ the\ last\ bit\ being\ the\ first\ bit\ flipped.$
$This\ means\ that\ the\ bottom\ row\ is\ of\ the\ same\ form,\ but\ starting$
$with\ the\ first\ bit\ flipped.$
$For\ the\ sake\ of\ the\ demonstration,\ We'll\ go\ with\ the\ first\ bit\ being\ 0.$
$Thus,\ x = [0|1],\ y = [10101...1|01010...0],\ z = \epsilon.$
$xyyz = [010101...\mathbf{1}10101...1/101010...\mathbf{0}01010...0]$
$The\ bottom\ row\ now\ has\ a\ bit\ which\ is\ incorrect,\ so\ xyyz \notin E.$

$\mathbf{Conclusion:}$
$Thus,\ we\ have\ a\ contradiction\ and\ our\ initial\ assumption\ is\ false,$
$so\ E\ is\ not\ regular\ (\mathbf{qed}).$

## $1.36$

$B_n = \{a^k\ |\ where\ k\ is\ a\ multiple\ of\ n\}$

$\mathbf{Show\ that\ for\ each\ n \geq 1,\ the\ language\ B_n\ is\ regular.}$

$Giving\ a\ formal\ description\ of\ our\ DFA\ is\ easier\ than\ drawing\ a\ state\ diagram.$

$For\ B_n:$
$\mathbf{1.}\ Q = {m_0,\ m_1,\ m_2\ ...\ m_{n-1}}$
$The\ states\ represent\ the\ remainder\ of\ the\ current\ length\ when\ divided\ by\ n,$
$\mathbf{2.}\ \Sigma = \{a\}$
$\mathbf{3.}\ \delta:$
$a.)\ for\ k \le n - 2:$

| |a|
|:---:|:---:|
|$m_k$|$m_{k+1}$|

$b.)\ for\ k = n - 1:$
| |a|
|:---:|:---:|
|$m_{n-1}$|$m_0$|

$\mathbf{4.}\ The\ start\ state\ is\ m_0.$
$\mathbf{5.}\ F = \{m_0\}$

## $1.37$

$C_n = \{x\ |\ x\ is\ a\ binary\ number\ that\ is\ a\ multiple\ of\ n\}$

$\mathbf{Show\ that\ for\ each\ n \geq 1,\ the\ language\ C_n\ is\ regular.}$

## $1.38$

