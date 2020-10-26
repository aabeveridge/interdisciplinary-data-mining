# *Interdisciplinary Data Mining: Best Practices and Research Methodologies for Studying Social Networks and Digital Content*

## Authors: Aaron Beveridge and Nicholas M. Van Horn

## Introduction: What is Data Mining?
The introduction extends the abstract (see: `README.md`) and explains how students, faculty, and non-academic researchers can get the most from *Interdisciplinary Data Mining*. Because this book has been written in R markdown, all of the example data visualizations in the methodologies section (Section II) also serve as functioning code examples to support readers in conducting their own studies. Each chapter provides suggested readings and tutorials to assist researchers in reproducing similar data visualizations for their own projects, and all of the code examples are available through GitHub. Additionally, the introduction will address why we have organized the book the way we have, providing a rationale for our choices and providing alternative ways of exploring the content in the book.

**Introduction Outline:**
- Extend abstract
- What is data mining?
  - Data Science vs. Big Data
- Rationale for outline and approach to book
- How to get the most out of this book
- Why R?
- How to contribute to MassMine

## Section I: Best Practices
### Chapter 1: Best Practices: Being Good Citizens of the Internet
This chapter explains the underlying rationale for MassMine: the use Application Programming Interfaces (APIs) to collect data from digital networks. Building on a basic description of API scraping, as compared to web scraping and web crawling, Chapter 1 explains the benefits and limitations of API scraping for interdisciplinary research.

**Chapter 1 Outline:**
- What are APIs and why do they exist?
- API scraping vs web scraping vs web crawling
- Scraping best practices
  - Robots.txt
  - Page visit delays
  - Bandwidth limitations of APIs
- Potential pitfalls/mishaps to avoid
  - Accidental DDOS
  - Unintended Doxing
- Conclusion
  - How other chapters extend the concept of "Being a Good Citizen of the Internet"

### Chapter 2: Knowing Networks: Network Types and Developer (Researcher) Guidelines
It's a common maxim to hear people proclaim: "I never read the documentation" or "I do not pay attention to terms of service." This chapter explains why researchers who are interested in interdisciplinary data mining cannot proceed with ignorance regarding the developer rules and terms of service for APIs. Additionally, it is important to pay attention to the ways in which various networks change over time, and how they account for these changes through developer blogs and public statements made about changes to their underlying systems and technologies.

**Chapter 2 Outline:**
- Why read the guidelines and terms of service?
- What can be found here?
- What are the types of Networks?
  - message boards and email groups
  - forums
  - RSS feeds
  - social networks

### Chapter 3: Research Ethics: Surveillance, Privacy, and Intellectual Property
- robots.txt
- the limitations of "anonymous" data
- intellectual property law and web scraping

### Chapter 4: Open Access: Sharing Data and Managing Collaborations
- the importance of the open data movement for interdisciplinary data mining
- legal issues involved with sharing data collected from APIs
- what are the current methods and what should researchers know?

## Section II: Research Methodologies

### Chapter 5: Defining Trends: Innovations, Games, and Graphs
This chapter tells the story of "trends" for digital networks. This chapter starts with a very simple definition of a trend according to Diffusion of Innovations, explaining the S-shaped model of diffusion, and the "Justin Bieber" problem. It then complicates this definition with discussions of "contagion" effects, and the problem of defining trends within singular networks.

Moving forward, it looks at the question of "trends" for game theory, explaining some fundamental issues related to information cascades, the unintended consequences of "datafication" (the 'like' button, for example), and then other issues--such as the common practice of 'gaming' social network algorithms. The goal for the chapter is to continue to complicate the idea of "trends," and to have the concept evolve as we work our way through Diffusion of Innovations, and then game theory, and then finally into graphs and other issues.

For graph theory we discuss strong and weak ties, triadic closure, and other known phenomenon resulting from agent based modeling. Additionally, we can bring in other ideas, like metcalfe's law and the dunbar number to also provide competing perspectives on how we make sense of patters/trends in digital networks.

- What is a trend?
  - Diffusion of innovations terminologies
  - S-shaped curve of innovation
  - the "newness" problem
- How "game theory" complicates any simple notions of "trends" and virality
  - weak/strong ties
  - triadic closure
  - others?
- Graphs, agents, and blackboxes
- Others?
  - metcalfe's law
  - dunbar's number

### Chapter 6: Text Mining: Natural Language Processing and Information Extraction
Outline:
- Text as Data
  - Brief History of NLP
  - Bag of Words vs. Word Embeddings
  - Scrubbing and Data Janitorial Work
  - Word Frequencies and N-Grams
    - Zips law
  - Word Correlations
- Documents and Corpora
- Emoji
- Sentiment Analysis
- Speech-to-Text: Analyzing Audio and Video
- Unicode and foreign languages

### Chapter 7: Mixed-Methods: Demographics, Psychometrics, and Qualitative Studies
This chapter explores use of surveys, case studies, and other qualitative methods in support of data-driven research practices.

### Chapter 8: Framing Research: [Need subtitle: Philosophy of Science Chapter (Where is all of this heading?), a guide to developing answerable/testable research questions]
