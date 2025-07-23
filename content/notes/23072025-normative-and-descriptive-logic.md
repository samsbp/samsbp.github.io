+++
date = '2025-07-23T17:53:12+05:30'
draft = false
title = '23072025 - Normative and Descriptive Logic'
+++

Normative logic is based on premises and represented similar to logical functions. Normative logic are prescriptive I would rather call it an algorithmic method.
If A is B, B is C, then A is C.

Whereas in descriptive logic, it is based on experience and intuitive thinking — deciding based on guts and what we see and observe.

In security, we often create normative logic, which of course is formed from descriptive observations. Standards are normative logic. Algorithms are normative and not descriptive.

If infrastructure is publicly accessible, developers could spin up instances. Then instances can be publicly accessible and exploited.

I have written a normative way of saying infrastructure should be under VPN. In my normative algorithm, what we are missing is the new VM is misconfigured to allow access to VM someway publicly. Then it is exploitable and accessible. But do we know the misconfiguration? Do we have the resources and knowledge to know? Obviously no. So that's why security follows normative rather than descriptive. Here, the descriptive way is asking about how do we know the instance is misconfigured, I have to observe and then do the changes.

In Cognitive Science, humans think in terms of descriptive logic. They cannot understand why security is putting us in a VPN, and it’s counterproductive to them — toiling and waiting to ask approval and deliver it.

Security is often coarse-grained solutions rather than fine-grained solutions. I cannot apply the rule of VPN to misconfigured instances only; rather, apply it as a whole. Do I have all the knowledge of what they are going to deploy? Obviously no, I am not God. Or else have a golden pathway to deploy selective instances, then I could control (fine-grain) the misconfigurations. I choose to allow what misconfigurations should be there rather than allowing all.

Rather than giving normative advice or solutions — most of them do not work, not bulletproof rather change the premises of normative logic to have more context and be fine-grained rather than more generalized. The more the generalized solution, the more it does not work.

## Reference

Stenning, K., & Van Lambalgen, M. (2008). "Human Reasoning and Cognitive Science", Chapter 1: Forms of Rationality. MIT Press.