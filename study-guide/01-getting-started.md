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


![](materials/plots/test-chart.plot.svg)

## 🟢 Results — opening days (11–12 June){{attrs[#blk-e1mycmh56wh1]}}

- **Mexico 2–0 South Africa** — Quiñones 9', Jiménez 67'. Hosts open the
  tournament with a comfortable win at the Estadio Azteca.
- **South Korea 2–1 Czechia** — Krejčí put Czechia ahead; Hwang In-beom (67')
  and Oh Hyeon-gyu (80') turned it around. Korea rallied from a goal down.
- **USA 4–1 Paraguay** — Paraguay OG 7', **Balogun brace** (31', 45+), Reyna
  with a trivela finish to close it out. The most emphatic opener of the host
  nations, at SoFi Stadium, LA.
- **Canada 1–1 Bosnia & Herzegovina** — Lukić headed Bosnia ahead; **Larin
  78'** salvaged a point for Canada in Toronto.

**Group A after MD1:** Mexico & South Korea lead on 3 pts; Czechia & South
Africa on 0.

---

## 🔵 Coming up — your viewing windows (Hong Kong time){{attrs[#blk-pgk7y4zv88mm]}}

US evening kickoffs land in your **early Sunday morning, ~6–9am HKT**.

**Sat 13 June (US) → Sun 14 June AM HKT**
- 🇧🇷 **Brazil vs Morocco** — New Jersey · ~6am HKT — the marquee tie of the day
- 🇶🇦 Qatar vs Switzerland — San Francisco · Sun afternoon-into-morning HKT
- 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Haiti vs Scotland — Boston · ~9am HKT
- 🇦🇺 Australia vs Türkiye — Vancouver · ~9am HKT

**Sun 14 June (US) → Mon 15 June AM HKT**
- 🇩🇪 Germany vs Curaçao — Houston
- 🇳🇱 **Netherlands vs Japan** — Dallas (one to watch for the Asian angle)
- 🇨🇮 Ivory Coast vs Ecuador — Philadelphia
- 🇸🇪 Sweden vs Tunisia — Monterrey

---

## 🟡 Peripheral news worth noticing{{attrs[#blk-ox2uyoiuj9z8]}}

- **Empty seats & ticket backlash.** Dynamic/surge pricing has pushed prices
  sky-high; visible empty blocks at early games drew an uproar. If you're
  eyeing tickets, expect volatile resale pricing.
- **VAR drama in the opener.** Mexico–South Africa featured a contentious
  multi-card VAR review — early sign the officiating standard will be a
  storyline all tournament.
- **Politics around the gates.** US travel restrictions and the prospect of
  immigration enforcement near venues have kept some fans/officials away;
  host-nation friction (US–Mexico–Canada) is a running backdrop.
- **Format note.** 48 teams / 12 groups: the top two from each group *plus* the
  8 best third-placed teams advance — so even a loss rarely ends a run. Expect
  more cautious group-stage math than past tournaments.

---

*Next digest lands ~7am HKT tomorrow. Reply with what you want more or less of —
a team to follow, deeper tactical notes, betting odds, whatever — and I'll tune it.*
