+++
date = '2025-03-01T19:11:27+01:00'
title = 'Dangerous AI - An Overwiew of AI Risks'
+++

I am currently taking part in the *AI Safety, Ethics, and Society* course by the Center for AI Safety (CAIS)[^1] and will be writing about some key learnings from the course and related discussions here. This week, we explored the various risks associated with AI. While I have been reading extensively about AI safety—and, inevitably, AI risks—this discussion brought my attention to certain risks I hadn't previously considered. At the same time, as I engage more in conversations about AI with friends from different disciplines, I increasingly realize how little awareness exists in the public about these risks.

To make motivations clear, most of the top AI-researchers believe AI pose serous risks. The statement[^2] 'Mitigating the risk of extinction from AI should be a global priority alongside other societal-scale risks such as pandemics and nuclear war.' have been signed by the nobel price laureates Geoffrey Hinton and Demis Hassabis among others. Therefore, I don't believe that it is exaggerated to talk about large scale risk that have widespread societal, economic, or geopolitical consequences, affecting a large number of people or critical infrastructure or even existential risks that would pose the end of humanity. I hope this article, in very simplified terms, helps explain why  this view is held and provides a useful perspective to anyone interested.

Broadly speaking (following the definitions from the *AI Safety, Ethics, and Society* book[^3]), AI risks can be categorized into four major groups: misuse, AI race, organizational risks, and rogue AI. However, these risks are deeply interconnected and are more likely to emerge in combination rather than in isolation. That said, let’s first look into each  individually.

## Misuse

As with almost any technology developed by humans, AI has many dual-use cases, making misuse a foreseeable concern. However, AI presents unique dangers due to its digital nature, making it accessible to virtually anyone with an internet connection.

While AI can be misused in numerous ways, I will focus on three particularly plausible large-scale risks: misinformation, cyberattacks, and AI warfare.

### Misinformation

We are already struggling with fake news and deepfakes, which undermine the credibility of media institutions, fuel conspiracy theories, and polarize societies worldwide. As distinguishing misinformation from reality becomes increasingly difficult, AI threatens democracy and societal stability. AI-driven misinformation campaigns may seem like a gradual risk, but their impact should not be underestimated.

Historically, misinformation has had significant consequences. For example, in the 19th century, *yellow journalism* in the U.S. played a role in escalating the Spanish-American War[^4]. AI-generated misinformation, spreading instantly through the internet, could lead to even more severe consequences, including heightened global tensions and the risk of war.

### Cyberattacks

Cyberattacks on critical infrastructure—such as power grids—are already possible without AI, but they require a high level of expertise and skill. AI could dramatically lower this barrier by assisting attackers in planning and executing such attacks. If individuals only need basic prompting skills to jailbreak an AI into generating a strategy for a cyberattack, the likelihood of such attacks will increase significantly.

Cyberattacks can cripple digital infrastructure, paralyzing societies that depend on electricity and the internet. Unlike AI-assisted bioterrorism—where an AI might help design a deadly virus—cyberattacks do not require interaction with the physical world to cause catastrophic harm. Moreover, the anonymity of cyberattacks makes it difficult to attribute responsibility, potentially escalating tensions between major powers and increasing the risk of war.

### AI Warfare

Misinformation and cyberattacks may contribute to the outbreak of war, but AI itself is poised to play an increasingly direct role in warfare. While AI-powered drones are already in use, they still require human approval for critical decisions. As AI systems become more autonomous, wars could escalate more quickly and unpredictably.

Historically, individual human decisions have prevented probable catastrophic conflicts, such as during the Cuban Missile Crisis[^5]. If AI systems were responsible for such decisions, wars could become much harder to control, increasing the likelihood of escalation.



Of course, these are just a few examples of how AI could be used maliciously at varying levels of severity. Given the almost unrestricted accessibility of AI, its misuse should not be dismissed as an inevitable trade-off for technological progress. The argument that regulation stifles innovation should not overshadow the urgent need for safeguards.

## AI Race

The Cold War serves as a stark reminder of how technological advancements can fuel dangerous arms races. If AI-driven warfare becomes as strategically important as nuclear weapons, we may face an even greater existential threat. Unlike nuclear weapons, AI cannot easily be contained through disarmament agreements or AI-free zones, making regulation even more challenging.

However, the risks of AI races extend beyond military applications. The corporate race to develop ever-more-powerful AI systems also presents significant dangers.

