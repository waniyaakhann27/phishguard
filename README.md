@@ -7,26 +7,36 @@ Phish-Guard (formerly Phish-Guard) is a high-fidelity phishing detection platfor
## 🚀 Key Features

### 1. **Tactical Tech-Stack**
- **Obsidian HUD**: Deep black (`#050505`) interface with a fixed **Cyber-Grid** and animated **Scanline** overlay.
- **Sci-Fi Typography**: Uses `Rajdhani` (Headers) and `JetBrains Mono` (Data) for a true command-line aesthetic.
- **Visual Intelligence**: **Slanted/Hexagonal** containers with glowing Neon Cyan borders (`#00E5FF`) and pulsing "Live Signal" indicators.
The interface is really dark. Has a grid and scan lines that move. It uses fonts to look like a command line. The boxes have neon borders and blinking lights to show when something is happening.


### 2. **Intelligence Layer (Detection Engine)**
- **Weighted Risk Scoring**: Precision analysis using a 40/20/10 point system.
    - **High Risk (40pts)**: Punycode/Homoglyphs (`xn--`), Direct IP connection, Urgency Keywords.
    - **Medium Risk (20pts)**: Open Redirects (`url=`, `next=`), Generic Greetings.
    - **Low Risk (10pts)**: Unsecured HTTP, excessive subdomains.
- **Advanced Heuristics**: Detects **Visual Homoglyphs** (spoofing `apple.com` with Cyrillic characters) and **Open Redirect** vulnerabilities.
This is the part that figures out if something is a scam. It uses a point system to decide how risky something is.

-High Risk things get 40 points: these are things like web addresses, direct connections to bad servers and words that try to scare you.

-Medium Risk things get 20 points: these are things like redirects and generic greetings.

-Low Risk things get 10 points: these are things like websites and too many subdomains.

-It also has advanced ways to detect scams like finding characters that look like real ones.


### 3. **Operator Progression (Gamification)**
- **XP System**: Earn XP for every URL scanned, email analyzed, or quiz completed.
- **Rank Promotion**: 
    - `0 - 100 XP`: **JUNIOR ANALYST** (Green)
    - `101 - 500 XP`: **SENIOR FORENSIC LEAD** (Cyan)
    - `501+ XP`: **ELITE DEFENDER** (Magenta)
This is the game part. You get points for scanning URLs analyzing emails or taking quizzes.

You can move up in rank:
- 100 Points: you are a Junior Analyst
  
- 500 Points: you are a Senior Forensic Lead
  
- 501+ points: you are an Elite Defender



### 4. **Forensic Reporting**
- **Incident Reports**: Generate and download detailed `.txt` forensic reports for any scan. Includes timestamp, risk score, specific threat vector breakdown, and the signing Operator's Rank.

You can make reports about incidents. Download them. These reports have timestamps, risk scores and information about the threat.

---
