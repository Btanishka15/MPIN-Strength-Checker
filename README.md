 # MPIN Strength Checker | OneBanc Fintech Task
 An interactive Python tool to evaluate the security strength of MPINs (Mobile PINs) using real-world logic:
- Common pattern detection
- Demographic info (DOB, spouse DOB, anniversary)
- Support for 4-digit and 6-digit PINs

# Problem Statement
In mobile banking, users often create 4- or 6-digit MPINs (Mobile PINs) that are easy to remember — but also easy to guess. These PINs frequently follow predictable patterns, such as:
-Common sequences (1234, 0000, 1212)
-Personal dates (DOB, Anniversary, Spouse’s birthday)
-Simple repeats (111111, 2580, 1980)

Such MPINs pose a high security risk and are frequently exploited in brute force or social engineering attacks.
This project addresses the problem by building a smart MPIN evaluation tool that-:
-Detects commonly used or guessable MPINs
-Checks for patterns based on demographic data
-Classifies MPINs as WEAK or STRONG
-Provides reasons for weakness (e.g., COMMONLY_USED, DEMOGRAPHIC_DOB_SELF)

# Features

Detects if MPIN is:
- Commonly Used (`1234`, `1212`, etc.)
- Based on demographic patterns (e.g., `0201`, `150819`)
- 4-digit or 6-digit PIN

Outputs:
- MPIN Strength: `STRONG` / `WEAK`
- Reason: e.g. `COMMONLY_USED`, `DEMOGRAPHIC_DOB_SELF`




