---
aliases:
- /2023-03-06-2023-02-16-minutes-of-the-server-certificate-working-group/
author: Iñigo Barreira
date: 2023-03-06 10:15:11
tags:
- Server Certificates
title: 2023-02-16 Minutes of the Server Certificate Working Group
type: post
---

**Meeting of the Server Certificate Working Group**

**February 16, 2023**

**Attendees:** Aaron Gable – (Let’s Encrypt), Aaron Poulsen – (Amazon), Adrian Mueller – (SwissSign), Andrea Holland – (SecureTrust), Ben Wilson – (Mozilla), Bruce Morton – (Entrust), Chad Ehlers – (IdenTrust), Chris Clements – (Google), Chris Kemmerer – (SSL.com), Clint Wilson – (Apple), Corey Bonnell – (DigiCert), Daryn Wright – (GoDaddy), David Kluge – (Google), Dimitris Zacharopoulos – (HARICA), Doug Beattie – (GlobalSign), Dustin Hollenback – (Microsoft), Ellie Lu – (TrustAsia Technologies, Inc.), Enrico Entschew – (D-TRUST), Fumi Yoneda – (Japan Registry Services), Inaba Atsushi – (GlobalSign), Inigo Barreira – (Sectigo), Janet Hines – (SecureTrust), Joanna Fox – (TrustCor Systems), Johnny Reading – (GoDaddy), Jos Purvis – (Fastly), Karina Sirota – (Microsoft), Kiran Tummala – (Microsoft), Lynn Jeun – (Visa), Mads Henriksveen – (Buypass AS), Martijn Katerbarg – (Sectigo), Michelle Coon – (OATI), Nargis Mannan – (SecureTrust), Paul van Brouwershaven – (Entrust), Pedro Fuentes – (OISTE Foundation), Peter Miskovic – (Disig), Rebecca Kelley – (Apple), Rollin Yu – (TrustAsia Technologies, Inc.), Roman Fischer – (SwissSign), Ryan Dickson – (Google), Stephen Davidson – (DigiCert), Steve Topletz – (Cisco Systems), Thomas Zermeno – (SSL.com), Tim Hollebeek – (DigiCert), Tobias Josefowitz – (Opera Software AS), Vijayakumar (Vijay) Manjunatha – (eMudhra), Wayne Thayer – (Fastly), Wendy Brown – (US Federal PKI Management Authority), Yoshiro Yoneya – (Japan Registry Services)

**Next Minute Taker:** Chris Kemmerer after the face-to-face meeting.

**Review of Agenda:** Inigo Barreira stated the agenda was published and there were no changes.

**Approval of Minutes:** Approved from the last call on February 2, 2023.

**Validation Subcommittee update:** Corey Bonnell stated the subcommittee discussed two topics at the last meeting. The first was planning for the face-to-face where they decided that they were going to use the hour and a half by splitting the time. In the first half they will discuss multi-perspective domain validation and mitigations against some of the attacks that we’ve seen. Corey thought it was a great idea proposed by Ryan Dickson to take advantage of the guest speakers’ knowledge that they’ll be sharing and seeing how we can apply it within the context of the subcommittee. The second topic will be a continuation of the discussion around applicant representatives and their roles and responsibilities throughout the certificate issuance process. They identified five top level certificate issuance flows or models and there was a call for volunteers to write up each issuance flow. The write ups would look at each flow and identify improvements to the requirements as needed to better accommodate the flows or discuss various security properties.

As an administrative note the call next Thursday is canceled, keeping the tradition of canceling before the face-to-face.

Inigo suggested discussing restructuring the calls or how the SCWG should manage the validation subcommittee. Corey recalls this conversation occurring in the context of the SCWG.

**Ballot Status:**

SC61v4 – Incorporation of Mozilla Revocation Reason Codes is now in the voting period.

SC62 – Certificate profiles. Still in discussion period with no end date defined yet.

SC59 – Revival of Debian Weak Keys Ballot. Chris Kemmerer stated while working on redline they discovered they need to satisfy some pretty cogent comments from one of their endorsers. They would like to have this as an item for discussion at the face-to-face meeting.

SCXX – SLO/Response for CRL & OCSP Responses. Clint stated there is no change.

SCXX – Make OCSP optional, require CRLs. Ryan stated this is staged behind the profiles ballot. If people are interested in providing feedback, it’s very welcome. If anyone is interested in becoming an endorser they can email Ryan.

**Any other business:** Tim suggested the SCWG should discuss where we want the working group to go and what it should be working on. The SCWG is in a state where it doesn’t have any clear direction and that’s really dangerous. The SCWG is one of the most important working groups we have. We need to get everybody on the same page about what we think are the important problems in the ecosystem that the group should be addressing and get people to start working on proposals to address those items. It’s a little bit dangerous that we continue to kind of let it continue its current trajectory, where not a lot gets done and the requirements just kind of sit the way they are. Inigo agreed and said even minor changes in the titling of the documents would help as well as updating the EV Guidelines in accordance with RFC 3647. The validation subcommittee was originally created for validation and when there was no working group structure. He plans on sending a list of topics to be included.

Inigo stated Dimitris sent an email to the management list regarding algorithms and suggested discussion at the SCWG. Dimitris sent the email already knowing there was a discussion in the S/MIME working group but he felt the email was geared towards TLS. From previous discussions he believes there was no intent of implementing the algorithms by the browsers. Regardless, we need an answer for the questions list. Indigo asked if there was a time limit to respond to the question list. Dimitris is not aware of a time limit. Ben will email Dean. Tim suggested the algorithms in question are a little bit more efficient, a little bit more trustworthy in the nature of how the curves were generated. There are a bunch of small advantages that some people find attractive. Until a browser adopts the algorithm there is a chicken and egg problem. It’s up to the browsers to decide if this is something that they want to support. Aaron Gable stated they continually get requests from applicants and subscribers asking why they don’t support these curves and the answer is always, “we can’t”. There are other questions about the level of HSM support for curves other than the ones they use, but they would love for browsers to support them. Tim stated HSM support is pretty good and that should not be a blocker.

**Next Meeting:** March 16, 2023

**Meeting adjourned.**