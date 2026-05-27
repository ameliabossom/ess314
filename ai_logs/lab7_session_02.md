### Part 2 — Worksheet

**Topic chosen:** B 

**One sentence on why this topic matters for my final project:**

> I dont think I actually knew what NMO correction was and it is very useful for seismic data corrections. 

**Most useful AI response (paste the key 3–5 lines):**

```
This is actually describing NMO stretch, not the breakdown of the approximation itself.

The better explanation is:

The small-offset approximation assumes x≪vt0.

At large offsets, higher-order terms in the square-root expansion become important.
So the quadratic approximation no longer matches the true hyperbola accurately.

The frequency lowering/stretching is a consequence of large corrections, but not the mathematical reason the approximation fails.
```

**Least useful AI response (paste the key 3–5 lines):**

```
A major limitation is NMO stretch: at large offsets and shallow times, the correction shifts neighboring samples by very different amounts, artificially stretching the seismic wavelet and lowering its dominant frequency. Because stretched data become distorted and less reliable, processors usually mute the most strongly stretched portions before stacking.
```

**Why the second was less useful:**

The second was less useful because it was just so vauge. It talkef about the stretch being a limitation but didn't get into HOW its lowered its dominant frequncy

**One claim from the session I cross-checked against the textbook
or my lab notebook, and what I found:**

> Claim: [That a reflection event in a CMP gather appears as a hyperbola]
>
> Cross-check source: [`Lab4.ipynb` question 3.2]
>
> Verdict: [ matches ]

