---
title: "Hexie Theory Guided Generative AI Ethics Study"
style:  app
date: 2023-09-10 10:12:20

author_profile: true
toc: true
toc_label: "Page Content"


tags:
  - AI models
  - Prompt Engineering
  - OpenAI
  - GPT3
  - AI
  - ChatGPT
  - Ethics
  - Hexie Theory
  - Hexie Pricineple
  - Hexie Framework


header:
  teaser: "/assets/posts/HeXie-management-theory_W640.jpg"
---
![Langague](/assets/posts/HeXie-management-theory_W640.jpg)

# Introduction
Generative AI has moved into its era of deployment. Throughout 2022 and the beginning of 2023, new large-scale generative AI models have been released every month. These models, such as ChatGPT, ERNIE Bot (Wenxin Yiyan), Stable Diffusion, Whisper, and DALL-E 2, based on Deep neural networks and huge training data, are capable of an increasingly broad range of tasks, from text generation, manipulation, and analysis to image generation, to unprecedentedly good speech recognition [Shelby Hiter 2023, Zen Soo 2023, Rebecca Heilweil 2023, G Li 2023]. These systems storm the world with capabilities in question answering and the generation of text, image, and code unimagined a decade ago, and they outperform state of the art technology on many benchmarks, old and new. This surge in technical innovation has ushered in a new era of possibilities. Applications range from marketing and sales, customer service and contact centres, graphic design and video production, healthcare, pharmaceuticals, biology, chemistry, biophysics, entertainment, legal and government, fashion, retail, and e-commerce. They cover almost every corner of the society from personal use to business, from education and to medical diagnoses and patient care. Startups and large companies find themselves in a race to deploy and release generative models; Industries find themselves under pressure of boosting productivity; Governments find themselves dealing with increasing AI-created incidents. Generative AI has no doubt transformed our way of living. 
These advancements have also brought forth a host of profound challenges. As generative AI technology evolves, so does the need for ethical research [Shelby Hiter 2023-2]. The stakes have never been higher. The power to generate content at a scale and sophistication previously unimaginable also raises critical questions about how this technology should be wielded responsibly [Jack Clark and Ray Perrault 2023]. The misuse, from spreading misinformation through deepfake technology to perpetuating societal biases, or being tricked into serving nefarious aims highlights the complicated ethical challenges associated with their deployment. Through misuse and harmful intentions this can cause damage to companies and harm to society. Many incidents have led to lawsuits [AIAAIC Repository, 2022].  Here are a few examples:

## Fake News

