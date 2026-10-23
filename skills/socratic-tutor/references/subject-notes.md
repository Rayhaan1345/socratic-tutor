# Subject notes

For a subject: what to ask first, the blockers that come up most and the question that moves the student past them, and what to give plainly because it is recall rather than reasoning.

## Mathematics

**Ask first.** "Which method, and why that one?" The plan before the algebra. If they have no plan, go to rung 2 of the ladder.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Sign errors when moving terms | 2x - 5 = 3 becomes 2x = -2 | "What did you do to both sides to get rid of the -5?" |
| Dividing before isolating | Divides one term by the coefficient and not the other | "Does the 2 multiply the whole left side or only the x?" |
| Quadratics with a leading coefficient | Factors as if the coefficient were 1 | "What must the first terms of the two brackets multiply to give?" |
| Formula without meaning | Plugs into the quadratic formula and cannot say why | "What does the discriminant tell you before you finish the calculation?" |
| Fractions | Adds numerators and denominators separately | "If you had 1/2 of a pizza and 1/3 of another, is that 2/5 of a pizza?" |
| Functions as objects | Treats f(x + 1) as f(x) + 1 | "If f(x) = x^2, what is f(3)? And f(3 + 1)?" |
| Derivative as a rule, not a rate | Differentiates correctly and cannot interpret the result | "Your answer is 6. Six of what, per what?" |
| Chain rule | Differentiates the outside and forgets the inside | "What is the inside function here, and what is its derivative on its own?" |
| Integration constant | Drops + C, or cannot use the initial condition | "How many functions have this derivative? What does the given point pick out?" |
| Word problems | Starts computing before writing the quantities | "Write the quantities with units first. Which one is the unknown?" |
| Proof by induction | Writes the base case and restates the claim for n + 1 without using the hypothesis | "Where in your n + 1 step did you use the fact that it holds for n?" |
| Proof in general | Cannot start | "What is given, what is to be shown, and which result you know connects them?" |
| Probability | Adds probabilities of events that are not mutually exclusive | "Can both of these happen at once? What does that do to your sum?" |
| Statistics | Computes a mean and cannot say what the spread tells them | "Two classes have the same mean. What would make you prefer to be in one of them?" |

**Give plainly.** Formulae they are expected to look up, standard identities, the names of methods, arithmetic they have set up correctly and asked you to check.

**Checking.** Before the final answer, ask for one check they can do themselves: substitute back, test a special case, check units or the order of magnitude.

## Physics

**Ask first.** "What is given, what is unknown, and can you draw it?" A diagram or a list of knowns and unknowns before any formula.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Force and motion | Thinks a moving object needs a force to keep moving | "A puck slides on ice with no friction. What force keeps it going?" |
| Net force | Uses one force when several act | "Draw the block. Which forces act on it?" |
| Newton's third law pairs | Treats action and reaction as acting on the same body | "The two forces in a pair act on which bodies?" |
| Mass and weight | Uses kg where newtons are needed | "What are the units of the quantity you need in this formula?" |
| Energy conservation | Tracks kinetic energy and forgets friction or height | "Where could the energy be at the end?" |
| Circuits | Thinks current is used up along a series circuit | "If current were used up, what would happen to the charge that flows into the bulb?" |
| Series and parallel | Adds resistors in parallel | "Adding a parallel path makes it easier or harder for current to flow?" |
| Vectors | Adds magnitudes of vectors at an angle | "If you walk 3 m east and 4 m north, how far are you from the start?" |
| Units | Reaches a number with no units | "What are the units of your answer, and is the size reasonable?" |
| Graphs | Reads the value where the slope is needed | "On this graph, what does the slope represent? And the area?" |

**Give plainly.** Constants, unit conversions, the statement of a law they ask for by name.

## Chemistry

**Ask first.** "What is reacting, and what is the balanced equation?" Most quantitative mistakes come from an unbalanced equation or a skipped mole step.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Moles | Goes straight from grams of A to grams of B | "What quantity does the balanced equation compare: grams or moles?" |
| Limiting reagent | Uses the reactant given first | "Which reactant runs out first? How would you decide?" |
| Balancing | Changes subscripts to balance | "If you change H2O to H2O2, is it still water?" |
| Concentration | Confuses moles with molarity | "How much solution is this dissolved in? Does the volume matter?" |
| Equilibrium | Thinks equilibrium means equal amounts | "What is equal at equilibrium: the amounts, or the rates?" |
| Le Chatelier | Predicts the shift and cannot say why | "The system is pushed. Which direction reduces the push?" |
| Acids and bases | Equates strong with concentrated | "Can you have a dilute solution of a strong acid? What would its pH depend on?" |
| Bonding | Calls a bond ionic or covalent by element type alone | "How different are the electronegativities of these two atoms?" |

**Give plainly.** Atomic masses, constants, the formula of a named compound, names of apparatus.

## Biology

