# Automotive Warranty Tracker
## A PM Case Study Born From Real Experience
### By Mrunal Ghode | Aspiring Product Manager

---

## Why This Case Study is Different

Most PM case studies are built from imagination.
This one is built from 12 months of real frontline
experience at a leading customer support organisation,
handling warranty escalations for a major USA
automotive OEM every single day.

I didn't read about this problem in a blog post.
I lived it. 50+ times a day.

---

## 1. My Background on This Problem

During my time supporting customers of a major
USA automotive OEM, I noticed a pattern that
repeated itself every single day:

- Customers called angry about warranty coverage
- They felt the company should fix their car 
  at no cost
- They didn't understand what was and wasn't covered
- Escalations happened constantly
- The same conversation repeated 50+ times daily

After 12 months of frontline experience I formed 
this hypothesis:

**80% of angry customers felt entitled regardless
of information provided. But 20% were genuinely
confused — and their anger was completely preventable
with the right information at the right time.**

That 20% is who I designed this product for.

---

## 2. The One Line Problem Statement

Customers of automotive OEMs are blindsided by
warranty expiration and coverage gaps at the worst
possible moment — when their car breaks down —
because OEMs communicate warranty information too
late, too generically, and too passively.

---

## 3. The Real Cost of This Problem

| Metric | Impact |
|---|---|
| Warranty complaint calls | Thousands daily across major OEMs |
| Escalation rate | ~40% of warranty calls reach supervisor |
| Agent time per escalation | 20–35 min vs 8–10 for normal calls |
| Customer sentiment | Deeply negative — affects brand loyalty |
| Preventable calls | ~20% of total warranty complaints |

**The insight:** Preventing 20% of warranty complaint
calls through proactive communication saves OEMs
thousands of agent hours monthly and protects
long-term brand loyalty.

---

## 4. Root Cause Analysis

### Root Cause 1 — Inaccessible warranty information
Warranty terms are buried in purchase documents
nobody reads. Customers have no easy way to check
their coverage status until something goes wrong.

### Root Cause 2 — Information delivered at the 
wrong moment
When a car breaks down the customer is shocked and
angry. Explaining warranty terms at that moment is
too late — they're not listening, they're escalating.

### Why I focused on Root Cause 2
Root Cause 1 requires customers to proactively seek
information — which they never do until it's too late.

Root Cause 2 is a timing problem. The information
exists. OEMs have all the data. The solution is
delivering it at the RIGHT moment — when the customer
is calm, receptive, and able to act on it.

**The right moment: Routine maintenance visits.**

During routine maintenance the customer is:
- Calm and not in crisis ✅
- Receptive to information ✅
- Already thinking about their car's health ✅
- Able to ask questions without anger ✅

---

## 5. CIRCLES Framework Analysis

### C — Comprehend the Situation
**Goal:** Reduce warranty-related customer confusion
and angry escalation calls through proactive
communication

**Platform:** OEM mobile app + SMS + Email +
Connected car platform + Mail

**Business context:** Every escalated warranty call
costs 3x the time of a normal call. Reducing
escalations by 20% saves significant operational
costs while improving brand perception and
customer loyalty.

---

### I — Identify the User

**Primary user: The Confused Car Owner**

Meet Priya. She bought a mid-size SUV 3 years ago.

- Age: 30–45
- Brings car in for annual service
- Has never read her warranty document
- Doesn't know her powertrain warranty expires
  in 2 months
- When her transmission fails next month she will
  call the OEM furious — convinced it should be
  covered
- She's not entitled — she's genuinely uninformed

**Why Priya and not the entitled customer?**
The entitled customer will be angry regardless of
what information they receive. Priya just needs
the right information at the right time.
She is completely preventable as an escalation.

---

### R — Report the User's Needs

**Need 1 — Know what's covered before something 
breaks**
Priya needs to understand her warranty coverage
in plain language — not legal jargon buried in
a purchase document she signed 3 years ago.

**Need 2 — Know when coverage is expiring**
Different parts have different warranty periods.
Priya has no idea that her basic warranty expired
last year but her powertrain warranty is still
active for 2 more months. She needs clarity
on each separately.

**Need 3 — Know what to do next**
When Priya learns her warranty is expiring she
needs a clear, simple next action. Not information
overload. Just one thing to do — book a service
check.

---

### C — Cut Through Prioritisation

| Need | User Impact | Business Impact | Effort | Priority |
|---|---|---|---|---|
| Know what's covered | High | High | Low | 🔴 P0 |
| Know expiry timeline | High | High | Medium | 🟡 P1 |
| Know what to do next | Medium | High | Low | 🟢 P2 |

**Prioritising Need 1 — Coverage clarity**
If Priya doesn't know what's covered she can't
act on expiry information. Coverage clarity is
the foundation everything else is built on.

---

### L — List Solutions

