# Cutshort Jobs Scraper & API - India Startup & Tech Jobs, Salary

Cutshort jobs scraper and API: search every live job on Cutshort (cutshort.io), India's hiring site for tech and startup jobs, by job title, skill, city, remote, years of experience and salary in lakhs, and get each job's title, company, city, remote or office, pay in INR (LPA), experience range, skills, funding stage, company type and size, posting date and link, newest first. Turn on full details for the job description.

Use it as a Cutshort API with no login or Cutshort API key, a Cutshort job scraper for recruiting and salary research, or a daily feed of India startup jobs from the Apify Console, the Apify API, Python, JavaScript, n8n, Make or an AI agent, and export JSON, CSV or Excel. Paste a Cutshort job list link such as cutshort.io/jobs/python-jobs-in-pune and it searches that list. Available as an [Apify Actor](https://apify.com/anshumanatrey/cutshort-jobs-search). $0.000027 per job with or without the full description, a $0.053 run start, no login.

## What does it do?

- **Searches every live job on Cutshort at once.** Cutshort listed 44,962 open jobs on 2026-11-08, about 1,100 of them first posted in the last 30 days and about 8,500 in the last 12 months, at employers such as Egnyte, Tracxn, MediBuddy, Wissen Technology and Asha Health (YC F24), mostly in Bengaluru, Hyderabad, Pune, Mumbai, Gurugram and remote.
- **Skills, experience and pay on every row.** Every job comes with the skills the company tagged, the experience range in years and the pay as shown (₹6L - ₹13L / yr) and as numbers, at no extra price. 89% of the 2,000 newest jobs show their pay.
- **Cutshort's own filters.** Years of experience, salary from a number of lakhs a year, funding stage (bootstrapped, funded, profitable), product or services company, and no agency jobs, on top of title, city, remote, job type and posting date.
- **One keyword is enough.** Type a job title and press Start. Leave the form empty for the newest jobs of every kind.
- **Newest first, read live.** Every job comes from Cutshort at the moment of your run, sorted by the date Cutshort's own job lists show.
- **Takes what people type.** Bangalore or Bengaluru, Gurgaon or Gurugram, Delhi NCR, wfh, 12 LPA, 2-5 or 5+ years, fresher, a pasted Cutshort list link or search link.
- **Checks job links.** Paste Cutshort job links and each comes back open, closed or not found.

## How is it different from other Cutshort scrapers?

- **A real title search across every job.** The other Cutshort actors turn a keyword into one of Cutshort's job list pages, such as Python Jobs, and read that page: it holds the newest 400 jobs of one skill. This actor reads Cutshort's full index of 44,962 live jobs and matches your words against every job title, so python developer finds every Python Developer job, from the newest to the oldest, and a skill finds the jobs that ask for it.
- **Experience, salary and funding stage filters.** Of the five most used actors that read Cutshort (their inputs read on 2026-11-08), one filters by years of experience (rt-solutions/india-tech-jobs-scraper) and none by salary in lakhs, funding stage or company type; here each is one field.
- **The posting date on every job, and a date filter that works.** Every row has the date Cutshort's job lists show (the same to the minute on 148 of 148 jobs compared), so Posted in the last 24 hours works on every search. The job page's own date, which moves forward while a company is still hiring, is a second field.
- **Remote, said the way Cutshort says it.** Cutshort marks jobs remote only, remote friendly or office only; they come back as remote, hybrid and onsite, with Cutshort's own words beside them.
- **Agency jobs named.** When a recruitment agency posts for a client, the row names the client as the company and the agency in its own field, and one tick leaves agency jobs out.
- **You pay for what you get.** One charge per delivered row plus a $0.053 run start, and a spending limit stops the run cleanly with the jobs it paid for.

## When should I use it?

- **Job seekers and job boards:** new tech and startup jobs in India by title, skill, city, experience and pay, on a daily schedule.
- **Recruiters and sourcing teams:** who is hiring for a role right now, at what pay and for how many years of experience.
- **Salary research:** pay ranges in lakhs by role, skill, city and company stage, as numbers ready for a spreadsheet.
- **Sales and market research:** startups hiring for a function, with their funding stage, size and website, as a buying signal.
- **Data teams and AI agents:** one clean, stable feed of Cutshort jobs through the API or MCP.

## How much does it cost to scrape Cutshort jobs?

Pay per event: $0.027 per 1,000 jobs, with or without the full description, and $0.053 when a run starts. No monthly fee, and platform usage is included. Apify's free $5 monthly credit covers about 89 runs of 100 jobs.

| Event | Price | When it is charged |
|---|---|---|
| Job | $0.000027 | One saved job, and one checked link that is closed or not found |
| Job with details | $0.000027 | One saved job with full details on |
| Run start | $0.053 | Once when a run starts, and once more for each GB of memory above 1 GB |

The "from" price in Cutshort Jobs Scraper's Apify Store header is the lowest discount-tier price, the GOLD price: $0.017 per 1,000 jobs, without the run start. FREE users (Apify's Free plan) pay $0.000027 a job, BRONZE (Starter) $0.000026, SILVER (Scale) $0.000021, GOLD (Business) $0.000017, and PLATINUM and DIAMOND $0.000016, with or without details. The run start, $0.053, is the same on every plan and is most of the price of a small run: it pays for the job pages a run reads, and a narrow search (one skill, remote only) reads thousands of them for a few dozen jobs.

