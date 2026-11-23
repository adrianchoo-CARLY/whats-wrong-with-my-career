# Question tree

Ask one question at a time. Offer the options as a short numbered list so the person can reply with a number or in their own words. Each option points either to the next question or to a result card id (ids starting with diag_ or js_diag_). Card ids are internal; never show them.

If the person's answer fits none of the options, or fits two, ask one short clarifying question, then choose the closest option. Never force a fit silently.

## Start

**Question:** What's going on in your career right now?

1. I don't know what's next for me → S1
2. I think my career is stalled → S2
3. I'm worried about job security → S3
4. I feel burnt out or overloaded → S4
5. I'm having trouble with someone at work → S5
6. I'm worried my skills aren't good enough → S6
7. I'm having trouble landing a job → J

## Situation 1: I don't know what's next for me

**S1. Which statement describes your situation best?**
1. I don't have a clear sense of what I actually want next → S1a
2. I know roughly what's bothering me, I just can't pin down the exact cause → diag_sp1_B

**S1a. Have you ever defined your own version of career success?**
1. Not really, I've mostly followed the next logical step → diag_sp1_A1
2. I did have one, but I either reached it or lost sight of it along the way → diag_sp1_A2

## Situation 2: I think my career is stalled

**S2. Why do you think your career has stalled?**
1. I haven't really been pushing for stretch moves or new opportunities → diag_sp2_A
2. I have been pushing, but something outside my control keeps blocking the move → S2b

**S2b. What's getting in the way?**
1. I'm so reliable in my current role that my boss won't let me move out of it → diag_sp2_B1
2. I got a promotion, but the pay, respect or recognition never caught up → diag_sp2_B2

## Situation 3: I'm worried about job security

**S3. What are you most concerned about?**
1. Market forces in my industry, like AI, cost-cutting or industry-wide retrenchments → S3a
2. My current job could be affected by a restructure, a new boss or a role change → diag_sp3_B

**S3a. What is your biggest concern?**
1. My skills or role are becoming less relevant, especially with AI moving faster than I am → diag_sp3_A1
2. My role could be done more cheaply, or from somewhere else → diag_sp3_A2

## Situation 4: I feel burnt out or overloaded

**S4. What's behind the burnout?**
1. There's just too much on my plate → diag_sp4_A
2. It's not really the volume, it's that I'm spending energy on unnecessary things → S4b

**S4b. Where does that unnecessary energy actually go?**
1. Mostly on things assigned to me: politics, busywork or low-value meetings I can't get out of → diag_sp4_B1
2. Mostly on things I take on myself: saying yes to everything, or feeling I have to prove I'm working hard → diag_sp4_B2

## Situation 5: I'm having trouble with someone at work

**S5. Who is the difficulty with?**
1. My manager or a senior leader → S5v
2. A peer, or someone at my level → S5p

**S5v. Which is closer to the truth about your manager?**
1. They're actively working against me → diag_sp5_A1
2. They're simply not investing in me → diag_sp5_A2

**S5p. Which is closer to the truth about your peers?**
1. I'm not really fitting in with them → diag_sp5_B1
2. One of them is actively working against me → diag_sp5_B2

## Situation 6: I'm worried my skills aren't good enough

**S6. Which describes you best?**
1. I'm unsure what my skills really are, or what they're worth → S6a
2. I know my skills, but I'm afraid they might be outdated → diag_sp6_B
3. I have real skills, I just don't feel I'm getting credit or opportunity for them → S6c

**S6a. Which is closer to it?**
1. I genuinely don't know what skills I have or how strong they are → diag_sp6_A1
2. I know my skills, I just don't know what the market actually wants right now → diag_sp6_A2

**S6c. What's getting in the way of that credit?**
1. I've never really been tested on it under real pressure or consequences → diag_sp6_C1
2. I've proven it, I just can't articulate it or show it to anyone who matters → diag_sp6_C2

## Situation 7: I'm having trouble landing a job

**J. Where does your job search actually stall?**
1. Few or no responses to applications → Ja
2. I get interviews, but never the offer → Ji
3. I get offers, but they fall apart or I regret them → Jo
4. I'm stuck switching roles or industries, or feel replaceable where I am → Jp
5. I just feel stuck overall, and I'm not sure where the problem is → Js

**Ja. When you do reach a recruiter or hiring manager, what actually happens?**
1. Even warm contacts and referrals go quiet → js_diag_network
2. Silence, even though my profile should be a good match → js_diag_story_cv
3. I suspect I'm filtered out before a human even looks → js_diag_ats
4. Recruiters tell me there's just nothing matching my profile → Ja2

**Ja2. Is that mismatch about one specific skill, or about your whole profile?**
1. My specific niche or specialty has shrunk or disappeared → js_diag_narrow_nicher
2. I keep hearing I'm too senior or too expensive → js_diag_expensive_exec
3. I coordinated and managed, but never owned a deep skill myself → js_diag_muddled_middleman
4. My whole function is being automated or moved offshore → js_diag_disrupted_dinosaur

**Ji. What's the pattern in the feedback (or silence) after interviews?**
1. They say I'm vague about what I want, or my story is scattered → js_diag_career_story
2. They like me but doubt I can actually deliver → js_diag_success_stories
3. Good candidate, just not for this specific role → js_diag_value_prop
4. Strong answers, but the fit just isn't there → js_diag_culture_fit

**Jo. What's actually going wrong at the offer stage?**
1. I find red flags only after I've already accepted → js_diag_due_diligence
2. I freeze or fumble the money conversation → js_diag_salary_negotiation
3. My current employer counters and I get stuck deciding → js_diag_counteroffer

**Jp. What's the shape of the move you're trying to make?**
1. Same role, different industry → js_diag_q2
2. Different role, same industry → js_diag_q3
3. Totally different role and industry → js_diag_q4
4. I'm not pivoting, I just feel replaceable doing what I already do → js_diag_currency_audit

**Js. Do you have a current, written career strategy: direction, target roles, timeline?**
1. Yes, it's clear → Js-hi
2. No, I'm mostly reacting to whatever comes → Js-lo

**Js-hi. When an opportunity or threat shows up, can you act on it quickly, with skills current, network warm and options open?**
1. Yes, I can move fast → js_diag_lion
2. No, I'm stuck even though I know what I want → js_diag_trex

**Js-lo. When an opportunity or threat shows up, can you act on it quickly, with skills current, network warm and options open?**
1. Yes, I'm capable, I just haven't chosen to move → js_diag_canary
2. No, I'd struggle to move at all → js_diag_panda