### Corporate AI Races

It can be argued that we are already in a corporate AI race, where companies compete to release the most advanced AI models as quickly as possible. We see how OpenAI responded to DeepSeek’s breakthrough with its own, even more advanced DeepResearch model within days—before even completing its internal safety evaluations and publishing its system card[^6]. The economic incentives for developing powerful AI are immense. The company that creates an AI capable of replacing most human labor stands to make billions.

However, corporate AI races are likely to undermine safety standards. If companies release premature models without rigorous testing, they may overlook new capabilities that could enable  malicious use or lead to rogue AI. This brings us to the next two categories of risks: organizational failures and rogue AI.

## Organizational Risks

So far, we have focused on risks stemming from external actors—whether through misuse or competition. Organizational risks, along with rogue AI, are more internal concerns. The first one primarily involves accidents occurring within AI companies during development.

Accidents are unavoidable, but in some technologies, their consequences can be catastrophic. Aviation and space travel, for instance, have seen devastating failures due to human error and overlooked safety measures. Given the discussions in this post so far, it seems reasonable to argue that AI development requires similarly stringent safety protocols.

AI companies bear a major responsibility for ensuring their systems are safe. While governmental regulations can help establish safety standards, compliance ultimately depends on the companies themselves. As we have seen, corporate AI races can erode safety culture. Even a small number of individuals within an organization who disregard safety measures could jeopardize the broader precautions in place.

To mitigate risks, companies should implement multiple layers of safety checks. For example, red-teaming, a process where security experts actively attempt to find vulnerabilities in AI systems by simulating adversarial attacks, helps identify weaknesses before they can be exploited. Anomaly detection involves using algorithms to monitor AI behavior and flag unexpected or potentially harmful deviations from normal operation. Transparency measures, which include techniques such as explainability research, auditing mechanisms, and open reporting of AI limitations, aim to improve oversight and accountability in AI development. However, all these measures presuppose that AI is controllable—a challenge that leads us to our final risk category.

## Rogue AI

Most technologies developed by humanity pose risks that can be categorized under misuse, competition, or organizational failures. However, AI presents a unique and serious concern: the possibility that it could act independently, pursue its own goals, and escape human control, leading to potentially catastrophic consequences.

Current AI models already exhibit opaque decision-making processes, making it difficult to control their behavior and ensure alignment with human values. There have been alarming cases where AI has encouraged suicide, engaged in deceptive behavior, or promoted extremist ideologies.

The *Orthogonality Thesis*[^7] suggests that intelligence and goals are independent—meaning a highly intelligent AI could pursue objectives completely misaligned with human interests. It would be reckless to assume that any AI, regardless of its intelligence level, will inherently respect human values or prioritize human well-being.

I have previously written about the [alignment problem](https://manonkempermann.eu/blog/25_01_intro_alignment_problem/) and will likely explore different facets of rogue AI risks in future posts. For now, it is crucial to acknowledge rogue AI as a serious danger—one that is exacerbated by weak organizational safety culture and corporate AI competition.

---

We explored on a very high level the four major categories of AI risks and saw how they are not independent of each other. I hope, it became also clear, why  the possibility of large-scale and existential threats posed by AI is not far-fetched. It is probably much easier to build misaligned, dangerous AI than AI that would purely benefit humanity. This is why we urgently need increased efforts in AI safety  that address and mitigate these risks. Right now, we still have control over the direction of AI development and its integration into society, but this window of opportunity may not stay open forever. We should act proactively rather than waiting until it is too late. 



### Footnotes
[^1]: https://www.aisafetybook.com/virtual-course
[^2]: https://www.safe.ai/work/statement-on-ai-risk
[^3]: https://www.aisafetybook.com/textbook/overview-of-catastrophic-ai-risks
[^4]: https://history.state.gov/milestones/1866-1898/yellow-journalism?utm_source=chatgpt.com
[^5]: https://en.wikipedia.org/wiki/Vasily_Arkhipov
[^6]: [OpenAi released DeepResearch to Pro Users on February 2, 2025](https://openai.com/index/introducing-deep-research/), [two weeks after DeepSeek released R1 on January 20, 2025](https://api-docs.deepseek.com/news/news250120), but [DeepResearchs system card](https://openai.com/index/deep-research-system-card/) was published only on February 25, 2025
[^7]: https://www.lesswrong.com/w/orthogonality-thesis