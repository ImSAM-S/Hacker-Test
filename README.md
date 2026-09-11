# Hacker-Test WalkThrought

# Overview of HackerTest.net's 20 Levels:

## Initial Phase (Levels 1–5): Reconnaissance & Client-side Inspection

Key vulnerabilities: Information leakage via HTML source code (e.g., `<!-- comments -->`) or hidden configuration files (`robots.txt`), raw cookie value manipulation, and decoding basic encoded strings (Base64, Hex, ROT13).

Lesson: Never trust data or state stored in the user's browser.

## Intermediate Phase [Levels 6–12 (do not have level 8 and 9)]: Parameter & HTTP Header Manipulation

Key vulnerabilities: Basic SQL Injection via login/search forms, HTTP header spoofing (Referer, User-Agent, X-Forwarded-For), and Local File Inclusion (LFI) to read system files.

Lesson: Always validate and sanitize input data on the backend; do not rely on easily spoofed headers.

## Advanced Phase (Levels 13–18): In-depth Attack Techniques

Key vulnerabilities: Command Injection (passing system commands via input), bypassing character filters (simulated WAF), advanced authorization logic flaws (IDOR), business logic attacks, and exploiting insecure file upload/download mechanisms.

Lesson: Apply the principle of least privilege; use whitelists instead of blacklists for character filtering.

## The Finish Line (Levels 19–20): Comprehensive Challenges (The Final Boss)

Key vulnerabilities: Chaining exploits—leveraging minor logic flaws for privilege escalation, cracking custom encryption algorithms unique to the game, or bypassing complex multi-step authentication layers.

Lesson: Security is a chain; a single weak link at any layer (Network, Application, or Database) can cause the entire system to collapse.

## The reason why i do not upload level 8 and 9 because in my present they are error
