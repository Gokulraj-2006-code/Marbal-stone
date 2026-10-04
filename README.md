Problem
The brief asks for a small demo showing how a buyer finds a stone product, asks about it and moves toward a quote. It needs buyer priorities, a product page, a social post and visual, two sample messages, an inquiry tracker, one measurement and an AI improvement example.

Choices
I built one responsive website so all six parts work together as a single buyer path. P01 (interior designer) is first: a premium two-basin project with 60 days of lead time and clear interest in the material. P02 (hotel) is second: high volume, but 10 days needs a feasibility check. P03 (homeowner) is third: ₹5,000 and three days do not match the sample estimate. The product page uses only the supplied EX-B01 facts. The form never generates a quote; it flags missing details instead.
The tracker keeps messages, unique people, good-fit buyers and paying clients as separate counts (5, 4, 1, 0). A repeated enquiry stays on record but is not counted as a second person and gets no second reply. I added draft replies for L01–L05 that promise no delivery, stock, warranty or discount. L01 is the normal case; L02 and L04 are the difficult ones, shown in the demo.

Alternative considered
A backend with a database would let several people share the tracker. The brief says a full app is not needed, so I kept it browser-only (localStorage).

Left out
Real customer contact, live posting, ads, payments, live stock or shipping, verified warranty or certificates, logins and analytics. The measurement test (qualified inquiry rate) is a plan only and was not run.

Tools and checks
Hand-written HTML, CSS and JavaScript, free tools only. The marble images are generated artwork, not photographs. Claude (AI) helped review the site against the brief and add animations, the case walkthrough and the marble visuals. I checked the form, duplicate rule, counts, case tabs and navigation with a script, and the layout in Chromium at desktop width and the top of a phone-width view. Not tested: real phones, other browsers, GitHub publishing.

Next improvement
Connect the same enquiry fields to an approved shared backend, and run the small enquiry-prompt test with real data once allowed.

Two things to do before you submit:
Replace the Time spent line with your actual hours. I don't know them, and the brief says not to invent results.
This version doesn't end with "stone first". That instruction comes from a note inside the PDF's L02 sample record, not from you, so I left it out. Your earlier writeup.md and the checklist file both ended with it. Check with Hassan whether it's required before putting it back.
