# Phishing Investigation: Fake University of Toronto Scholarship Website

**Project Type:** Cybersecurity Investigation | Threat Intelligence | Phishing Analysis

**Investigator:** sudofloyd

**Investigation Status:** Completed

## 1. Project Overview

This project documents a cybersecurity investigation into a suspicious scholarship campaign impersonating the University of Toronto's Lester B. Pearson International Scholarship.

The campaign was discovered through a message received on WhatsApp. The message promoted a fully funded scholarship and directed recipients to a website that raised multiple security concerns.

The objective of this investigation was to examine the suspicious links, identify potential phishing indicators, review publicly available security scan results, and document recommendations for protecting potential victims.

## 2. How I Discovered the Website

I received the following scholarship promotion through WhatsApp:

> 🎓 University of Toronto Scholarship 🇨🇦
>
> The Lester B. Pearson International Scholarship offers outstanding international students the opportunity to study at the University of Toronto with major financial support.
>
> Full tuition, books, fees and residence support for 4 years.
>
> Deadline: November 6, 2026.
>
> APPLY NOW:
> https://www.link-trim.com/utoronto-scholarship

The message encouraged recipients to apply for a scholarship using the provided link.

Because the message promoted a major financial opportunity and directed users to an unfamiliar domain, I investigated the website before trusting it.

The message may have been forwarded to other recipients, although the total number of people who received it was not established.

## 3. URLs Investigated

### Link received through WhatsApp

`https://www.link-trim.com/utoronto-scholarship`

### Scholarship website investigated

`https://www.utoronto.priosoccer.com/`

**Important:** These are two different URLs. The relationship between them should be established using redirect evidence before claiming that the WhatsApp link definitely redirected to the investigated website.

## 4. Suspicious Indicators Identified

### 4.1 Domain impersonation concerns

The website used the domain `priosoccer.com`, with `utoronto` appearing as a subdomain.

The university's official domain is `utoronto.ca`.

A website can include a university's name in a subdomain without being operated or authorized by that university. Users should verify scholarship opportunities through the institution's official website.

### 4.2 Suspicious application countdown

While visiting the website, I observed a countdown-style display showing how many students were supposedly applying for the scholarship.

When I reloaded the page or opened the link again, the displayed count started counting again.

This behaviour raised concerns that the counter might be intended to create urgency and pressure visitors into applying quickly.

However, the underlying implementation of the counter was not independently examined, so it cannot be conclusively described as fabricated.

### 4.3 VirusTotal scan results

An initial VirusTotal scan showed:

- **Detections:** 2 out of 93 security vendors.
- **Finding:** The results included phishing classifications.

These results were recorded during the initial investigation. Security-vendor detections can change over time, and the results should not be treated as proof on their own.

### 4.4 Website availability

At a later point, the website was reported to be taken down or no longer accessible.

This was a subsequent observation, not proof of who removed the website, why it became unavailable, or whether the investigation contributed to its removal.

## 5. Tools and Investigation Methods

The investigation involved the following methods:

- **VirusTotal:** Reviewing security-vendor classifications for the suspicious URL.
- **URL and domain analysis:** Comparing the investigated domain with the university's official domain.
- **Website behaviour observation:** Recording the restarting application counter.
- **Open-source research:** Identifying the scholarship promotion and documenting the links involved.

Additional redirect, DNS, WHOIS/RDAP, and page-source checks should only be recorded as completed if the corresponding evidence has actually been collected.

## 6. Investigation Conclusion

The combination of scholarship impersonation concerns, an unrelated domain, the unusual application counter, and phishing-related security-vendor detections supported treating the website as a phishing threat.

The campaign used a message promoting a valuable educational opportunity and encouraging recipients to apply through a provided link. This is consistent with social-engineering techniques that exploit trust, urgency, and the appeal of financial assistance.

The website's subsequent reported unavailability was also documented.

This investigation demonstrates the importance of checking suspicious links before submitting personal information or trusting scholarship offers circulated through messaging platforms.

## 7. Security Recommendations

- Verify scholarships through the institution's official website.
- Be cautious of scholarship links received through unsolicited or forwarded messages.
- Check the registered domain rather than relying on familiar names appearing in a URL.
- Avoid submitting passwords, banking information, or identity documents to unverified websites.
- Use reputable URL-scanning services as one source of evidence, not as a guarantee of safety.
- Report suspected scholarship impersonation to the affected institution and relevant cybersecurity reporting services.
- If information has already been submitted, change any exposed passwords and contact the relevant institution or financial provider as appropriate.

## 8. Evidence and Limitations

This report documents the observations and initial scan results available during the investigation.

The following details were not independently established:

- The identity of the website operator.
- Whether personal information or credentials were collected.
- The number of people who received the WhatsApp message.
- The technical implementation of the application counter.
- The precise reason the website became unavailable.
- Whether the WhatsApp link redirected to the investigated website at the time of testing.

These limitations do not eliminate the warning signs identified; they distinguish observed evidence from unverified assumptions.

## 9. Disclaimer

This project was conducted for educational and defensive cybersecurity purposes. It documents suspicious activity using publicly available information and observed website behaviour.

No unauthorized access, exploitation, or submission of personal information is claimed.

---

**Created by Floyd Godson (Sudo Floyd)**

Cybersecurity | Threat Intelligence | Security Awareness
