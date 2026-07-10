# How-good-is-Antonelli-
I'm a big fan of Kimi Antonelli and motorsport in general, and as a way to build my skills in data analysis I decided to dig into something I actually care about: how much better has he gotten in 2026 compared to his rookie season in 2025?
But just looking at points and wins doesn't really tell the full story. The 2026 season brought completely new cars and new regulations, so a jump in results could just mean Mercedes built a better car. To get a fair picture I'm benchmarking Antonelli against his teammate George Russell across both seasons, same car, same conditions. That way I can separate what's the driver and what's the machinery.
I'm also looking at whether a development like this between year one and year two is normal for rookies, or whether Antonelli is genuinely exceptional which i think he is.

Tools used: Python, FastF1 API, pandas, matplotlib.

The plan is to build this analysis in 4 stages:

**Stage 1:** Compare Antonelli vs Russell's pace in 2025 and in 2026, and see how the gap between them changed. Also check if the gap shifted within a season itself (early races vs late races), to rule out Antonelli just having a slow start rather than a real season-over-season jump.

**Stage 2:** Zoom out from Antonelli specifically and check the bigger picture: have teammate gaps across the grid gotten smaller or bigger in general with the 2026 regulations? This puts Stage 1's numbers in context, so I know if what I'm seeing is Antonelli-specific or just a side effect of the new rules.

**Stage 3:** Compare against other rookie-to-sophomore pairs from past seasons (e.g. Piastri/Norris, Norris/Sainz) to see if Antonelli's improvement is a normal second-year jump or genuinely exceptional.

**Stage 4:** Visualize everything and pull it together into a clear story for the README.