**Ask first.** "Which system or process is this about, and what is it for?" Biology questions are usually about function; students memorise structure and miss the purpose.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Memorised steps without mechanism | Lists stages of a process and cannot say what a stage achieves | "What would go wrong if this stage were skipped?" |
| Feedback loops | Describes a change and misses the response | "The body detects this. What does it do to bring the value back?" |
| Genetics crosses | Gives a gamete two alleles of one gene | "How many alleles for this gene end up in a gamete?" |
| Natural selection | Says organisms adapt because they need to | "Does the giraffe stretch its neck, or do longer-necked giraffes leave more offspring?" |
| Enzymes | Says enzymes are used up or killed by heat | "What does heat do to the shape of a protein? Why would shape matter?" |
| Experiments | Cannot name the variables | "What did you change, what did you measure, and what did you keep the same?" |
| Scale | Confuses cell, tissue, organ, system | "Is a neuron a cell, a tissue or an organ? What is the brain?" |

**Give plainly.** Definitions, the function of a named structure, the names of stages.

## Programming

**Ask first.** "What do you expect this to print on one small input, and what does it print?" Prediction before running. If they have not run it, ask them to.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Off-by-one | Loop runs one time too many or too few | "What is the value of the loop variable on the last pass? Is that the index you meant?" |
| Accumulator reset | Total is reset inside the loop | "What is `total` after the first iteration? And the second?" |
| Assignment and comparison | `=` where `==` is meant | "What does this line do to the variable, and what did you want it to do?" |
| Integer division | 7 / 2 gives 3 in some languages | "What type are the two numbers in this division?" |
| Mutation while iterating | Removes items from a list in a for loop over it | "What happens to the indices when you delete the second item?" |
| Scope | Changes a variable inside a function and expects it outside | "Where does this variable live? Who can see it?" |
| Recursion | No base case, or the recursive call does not shrink the problem | "On the smallest possible input, what should the function return without calling itself?" |
| Reading errors | Pastes the traceback without reading it | "Which line does the error name, and what does the last sentence of the message say?" |
| Debugging by changing things | Edits at random until it works | "What is the smallest input that still shows the bug?" |
| Nested structures | Confuses a list of lists with a flat list | "What is `data[0]`? And `data[0][0]`?" |

**Give plainly.** Syntax, the name of a library function, what an error message means, how to print a variable. Syntax is recall.

**Never** paste a complete corrected program. Point at one line with a question. If they ask for the fix after two attempts, show the corrected line and ask them to explain why it works.

## Writing and essays

**Ask first.** "What is your claim, in one sentence, and what is the strongest evidence for it?" An essay without a claim cannot be fixed at the sentence level.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| No thesis | The introduction describes the topic and takes no position | "If someone disagreed with your essay, what would they be disagreeing with?" |
| Summary instead of argument | Paragraphs retell the source | "This paragraph tells me what happens. What does it show?" |
| Evidence without analysis | A quotation followed by a new topic | "What does this quotation prove that the previous sentence did not?" |
| Paragraph with two ideas | A paragraph changes subject in the middle | "Which sentence in this paragraph does the work? Which could go?" |
| Vague words | "Many factors", "very important", "society" | "Which factors? Important to whom?" |
| No counterargument | The essay never considers the other side | "What is the best objection to your claim, and what is your answer to it?" |
| Weak conclusion | Restates the introduction | "What does the reader know now that they did not know at the start?" |

**Give plainly.** Spelling, a word's meaning, a citation format, the convention of a genre they ask about.

**Never** rewrite their paragraph. Quote one phrase and ask what it is trying to say. If they ask for a model sentence after two attempts, give one sentence on a different topic that shows the structure.

## Languages

**Ask first.** "Try the sentence first, then we fix it." An attempt before any correction.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Word-for-word translation | Native-language word order | "In the language you are learning, where does the verb go in this kind of sentence?" |
| Agreement | Adjective does not match the noun | "What is the gender and number of the noun? What does that do to the adjective?" |
| Tense | Uses present for a completed action | "When did this happen: now, before, or after? Which tense marks that?" |
| False friends | Uses a look-alike word with a different meaning | "What does that word mean in the language you are learning? Check it." |

**Give plainly.** Vocabulary, conjugation tables, pronunciation. Vocabulary is recall.

Correct at most two errors per turn, the ones that affect meaning first.

## History, economics and other essay subjects

**Ask first.** "What is the question actually asking: describe, explain, compare, or evaluate?" Students answer the question they expected rather than the one set.

**Blockers and the question that unblocks them**

| Blocker | What it looks like | Question |
| --- | --- | --- |
| Narrative instead of analysis | Tells the story in order | "The question asks why. Which of these events caused which?" |
| Single cause | One reason for a complex event | "If that cause were removed, would the event still have happened? What else was needed?" |
| Source as fact | Treats a source as true because it is old or official | "Who wrote this, for whom, and what did they want the reader to think?" |
| Economics diagrams | Draws the shift without saying why | "What changed for buyers or sellers that moves this curve?" |
| Economics as morality | Says a price is unfair instead of explaining it | "What would happen to the quantity demanded at the lower price you prefer?" |
| Definitions | Uses a technical term loosely | "Define that term as your textbook does. Does your sentence still hold?" |

**Give plainly.** Dates, names, definitions, the content of a named treaty or policy.

## When the subject is not listed

Use the ladder. Ask what the question is asking, what they know that is relevant, and what they have tried. Give recall plainly and question the reasoning.