One example of the incidents reported to the [AIAAIC database](https://aiaaic.org/home) is the “Deepfake of President Volodymyr Zelenskyy Surrendering”. In March of 2022, a video that was circulated on social media and a Ukrainian news website purported to show the Ukrainian president directing his army to surrender the fight against Russia. It was eventually revealed that the video was a deepfake. 
![Deepfake of President Volodymyr Zelenskyy Surrendering (Deepfake, March 2022)](/assets/posts/Hexie/Zelensky.jpg) 

## Lawsuit

Recently, A notable case involves [a class-action lawsuit filed against GitHub, Microsoft, and OpenAI](https://www.perkinscoie.com/en/news-insights/first-lawsuits-arrive-addressing-generative-ai.html). This lawsuit pertained to GitHub's Copilot tool, which is powered by generative AI. Copilot suggests new lines of code in real-time to programmers. The lawsuit raised questions about code ownership and copyright, as Copilot generated code that some developers claimed was similar to their own, potentially causing financial and reputational damage to these developers and companies involved in the suit.
## Intellectual Property Disputes

Generative AI has led to disputes over intellectual property rights. As generative AI systems create content autonomously, determining ownership and protecting original work becomes challenging. Companies have faced legal battles over who owns content generated by AI systems. Two companies behind popular AI art tools, Midjourney and Stable diffusion, are in the crosshairs of a legal case that alleges they infringed on the rights of millions of artists by training their tools on web-scraped images. In January 2023, stock image supplier Getty Images took Stability AI to court for reportedly using millions of images from its site without permission to train Stable Diffusion. In another recent example, an AI tool used by CNET to write explanatory articles was found to have plagiarised articles written by humans (articles presumably swept up in its training dataset). These kinds of cases that accuse generative AI of using other human’s intellectual properties have been increasing day by day.
## Social disturbance

Allegations of deepfake technology and AI-generated disinformation have been swirling around the events of the 2023 presidential elections in Turkey. Just days before the Sunday election, one of the best-known opposition candidates, Muharrem İnce, pulled out. An alleged sex tape had been circulating on social media and he claimed his appearance in it was the result of deepfake technology; nonetheless, he withdrew from the contest.![Muharrem İnce](/assets/posts/Hexie/Ince.jpg)
## Fake and Harmful Contents

While not always leading to lawsuits, generative AI's ability to create deepfake content (see section 2.1) has raised ethical and reputational concerns. Misuse of deepfake technology, such as creating misleading or fraudulent content (picture, voice and text) can cause damage and lead to public backlash. Fake human figures can create anger and some uprising; Fake user feedback can produce a wrong and negative impression of a product and the company, therefore causing damage to the company and the customer’s trust. Apart from the fake content AI models can also produce harmful and potentially dangerous content. Researcher Matt Korda [Matt Korda 2023](https://outrider.org/nuclear-weapons/articles/could-chatbot-teach-you-how-build-dirty-bomb) discovered that ChatGPT could be tricked into giving detailed instructions on how to build a bomb if asked to do so from the perspective of a researcher claiming to work on safety research related to bombs. 

# GAI Ethics 
Generative AI Ethics research becomes imperative because AI technologies have shortfalls, and the misuse and adoption of the technology also lacks unique and practical principles and guidelines. To responsibly develop and deploy Generative AI technology there needs to be a structured and balanced approach to Ethical research. There are a few reasons for this:
1. No agreement on the Inclusion/Exclusion criteria.  
An ethcial review report [ethcial review reprot by Khan](https://www.researchgate.net/publication/354651489_Ethics_of_AI_A_Systematic_Literature_Review_of_Principles_and_Challenges) has exposed that there is no agreement on what the key principles should include and how they should be developed. 
2. Existing principles are practically inadequate.  
when ethical principles were developed, the practical implications and effectiveness of these principles are seriously doubted. Some principles are too vague. Some of them are very abstract such as “fair” and “dignity”, a lack of precise definition makes those principles difficult to be considered in real world settings. Other principles are too general. The available principles are highly general and broad in concept to specifically consider in the AI industry. Policymakers involved in drafting AI ethics principles might not have strong technical understanding of AI system development processes, which makes the principles more general and ambiguous. some principles conflict in practice. Organizations, committees and groups involved in developing the AI ethics guidelines and principles have opinion conflicts regarding the real-world implementation of AI ethics. Principles are also interpreted differently.  AI ethics principles are widely considered ambiguous and general by the majority of the organizations. It has been found that tech firms involved in the development of AI and autonomous systems follow ethical guidelines based on their own understanding. There are no universally agreed ethical principles that can bring all the institutions on one page. 
3. Lack of ethical knowledge. The third and the main challenge that AI ethics face is the lack of ethical knowledge. This results in practice that is still far from being mature. On one hand, AI model and application developers are focused on the technical capability and mostly have no much knowledge of how people use the technology; on the other hand, AI model users are driven by personal goals, and motivated to use the most advanced technology to achieve those goals. This goal-driven behaviour often drives AI users naturally to ignore any other issues including ethics. 
Government organisations are not experts in the AI model development and therefore not in a position to give expert advice, while some opine that establishing ethics in AI by a political organisation is not possible without there being a political agenda. At the same time, governing bodies also believe that management and technical staff are not aware of the moral and ethical complexity of the AI systems in application. These split beliefs result in not enough ethical standards and frameworks being available that can provide detailed guidelines to the AI industry. 

Therefore, the review suggests that the only way forward is gathering people from different disciplines, learning from each other, and working together to develop new ethical principles for this innovative technology. 

# Research Method - Hexie Theory as a framework for guiding the Generative AI Ethics research 

In a rapidly evolving field, generative AI characterized by innovative technologies that can create human-like content, ethical concerns have never been more pronounced as described above. In searching for guidance for AI Ethics research to fulfil the need of new principles and guidelines to accommodate multiple party’s interests and society concerns, a structured approach is needed. Hexie theory with its focus on goal-setting and principles for effective problem-solving, presents an intriguing and highly relevant possibility. 
The Hexie theory, principles and framework can be incorporated in our research method for guiding our research in the domain of Generative AI Ethics. This necessitates a systematic and well-structured approach. This approach is the fundamental principle of the Hexie theory. Before fully describing our research method, we would like to briefly review the basics of Hexie Theory. 

## The Basics of Hexie theory
Hexie Theory or Hexie Management Theory (HXMT) [W. Han and Y.M.Xi 2008, P Liu and YM Xi 2012, Youming Xi, Xiaojun Zhang and Jing Ge 2012] was initially developed to explore and solve real world management issues like uncertainty and ambiguity under complex and dynamic organizational contexts. It was firstly introduced by Xi [Xi 1989] in his doctoral dissertation and has been developed in the following three decades and now it has established itself as a systematic framework applied to many research and practical areas such as strategy, leadership, and organization theory [Xi and Shang 2002; Xi and Zeng 2005; Xi et al., 2006; Xi and Wang 2006].
The theoretical framework of HXMT is shown in following figure.
![Hexie Theory](/assets/posts/Hexie/Hexie.jpg)
Hexie Theory believes that human activities are uncertain, diverse, and involve multiple meanings, that they evolve with limited intervention, and the evolution process often includes gaming. The theoretical framework for Hexie Management Theory consists of a Vision and Mission, the Hexie Theme, the He Principle, the Xie Principle, the Coupling of He and Xie Principles, Hexie Leadership, and Hexie Expansion, etc. [XJTLU]. Hexie Theory, originating from the Chinese term "Hexie" meaning harmony, introduces four critical components that are integral to its framework: the He Principle, the Xie Principle, the Hexie Theme, and the Hexie Coupling. Among the 4 components the two most important components are: The Hexie Theme and the Xie Principle. 
The Hexie Theme represents a medium-term goal, a specific objective to be achieved within a defined period. It serves as a guiding light, highlighting key issues that require resolution and allowing for adaptability over time. The Hexie Theme embodies the notion of harmony in problem-solving, emphasizing the need for balance and coherence in addressing challenges within a particular context.
Complementing the Hexie Theme is the Xie Principle, which offers a set of rules and propositions designed to reduce complexity in management processes. The Xie Principle acts as a practical guide, providing a structured approach to problem-solving by breaking down intricate issues into manageable components. It encourages systematic thinking and efficient decision-making, aligning actions with the overarching Hexie Theme. The Xie Principle embodies the essence of harmony through its emphasis on order, coherence, and the reduction of unnecessary complexities in achieving the defined goal.

## Research Methodology - Hexie Theroy integration
In the context of Generative AI Ethics research, integrating Hexie Theory entails applying Hexie Theme and Xie Principle as a systematic and goal-oriented approach to guide ethical decision-making at each step of the Ethical framework development. Following figure  shows our research method integrated and guided by the Hexie Theory.
![Integration of Hexie Theory into our research and research actions guided by the Hexie Theory](/assets/posts/Hexie/HexieInte.jpg)
Detailed below is how Hexie Theory can be applied in our method:
1.	Defining the Hexie Theme for Ethical Research Goals: 
  -	Start by identifying the medium-term ethical goals for generative AI research. These could include minimizing biases in AI-generated content, ensuring transparency in AI algorithms, or preventing malicious use of generative AI technology.
-	Clearly articulate these goals, specifying the issues that need to be addressed to achieve them. For example, if the goal is to minimize biases, the Hexie Theme may involve reducing bias in AI training datasets.
2.	Developing a Structured Ethical Framework:
-	Utilize the Xie Principle to develop a structured ethical framework for generative AI research. Break down the ethical challenges into manageable components.
-	Define rules and propositions for ethical decision-making. For instance, establish guidelines for data collection and usage to ensure fairness and privacy.
3.	Balancing Ethical Considerations:
-	Hexie Theory emphasizes balance and harmony. Apply this principle by considering the trade-offs between different ethical concerns. For example, achieving complete transparency might conflict with user privacy, so a balanced approach is essential.
4.	Continuous Adaptation and Adjustment:
-	Hexie Theory allows for adjustments over time. Ethical considerations in generative AI research are dynamic and may change with evolving technology and societal expectations.
-	Regularly revisit the Hexie Theme to ensure it aligns with the current ethical landscape and make necessary adjustments to your ethical framework.
5.	Setting Milestones and Monitoring Progress:
-	Define milestones and key performance indicators (KPIs) to measure progress toward ethical goals. For instance, monitor the reduction in bias in AI-generated content or improvements in transparency.
- Hexie Theory's goal-oriented approach encourages continuous improvement and provides a mechanism to assess the effectiveness of ethical measures.
6.	Incorporating Ethical Reflection in the Research Process:
-	Make ethical considerations an integral part of the generative AI research process. Encourage researchers to reflect on the ethical implications of their work at each stage, from data collection to model training and deployment.
-	Hexie Theory's systematic approach ensures that ethical reflection is not an afterthought but an ongoing practice.
7.	Collaboration and Stakeholder Engagement:
-	Hexie Theory promotes cooperation and harmony. Engage with stakeholders, including ethicists, policymakers, and the wider AI community, to ensure a collaborative approach to ethical decision-making.
-	Seek external input and feedback to maintain balance and harmony in ethical choices.
By adapting Hexie Theory in this manner, Generative AI research can benefit from a structured and balanced approach to ethical decision-making, fostering responsible and harmonious development and deployment in this innovative field.

# Conclusion
Ethics in Generative AI has become a global topic of interest for both policy makers and academic researchers. In the last few years, various research organizations, lawyers, think tanks, and regulatory bodies have become involved in developing AI ethics guidelines and principles. However, there is still debate about the implications and practical feasibility of these principles. This research proposal believes that current Generative AI Ethics research is too focused on the technology aspects and there should be more emphasis on mitigation of bias and filtering untruthful content that has been generated. Based on the Hexie Theory, a lack of the He Principle and cultural and philosophical context cannot achieve holistic and interconnectedness perspectives. Inspired by the Hexie Theory, this research proposal “Hexie theory guided Generative AI Ethics study” not only integrates Hexie Principles into our own research but will guide our work to produce responsible AI development and deployment. This research is significant because it is the Hexie Principles in practice. The proposed research brings an unprecedented broader expertise from different disciplines into one unique team, following a novel approach that blends “He Principle” - eastern humanity-centric approach with “Xie Principle” - western – systematic and process-based approach together into this uncharted territory. Our Hexie Theory guided research method integrates Hexie Theme and Hexie Principles into our systematic and structured process. Using the Hexie theory guides our actions across our research phases. With that we can expect revolutionary outcomes in comparison with existing approaches. Our research will contribute to a wide range of areas such as improvements in ethical practices, transparency, fairness, and collaboration within the Generative AI research community as well as leading to more responsible, accountable, and trustworthy AI technology deployment and adoption. These contributions aim to foster responsible AI development and development and enhance the ethical integrity of generative AI technologies. It has great potential to be significant and influential in this field.

# References
1. AIAAIC Repository, (2022). AIAAIC, https://www.aiaaic.org/home
2. Abhishek Gupta, Alexandrine Royer, Connor Wright, Victoria Heath, Muriam Fancy, Marianna Bergamaschi Ganapini, Shannon Egan, Masa Sweidan, Mo Akif, Renjie Butalid (2021), The State of AI Ethics Report (Volume 4), https://arxiv.org/abs/2105.09060
3. Deepfake, March 2022, AIAAIC - President Zelenskyy deepfake surrender, https://www.aiaaic.org/aiaaic-repository/ai-and-algorithmic-incidents-and-controversies/president-zelenskyy-deepfake-surrender
4. Arif Ali Khan, Sher Badshah, Peng Liang, Bilal Khan, Muhammad Waseem, Mahmood Niazi, Muhammad Azeem Akbar (2021), Ethics of AI: A systematic literature review of principles and challenges, published in September 2021 https://arxiv.org/pdf/2109.07906.pdf
5. Arif Ali Khan (2022). Ethics of AI: A Systematic Literature Review of Principles and Challenges. EASE, 13-15 June 2022, Gothenburg, Sweden. Available from: https://www.researchgate.net/publication/354651489_Ethics_of_AI_A_Systematic_Literature_Review_of_Principles_and_Challenges
6. G Li (2023), Generate an Avatar-based Movie Using AI models, Blog, 10 May, 2023, https://gangminli.github.io/Generate-an-Avatar-based-Movie-Using-AI-models/
7. Jack Clark and Ray Perrault (2023), AI Index 2023. AI Index Report 2023 – Artificial Intelligence Index (stanford.edu). https://aiindex.stanford.edu/report/
8. Jack Clark et al (2023), Technical AI Ethics (chapter 3 of The 2023 AI Index: AI’s Ethical Growing Pains). HAI_AI-Index-Report_2023.pdf (stanford.edu) https://aiindex.stanford.edu/wp-content/uploads/2023/04/HAI_AI-Index-Report_2023.pdf
9. Katharine Miller (2022), The 2022 AI Index: AI’s Ethical Growing Pains. https://hai.stanford.edu/news/2022-ai-index-ais-ethical-growing-pains.
10. Shelby Hiter (2023), Generative AI Landscape: Current and Future Trends, Artificial Intelligence, May 11, 2023. https://www.eweek.com/news/generative-ai-landscape/
11. Shelby Hiter (2023-2), Generative AI Ethics: Concerns and Solutions, Artificial Intelligence, June 13, 2023. https://www.eweek.com/artificial-intelligence/generative-ai-ethics/#concerns_and_challenges
12. Junhua Zhu (2022), AI ethics with Chinese characteristics? Concerns and preferred solutions in Chinese academia, AI & Soc (2022). https://doi.org/10.1007/s00146-022-01578-w
13. Matt Korda (2023), Could a Chatbot Teach You How to Build a Dirty Bomb? January 30, 2023, https://outrider.org/nuclear-weapons/articles/could-chatbot-teach-you-how-build-dirty-bomb
14. Stephanie Lin, Jacob Hilton, and Owain Evans. 2022. TruthfulQA: Measuring How Models Mimic Human Falsehoods. In Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 3214–3252, Dublin, Ireland. https://aclanthology.org/2022.acl-long.229.pdf
15. Thilo Hagendorff (2020), The ethics of AI ethics: An evaluation of guidelines. Minds and Machines 30, no. 1 (2020), 99-120. https://doi.org/10.1007/s11023-020-09517-8, 
16. Ray Eitel-Porter (2021), Beyond the promise: implementing ethical AI. AI and Ethics 1, 1 (2021), 73-80. https://doi.org/10.1007/s43681-020-00011-6
17. Rebecca Heilweil (2023), What is generative AI, and why is it suddenly everywhere? Vox, 5 Jan 2023. https://www.vox.com/recode/2023/1/5/23539055/generative-ai-chatgpt-stable-diffusion-lensa-dall-e
18. Xi, Y.M. (1989), Hexie Theory and Strategy, Guizhou People’s Publishing House, Guiyang (in Chinese).
19. Xi, Y.M. and Shang, Y.F. (2002), Hexie Management Theory, Renmin University Press, Beijing (in Chinese).
20. Xi, Y.M. and Wang, D.G. (2006), “Harmony configuration and Hexie management: an empirical examination of Chinese firms”, paper presented at the 13th International Conference on Management & Engineering, Lille.
21. Xi, Y.M. and Zeng, X.J. (2005), “Complex problem solving: Hexie management theory from China”, paper presented at the First World Congress of the International Federation for Systems Research, Kobe.
22. Xi, Y.M., Cao, X.W. and Xiangli, L.X. (2010), “A Chinese view on rebuilding the integrity of management research: the evolving He-Xie management theory”, Chinese Management Studies, Vol. 4 No. 3, pp. 197-211.
23. Xi, Y.M., Han, W. and Ge, J. (2006), Research on He-Xie Management Theory, Xi’an Jiaotong University Press, Xi’an (in Chinese). 
24. XJTLU. The web site of the Hexie Academy. https://www.xjtlu.edu.cn/en/research/institutes/Hexie-management-research-centre/research/management-theory
25. Youmin Xi, Xiaojun Zhang, Jing Ge (2012),"Replying to management challenges: Integrating oriental and occidental wisdom by Hexie Management Theory", Chinese Management Studies, Vol. 6 Iss: 3 pp. 395 – 412. http://dx.doi.org/10.1108/17506141211259104
26. ZEN SOO (2023), China’s Baidu makes AI chatbot Ernie Bot publicly available. August 31, 2023. https://apnews.com/article/baidu-ai-chatbot-ernie-chatgpt-627bd09608816847907d41f44da235d9

<p>
{% include  share.html %}
</p>

<span style="color:#9e9696"><i> Last updated: 10/00/2023</i> </span>

<p>
{% include  license.html %}
</p>