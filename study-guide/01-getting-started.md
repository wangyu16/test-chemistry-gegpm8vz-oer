## Getting started{{attrs[#blk-b801baskjviq]}}

Welcome to **Test Chemistry**. This is your first study-guide section — replace it
with your own material. Each section keeps a permanent invisible label (the
`{{attrs[#…]}}` marker) so worksheets and slides generated from it stay
connected even as you edit.

Chemistry notation works out of the box: H~2~O, CO~3~^2-^, and equations like
$K_a = \frac{[\mathrm{H^+}][\mathrm{A^-}]}{[\mathrm{HA}]}$.

## Scientific Notation{{attrs[#blk-9dtvy20cwf73]}}

When studying chemistry, you will frequently encounter numbers that are either extremely large or incredibly small. For instance, the number of atoms in a small sample of matter (Avogadro's number) is $602,200,000,000,000,000,000,000$. Conversely, the mass of a single electron is approximately $0.0000000000000000000000000000009109$ kilograms. Writing out these numbers in their standard form is not only tedious but also increases the chances of making errors in calculations or transcription.

**Scientific notation** is a standardized way to express these very large or very small numbers concisely. It simplifies calculations, makes numbers easier to read, and helps avoid errors by reducing the number of zeros you need to write.

### The Format

A number written in scientific notation has two parts:

$N \times 10^x$

Where:
*   $N$ is the **coefficient** (or mantissa). This number must be greater than or equal to 1 and less than 10 ($1 \le N < 10$). It contains all the significant figures of the original number.
*   $10^x$ is the **base 10 raised to an exponent** ($x$).
    *   The exponent $x$ is an integer (a whole number, which can be positive or negative).
    *   A **positive exponent** ($x > 0$) indicates a large number (the decimal point was moved to the left).
    *   A **negative exponent** ($x < 0$) indicates a small number (the decimal point was moved to the right).

**Examples:**
*   Avogadro's number: $6.022 \times 10^{23}$ (Here, $N = 6.022$, and $x = 23$)
*   Mass of an electron: $9.109 \times 10^{-31}$ kg (Here, $N = 9.109$, and $x = -31$)

### Converting to Scientific Notation

To convert a number from its standard form to scientific notation:

1.  **Locate the decimal point.** If no decimal is explicitly written (e.g., in a whole number like 500), assume it's at the end of the number ($500.$).
2.  **Move the decimal point** until there is only one non-zero digit to its left. This new position defines the coefficient $N$.
3.  **Count the number of places** you moved the decimal point. This count will be the absolute value of your exponent $x$.
4.  **Determine the sign of the exponent:**
    *   If you moved the decimal point to the **left** (because the original number was large), the exponent is **positive**.
    *   If you moved the decimal point to the **right** (because the original number was small), the exponent is **negative**.

**Example 1: Converting a large number**
Convert $123,000$ to scientific notation.
1.  Original number: $123,000.$ (decimal is implied at the end)
2.  Move decimal to get one non-zero digit to its left: $1.23000$
3.  Number of places moved: 5 places to the left.
4.  Exponent is positive.
    Therefore, $123,000 = 1.23 \times 10^5$

**Example 2: Converting a small number**
Convert $0.000045$ to scientific notation.
1.  Original number: $0.000045$
2.  Move decimal to get one non-zero digit to its left: $4.5$
3.  Number of places moved: 5 places to the right.
4.  Exponent is negative.
    Therefore, $0.000045 = 4.5 \times 10^{-5}$

### Converting from Scientific Notation to Standard Form

To convert a number from scientific notation back to its standard form:

1.  **Examine the exponent** ($x$).
2.  **Move the decimal point** in the coefficient ($N$) by the number of places indicated by the exponent.
    *   If the exponent is **positive**, move the decimal point to the **right**. Add zeros as placeholders if you run out of digits.
    *   If the exponent is **negative**, move the decimal point to the **left**. Add zeros as placeholders if you run out of digits.

**Example 1: Positive exponent**
Convert $3.14 \times 10^3$ to standard form.
1.  The exponent is $3$ (positive).
2.  Move the decimal point 3 places to the right: $3.14 \rightarrow 31.4 \rightarrow 314. \rightarrow 3140.$
    Therefore, $3.14 \times 10^3 = 3140$

**Example 2: Negative exponent**
Convert $7.8 \times 10^{-4}$ to standard form.
1.  The exponent is $-4$ (negative).
2.  Move the decimal point 4 places to the left: $7.8 \rightarrow 0.78 \rightarrow 0.078 \rightarrow 0.0078 \rightarrow 0.00078$
    Therefore, $7.8 \times 10^{-4} = 0.00078$

## Le Chatelier's Principle{{attrs[#blk-jxkictyyv9hj]}}

Le Chatelier's Principle is a powerful tool that helps us predict how a system at chemical equilibrium will respond to a disturbance, or "stress." It states that if a change of condition (stress) is applied to a system in equilibrium, the system will shift in a direction that relieves the stress and re-establishes a new equilibrium. Think of it as the system trying to "fight back" against the change to restore balance.

Let's look at common types of stress and how they affect equilibrium:

**1. Change in Concentration**
If you add more of a reactant or product, the system will shift to consume the added substance. If you remove a reactant or product, the system will shift to produce more of that substance.

*   Consider the Haber-Bosch process for ammonia synthesis: $\ce{N2(g) + 3H2(g) <=> 2NH3(g)}$
    *   If you **add more $\ce{N2}$** (a reactant), the equilibrium will shift to the **right** (towards products) to consume the extra $\ce{N2}$, producing more $\ce{NH3}$.
    *   If you **remove $\ce{NH3}$** (a product, e.g., by liquefying it), the equilibrium will shift to the **right** to replace the lost $\ce{NH3}$, producing more $\ce{NH3}$.
    *   If you **add more $\ce{NH3}$**, the equilibrium will shift to the **left** (towards reactants) to consume the extra $\ce{NH3}$.

**2. Change in Pressure (for gaseous systems)**
Changes in pressure primarily affect reactions involving gases, especially when there's a different number of gas moles on each side of the equation.

*   **Increasing pressure** (e.g., by decreasing the volume of the container) will cause the equilibrium to shift towards the side with *fewer moles of gas* to reduce the overall pressure.
*   **Decreasing pressure** (e.g., by increasing the volume) will cause the equilibrium to shift towards the side with *more moles of gas* to increase the overall pressure.
*   Using the Haber-Bosch process again: $\ce{N2(g) + 3H2(g) <=> 2NH3(g)}$
    *   Reactant side: $1$ mole $\ce{N2}$ + $3$ moles $\ce{H2}$ = $4$ moles of gas.
    *   Product side: $2$ moles $\ce{NH3}$ = $2$ moles of gas.
    *   If you **increase the pressure**, the equilibrium will shift to the **right** (towards $2$ moles of $\ce{NH3}$) because there are fewer moles of gas on the product side, which helps relieve the pressure stress.
    *   If you **decrease the pressure**, the equilibrium will shift to the **left** (towards $4$ moles of reactants) to produce more gas moles and increase the pressure.
    *   *Note:* Adding an inert gas (one not involved in the reaction, like argon) to a constant-volume system does *not* change the partial pressures of the reacting gases, and thus does *not* shift the equilibrium.

**3. Change in Temperature**
Temperature changes are unique because they affect the value of the equilibrium constant ($K$) itself, not just the position of equilibrium. To understand the shift, treat heat as either a reactant or a product.

*   **Endothermic Reactions** (absorb heat): $\ce{\text{Reactants} + \text{Heat} <=> \text{Products}}$
    *   If you **increase the temperature** (add heat), the equilibrium shifts to the **right** (towards products) to consume the added heat.
    *   If you **decrease the temperature** (remove heat), the equilibrium shifts to the **left** (towards reactants) to produce more heat.
*   **Exothermic Reactions** (release heat): $\ce{\text{Reactants} <=> \text{Products} + \text{Heat}}$
    *   If you **increase the temperature** (add heat), the equilibrium shifts to the **left** (towards reactants) to consume the added heat.
    *   If you **decrease the temperature** (remove heat), the equilibrium shifts to the **right** (towards products) to produce more heat.

**What Doesn't Shift Equilibrium?**
*   **Catalysts** speed up both the forward and reverse reactions equally. They help the system reach equilibrium faster, but they do *not* change the position of the equilibrium or the values of equilibrium constants. The system will reach the same equilibrium composition, just more quickly.

### An example of equilibirium

## 🟢 Results — Sunday 14 June (Groups E & F){{attrs[#blk-xhb7n1or70q8]}}

- **Germany 7–1 Curaçao** (Group E) — Nmecha 6', Schlotterbeck 38', Havertz
  45+5' (pen) & 88', Musiala 47', Brown 68', Undav 78'; Comenecia 21' for
  Curaçao. **Havertz** named Man of the Match. Nagelsmann's side ran riot, but
  debutants Curaçao got a goal their history deserved.
  [FIFA report](https://www.fifa.com/en/tournaments/mens/worldcup/canadamexicousa2026/articles/germany-curacao-highlights-match-report) ·
  [ESPN](https://www.espn.com/soccer/match/_/gameId/760422/curacao-germany)
- **Côte d'Ivoire 1–0 Ecuador** (Group E) — Amad Diallo 90'. The sub drilled a
  left-footer to win it at the death and **end Ecuador's 19-match unbeaten
  streak**; Ecuador hit the woodwork twice and will feel robbed.
  [Sky Sports](https://www.skysports.com/football/news/11095/13552703/world-cup-2026-ivory-coast-1-0-ecuador-amad-diallo-nets-90th-minute-winner-to-end-ecuadors-19-game-unbeaten-streak) ·
  [ESPN](https://www.espn.com/soccer/report/_/gameId/760423)
- **Netherlands 2–2 Japan** (Group F) — Van Dijk 51', Summerville 64'; Nakamura
  57', Kamada 89'. Japan twice hit back, Kamada's late equaliser stealing a
  deserved point off a corner. Two dropped points for a flat Dutch side.
  [Sky Sports](https://www.skysports.com/football/netherlands-vs-japan/549776) ·
  [ESPN](https://www.espn.com/soccer/match/_/gameId/760425/japan-netherlands)
- **Sweden 5–1 Tunisia** (Group F) — **Ayari brace** (two long-range stunners),
  Isak, Gyökeres and Svanberg (seconds after coming on). Sweden's front line
  looked the part; Tunisia were blown away.
  [ESPN report](https://www.espn.com/soccer/report/_/gameId/760424) ·
  [ESPN as-it-happened](https://www.espn.com/soccer/story/_/id/49064457/sweden-tunisia-live-world-cup-2026-latest-updates-commentary-score-result)

*(All four scores cross-checked against ESPN, FIFA, Sky and Fox.)*

---

## 📊 Standings — after Matchday 1{{attrs[#blk-bmhevl9192m6]}}

- **Group E:** Germany 3 pts (+6) lead on goal difference, Côte d'Ivoire 3 pts
  (+1) just behind. Ecuador & Curaçao on 0 — both already need a result.
- **Group F:** Sweden 3 pts (+4) top; Japan 1, Netherlands 1; Tunisia 0.
  Wide open behind Sweden — the Japan–Netherlands draw means matchday 2 decides
  who chases.

[Official FIFA standings & fixtures](https://www.fifa.com/en/tournaments/mens/worldcup/canadamexicousa2026/scores-fixtures) ·
[CBS group tables](https://www.cbssports.com/soccer/news/world-cup-group-standings-table-results/)

*Format reminder: top two from each group **plus the 8 best third-placed teams**
advance, so one slip rarely ends a campaign.*

---

## 🔵 Coming up — Groups G & H (Hong Kong time){{attrs[#blk-gl4wnquep1bd]}}

US kickoffs land overnight/early **Tuesday 16 June HKT**:

- 🇪🇸 **Spain vs Cape Verde** (Group H) — **00:00 HKT** (midnight) · Atlanta
- 🇧🇪 Belgium vs Egypt (Group G) — **03:00 HKT** · Seattle
- 🇸🇦 Saudi Arabia vs 🇺🇾 **Uruguay** (Group H) — **06:00 HKT** · Miami
- 🇮🇷 Iran vs New Zealand (Group G) — **09:00 HKT** · Inglewood (SoFi)

**Can't-miss:** Spain — the tournament favourites' opener — but it's a midnight
start. If you'd rather stay in your window, **Uruguay vs Saudi Arabia at 6am
HKT** is the pick: Uruguay are a genuine dark horse.

[ESPN schedule & how to watch](https://www.espn.com/soccer/story/_/id/49071210/2026-world-cup-june-15-schedule-soccer-games-today) ·
[FIFA fixtures](https://www.fifa.com/en/tournaments/mens/worldcup/canadamexicousa2026/scores-fixtures)

---

## 🟡 Peripheral — worth noticing{{attrs[#blk-f6zxnh0ds8ws]}}

- **Heat breaks back in the spotlight.** FIFA's mandatory in-match hydration
  breaks split Netherlands–Japan into quarters — even in the air-conditioned
  Dallas stadium. **Van Dijk publicly criticised** the measure; expect this to
  rumble on through a hot US summer.
  [ESPN](https://www.espn.com/soccer/story/_/id/48945011/why-there-drinks-breaks-2026-world-cup-fifa-criticised)
- **Curaçao make history.** Population ~156,000 — the smallest nation/territory
  ever at a World Cup — led by **78-year-old Dick Advocaat**, the oldest manager
  in tournament history. Comenecia's goal vs Germany is one for their record book.
  [ESPN](https://www.espn.com/soccer/story/_/id/48948700/the-world-cup-record-broken-three-s-first-week-curacao-dick-advocaat-south-africa-hugo-broos-czechia-miroslav-koubek)
- **Streak snapped.** Ecuador had gone **19 games unbeaten** before Diallo's
  90th-minute winner — one of the quieter shocks of the weekend (see Sky link above).
- **Dutch injury watch.** Jurriën Timber is sidelined for the Netherlands —
  worth tracking as their group tightens.
  [ESPN injury tracker](https://www.espn.com/soccer/story/_/id/48572979/2026-fifa-world-cup-injuries-tracker-which-stars-miss-latest-info)

---

*Next digest ~7am HKT tomorrow. Want a team followed, tactical detail, or odds?
Tell me and I'll tune it.*