| Run (Free plan price, run start included) | Cost |
|---|---|
| 100 newest jobs | $0.056 |
| 100 jobs with full descriptions | $0.056 |
| 1,000 jobs | $0.08 |
| Every Python Developer job, 632 on 2026-11-08 | $0.07 |
| Every job Cutshort lists, 44,962 on 2026-11-08 (about 100 to 110 minutes: raise the run timeout) | $1.27 |

Number of jobs (`maxJobs`) sets the most a run can cost, and a run stops at its spending limit with a message saying so.

## How does the price compare with other Cutshort scrapers?

Every actor on the Apify Store that names Cutshort in its title or slug and had 5 or more users in the last 30 days on 2026-11-08, found by searching the Store for cutshort (86 actors read), ordered by users. Free-plan prices from each actor's current pricing.

| Actor | Users, 30 days | Per job | Run start | Input |
|---|---|---|---|---|
| getascraper/cutshort-scraper | 266 | $0.0013 | $0.00005 | Skills or Cutshort list and job links, each list read to its newest 400 |
| memo23/cutshort-jobs-scraper | 31 | $0.0018 | $0.05 | Cutshort list and job links, keywords mapped to one list |
| seemuapps/india-tech-jobs-scraper | 25 | $0.004 | none | Instahyre, Cutshort and Foundit in one run |
| thirdwatch/cutshort-jobs-scraper | 9 | $0.002 | $0.00005 | Skills |
| rt-solutions/india-tech-jobs-scraper | 6 | $0.0015 | none | Instahyre, Hirist and Cutshort in one run |
| This actor | new | $0.000027 | $0.053 | Title, skill, city, experience, salary, funding stage, every job, live |

Where others are cheaper or do more: getascraper's run start is $0.00005, so a run that saves fewer than 42 jobs costs less there; from 42 jobs up this actor costs less, and on paid plans getascraper's job is still $0.00119 (Starter), $0.00108 (Scale) and $0.00097 (Business) against $0.000026, $0.000021 and $0.000017 here. getascraper and memo23 also return the pay band Cutshort keeps but does not show on the job page, the name of the person who posted the job, an employer email found on the company's website, and a monitoring mode that returns only new and changed jobs; this actor returns the pay the job page shows and leaves people's names out. The multi-site actors cover two more Indian job sites in one run.

## Which inputs does it take?

Nothing is required. Type a job title and press Start, or press Start with the form empty.

