---
layout: post
title: "Yeasayers, naysayers and non-voters"
subtitle: "Italians justifications for their vote in the 2026 referendum on the judiciary"
tags: [referendums, public opinion, Italy, text analysis, survey research]
thumbnail-img: /assets/img/posts/referendum-2026/registers-yes-no.png
share-description: "Two thousand open-ended justifications from the March 2026 Italian constitutional referendum: the two camps argued from different registers but the sharpest divide ran between voters and non-voters."
---

On 22 and 23 March 2026, Italian voters rejected the constitutional reform of the judiciary that the Meloni government had steered through Parliament in October 2025. The reform would have separated the careers of judges and prosecutors, split the *Consiglio Superiore della Magistratura* in two, introduced random selection (*sorteggio*) of its members and created a separate High Disciplinary Court. Within Italy, the No won 53.7 to 46.3 per cent on a turnout of 58.9 per cent, far above the roughly 30 per cent of the abrogative referendums held in June 2025.

Earlier this month I presented a paper at the [SISP](https://www.sisp.it/) annual conference in Trento that asks a simple question about that vote: **how did Italian citizens justify their voting choice?** Was it a verdict on the reform, a defence of the Constitution, or a vote on the government? This post summarises the main results.

## Letting voters speak for themselves

Constitutional referendums on institutional design are hard cases for theories of citizen competence. The object of the vote is technical and remote from everyday life, and it is easily translated into a simpler question: do you support this government or not? Optimists argue that voters use cues competently and end up voting on the substance. On the other side, pessimists expect second-order voting, status-quo bias and partisan alignment.

Both camps make claims about the *content* of citizens' reasoning, but they usually test them with closed-ended vote-choice data, inferring motivation from whatever covariates predict the vote. The problem is that the same vote can be reached along very different paths.

The paper takes a different route. It relies on a two-wave online panel fielded by Demetra for CISE and the University of Southern Denmark: a first wave in February 2026, about a month before the vote (n = 2,520), and a second immediately afterwards (n = 2,192). Right after reporting their vote, respondents were asked to explain in their own words why they voted Yes, why they voted No, or why they did not vote. The analysis covers **2,005 unprompted justifications**: 629 from Yes voters, 1,179 from No voters and 197 from abstainers.

The texts are analysed with keyness statistics, Jensen–Shannon divergence between the three groups' vocabularies, and a purpose-built dictionary that classifies each answer into argumentative registers: the **merit** of the reform (careers, CSM, *sorteggio*, judicial factions), the **constitutional** register (the Constitution, the method of revision, the role of Parliament) and the **partisan** register (government, parties, leaders, the campaign). Because the attitudinal measures come from the pre-vote wave, the arguments people give after voting can be linked to what they thought a month earlier.

## The argument: asymmetric repertoires

The paper's central claim is that, in a confirmatory referendum on a government-sponsored reform, the two camps do not have the same arguments at their disposal.

The Yes side supports a change. To justify it, a voter has to say something about what the reform does and why it is desirable. The No side can do that too, but it can also draw on two further registers. The first is **constitutional**: the Constitution should not be touched, a register that requires little evaluation of the reform's content because it appeals to the status quo as such. The second is **second-order**: because the reform belongs to the government, voting against it is directly available as a vote against the government, in a way that a Yes is not equally available as a vote for it.

If this is right, the question "was it issue voting or second-order voting?" is badly posed for the contest as a whole. The answer can be both, on different sides of the same ballot.

## Finding 1: the sharpest divide is between voters and non-voters

The first result was not the one I expected. The two voting camps look almost identical on political sophistication, and they are sharply opposed on ideology and on institutional trust. Abstainers sit on a different axis altogether.

| | Yes | No | Non-voters |
|:--|--:|--:|--:|
| Words per answer (mean) | 13.0 | 17.5 | 9.5 |
| Minimal answers (≤ 2 words) | 8.9% | 3.0% | 14.7% |
| Left–right (0–10) | 7.59 | 3.35 | 5.51 |
| Trust in the judiciary (0–10) | 3.53 | 5.77 | 3.56 |
| Trust in government (0–10) | 5.81 | 2.24 | 2.96 |
| Party-position knowledge (0–6) | 4.49 | 4.49 | 2.78 |
| Campaign attention (0–4) | 2.56 | 2.59 | 1.80 |
| University degree | 29.6% | 35.5% | 18.8% |

*Table 1. Means and proportions of selected characteristics of the three groups. Attitudinal and knowledge measures come from the pre-vote wave.*

The lexical distances make the same point. The language of abstention is more than twice as far from the language of the Yes as the language of the No is.

| Pair | Jensen–Shannon distance |
|:--|--:|
| Yes vs No | 0.275 |
| Yes vs Non-voters | 0.618 |
| No vs Non-voters | 0.527 |

*Table 2. Distance between the three groups' vocabularies.*

Yes and No voters, however opposed, are talking about the same object. Abstainers are talking about something else. The word *magistratura* never appears in the abstainers' answers, against 300 occurrences among voters, and *costituzione* appears once against 260. Their most distinctive words are *salute*, *residenza*, *fuori*, *sede* and *familiari*, with a smaller nucleus of explicit disaffection (*interessa*, *niente*, *capito*).

![Distinctive vocabulary of each group](/assets/img/posts/referendum-2026/keyness-by-group.png){: .mx-auto.d-block}

*Figure 1. Distinctive words of each group compared with the other two (keyness, log-likelihood ratio G²). Bigrams are joined by an underscore.*

## Finding 2: two camps, two vocabularies

Between the two voting camps, the difference is not one of emphasis within a shared vocabulary. The Yes lexicon is technical and reform-centred: *giudici*, *magistrati*, *separazione_carriere*, *correnti*, *giusto*, *imparziale*. The No lexicon is institutional and procedural: *costituzione*, *governo*, *parlamento*, *maggioranza*, and above all the bigrams *costituzione_tocca*, *cambiare_costituzione* and *modificare_costituzione*.

Those three bigrams occur 47, 40 and 31 times among No voters and **exactly zero times** among Yes voters. Symmetrically, *giudice* appears 28 times among Yes voters and twice among No voters, and *correnti* 21 times against once.

The dictionary coding confirms the pattern. The merit register is the modal register of the Yes camp, while the constitutional register is almost exclusively a No register.

![Argumentative registers among Yes and No voters](/assets/img/posts/referendum-2026/registers-yes-no.png){: .mx-auto.d-block}

*Figure 2. Share of Yes and No voters using each argumentative register (dictionary coding; conservative estimates). Labels, from top: Constitution, partisan cue, the judiciary, merit.*

The gap survives controls for response length, political knowledge, campaign attention, education, age and gender:

| Register | No − Yes (AME) | 95% CI | p |
|:--|--:|:--:|--:|
| Merit | −0.222 | [−0.265; −0.179] | < 0.001 |
| Constitutional | +0.390 | [0.356; 0.423] | < 0.001 |

*Table 3. Average marginal differences between No and Yes voters in register use (logistic regressions, robust standard errors, n = 1,808).*

This separation is not explained by sophistication, since the two camps are indistinguishable on campaign attention and knowledge of party positions. And because the dictionary penalises short answers, which are more common among Yes voters, the merit gap is probably understated.

## Finding 3: second-order voting as a resource

The partisan register is more frequent among No voters (11.9 percentage points more than among Yes voters) but two null results qualify this.

First, the strongest single predictor of the partisan register is not political at all: it is **how much the respondent wrote**. People who write more touch on more themes, and the government is one of the themes available. Second, neither political knowledge, nor campaign attention, nor education, nor partisan identification has a significant effect. In these data, the partisan register is not a shortcut used by the poorly informed.

| Term | AME | 95% CI | p |
|:--|--:|:--:|--:|
| Vote group (No − Yes) | 0.119 | [0.085; 0.153] | < 0.001 |
| log(words) | 0.143 | [0.123; 0.163] | < 0.001 |
| Factual political knowledge | 0.018 | [−0.002; 0.038] | 0.072 |
| Campaign attention | 0.015 | [−0.006; 0.036] | 0.154 |
| University degree | 0.012 | [−0.026; 0.049] | 0.538 |
| Partisan identifier | 0.013 | [−0.024; 0.051] | 0.494 |

*Table 4. Average marginal effects on the partisan register (Yes and No voters).*

## Finding 4: both No registers are anchored in pre-vote attitudes

If the partisan register were just a by-product of verbosity, it would not be tied to anything political. If the argument holds, the constitutional register should be rooted in trust in the judiciary, whose independence it claims to defend, and the partisan register in distrust of the government that wrote the reform. And both associations should appear only among No voters, since the Yes camp does not have access to these registers.

That is exactly what happens. Among No voters, each additional point of trust in the judiciary, measured a month before the vote, raises the probability of using the constitutional register. Each additional point of trust in the government lowers the probability of using the partisan register. Among Yes voters, both slopes are flat.

![Attitudinal anchoring of the two No registers](/assets/img/posts/referendum-2026/attitudinal-anchoring.png){: .mx-auto.d-block}

*Figure 3. Predicted probability of using the constitutional register by trust in the judiciary (top) and the partisan register by trust in government (bottom), by vote group. Green = Yes, red = No; bands are 95% confidence intervals. Trust is measured in the pre-vote wave.*

So the constitutional register is not an empty rhetorical container activated by the vote choice. It is anchored in a specific predisposition towards judicial power, which a purely plebiscitary reading of the referendum would not predict. The partisan register instead is a resource available to opponents of the reform, not the engine of the opposition.

## Finding 5: two kinds of abstainers

Abstention is usually treated as a residual category. The answers suggest otherwise: non-voters split into a **practical** group (away from their registered constituency, illness, work or family obligations) and an **attitudinal** group (disengagement, protest, distrust of politics, feeling unable to decide).

| Type | N | Interest | Knowledge | Trust gov. | Trust judiciary | Sat. democracy | Degree |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Attitudinal abstainers | 42 | 1.98 | 0.85 | 1.86 | 2.38 | 2.76 | 7.1% |
| Unclassified abstainers | 106 | 2.01 | 0.88 | 2.91 | 3.54 | 3.87 | 19.8% |
| Practical abstainers | 49 | 2.16 | 0.91 | 4.02 | 4.63 | 4.51 | 26.5% |
| No voters | 1,179 | 2.65 | 1.40 | 2.24 | 5.77 | 4.71 | 35.5% |
| Yes voters | 629 | 2.67 | 1.30 | 5.81 | 3.53 | 5.33 | 29.6% |

*Table 5. Means and proportions of the two types of abstainers and voters.*

The numbers are small, and the analysis is exploratory, but the picture is consistent. The two types do not differ in political interest or knowledge; they differ in trust. The practical abstainer is essentially an ordinary voter who could not vote. The attitudinal abstainer is systematically more distrustful of every institution. Attitudinal abstention looks less like a cognitive deficit than like a position.

## What this means

Three conclusions stand out.

1. **The primary cleavage is not Yes versus No.** The discourse of abstention differs in kind, not in degree, from the discourse of voting.
2. **The asymmetry between the camps is structural.** The Yes camp talked about the reform, while the No camp talked about the Constitution and about the method. That follows from the structure of a confirmatory referendum on a government proposal, and it counsels caution in reading the outcome as a verdict on the reform's content.
3. **Second-order voting is a property of positions.** The partisan register exists, is more common among opponents and is rooted in distrust of the government, but it remains a minority register. It is a weaker second-order signal than the one found for the 2016 Renzi referendum.

Still, whether "the Constitution should not be amended by a bare parliamentary majority for its own purposes" counts as a substantive constitutional judgement or as a heuristic substitute for one is a normative question these data cannot settle.

## Caveats

This is work in progress. Like most post-electoral online panels, the sample over-reports turnout and over-represents the No.

*The paper, "Yeasayers, Naysayers, and Non-Voters: Argumentative Repertoires in the 2026 Italian Constitutional Referendum on the Judiciary", was presented at the 2026 SISP Annual Conference, University of Trento, 3–5 September 2026. Comments are very welcome.*
