 © iki1uc wieimmer
Site Status Checker

A small, self-contained diagnostic tool for websites. It checks which pages/sections of a site are reachable, classifies their status, and compares pairs of sections to see how compatible they are.

What it does
Checks a fixed list of pages on the site (via HTTP HEAD requests).
Classifies each page's status as one of: OK, MISSING (wrong path), NETWORK ERROR, READY, COMPATIBLE, FIXED, DONE, HELP NEEDED, UNCLEAR.
Computes a small set of properties for each status (a priority score, a category label, likely cause, likely effect, and an estimated impact/horizon score).
Compares pairs of pages and rates how well they "pair up" (HOT / SYNC / START / LOW / FAIL) based on how similar their status, category, and impact score are.
Displays the results as a readable report in the browser.