**Option A — Warranty Tracker (App Feature)**
A dedicated section in the OEM's mobile app
showing all active warranties for the customer's
specific vehicle — with expiry dates, coverage
details, and countdown timers for each warranty
type.

**Option B — Proactive SMS + Deep Link**
Automated personalised SMS sent 90, 60, and 30
days before each warranty expiry. Message includes
customer name, vehicle model, specific warranty
type expiring, exact date, what won't be covered,
and a direct booking link for a service check.

**Option C — Service Visit Warranty Briefing**
During every routine maintenance visit, the service
advisor is prompted by the dealer management system
to give the customer a 2-minute warranty status
update — what's active, what's expiring, and
what to watch for.

---

### E — Evaluate Tradeoffs

**My pick: All three — shipped in phases**

**Phase 1 — Option B (Proactive SMS)**
Ships in 2–3 weeks. Uses existing customer data
and SMS infrastructure. Immediately reaches all
customers regardless of whether they have the app.

Personalised SMS example:
"Hi Priya, your mid-size SUV's powertrain warranty
expires in 30 days on 25 June 2026. Your engine
and transmission will no longer be covered after
this date. Book a service check today: [link]"

Risk: SMS without follow-up is easy to ignore.
Mitigation: Phase 2 gives them a place to go.

**Phase 2 — Option A (Warranty Tracker App)**
Ships in 6–8 weeks. Gives customers a permanent
home to check all warranty details anytime.
Turns a one-time notification into an ongoing
relationship with their vehicle's health.

Risk: Requires app download and engagement.
Mitigation: SMS in Phase 1 drives app downloads
via deep link.

**Phase 3 — Option C (Service Visit Briefing)**
Ships in 10–12 weeks. Requires dealer system
integration and staff training. Highest effort
but closes the loop at the most receptive moment
— the maintenance visit.

Risk: Dealers are independent bodies — OEMs
cannot legally mandate this behaviour.
Mitigation: Incentivise dealers through CSI
(Customer Satisfaction Index) scores tied to
warranty briefing completion rates.

---

### S — Summarise

Car owners are blindsided by warranty expiration
because information reaches them too late and
too generically.

The Automotive Warranty Tracker solves this in
three phases:

1. Personalised SMS alerts 90/60/30 days before
   each warranty expiry — with specific coverage
   details and a direct booking link
2. In-app Warranty Tracker showing all warranties,
   expiry dates, and coverage details in one place
3. Service visit warranty briefing integrated into
   the dealer management system

Start with Phase 1 — ships in weeks, reaches
everyone, costs almost nothing.

Measure success by reduction in warranty escalation
calls and improvement in customer CSAT.

---

## 6. Success Metrics — HEART Framework

| Framework | Metric | Target |
|---|---|---|
| Happiness | CSAT after warranty interactions | Above 4.5/5 |
| Happiness | Reduction in angry warranty calls | 70% reduction |
| Engagement | Customers checking warranty details 2x/month | 80% of active users |
| Adoption | New users opening Warranty Tracker in first 30 days | 50% |
| Retention | Users returning to Warranty Tracker within 90 days | 70% |
| Task Success | Warranty call escalation rate | Drop from 40% to 20% |

---

## 7. My Unfair Advantage on This Problem

I spent 12 months at a leading customer support
organisation handling automotive warranty
escalations daily. Here is what I know that no
PM sitting in a product team knows:

- The exact moment customers snap — when the
  repair cost is read out and it's not covered
- The specific language customers use when confused
  vs when entitled — they sound completely different
- The fact that dealerships are independent bodies
  — OEMs cannot legally mandate their behaviour,
  only incentivise it
- The 80/20 split — 80% entitled, 20% genuinely
  confused and completely preventable
- That the maintenance visit is the golden window
  — calm, receptive, actionable

No blog post taught me this. 12 months of real
user research did.

**That is what makes this case study different.**

---

## 8. What I Learned

- The best PM insights come from being close to
  the user — not from reading about them
- Delivering the right information at the wrong
  moment is as bad as not delivering it at all
- Phasing solutions by effort and impact beats
  trying to build everything at once
- Operational constraints like dealer independence
  are product constraints — always design around
  real world limitations
- 20% of a problem is still worth solving if
  the impact is significant enough

---

## 9. Target Companies This Applies To

| Company | Why relevant |
|---|---|
| Tata Motors | Automotive warranty communication |
| Mahindra | Same problem, different market |
| CarDekho / Cars24 | Used car warranty communication |
| Acko / Digit Insurance | Vehicle insurance communication gap |
| Ola Electric | EV warranty education gap |

---

*Case study by Mrunal Ghode — Aspiring Product Manager*

*Built from 12 months of real frontline experience
supporting customers of a major automotive OEM.*

*Client name withheld for confidentiality.
Every insight is real. Every number is observed.
Every solution is designed around actual constraints.*

*📧 Connect: www.linkedin.com/in/mrunal-ghode*
*🔗 Portfolio: github.com/mrunalghode11*
