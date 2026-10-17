# Evidence Log: Scholarship Phishing Investigation

## 1. Investigation Details

- **Investigator:** Sudo Floyd
- **Investigation date:** October 16, 2026
- **Purpose:** Document evidence relating to a suspicious scholarship website.

## 2. WhatsApp Message

The following scholarship promotion was received through WhatsApp:

> University of Toronto Scholarship
>
> The Lester B. Pearson International Scholarship offers outstanding international students the opportunity to study at the University of Toronto with major financial support.
>
> Full tuition, books, fees and residence support for 4 years.
>
> Deadline: November 6, 2026.
>
> Apply: https://www.link-trim.com/utoronto-scholarship

**Observation:** The message promoted a valuable educational opportunity and encouraged recipients to apply through a supplied link.

## 3. URLs

**URL A — Link received through WhatsApp**

`https://www.link-trim.com/utoronto-scholarship`

**URL B — Website investigated**

`https://www.utoronto.priosoccer.com/`

These URLs are recorded separately. A confirmed redirect relationship requires supporting evidence.

## 4. VirusTotal Results

- **Reported detection count:** 2 out of 93 security vendors.
- **Reported classifications:** The results included phishing-related classifications.
- **Source:** VirusTotal.
- **Collection date:** October 16, 2026.

**Interpretation:** The detections provide a warning indicator. Vendor classifications can change, and a detection count alone does not establish every aspect of a website's behaviour.

**Evidence attachment:** The original scan screenshot or report URL has not yet been added to this repository.

## 5. Website Behaviour

During my visit, the website displayed a countdown-style counter representing the number of students supposedly applying.

After reloading the page or reopening the link, the counter started counting again.

**Security concern:** This behaviour could be intended to create urgency and encourage visitors to apply quickly.

**Limitation:** The counter's implementation was not independently examined, so its exact mechanism remains unverified.

## 6. Domain Assessment

The investigated website used the domain `priosoccer.com`, with `utoronto` appearing as a subdomain.

The University of Toronto's official domain is `utoronto.ca`.

**Security concern:** The presence of a university's name in a subdomain does not establish that the university owns or authorizes the website.

## 7. Availability Observation

The website was subsequently reported to be taken down or no longer accessible.

- **Evidence type:** User observation.
- **Independent confirmation:** Not yet documented.
- **Reason for unavailability:** Unknown.

The website's unavailability does not, by itself, establish who removed it or why.

## 8. Preliminary Evidence Assessment

The combined observations raised concerns about scholarship impersonation and possible phishing:

1. A scholarship promotion distributed through WhatsApp.
2. A domain different from the university's official domain.
3. A restarting application counter that could create urgency.
4. Phishing-related VirusTotal detections.
5. Subsequent reported website unavailability.

These indicators supported treating the website as a phishing threat and avoiding the submission of personal information.

## 9. Evidence Still to Preserve

- Original VirusTotal report URL or screenshot.
- Screenshot of the WhatsApp message, with private sender information redacted.
- Screenshot of the website counter, if available.
- Safe, timestamped evidence of the website's availability status.
- Redirect analysis, if the relationship between the two URLs can be established safely.

Only evidence actually collected should be marked as verified.

---
