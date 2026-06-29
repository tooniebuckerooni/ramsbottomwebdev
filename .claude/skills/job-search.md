# Job Opportunity Search

Search for job opportunities matching Dusty Ramsbottom's profile and send a push notification with the best finds.

## Profile Summary

- **Location:** East of Toronto, Canada. Top priority: Kingston and surrounding area (Napanee, Belleville, Brockville). Ottawa is acceptable but apply a 15% ranking penalty — French language requirements are a barrier. New Brunswick is fine but tends rural. Remote is acceptable but flag clearly — in-person/hybrid roles are preferred and more trusted.
- **Minimum Salary:** CAD $60,000/year
- **Priority Role:** Restaurant General Manager (search this first and weight it highest)
- **All Target Roles:** Restaurant General Manager, General Manager, Event Manager, Digital Marketer, Marketing Manager, Marketing Coordinator, Assistant Manager, Web Developer, Frontend Developer
- **Background:** 10+ years restaurant/bar management, founder of entertainment company, web developer, digital marketer
- **Key Skills:** Leadership, team management, restaurant operations, event marketing, JavaScript, HTML/CSS, Node.js, full-stack web development, digital marketing, Google Ads, Google Analytics, social media management, e-commerce, content creation, Adobe Creative Suite, Canva
- **Known Good Companies:** Jack Astor's, Delta Hotels by Marriott, SIRCorp brands (Scaddabush, Reds, Loose Moose, etc.) — flag these if they appear

## Search Strategy

### Indeed Searches (country_code: "CA" for all)

Run all of these and compile results:

1. **Restaurant General Manager** — location: "Kingston, ON" — search: "restaurant general manager"
2. **General Manager** — location: "Kingston, ON" — search: "general manager restaurant"
3. **Restaurant General Manager** — location: "Ottawa, ON" — search: "restaurant general manager"
4. **General Manager** — location: "Belleville, ON" — search: "general manager"
5. **Event Manager** — location: "Ontario" — search: "event manager"
6. **Digital Marketing Manager** — location: "Ontario" — search: "digital marketing manager"
7. **Marketing Coordinator** — location: "Kingston, ON" — search: "marketing coordinator"
8. **Web Developer** — location: "remote" — search: "web developer javascript"
9. **General Manager** — location: "New Brunswick" — search: "general manager restaurant"
10. **Frontend Developer** — location: "remote" — search: "frontend developer"
11. **Hotel Manager** — location: "Kingston, ON" — search: "hotel food beverage manager"

### Web Search

Also run web searches for recent postings:
- "restaurant general manager Kingston Ontario hiring"
- "general manager hospitality eastern Ontario job posting"
- "Jack Astors Delta Hotels Kingston hiring"
- "web developer remote Canada hiring"

## Filtering & Ranking

From results, select the **top 5-8 most relevant** opportunities using this ranking:

### Location scoring
- Kingston / Napanee / Belleville / Brockville / Eastern Ontario (not Ottawa): **full value**
- Ottawa area: **apply 15% penalty** (French requirements may be a barrier)
- New Brunswick: **slight penalty** (rural, lower salaries)
- Remote: **flag with [REMOTE]** — acceptable but user is skeptical of remote roles
- West of Toronto or far-flung: **exclude**

### Role scoring
- Restaurant General Manager: **top priority, always include**
- General Manager (hospitality/entertainment): **high priority**
- Hotel F&B Manager: **high priority**
- Event Manager: **medium-high**
- Marketing Manager / Coordinator: **medium**
- Web Developer / Frontend Dev: **medium**

### Other filters
- Salary meets or exceeds CAD $60,000/year (if listed)
- Avoid roles requiring French fluency as a hard requirement
- Avoid roles requiring unrelated skills (Java, C++, data science, heavy enterprise tech)
- Prefer smaller companies, independent restaurants, and known-good brands (SIRCorp, Marriott/Delta)

## Output Format

Send a **PushNotification** with a brief summary like:
"Found X job matches! Top: [role] at [company] in [location]. Check session for details."

Then output the full list with:
- Job title (with apply link if available)
- Company name
- Location (tag [REMOTE] if remote, [OTTAWA - French may apply] for Ottawa roles)
- Salary (if listed)
- Why it's a good match (1 sentence)

If no good matches found, send notification:
"No strong job matches this round. Will check again later."
