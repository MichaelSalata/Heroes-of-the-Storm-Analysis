# Heroes of the Storm - Analysis

## My Background

I'm Michael Salata, a former professional Heroes of the Storm player and coach specializing in tank roles, macro strategy and shot-calling.

**Professional Achievements:**
- Led a team to victory in multiple weekly ESL Heroes of the Storm tournaments, earning prize money
- Shot-called for hundreds of professional matches
- Coached an amateur team that went on to place well in their own competitive division

## What This Is
This document showcases a small selection of the analysis I developed for professional Heroes of the Storm play. While my team and I typically worked with closely raw data and brief summaries, I've published this analysis with detailed explanations to make the information accessible to newer and non-competitive players.

**Purpose:**
- Demonstrate the analytical approach that drives high-level decision-making
- Provide strategies that may not be apparent without extensive competitive experience
- Bridge the gap between raw data and actionable understanding

## XP per Level Analysis
### CONTEXT
- Levels 4, 7, 10, 13, 16, and 20 are talent tier levels and represent power spikes for both teams. The spike in experience (and time) required to reach key levels dictates the time duration before, during and after a talent advantage/disadvantage. Knowing when and where you biggest timing windows to take teamfight is critical to high level strategy in competitive play.

### XP per Level - Chart Preview
![XP per Level](assets/HotS_Charts/HotS_xp_per_Level.png)
[Link to public spreadsheet](https://docs.google.com/spreadsheets/d/1XsdmDGCv5CXcDPE0u7HsFiBPaS7XBHaMglIu3-iLZXQ)

### Insights and Use Cases
- **Levels 6-7:** ~60% SPIKE in experience required to reach level 7. For teams behind in experience, this creates a prolonged window to fight on talent parity and mount a comeback before the enemy team hits level 7's substantial power spike. However, if an advantage is gained, this represents a prolonged advantage, as the losing team must still accumulate the 6-7 experience. However, if an advantage is gained, this represents a prolonged advantage, as the losing team must still accumulate the 6-7 experience.

- **Levels 9-10:** ~40% DROP in experience required to reach level 10. After the experience-advantaged team hits level 9, the window for the behind team to fight on talent parity (and ultimate parity) becomes very small.

- **Levels 16-17:** ~30% SPIKE in experience required to reach level 17. With level 16 being the power spike and relatively easy to get, xp wise, there is no opportunity window for a disadvantaged team. This favors the experience advantaged team as they already want to fight after 16 instead of soak experience for more levels.

- **Kill XP vs Level:** Kill experience remains relatively proportional to XP required—no strategic advantage gained here.

- **Kill XP at Level 20:** Kill experience DOUBLES at level 20. Team fighting becomes extremely valuable late game. This is widely recognized.

### Future Analysis Possibilities
- Highlight the ratio of passive experience gain vs minion experience vs kills
- Compare kill experience vs farming minion waves, factoring in death timers
- Analyze how many minion waves can be missed before fighting enemy teams becomes unprofitable in early game

## HP per Hero - Analysis
### CONTEXT

Understanding each hero's HP level is critical for gameplay. Since most heroes function identically at 1% HP versus 100% HP, developing strong intuition for each hero's relative HP is essential for prioritizing targets to efficiently defeat enemy teams.

**NOTE:** Since numerical values fluctuate with hero levels throughout each game, understanding a hero's RELATIVE HP is the key insight. For this reason, specific numerical values have been omitted from this visualization.

For this HP analysis, I'll examine notable entries in the chart. While HP affects dueling ability, it primarily determines a hero's ability to survive combined burst damage from an enemy team. This analysis focuses primarily on that aspect. I will not comment on survivability gained through technical abilities like invisibility, teleports, dashes, etc.

### Hero HP per Hero - Bar Chart
![Hero HP per Hero](assets/HotS_Charts/HP_per_Hero.png)
[Link to public spreadsheet](https://docs.google.com/spreadsheets/d/1Lj6p__CxRtoO6-UZv3RW_0QxE5hp_4aI0R_0ZYYvBzU/edit?usp=sharing)

### Insights: Unexpected Hero HP Levels 

**VERY DURABLE**
- **Cho:** Durable Late Game - His HP scales more than other heroes, making him significantly (~20-50%) more durable late game. His high HP makes him a very high risk-reward target.
- **Stitches:** His HP-boosting talents combined with his massive HP pool and low damage output means he's almost never worth prioritizing.
- **Azmodan:** Abnormally large HP pool for a mage. Combined with his laser ability, his 1v1 strength often catches new players off guard.
- **Dehaka:** Unexpectedly durable. Beyond his high HP pool, he has multiple HP-boosting and defensive cooldowns.
- **Varian:** His HP increases significantly when taking the TANK talent at level 7, putting him closer to Muradin's HP range.

**ABOVE AVERAGE DURABILITY**
- **Uther:** He actually WANTS to die. His passive ability to heal quickly after death significantly reduces his target priority.
- **Rehgar:** While he appears durable with solid HP pool, his limited self-healing makes him a viable target. Success depends on whether you can burst him completely or disable his ultimate. His high movement speed and AoE slow help ensure escape if he survives the initial burst.
- **D.Va:** Almost never worth prioritizing. Since she loses all mech HP when triggering her bomb, damage dealt before triggering this ability is nearly meaningless.
- **Garrosh:** Unusually small HP pool for a tank. His passive ability to gain armor when near death compensates for this. This makes armor-penetrating abilities more valuable against him at low health.

**AVERAGE-LOW DURABILITY**
- **Kerrigan:** Her AoE abilities generate shields/temporary health, making her deceptively durable depending on her damage output.
- **Cassia:** Gains physical armor while moving, making her deceptively durable against auto-attacks.
- **Illidan:** Like Kerrigan, his damage output provides self-healing, making him deceptively durable based on damage dealt.
- **Nazeebo:** Very durable late game - Key passives in his kit make him extremely difficult to burst after levels 13 & 16.
- **Lucio:** Similar to Rehgar, his limited self-healing makes him a priority target, but success depends on complete burst potential or disabling his ultimate. High movement speed ensures escape if he survives.
- **Lunara:** Has a key passive at level 13 that significantly mitigates burst spell damage.


## Analysis I've Conducted but not Included
- Hero dueling strength
- Hero win rates per map
- Hero win rates vs other heroes
- Hero pick rates for specific enemy team compositions
- Hero DPS with abilities factored in
- Initiation range visualization
- and more...
