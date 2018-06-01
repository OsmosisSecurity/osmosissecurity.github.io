---
layout: post
title:  "Startups: Recruiting for Compliance"
date:   2018-04-23 11:42:59 -0700
tags: startups compliance recruiting cloud pci
---

In order for new startups with innovative product ideas to gain customers and compete in their respective markets, they are required by their customers, partners, and regulatory authorities to demonstrate compliance with at least one information security standard. This usually forces a small startup to start the search for their first Infosec / Compliance leadership hire(s). If you’re not sure what you’re looking for or how to vet an applicant, it can become a frustrating endeavor of trial and error hiring practices.

<img src="/assets/interview.jpg" style="float: left; width: 50%; padding: 1em; padding-left: 0;"/>

When attempting to hire a compliance expert, how do you know you’re getting a decent one? There are a LOT of compliance candidates out there who take advantage of the lack of knowledge and interest most organizations display. We’re talking career time-wasters. You want someone who is knowledgable in their domain, who is going to be the glue to your departmental silos, who engineers won’t get frustrated with, and who everyone — all department heads and external auditors — will understand. This guide is meant to help you suss out career time-wasters from the genuine compliance experts who will work best in a startup environment.

## The 3 Compliance Candidates to Decline ASAP

<img src="/assets/cogs.jpg" style="float: right; width: 50%; padding: 1em; padding-right: 0;"/>

**Cogs in the Wheel:** Follows orders, in general doesn’t know whats going on, needs a ton of guidance, and mostly feels comfortable handling paperwork. Cogs usually spent a lifetime working at huge (and archaic) financial & health institutions exclusively, where it doesn’t matter if the same person does the same thing day in and day out. A startup will be severely impacted by accidentally hiring a Cog to manage compliance roadmaps or even individual compliance projects.

Sadly, Cogs don’t realize they’re cogs, speak confidently in interviews via parroting things they heard others say, and honestly believe they can run an entire department after only doing one task over and over for several years. Be extremely wary if you get someone with only financial or healthcare verticals on their resume. Friends don’t let friends hire Cogs.

<img src="/assets/policy_police.jpg" style="float: left; width: 50%; padding: 1em; padding-left: 0;"/>

**Policy Police:** These folks aggressively implement processes and policies without having an engineering background or performing even basic research on how organization processes flow present-day. There are no resume markers to immediately tell if your candidate is a Policy Police, but you can suss it out by asking the below questions and paying close attention to candidate responses. While your candidate should have policy and process creation experience under their belt, it should be the type of experience that is collaborative and scalable, not authoritarian.

**YOLO Bros:** Doesn’t look out for the best interests of the company, doesn’t speak up if the organization is headed in a bad direction, appears to know what they’re doing, and it’s too late by the time you figure out they’re just collecting a paycheck and you’re hit with a serious inquiry (lawsuit, government agencies, etc). Will not stand up to engineers and will allow insecure product to ship. No resume markers, but won’t pass the interview with the below questions.

You can suss out these three with the following basic interview questions.

## Some Basic Interview Questions to Start With

These are some great basic questions that anyone could ask during the interview process, though I recommend asking them up front. Not limited to just the phone screen, I encourage all participating in the interview process to ask the following:

* *How much experience do you have conducting SOC2/PCI/ISO27001/2 assessments?*

You want someone who has been doing junior assessments for 1–2 years, who then moved on to assessing a major organization (internal) or several major Fortune 500 companies (consultant) for 3–10 years, depending on your budget.

* *What was your most complex assessment? Feel free to detail architectural, technical and organizational challenges.*

Architectural and technical details, YMMV. You should be able to judge from their individual answer if they’re worth their salt in those categories by the depth and clarity of response. However, if the candidate starts discussing organizational challenges they overcame, the common thread that links many experienced compliance folk is an organization having a poor attitude towards compliance, and needing to change hearts and minds to get things done. A candidate worth their salt has dealt with at least one organization that needed an attitude overhaul to be effective.

Another common organizational challenge for a compliance person is the ability to bring siloed teams together within an organization. Since compliance projects are cross-cutting and involve ALL teams across an organization, this is perhaps one of the biggest organizational challenges one could face in the field. If your candidate calls this out and describes how they got things to a palatable state, its a very good indicator of a solid compliance lead.

* *Tell me about L1 Service Provider assessments you’ve performed (PCI-specific / optional).*

