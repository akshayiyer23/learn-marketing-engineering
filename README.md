# Learn Marketing Engineering

A directory of resources for learning Marketing Engineering: building the AI agents, automations, and data systems that let a marketing team do the work of a much bigger one.

I made this because I couldn't find one place to learn the role. GTM Engineering has great learning lists. Marketing Engineering is newer, and the good material is scattered across job posts, podcasts, and a few blog posts. This repo pulls it together, plus a 30-day path I'm following myself.

## Contents

- [How To Use This Repo](#how-to-use-this-repo)
- [Start Here](#start-here)
- [A 30-Day Path](#a-30-day-path)
- [Courses](#courses)
- [Tool Academies](#tool-academies)
- [Podcasts](#podcasts)
- [Newsletters And Blogs](#newsletters-and-blogs)
- [What Companies Are Hiring For](#what-companies-are-hiring-for)
- [Projects To Build](#projects-to-build)
- [People To Follow](#people-to-follow)
- [Related Lists](#related-lists)
- [Contributing](#contributing)

## How To Use This Repo

Resources are grouped by format and shown in tables.

- **Cost** is Free, Paid, or Freemium.
- **Level** is Beginner, Intermediate, or Advanced.
- **Notes** explain what the resource helps you learn.

New to the role? Read [Start Here](#start-here), then follow [A 30-Day Path](#a-30-day-path).

## Start Here

Three reads that explain the role better than anything else.

| Resource | Cost | Level | Notes |
|---|---|---|---|
| [What Is A Marketing Engineer?](https://nicklafferty.com/blog/marketing-engineer/) | Free | Beginner | Nick Lafferty, Profound's founding Marketing Engineer, on the two halves of the job: automating what marketers already do, and building marketing that wasn't possible before. |
| [Meet the marketing engineer](https://www.marketingbrew.com/stories/profound/the-new-role-shaping-ai-powered-marketing) | Free | Beginner | Marketing Brew recap on the role as an AI-savvy builder who oversees agents, and how companies can start by automating one repetitive task. |
| [Building Vercel's First GTM Agent](https://drew.tech/posts/building-vercels-first-gtm-agent) | Free | Beginner | Drew Bredvick on an agent built in a weekend that took an inbound SDR team from 10 people to 1. The clearest example of "build the machine that does the work." |

## A 30-Day Path

One way to go from zero to your first shipped system. Each week ends with something real.

| Week | Focus | Ship by the end of the week |
|---|---|---|
| 1 | Understand the role and the stack. Read Start Here, take the Profound Marketing Engineering course, and set up Claude Code. | A list of 10 repetitive tasks in a marketing workflow you know, ranked by hours spent. |
| 2 | Data. Learn to pull data with Apify or an API and store it in Supabase. | A database of real data from one channel (your posts, a competitor's pages, or job listings). |
| 3 | Agents. Build one Claude workflow that reads that data and produces a decision or a draft, with structured output. | One agent that runs on real data, plus 20 examples you checked by hand. |
| 4 | Close the loop. Schedule it with n8n, add a human approval step, and measure one number before and after. | A working system, a README, and a 2-minute demo video. |

## Courses

| Resource | Cost | Level | Notes |
|---|---|---|---|
| [Profound University](https://university.tryprofound.com/) | Free | Beginner | Courses from Profound, including Introduction to Agentic Marketing and a full Marketing Engineering course. |
| [Anthropic Academy](https://anthropic.skilljar.com) | Free | Beginner | Official courses on Claude, Claude Code, the API, MCP, and agent skills. |
| [HubSpot Academy](https://academy.hubspot.com) | Free | Beginner | Marketing, CRM, and inbound fundamentals, useful before you automate any of it. |
| [Clay University](https://www.clay.com/university) | Free | Beginner | Enrichment, research, and personalization workflows. The GTM side of the same skill set. |

## Tool Academies

| Resource | Cost | Level | Notes |
|---|---|---|---|
| [n8n Docs](https://docs.n8n.io) | Free | Beginner | Building scheduled workflows, AI agents, and API integrations. |
| [Make Academy](https://academy.make.com) | Free | Beginner | Visual automation fundamentals for connecting marketing apps. |
| [Apify Academy](https://docs.apify.com/academy) | Free | Beginner | Web scraping basics for pulling social, competitor, and web data. |
| [Supabase Docs](https://supabase.com/docs) | Free | Beginner | Postgres, APIs, and auth for the data layer your agents read from. |
| [Google Search Central](https://developers.google.com/search/docs) | Free | Intermediate | How search engines find and read pages, including structured data. The base layer for AEO. |

## Podcasts

| Resource | Cost | Level | Notes |
|---|---|---|---|
| [The Marketing Engineer](https://podcasts.apple.com/us/podcast/id1896897707) | Free | Beginner | Nick Lafferty interviews people already doing the work, including marketing leaders at Samsara, Figma, and Wispr Flow. |

## Newsletters And Blogs

| Resource | Cost | Level | Notes |
|---|---|---|---|
| [Nick Lafferty](https://nicklafferty.com) | Free | Beginner | Marketing engineering, AI search, and AEO from someone doing the job. |
| [Drew Bredvick](https://drew.tech) | Free | Intermediate | Field notes on building and deploying GTM agents at Vercel. |
| [the gtm engineer](https://thegtmengineer.substack.com) | Free | Beginner | Weekly roundups and deep dives on GTM Engineering and AI in go-to-market. Many plays apply directly to marketing. |

## What Companies Are Hiring For

Job posts are the best curriculum for a new role. These are the patterns that show up again and again in Marketing Engineer, Growth Engineer, and AI Content Engineer postings.

| Skill | What it looks like in practice |
|---|---|
| Agents in real workflows | Content drafting, campaign reporting, lead follow-up, and social engagement handled by agents, with a human approving the output. |
| Evals and monitoring | Every agent has a test set, a success rate, and a defined failure mode before it touches customers. |
| AI search (AEO / GEO) | Tracking where the brand shows up in AI answers and rewriting pages so it shows up more. |
| A marketing data layer | One source of truth that connects campaigns, attribution, and pipeline, so reports update themselves. |
| Publishing systems | Content moves from draft to CMS to every channel with minimal manual work. |
| Taste | Knowing when a draft is accurate but lifeless, binning it, and fixing the pipeline that produced it. |
| Experiments | A clear hypothesis, a success metric defined up front, and a decision to scale, change, or stop. |

## Projects To Build

The fastest way to learn the role is to build systems on something real: your own brand, a side project, or a team that will let you help.

| Project | What it teaches |
|---|---|
| Content engine | Scrape what's working, write hooks, post, pull results back in, and feed the winners into next week's ideas. |
| AI visibility tracker | Run buyer questions through AI answer engines every week and log where a brand appears. |
| Agentic email program | Segmented nurture emails with real A/B tests and a weekly health report. |
| Competitor watch | An agent that monitors competitor pages and alerts you only when something changes. |
| Video-to-article engine | Turn recordings into search-friendly articles and refresh them over time. |

## People To Follow

| Person | Channels | Notes |
|---|---|---|
| Nick Lafferty | LinkedIn | Founding Marketing Engineer at Profound and host of The Marketing Engineer podcast. |
| Drew Bredvick | LinkedIn, Blog | Director of GTM Engineering at Vercel. Built the lead agent. |
| Holly Chen | LinkedIn | VP of Growth Marketing at Samsara, running a marketing org with roughly 90 agents. |
| Reema Batta | LinkedIn | VP of Growth Marketing at Figma, on why judgment is the new bottleneck. |
| Elias Stråvik | LinkedIn, GitHub | Builds open-source software for GTM teams. |

## Related Lists

- [Awesome Marketing Engineering](https://github.com/akshayiyer23/awesome-marketing-engineering) - Tools for building marketing systems.
- [Learn GTM Engineering](https://github.com/eliasstravik/learn-gtm-engineering) - The GTM side of the same skill set.
- [Awesome GTM Engineering](https://github.com/eliasstravik/awesome-gtm-engineering) - Tools for GTM Engineering.

## Contributing

Contributions are welcome! Thanks for reading!
