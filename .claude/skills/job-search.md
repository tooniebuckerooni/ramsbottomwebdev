# Job Opportunity Search

Search for job opportunities matching Dusty Ramsbottom's profile and send a push notification with the best finds.

## Profile Summary

- **Location:** East of Toronto, Canada. Priority areas: Kingston, Ottawa (but prefer outside Ottawa proper), New Brunswick. Remote is acceptable but flag it clearly — in-person/hybrid roles are preferred.
- **Minimum Salary:** CAD $60,000/year
- **Priority Role:** Restaurant General Manager (search this first and weight it highest)
- **All Target Roles:** Restaurant General Manager, General Manager, Event Manager, Digital Marketer, Marketing Manager, Marketing Coordinator, Assistant Manager, Web Developer, Frontend Developer
- **Background:** 10+ years restaurant/bar management, founder of entertainment company, web developer, digital marketer
- **Key Skills:** Leadership, team management, restaurant operations, event marketing, JavaScript, HTML/CSS, Node.js, full-stack web development, digital marketing, Google Ads, Google Analytics, social media management, e-commerce, content creation, Adobe Creative Suite, Canva

## Search Strategy

### Indeed Searches (country_code: "CA" for all)

Run all of these and compile results:

1. **Restaurant General Manager** — location: "Kingston, ON" — search: "restaurant general manager"
2. **Restaurant General Manager** — location: "Ottawa, ON" — search: "restaurant general manager"
3. **General Manager** — location: "Kingston, ON" — search: "general manager"
4. **Event Manager** — location: "Ontario" — search: "event manager"
5. **Digital Marketing Manager** — location: "Ontario" — search: "digital marketing manager"
6. **Marketing Coordinator** — location: "Kingston, ON" — search: "marketing coordinator"
7. **Web Developer** — location: "remote" — search: "web developer javascript"
8. **General Manager** — location: "New Brunswick" — search: "general manager restaurant"
9. **Frontend Developer** — location: "remote" — search: "frontend developer"

### Web Search

Also run web searches for recent postings:
- "restaurant general manager Kingston Ottawa Ontario 2026 hiring"
- "general manager hospitality eastern Ontario job posting"
- "web developer remote Canada hiring 2026"

## Filtering Criteria

From results, select the **top 5-8 most relevant** opportunities:
- Restaurant General Manager roles get top priority regardless of other matches
- Salary meets or exceeds CAD $60,000/year (if listed)
- Located east of Toronto (Kingston, Ottawa area, Eastern Ontario, New Brunswick) — or remote
- For remote roles, flag clearly with [REMOTE] tag so the user can evaluate trust
- Avoid roles requiring unrelated skills (e.g., Java, C++, data science, heavy enterprise tech)
- Prefer smaller companies, independent restaurants, startups, or agencies over large corporate chains

## Output Format

Send a **PushNotification** with a brief summary like:
"Found X job matches! Top: [role] at [company] in [location]. Check session for details."

Then output the full list with:
- Job title (with apply link if available)
- Company name
- Location (tag [REMOTE] if remote)
- Salary (if listed)
- Why it's a good match (1 sentence)

If no good matches found, send notification:
"No strong job matches this round. Will check again later."
