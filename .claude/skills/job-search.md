# Job Opportunity Search

Search for job opportunities matching Dusty Ramsbottom's profile and send a notification with the best finds.

## Profile Summary

- **Location:** Canada (not willing to relocate)
- **Minimum Salary:** CAD $60,000/year
- **Background:** Web developer, digital marketer, restaurant/entertainment management
- **Skills:** JavaScript, HTML/CSS, Node.js, full-stack web development, digital marketing, Google Ads, Google Analytics, social media management, e-commerce, content creation, video production, team leadership, event management, Adobe Creative Suite, Canva

## Search Strategy

Run the following searches on Indeed (country_code: "CA") and compile the best results:

### Indeed Searches (run all of these)

1. **Web Developer** — location: "remote" — Search: "web developer javascript"
2. **Digital Marketer** — location: "Canada" — Search: "digital marketing manager"
3. **Marketing Coordinator** — location: "Canada" — Search: "marketing coordinator"
4. **General Manager** — location: "Canada" — Search: "general manager restaurant entertainment"
5. **Event Manager** — location: "Canada" — Search: "event manager"
6. **Frontend Developer** — location: "remote" — Search: "frontend developer"

### Web Search

Also run a web search for recent job postings:
- "web developer remote Canada 2026 hiring"
- "digital marketing manager Canada remote job posting"

## Filtering Criteria

From the results, select the **top 5-8 most relevant** opportunities based on:
- Salary meets or exceeds CAD $60,000/year (if listed)
- Role matches skills in web development, marketing, or management
- Remote-friendly or located in Canada
- Preference for roles at smaller companies, startups, or agencies (matches entrepreneurial background)
- Avoid roles requiring skills not in the profile (e.g., Java, C++, data science)

## Output Format

Compile the best opportunities into a concise summary and send a **PushNotification** with a brief message like:
"Found X new job matches! Best: [top role] at [company]. Run /job-search for details."

Then output the full list in chat with:
- Job title (with apply link if available)
- Company name
- Location
- Salary (if listed)
- Why it's a good match (1 sentence)

If no good matches are found, send a notification saying:
"No strong job matches today. Will check again later."