If you have someone who is claiming to be an external (consultant) PCI DSS compliance person, and they’ve never done a L1 service provider assessment, RUN. Just decline them.

* *Have you ever run or assisted in running an organization’s compliance regiment during that company’s first year? (Or alternatively: Tell me about your experiences working with a company who is going through compliance assessments during their first year.) What challenges did you face, and how did you overcome those? If candidate needs more context, ask for technical, project management, and organizational challenges.*

There are some unique challenges between an organization that is going through their first year of any compliance framework or a specific compliance framework, and an organization who has been there, done that, got the t-shirt. Startups in particular need candidates who have walked an org through their first year of anything.

## Governance / Risk / Compliance-specific Questions

* *In your opinion and as dirty of a question as this might be, which compliance standard does the best job of enabling companies to implement real life security controls, or at least, provides the most guidance?*

The PCI DSS is a prescriptive set of requirements with a lot of supplemental reading, but only has an annual snapshot in time checkpoint (with quarterly vuln scans) and only applicable to payments. SOC 2 Type II (SSAE 18) allows for continuous auditing. ISO27001/2 is internationally recognized, great for business, and includes elements of both aforementioned standards but with less implementation advice than the PCI DSS. If your candidate says a combo of 2 out of 3 of these, you’re on the right track. YMMV, and that shouldn't be treated as gospel.

* *Have you made any significant contributions to the compliance/risk community?*

If your candidate participates in the security or compliance communities, get interested! Ask them to send you the slides from their last talk, or a link to a blog they’re excited about. Examples of community participation may include published whitepapers, SIG participation, been a part of developing or architecting secure products to consumers that meet compliance regiments, doing security talks at conferences, etc.

* *What makes performing a security/compliance assessment against cloud architecture different from other assessments? What challenges do you anticipate with these sorts of assessments?*

Your seasoned compliance candidate is going to expect many potential challenges to cloud architecture, but the most obvious will be people-translation challenges. Some of these industry security requirements that cloud-based companies are also required to comply with have standards that are out of date with current cloud offerings. This creates a challenge with having to explain to an external auditor how you’re meeting firewall requirements using AWS security groups, to give a very elementary example.

<img src="/assets/force_backups.jpg" style="float: right; width: 50%; padding: 1em; padding-right: 0;"/>

To put it into further perspective and as an example, the PCI DSS has a three year lifecycle, while cloud providers push out a new product offering damn near every quarter. Those new products and services create new challenges, and the easiest way to overcome them is by being a decent translator across audiences. At the end of the day, your compliance expert is going to have to explain to an external auditor how some new widget they’re using meets security requirements that are 3–5 years old.

## Other Considerations & Caveats

1. You want someone who has an engineering background somewhere in their career if you don’t want your engineers to go nuts. Trust me. This doesn’t necessarily need to be programming, but sysadmin or other hands-on implementation or break/fix experience is very helpful in establishing credibility and rapport with engineers.

2. Sketch out what your values are and what you want in a compliance expert before you post the job. Do you want someone to pass audits, or do you actually care about security? Are you working on a budget, or are you willing to invest in security up front? Give it a think, and then be honest regarding what you’re looking for with your candidates. This is one important area your candidate will want an excellent fit on, and so will you.

3. Make sure your new compliance candidate has had a chance to meet and interview with all department heads during their onsite interview. The panel will be able to suss out how good of a “translator” the compliance candidate is, which directly impacts how well they can communicate when challenges arrive (and they will — its compliance). Further, compliance will affect all department heads.

4. Have each department head ask the compliance candidate to set expectations on what challenges they think their department will face, and invite them to ask questions about their departments. An expert will be able to provide department-specific insight to Legal, HR, DevOps, Marketing, Engineering and Security alike. Keep in mind that the candidate will need to ask at least a few questions in order to provide the requested general insights — they aren’t mind-readers, and don’t know how everything works at your company. But the questions they ask and the organic conversation it should inspire will allow you to determine if this person has really worked with multiple departments.

5. If they claim they’re a GDPR expert, they likely aren’t. Everyone is being challenged by GDPR, and it’s too new for anyone to be an expert (with some very rare exceptions).

6. Someone who has both internal and external (auditor/consultant) experience will be extremely beneficial for a startup. They can tell you what to expect from an external auditor, and have previous experience working internal to an organization.
