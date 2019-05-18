> Please, refer to TheWebConf [Registration Page](https://www2019.thewebconf.org/registration) for details on registration package options.

# About

**Search-Oriented Conversational AI (SCAI) - WWW'19 Special**

at [The Web Conference 2019](https://www2019.thewebconf.org/), San Francisco, USA,
May 14 2019, 9:00–12:30.

> Click [here](https://scai.info) to go to the main page of the SCAI series.

More and more information is found and consumed in a conversational form
rather than using traditional search engines. Chatbots, personal assistants
in our phones and eyes-free devices are being used increasingly more for
different purposes, including information retrieval and exploration. On the
other side, information retrieval empowers dialogue systems to answer
questions and to get context for assisting the user in her tasks.  With the
recent success of deep learning in different areas of natural language
processing, this appears to be the right foundation to power search
conversationalization. Yet, we believe more can be done for theory and
practice of conversation-based search and search-based dialogues.

This workshop aims to bring together ML and NLP researchers on one hand
and Web Search/IR specialists on the other hand to lay the groundwork for collaboration on search-oriented conversational AI and establish future directions.

The [1st edition](/2017/) of the workshop was co-located with International Conference on the Theory of Information Retrieval (ICTIR 2017).

The [2nd edition](/2018/) of the workshop was co-located with the Conference on Emperical Methods in Natural Language Processing (EMNLP 2018).

The [4th edition](/ijcai2019/) will be held together with the 28th International Joint Conference on Artificial Intelligence (IJCAI-19) in August 2019. **Extended paper deadline: May 19, 2019**

## Topics of Interest
   * Surfacing search results in form of a dialogue (how to present information that search gives us in a form of a dialogue? Which model to use for dialogue-state tracking?
   * Evaluation of search-oriented conversational AI: despite early attempts at computing dialogue system's quality in a scaleable way, this is still an open challenge.
   * From conversational AI to personal assistants (how to maintain a stable and consistent assistant behavior)
   * Personalization for conversational AI and for its evaluation (what aspects and knowledge is needed for personalized experiences)
   * Deep Learning for conversational search: how to make it more grounded to the knowledge of the Web
   * Reinforcement Learning for conversational AI 
   * Voice as input (voice interactions with a personal assistant: how it will affect existing models?)
   * Specialized applications and uses cases for conversational search (specialized domains in health, finance, travel, etc...)
   * Balance and bias for more inclusive conversational AI systems

# Organizers
  * [Julia Kiseleva](http://juliakiseleva.com), *Microsoft Research & AI*, Seattle
  * [Jeff Dalton](http://www.dcs.gla.ac.uk/~jeff/), *University of Glasgow*, Glasgow
  * [Aleksandr Chuklin](https://www.linkedin.com/in/chuklin/), *Google Research*, Zürich
  * [Mikhail Burtsev](https://www.linkedin.com/in/mikhail-burtsev-85a47b9/), *MIPT*, Moscow

# Workshop Format
  * Invited talks
  * Panel discussion: you can [send](https://admin.sli.do/event/soadmtyz/questions) your suggestions
  * Breakout session to plan a roadmap for Conversational AI

## Invited Speakers
  * [Larry Heck](https://www.linkedin.com/in/larryheck/), *Viv Labs* & *Bixby Research*
  > * **Title**: The Conversational Web
  > * **Abstract**: We are in the "era of Conversational AI". Through the combination of natural language (spoken and written) with gesture, touch, and gaze, the conversational AI in modern virtual personal assistants (Siri, Alexa, Google Assistant, Bixby) can help you complete online tasks, find what you want, and answer any question as naturally as having a conversation – anytime, anywhere. While much progress has been made in recent years, building conversational AI systems still requires large volumes of annotated training data that is often difficult to obtain. This talk explores the emergence of the Conversational Web: an approach to address this challenge through the combination of what is traditionally considered web search with conversational AI.  First, this talk will discuss how the Conversational Web approach leverages the massive query click stream from Web search to bootstrap conversational AI systems. Second, the talk will discuss how the Conversational Web approach also leverages context (e.g., visual, gesture, location, knowledge). With these emerging methods, the Conversational Web  is showing significant promise towards creating deep, broad and seamless conversational experiences across our lives.
  > * [Slides](../slides/www2019/SCAI_WWW2019_Heck.pptx)

  * [Zhou Yu](http://zhouyu.cs.ucdavis.edu), *University of California, Davis*
  > * **Title**: Building dialog systems with less supervision
  > * **Abstract**: End-to-end methods are popular in training dialog systems recently, as such framework is easier to implement. However, similar to previous traditional methods, end-to-end methods still require at least a thousand labeled dialogs to obtain a decent system. In real-world scenarios, such as customer services, it is extremely difficult to adopt any of the neural-net based end-to-end training algorithms due to the lack of a large amount of labeled data. Obtaining human-human dialogs are costly. It is also difficult to use crowd workers to annotate customer dialogs due to data privacy. Building dialog systems with less data and fewer labels is an area that calls for better machine learning algorithms. We will talk about three work on building end-to-end task-oriented dialog systems using a reduced amount of supervision leveraging unsupervised learning, transfer learning and reinforcement learning.

  * [Jayesh Govindarajan](https://www.linkedin.com/in/jayeshg/), *Salesforce*
  > * **Title**: The Conversational Enterprise
  > * **Abstract**: The nature of conversations with and within the enterprise differ in significant ways from typical daily interactions with virtual assistants, in that they are more task oriented, less exploratory and need to evoke competence. To build enterprise grade conversational system requires an understanding of both the mechanics of user interactions as well as integrations with backend task execution systems. In this talk we will layout a canonical conversational flow along with the underlying NLP systems employed to execute broad, multi-step tasks such as providing customer service or conducting a sales call. We discuss a general typology of conversations inferred from analyzing these rich customer-company interactions. We will also share how the Salesforce has applied these learnings to design a simple “Conversational Model” that uses RNNs to keep track of conversational state. And finally, delve into the Salesforce Agent Assist AI service, which applies the deep learning conversational model to first learn and then suggest context-aware responses for customer service professionals.

  Startups:
  * [Eloquent Labs](https://www.eloquent.ai): Gabor Angeli
  > * **Title**: Mimic and Rephrase: Reflective listening in open-ended dialogue
  > * **Abstract**: Reflective  listening—demonstrating that you have heard your conversational partner—is key to effective communication. Expert human communicators often mimic and rephrase their  conversational partner, e.g., when responding to sentimental stories or to questions they don’t know the answer to. We introduce a new task and an associated dataset wherein dialogue agents must similarly mimic and rephrase a user’s request to communicate sympathy (I’m sorry to hear that) or lack of knowledge (I do not know that). We find that a syntax-aware rule-based baseline struggles to identify relevant subclauses or to handle non-trivial constructions like conditional clauses. To handle these challenges, we propose a simple end-to-end neural model: an LSTM with attention and a copy mechanism. In a human evaluation the neural model output is preferred  significantly more often than  the rule-based baseline and almost as often as a human-generated response, suggesting that this generation task is a practical addition to real world conversational agents.

  * [Replika AI](https://replika.ai): Nicolas Ivanov
  > * **Title**: Replika - AI that Cares
  > * **Abstract**: Replika is a chatbot application that aims to make people feel better via meaningful and supportive conversations. With over 100K monthly active users Replika has a great opportunity to collect a vast amount of conversational data (user-chatbot conversations) to later use this data to enhance its own models. Under the hood Replika employs different types of modern approaches to building conversational chatbots, ranging from traditional rules-based models to freshly adopted BERT-based selective and RL-boosted generative models. The presentation will touch on each component of Replika’s dialog system, demonstrating their ability to work smoothly in ensemble in order to solve one of the most important real-life problems of nowadays.

  * [Rulai](https://rul.ai): Yi Zhang
  > * **Title**: Virtual Assistant Ability Model
  > * **About**: Rulai is a new Enterprise Conversational Computing Platform provider. Rooted in academia, the founding team has published over 400 research papers and filed over 80 patents in AI. Its SaaS platform enables companies to build automated chatbots for customer service, marketing, sales, logistics, and HR use cases and has been deployed across a wide variety of industries. Rulai-powered bots help companies automate many human-centered processes to create a fast and frictionless experience for employees and customers. Its self-serve platform allows business users to create and evolve bots with minimal use of precious IT resources. Rulai was recently recognized by Gartner, Forrester, and Bloomberg.'

  * [Mosaix](http://www.mosaix.ai): Ni Lao
  > * **Title**: Weakly Supervised Natural Language Understanding (WSNLU)
  > * **Abstract**: In this talk, I will introduce recent work in applying weak supervision and reinforcement learning to Questions Answering (QA) systems. The discussion will include how semantic parsing tasks for natural language queries are converted to computation steps on knowledge graphs or data tables and produce the expected answers. State-of-the-art results can be achieved by novel short-term memory structures for sequence models and properly leverage long term memory in reinforcement learning algorithms. 

## Schedule
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQXyywonUIOKtBPucNr0PIpKWgZLzjEvJkJcWMTCWoPp7qrYskQfCQn-O9-zbJn_yH-6l_KjlqMX1wL/pubhtml?gid=1385852677&amp;single=true&amp;widget=true&amp;headers=false" height="300px" width="100%"></iframe> 

## Questions

<iframe src="https://app.sli.do/event/soadmtyz" height="800px" width="100%"></iframe>

