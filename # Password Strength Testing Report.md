\# Password Strength Testing Report

 

\#\# Objective

To create passwords of varying complexity, test their strength using an online tool, and analyze the results to understand password security best practices.

 

\---

 

\#\# Step 1 — Password Creation

Four passwords were created, ranging from weak to very strong:

 

1\. \*\*Weak:\*\* \`sunshine12\`

2\. \*\*Medium:\*\* \`Winter2024\`

3\. \*\*Strong:\*\* \`T9\!gZ6@rLp3\#\`

4\. \*\*Very Strong (Passphrase):\*\* \`Blue\_Coffee-42\!River\_Hawk\`

 

\---

 

\#\# Step 2 — Testing Tool

All passwords were tested using \*\*\[PasswordMeter\](https://passwordmeter.com)\*\*, which provides:

\- Strength score (%)

\- Complexity rating

\- Positive and negative feedback

 

\---

 

 

 

\#\# Step 3 — Results Table

\*(Real test results will be inserted later)\*

 

| Password                       	| Strength Score (%) | Rating   	| Feedback from Tool                                                                 |

|------------------------------------|--------------------|--------------|-------------------------------------------------------------------------------------|

| sunshine12                     	| 15%            	| Very Weak	| Too short, uses common word and numbers; very predictable                          |

| Winter2024                     	| 35%            	| Weak     	| Mixed case and digits help slightly, but common pattern “Season \+ Year” is weak   |

| T9\!gZ6@rLp3\#                   	| 72%            	| Strong   	| Good mix of character types; moderate length; somewhat random — still short        |

| Blue\_Coffee-42\!River\_Hawk      	| 89%            	| Very Strong  | Long passphrase, includes words, symbols, digits; high entropy, easy to remember  |

 

\---

 

\#\# Step 4 — Screenshots

Screenshots of each test result are stored in the \`/screenshots\` folder:

\- \`Password1\_sunshine12.png\`

\- \`Password4\_VeryStrong.png\`

 

\---

 

\#\# Step 5 — Analysis of Strength

\- Weak passwords are easily guessable and crackable due to common words and patterns.

\- Medium passwords improve slightly with mixed case and digits but are still predictable.

\- Strong passwords use random characters and symbols but need more length for higher entropy.

\- Very strong passwords (passphrases) combine length, randomness, and complexity, making them highly resistant to brute-force attacks.

 

\---

 

\#\# Step 7 — Research on Common Password Attacks

 

\#\#\# Brute Force Attack

\- \*\*Definition:\*\* Systematically tries every possible character combination until the correct password is found.

\- \*\*Impact of Complexity:\*\* Longer and more complex passwords exponentially increase cracking time.

 

\#\#\# Dictionary Attack

\- \*\*Definition:\*\* Uses a predefined list of common passwords or words to guess the password quickly.

\- \*\*Impact of Complexity:\*\* Passwords based on common words or patterns are easily found in wordlists.

 

\---

 

\#\# Estimated Cracking Times

 

| Password                       	| Length | Character Types Used   	| Brute Force Time Estimate\*         	| Dictionary Attack Risk |

|------------------------------------|--------|----------------------------|------------------------------------------|------------------------|

| \`sunshine12\`                   	| 10 	| Lowercase \+ digits     	| \< 1 second                           	| \*\*Very High\*\* — common word \+ numbers |

| \`Winter2024\`                   	| 10 	| Mixed case \+ digits    	| Seconds to minutes                   	| \*\*High\*\* — common word \+ year format  |

| \`T9\!gZ6@rLp3\#\`                 	| 12 	| Upper, lower, digits, symbols | Weeks to months (offline)           	| \*\*Low\*\* — unlikely in wordlists   	|

| \`Blue\_Coffee-42\!River\_Hawk\`    	| 26     | Upper, lower, digits, symbols | Millions of years (offline)         	| \*\*Very Low\*\* — long random passphrase |

 

\\\*Assumes:

\- Offline cracking speed \~10 billion guesses/sec (GPU rigs)

\- Online cracking speed \~100–1,000 guesses/sec (due to rate limits)

 

\---

 

\#\# Step 8 — Summary: Password Complexity & Security

\- \*\*Length\*\* is the single most important factor in resisting brute-force attacks.

\- \*\*Randomness\*\* prevents dictionary and pattern-based attacks.

\- \*\*Passphrases\*\* provide high security while still being memorable.

\- Weak or predictable passwords can be cracked instantly, while long, random ones can be effectively impossible to break with current technology.

 

\---

 

\#\# Step 9 — Recommendations

\- Use passwords at least \*\*12–16 characters long\*\*.

\- Prefer \*\*passphrases\*\* with unrelated words, numbers, and symbols.

\- Use a \*\*password manager\*\* to store unique, complex passwords.

\- Enable \*\*multi-factor authentication (MFA)\*\* whenever possible.

