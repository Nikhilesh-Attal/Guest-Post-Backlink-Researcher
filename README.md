Guest Post Backlink Researcher

A research-first skill for finding and planning guest-post backlink opportunities without wasting tokens on unnecessary website research or drafting articles too early.

The skill is designed around a simple workflow:

Target Page → Search Strategy → Candidate Site → Site Analysis → Backlink Strategy → Approval → Draft → Submission Package

Why this skill exists

Most guest-post workflows start writing too early or spend a lot of time researching dozens of potential websites.

This skill takes a different approach:

Understand the page that needs the backlink.

Give practical search queries and niche directions first.

Let the user choose the publication.

Analyze only the selected publication.

Decide the backlink angle before writing.

Wait for user approval before drafting.

Produce a ready-to-submit article and submission package.

This makes the workflow more controlled, cheaper in tokens, and less likely to produce irrelevant guest posts.

Core workflow

1. Identify the backlink target

The skill first asks for or identifies:

Target page URL or topic

Website/domain when needed

It briefly determines:

What the target page is about

Main topic/keyword

Search intent

Likely audience

Relevant publication niches

It avoids performing a full SEO audit unless it is actually needed.

2. Discovery mode

By default, the skill does not search the web for dozens of guest-post websites.

Instead, it provides:

Around 4-8 useful search queries

Relevant publication niches

Basic quality filters

Example:

"write for us" ERP
"guest post" ERP
"contribute" "business technology"
"submit an article" accounting
intitle:"write for us" "business software"

The user then finds candidate publications and chooses one.

3. Optional website discovery

If the user explicitly asks the skill to find guest-post websites, it can research actual opportunities.

The default limit is four candidates initially.

The skill prioritizes:

Topic relevance

Genuine editorial activity

Recent content

Clear contribution opportunities

Natural backlink relevance

It does not promise publication, acceptance, or a dofollow backlink.

4. Analyze the selected publication

Once the user supplies a publication URL, the skill focuses only on the pages needed to make the decision.

Priority:

Guest-post/contributor guidelines

Submission/contact page

Link policy

2-3 relevant recent articles

The analysis covers:

Publication fit

Niche

Audience

Relevance to the target page

Editorial rules

Word count

Topics

Formatting

Link limits

In-body links

Author bio

Promotional restrictions

AI-content rules, if stated

Submission method

Editorial style

Approximate article length

Tone

Paragraph structure

Heading patterns

Lists and FAQs

Findings are labeled:

VERIFIED: directly stated by the publication

OBSERVED: inferred from published content

NOT VERIFIED: could not be confirmed

The skill never claims that a link is dofollow unless this is actually verified.

5. Backlink strategy

Before writing, the skill proposes up to three article directions.

Each direction includes:

Proposed title

Primary keyword

Related terms

Why the topic fits the publication

Natural backlink opportunity

Link placement

Suggested anchor text

Promotional risk

The user approves the direction before drafting starts.

6. Drafting

Only after approval does the skill create the article.

The article should:

Be useful without the backlink

Match the publication's general editorial style

Use natural keyword placement

Avoid keyword stuffing

Avoid forced exact-match anchors

Use concrete examples

Avoid fabricated facts or statistics

Avoid fake personal experience

Keep brand promotion limited

The skill also avoids common generic AI filler such as:

"In today's fast-paced world"

"In the ever-evolving landscape"

"Delve into"

"Unlock"

"Seamless"

"Robust"

"Elevate"

"Game-changer"

"Revolutionize"

FAQs are added only when they make editorial sense or are commonly used by the publication.

7. Quality control

Before finalizing, the skill checks:

Word count

Structure

Link count

Link placement

Brand mentions

Promotional tone

Keyword naturalness

Unsupported claims

Confidential information

Whether the article remains useful without the backlink

If a requirement cannot be verified, it is stated as uncertain rather than invented.

8. Submission package

When the article is ready, the skill can provide:

Final article

Author bio, when appropriate

Backlink details

Link attribute status

Submission instructions

Submission email

Final submission checklist

Token-saving design

The skill intentionally avoids unnecessary research.

It does not:

Crawl many websites by default

Analyze a complete website when only one page matters

Draft before the target publication is selected

Generate multiple full articles

Repeat research already supplied by the user

Search for more examples when 2-3 relevant examples are enough

It does:

Research only what is needed for the next decision

Prefer user-provided guidelines over broad web research

Use concise research summaries

Separate discovery from publication analysis

Require approval before drafting

User-controlled workflow

The user remains in control of the publication target.

The default behavior is:

User provides target page
        ↓
Skill provides search queries
        ↓
User finds candidate publications
        ↓
User selects a publication
        ↓
Skill analyzes the publication
        ↓
Skill proposes backlink/article directions
        ↓
User approves
        ↓
Skill drafts article
        ↓
Skill prepares submission package

The skill does not automatically choose a publication unless the user explicitly asks it to.

NDA and confidential projects

If the user says that a project or client is under NDA, the skill avoids requesting or exposing unnecessary private information.

It should not request or include:

Private repositories

Credentials

Internal URLs

Source code

Private architecture

Internal workflows

Client-sensitive information

Unpublished technical details

Only publicly shareable information should be used.

Working without web access

If web research is unavailable, the skill does not pretend that a publication was checked.

Instead, it asks for relevant materials such as:

Guest-post guidelines

Guidelines URL or copied text

2-3 recent relevant articles

Submission/contact information

It can then continue the analysis from those materials.

Example

User

I want a backlink to my ERPNext page.

Skill

The skill asks for the target page URL.

Then it provides a small set of searches such as:

"write for us" ERPNext
"guest post" ERP
"contribute" "business technology"
"submit an article" accounting software

It also suggests relevant niches such as:

Accounting and GST

MSME and business

ERP and business technology

Logistics and operations

The user finds a suitable publication and sends its URL.

The skill then analyzes that publication and proposes article/backlink directions.

It does not immediately write the article.

Important behavior rules

Do not draft before the target publication is known.

Do not research actual candidate sites unless the user asks for discovery.

Analyze only the selected publication when possible.

Separate verified facts from observations and unknowns.

Do not claim a backlink will be accepted or be dofollow unless verified.

Use the minimum number of links needed.

Do not fabricate statistics, quotes, case studies, credentials, or experience.

Respect the publication's stated editorial and link rules.

Do not expose confidential or NDA-protected information.

Get user approval before drafting the final article.

Files

guest_post_backlink_skill_v2/
├── SKILL.md
└── README.md

SKILL.md contains the actual skill instructions.

README.md explains the skill, workflow, behavior, and intended use.

Status

Version: 2.0

Focus: Guest-post backlink research, editorial fit, backlink planning, and submission preparation.

Design priority: Relevance first, controlled research, low unnecessary token usage, and user approval before drafting.