| Field | What it does |
|---|---|
| Job titles to find (`searchTerms`) | One per line. A job matches when its title has every word: frontend also finds Front-End. A pasted Cutshort list or job link works too |
| Where the job is (`location`) | A city, state or country: Bangalore, Pune, Delhi NCR, India. Remote alone asks for remote-only jobs; next to a city it adds nothing |
| Remote or office (`workType`) | remote (Cutshort's remote only), hybrid (remote friendly: remote or the office it names) or onsite |
| Posted in the last (`postedWithin`) | 24 hours, 3 days, 7 days, 30 days, any time, or your own period such as 48 hours |
| Number of jobs (`maxJobs`) | How many, newest first: 100 by default, 0 for every match |
| Full details (`includeDetails`) | Adds the description as text and HTML, and the city and country |
| Skills or roles (`skills`) | Jobs that ask for one of these skills, or name it in their title: react finds React.js |
| Experience (`experienceYears`) | Your years of experience: 3, a range such as 2-5, 5+ or fresher. Jobs whose experience range overlaps yours |
| Salary from (`minSalaryLakhs`) | The lowest yearly pay you want, in lakhs: 12 means 12 LPA |
| Funding stage (`companyStage`) | bootstrapped, funded or profitable |
| Company type (`companyType`) | product or services |
| No agency jobs (`excludeAgencies`) | Leaves out jobs a recruitment agency posted for a client |
| Leave out words (`excludeTerms`) | Drops jobs whose title has these words, such as senior or intern |
| Job type (`employmentType`) | full-time or intern, the two job types Cutshort has |
| Match descriptions (`searchDescriptions`) | Finds your words in the description too, not only the title |
| Only these companies (`companies`) | A company name (Egnyte) or a Cutshort company link. Empty searches everyone |
| Job links to check (`jobUrls`) | Paste job links to check whether they are still open, instead of searching |

Example input:

```json
{
  "searchTerms": ["python developer"],
  "location": ["Bangalore"],
  "experienceYears": "3",
  "minSalaryLakhs": 12,
  "maxJobs": 100
}
```

## What does the output look like?

One row per job, newest first. These rows are from a local run of python developer in Bangalore on 2026-11-08 (109 matching jobs at 74 companies, the 100 newest saved).

| Job title (`title`) | Company name (`company`) | Main location (`location`) | Pay as shown (`salary`) | Experience from (`experienceMin`) | Posted on (`postedAt`) |
|---|---|---|---|---|---|
| Python Developer with GenAI | VY SYSTEMS PRIVATE LIMITED | Bengaluru (Bangalore) | ₹2L - ₹20L / yr | 6 | 2026-11-06 |
| Python Developer | VY SYSTEMS PRIVATE LIMITED | Bengaluru (Bangalore) | ₹5L - ₹25L / yr | 7 | 2026-10-31 |
| Python Developer | Codenatives | Bengaluru (Bangalore) | ₹5L - ₹24L / yr | 7 | 2026-10-30 |
| Java + Python + Angular Developer | VY SYSTEMS PRIVATE LIMITED | Bengaluru (Bangalore) | ₹5L - ₹30L / yr | 4 | 2026-10-23 |
| Python Full Stack Developer | Gadgeon Systems | Bengaluru (Bangalore) | ₹8L - ₹24L / yr | 2 | 2026-10-15 |

One row as JSON (a search for operations jobs in Mumbai):

```json
{
  "title": "Events & Operations Executive",
  "company": "TorqWars",
  "location": "Mumbai",
  "otherLocations": [],
  "workType": "onsite",
  "employmentType": "full-time",
  "salary": "₹3.2L - ₹6L / yr",
  "postedAt": "2026-11-06T04:16:34.433Z",
  "jobUrl": "https://cutshort.io/job/Events-Operations-Executive-Mumbai-TorqWars-PQmAGhw4",
  "applyUrl": "https://cutshort.io/job/Events-Operations-Executive-Mumbai-TorqWars-PQmAGhw4",
  "status": "open",
  "platform": "cutshort",
  "companySlug": "jobs-at-torqwars-45-ERsD3zeF",
  "companyWebsite": "https://torqwars.com",
  "jobId": "PQmAGhw4",
  "checkedAt": "2026-11-08T01:25:39+00:00",
  "skills": ["Event Management", "Logistics", "Vendor Management", "Event production"],
  "experienceMin": 1,
  "experienceMax": 4,
  "salaryMin": 320000,
  "salaryMax": 600000,
  "salaryCurrency": "INR",
  "salaryPeriod": "year",
  "remotePolicy": null,
  "companyType": "Products & Services",
  "companySize": "0-20",
  "companyStage": "Raised funding",
  "companyFounded": 2026,
  "agency": null,
  "offersEquity": null,
  "lastActiveAt": "2026-11-06T04:16:34.526Z"
}
```

Full details add `description`, `descriptionHtml`, `city`, `country` and `countryCode`. A checked link that is closed or not found comes back with its `status` and link, and the other fields empty. A run also writes an `OUTPUT` record: how many jobs were read, matched and saved, any notes on how your input was read, and the settings used.

On the 2,000 newest jobs (2026-11-08) these fields were filled: title, company, location, work type, job type, skills, experience, posting dates and links on every row; pay 89%; company website 83%; year founded 73%; company type 72%; funding stage and company size 64%; agency 21% (the share of agency jobs); remote policy 18% (the share of remote and remote-friendly jobs).

## How fast is it?

About 20 to 45 seconds for 100 jobs on Apify at the default 512 MB, measured on 2026-11-08: the 100 newest jobs in 21 s, python developer in 44 s (35 s at 1 GB, 19 s at 2 GB), python developer in Bangalore with 3 years in 36 s, sales or operations in Mumbai with full details in 24 s, and the 1,000 newest jobs in 142 s (7 jobs a second). The run reads Cutshort's job index once, then each job's page at a steady 8 a second, so Cutshort keeps answering; a title or a town narrows which pages it reads. A search that Cutshort's own filters narrow reads more jobs to find enough: fresher jobs read 1,050 jobs for 100 rows in 138 s, and remote React jobs read 5,000 jobs, the most one run reads, for 74 rows in 712 s.

## Common questions

### Which date does it use?

Cutshort Jobs Scraper's Posted on (`postedAt`) is the date Cutshort's own job lists show and sort by: when the job was posted, or reopened after it closed. The same to the minute on 148 of 148 jobs compared with Cutshort's Python Jobs list. A job's own page shows a later date once the company shows it is still hiring; that date is Last active on (`lastActiveAt`), later than `postedAt` on 59% of the 2,000 newest jobs and by over a week on 35%. So Posted in the last 24 hours returns jobs that are new, not old jobs that are still open.

### How do I search by skill, such as React, Python or Golang?

Type the skill in Skills or roles (`skills`): Cutshort Jobs Scraper finds every job that lists it as a skill or names it in the title, so react also finds React.js and golang finds Go Programming (Golang). It reads Cutshort's own list of the skill to know which jobs to open, and opens every job past the 400 that list holds, so older jobs are found too. Several skills find jobs with any of them. A job title in Job titles to find (`searchTerms`) and a skill together find jobs with both. Pasting a Cutshort list link such as cutshort.io/jobs/remote-golang-jobs works the same way.

### How do I filter by experience or salary in lakhs?

Type your years in Experience (`experienceYears`): a number such as 3, a range such as 2-5, 5+ for five or more, or fresher. Cutshort Jobs Scraper keeps the jobs whose experience range overlaps yours: 3 keeps a job for 2 - 6 years, 5+ a job for 4 - 8 years, and fresher the jobs that start at 0. Type the lowest yearly pay you want in Salary from (`minSalaryLakhs`): 12 keeps the jobs whose pay reaches 12 lakh rupees a year (12 LPA), and a monthly stipend counts twelve times. Jobs that hide their pay, which Cutshort shows as Best in industry, are left out once you set a salary.

### What does remote, hybrid and onsite mean on Cutshort?

Cutshort marks every job remote only, remote friendly or office only. Cutshort Jobs Scraper returns remote only as remote, remote friendly (the job can be done remotely or from the office it names, as in Remote, Coimbatore) as hybrid, and office only as onsite, with Cutshort's own words in Remote policy (`remotePolicy`). Cutshort's own remote list holds only remote-only jobs, as remote does here. On the 2,000 newest jobs, 16% were remote only and 2% remote friendly. Remote typed alone in Where the job is (`location`) asks for remote-only jobs; typed next to a city it adds nothing, since that city's remote-friendly jobs are already in, so to get remote-only jobs set Remote or office (`workType`) to remote.

### Why did my search return no jobs?

When nothing matches, Cutshort Jobs Scraper's message names the one filter that left jobs out and how to loosen it. A search for python developer in Bangalore with 5+ years and a salary from 500 lakhs ended: "No open job matched on Cutshort in 31 s. 225 jobs had your words but not your other filters: the salary alone left out 189. To see them, type a lower Salary from or leave it empty." The `OUTPUT` record also shows how each field of your input was read.

### Does it need a login or a Cutshort API key?

Cutshort Jobs Scraper needs no login and no Cutshort API key: it reads the public pages every visitor sees and Cutshort's public job index. Cutshort's own API and MCP server are for employers searching candidates and need a company key; this actor reads jobs. You need only an Apify account.

### Does it work on Apify's free plan?

Cutshort Jobs Scraper works on Apify's free plan: $0.000027 a job and $0.053 a run start. The free $5 monthly credit pays for about 89 runs of the 100 newest jobs, $0.056 each.

### How often should I run it?

Running Cutshort Jobs Scraper once a day keeps a job feed fresh: set Posted in the last (`postedWithin`) to 24 hours and Number of jobs (`maxJobs`) to 0 to get every job posted that day, about 30 to 40 a day in early November 2026, about $0.054 a run. Set the run up under Schedules in Apify Console, and match rows on `jobId` to skip jobs you already have.

### How do I get every job of one company?

To get every open job of one company with Cutshort Jobs Scraper, type the company's name in Only these companies (`companies`), such as Egnyte, or paste its Cutshort company link, and set Number of jobs (`maxJobs`) to 0. Only that company's page is read: Egnyte's 5 open jobs came back in 3 seconds.

### How do I check a list of job links?

Cutshort Jobs Scraper checks whether Cutshort job links are still open when you paste them into Job links to check (`jobUrls`), one per line, instead of searching. Each link comes back as one row: open with the job's fields, closed (the company closed or deleted it) or not found. 10 links cost $0.053.

### How do I call it from the API, Python, JavaScript, n8n or an AI agent?

Cutshort Jobs Scraper runs from the Apify API, Python, JavaScript, n8n, Make or an AI agent over MCP. Each way uses your Apify token (Apify Console, Settings, API & Integrations) and takes the input as JSON keyed by the field names, such as `searchTerms` and `maxJobs`.

**API.** One call runs the actor and returns its rows. Apify stops that wait after 300 seconds, more than a search of 100 jobs takes; for every match (`maxJobs` 0) use a client below, which waits until the run ends.

```bash
curl -X POST "https://api.apify.com/v2/acts/anshumanatrey~cutshort-jobs-search/run-sync-get-dataset-items" \
  -H "Authorization: Bearer <YOUR_APIFY_TOKEN>" \
  -H "Content-Type: application/json" \
  -d '{"searchTerms": ["python developer"]}'
```

**Python** (`pip install apify-client`):

```python
from apify_client import ApifyClient

client = ApifyClient("<YOUR_APIFY_TOKEN>")
run = client.actor("anshumanatrey/cutshort-jobs-search").call(run_input={"searchTerms": ["python developer"]})
for row in client.dataset(run.default_dataset_id).iterate_items():  # apify-client 3+; on 2.x use run["defaultDatasetId"]
    print(row["title"], row["company"], row["location"], row["salary"], row["jobUrl"])
```

**JavaScript** (`npm install apify-client`):

```js
import { ApifyClient } from 'apify-client';

const client = new ApifyClient({ token: '<YOUR_APIFY_TOKEN>' });
const run = await client.actor('anshumanatrey/cutshort-jobs-search').call({ searchTerms: ['python developer'] });
const { items } = await client.dataset(run.defaultDatasetId).listItems();
for (const row of items) console.log(row.title, row.company, row.location, row.salary, row.jobUrl);
```

**n8n and Make.** In n8n, add the Apify node, pick Run an Actor and get dataset, choose this actor and paste the input JSON: the rows come out as n8n items. In Make, the Apify app's Run an Actor and Get Dataset Items modules do the same.

**AI agents (MCP).** Add `https://mcp.apify.com?tools=anshumanatrey/cutshort-jobs-search` to your MCP client and sign in with Apify, or send `Authorization: Bearer <YOUR_APIFY_TOKEN>`. The agent gets this actor as a tool and sees every input field by its JSON key.

### Am I charged for closed jobs?

Cutshort Jobs Scraper charges for a closed job only when you paste its link to check. A search returns open jobs only, and a pasted link that turns out closed or not found is one Job row, because it was checked and answered.

### Is it legal to use?

Cutshort Jobs Scraper reads public job postings and leaves out the people who posted them. You are responsible for how you use the data, including Cutshort's terms and the privacy laws that apply to you. This actor is not made by or affiliated with Cutshort.

## Limitations

- Cutshort keeps every job open until its company closes it, so its index reaches back to 2015: of 44,962 open jobs on 2026-11-08, about 8,500 were posted in the last 12 months. Newest first keeps old ones last, and Posted in the last leaves them out.
- A search reads each job's page at 8 a second, so a search that many filters narrow reads many jobs: up to 5,000 in one run (about 12 minutes on Apify at 512 MB) when a number of jobs is asked for, and the message says how far back it read.
- Pay is the pay the job page shows: 11% of jobs hide it (Best in industry), and the band Cutshort keeps but does not show is not returned.
- Funding stage, company type and size exist only where the company filled them in (64% to 72% of jobs); a filter on them leaves the rest out.
- Cutshort's job types are full time, which it also uses for contract roles, and internship.
- A job a company posts twice at the same place is delivered once, the newer copy.
- If Cloudflare asks the run's address to slow down, the run waits once (about 5 minutes) and then stops with the jobs read so far; the message says so.

## Who maintains it?

Built and maintained by **Anshuman Atrey** ([@AnshumanAtrey](https://github.com/AnshumanAtrey)), who publishes a portfolio of data and OSINT actors on Apify Store. For a feature request or a bug, message [LinkedIn](https://linkedin.com/in/anshumanatrey) (fastest), open an issue on the GitHub repo, or write through [atrey.dev](https://atrey.dev).

## Sibling actors

| Actor | What it searches |
|---|---|
| [Greenhouse Jobs Scraper](https://apify.com/anshumanatrey/greenhouse-jobs-search) | Jobs from every company on Greenhouse, searched live |
| [Lever Jobs Scraper](https://apify.com/anshumanatrey/lever-jobs-search) | Jobs from 2,300+ companies on Lever (jobs.lever.co), searched live |
| [Ashby Jobs Scraper](https://apify.com/anshumanatrey/ashby-jobs-search) | Jobs from every company on Ashby (jobs.ashbyhq.com), searched live |
| [Workday Jobs Scraper](https://apify.com/anshumanatrey/workday-job-search) | Jobs from every company on Workday (myworkdayjobs.com), searched live |
| [Workable Jobs Scraper](https://apify.com/anshumanatrey/workable-job-search) | Jobs from every company on Workable, in one search |
| [SmartRecruiters Jobs Scraper](https://apify.com/anshumanatrey/smartrecruiters-jobs-search) | Jobs from 2,900+ companies on SmartRecruiters, searched live |
| [Cornerstone Jobs Scraper](https://apify.com/anshumanatrey/cornerstone-jobs-search) | Jobs from every company on Cornerstone (csod.com), searched live |
| [Deel Jobs Scraper](https://apify.com/anshumanatrey/deel-jobs-search) | Jobs from every company on Deel ATS (jobs.deel.com), with pay |

For the people behind a company: [LinkedIn Profile Finder](https://apify.com/anshumanatrey/linkedin-harvester) turns an email into a public LinkedIn profile.

## Documentation

- Apify Store: https://apify.com/anshumanatrey/cutshort-jobs-search
- GitHub repo: https://github.com/AnshumanAtrey/cutshort-jobs-search (MIT license, see [LICENSE](LICENSE))
- The engine behind it: https://github.com/AnshumanAtrey/ats-jobs-engine

## Last updated

2026-11-08 (version 1.0)
