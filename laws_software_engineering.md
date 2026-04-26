# Laws of Software Engineering

> A collection of 56 principles and patterns that shape software systems, teams, and decisions.
> Source: [lawsofsoftwareengineering.com](https://lawsofsoftwareengineering.com/) by Dr. Milan Milanović

---

## 🏗️ Architecture

| Law | Principle |
|-----|-----------|
| **Conway's Law** | Organizations design systems that mirror their own communication structure. |
| **Hyrum's Law** | With enough API users, all observable behaviors will be depended on by somebody. |
| **Gall's Law** | A complex system that works evolved from a simple system that worked. |
| **Law of Leaky Abstractions** | All non-trivial abstractions, to some degree, are leaky. |
| **Tesler's Law** | Every application has irreducible complexity that can only be shifted, not eliminated. |
| **CAP Theorem** | A distributed system can guarantee only two of: consistency, availability, partition tolerance. |
| **Second-System Effect** | Small, successful systems tend to be followed by overengineered replacements. |
| **Fallacies of Distributed Computing** | Eight false assumptions that new distributed system designers often make. |
| **Law of Unintended Consequences** | Whenever you change a complex system, expect surprises. |
| **Zawinski's Law** | Every program attempts to expand until it can read mail. |

---

## 👥 Teams

| Law | Principle |
|-----|-----------|
| **Conway's Law** | Teams' communication structure is mirrored in the systems they build. |
| **Brooks's Law** | Adding manpower to a late software project makes it later. |
| **Dunbar's Number** | A person can maintain roughly 150 stable relationships. |
| **Ringelmann Effect** | Individual productivity decreases as group size increases. |
| **Price's Law** | The square root of the total contributors does 50% of the work. |
| **Putt's Law** | Those who understand technology don't manage it; those who manage it don't understand it. |
| **Peter Principle** | In a hierarchy, every employee tends to rise to their level of incompetence. |
| **Bus Factor** | The minimum number of team members whose loss would put the project in serious trouble. |
| **Dilbert Principle** | Companies promote incompetent employees to management to limit the damage they can do. |

---

## 📅 Planning

| Law | Principle |
|-----|-----------|
| **Premature Optimization (Knuth)** | Premature optimization is the root of all evil. |
| **Parkinson's Law** | Work expands to fill the time available for its completion. |
| **Ninety-Ninety Rule** | The first 90% of code takes 90% of the time; the last 10% takes another 90%. |
| **Hofstadter's Law** | It always takes longer than expected, even when accounting for Hofstadter's Law. |
| **Goodhart's Law** | When a measure becomes a target, it ceases to be a good measure. |
| **Gilb's Law** | Anything you need to quantify can be measured in some way better than not measuring it. |

---

## ✅ Quality

| Law | Principle |
|-----|-----------|
| **Boy Scout Rule** | Leave the code better than you found it. |
| **Murphy's Law** | Anything that can go wrong will go wrong. |
| **Postel's Law** | Be conservative in what you do; be liberal in what you accept. |
| **Broken Windows Theory** | Don't leave bad designs, wrong decisions, or poor code unrepaired. |
| **Technical Debt** | Everything that slows development down over time due to shortcuts taken earlier. |
| **Linus's Law** | Given enough eyeballs, all bugs are shallow. |
| **Kernighan's Law** | Debugging is twice as hard as writing the code in the first place. |
| **Testing Pyramid** | Many unit tests → fewer integration tests → very few UI tests. |
| **Pesticide Paradox** | Repeatedly running the same tests becomes less effective over time. |
| **Lehman's Laws** | Software reflecting the real world must evolve, and that evolution has predictable limits. |
| **Sturgeon's Law** | 90% of everything is crap. |

---

## 📈 Scale

| Law | Principle |
|-----|-----------|
| **Amdahl's Law** | Speedup from parallelization is limited by the fraction that cannot be parallelized. |
| **Gustafson's Law** | Significant speedup is achievable by increasing the problem size in parallel processing. |
| **Metcalfe's Law** | The value of a network is proportional to the square of the number of users. |

---

## 🎨 Design

| Law | Principle |
|-----|-----------|
| **YAGNI** | Don't add functionality until it is necessary. |
| **DRY** | Every piece of knowledge must have a single, unambiguous, authoritative representation. |
| **KISS** | Designs and systems should be as simple as possible. |
| **SOLID Principles** | Five guidelines that make code more maintainable and scalable. |
| **Law of Demeter** | An object should only interact with its immediate friends, not strangers. |
| **Principle of Least Astonishment** | Software should behave in the way that least surprises users and developers. |

---

## 🧠 Decisions

| Law | Principle |
|-----|-----------|
| **Dunning-Kruger Effect** | The less you know, the more confident you tend to be. |
| **Hanlon's Razor** | Never attribute to malice what is adequately explained by carelessness. |
| **Occam's Razor** | The simplest explanation is often the most accurate one. |
| **Sunk Cost Fallacy** | Don't stick with a bad choice just because you've already invested in it. |
| **The Map Is Not the Territory** | Our representations of reality are not the same as reality itself. |
| **Confirmation Bias** | We tend to favor information that supports our existing beliefs. |
| **Hype Cycle & Amara's Law** | We overestimate technology's short-term impact and underestimate its long-term impact. |
| **The Lindy Effect** | The longer something has been in use, the more likely it continues to be used. |
| **First Principles Thinking** | Break complex problems into basic components and build back up from there. |
| **Inversion** | Solve problems by considering the opposite outcome and working backward. |
| **Pareto Principle (80/20)** | 80% of problems come from 20% of causes. |
| **Cunningham's Law** | The best way to get the right answer online is to post the wrong one. |

---

## Quick Reference by Experience Level

- **Junior** — Boy Scout Rule, YAGNI, KISS, DRY, Murphy's Law, Broken Windows Theory
- **Mid-Level** — Brooks's Law, Conway's Law, Hofstadter's Law, Kernighan's Law, SOLID, Testing Pyramid, Technical Debt
- **Senior** — Hyrum's Law, CAP Theorem, Amdahl's Law, Gall's Law, Lehman's Laws, Goodhart's Law, Pareto Principle

---

*Source: [lawsofsoftwareengineering.com](https://lawsofsoftwareengineering.com/) · © Dr. Milan Milanović · CC BY-NC-ND 4.0*
