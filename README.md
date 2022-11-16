# KIT thesis writing notes
These notes were written by Judy Kay and collated & edited by Matthew Merkas for the Keep In Touch theses of 2022 (see Past Honours Students and Coursework Master’s students on Judy's [alumni page](https://jkay-github.github.io/students-all/)). Some notes are only relevant to KIT, but many are also relevant to other HCI or even more general computer science writing.

## Miscellaneous

* Make any code repos (e.g., GitHub) accessible to examiners
* Stay on top of INFO4001/4002/4990 deadlines
* Please use Zotero to manage your references

### Past/example theses

Available on Judy's [Alumni page](https://jkay-github.github.io/students-all/) @ Past Honours Students and Coursework Master’s students

### Audience

Examiners. Needs to be detailed enough for both classes of examiners: (1) a researcher in the area and potentially familiar with the work, (2) a non-HCI computer science researcher

### Writing Style

* Give your system a name, starting with a consonant
  * In LaTeX, define a new command for easy changes
* Write in the style of the academic papers you've read
  * Use headings to signpost the writing
    * Also write a short introduction for each chapter - see example theses
  * Keep sentences short
  * Avoid passive voice
  * Not colloquial, but formal
  * Back up claims with citations to the literature
  * Avoid broad claims that aren't needed - big claims need strong support (>= 5 citations to strong work) and they often aren't necessary. Soften them
  * Common English slips: ~~participants that~~ participants who
  * If you're repeating material, you may need to reorganise your information. Be careful about forward and backward references. Use LaTeX labels on each section so you can refer to them
    * e.g., rather than "as described in a previous section", write "as described in Section _"
    * Use these cross references for figures and tables also
* Link the material to your thesis
  * Help the reader understand why they are reading what you tell them

### Figures and Tables

* Refer to all tables/figures before they appear in text
* Explain all tables/figures in text
* Write meaningful captions that enable a reader to make sense of the figure, even without reading all the text
* Typically the caption explains what the user should see and understand
* Associated text may explain your design of each aspect or how it links to other aspects
* Ensure that text adds value to what is obvious in the figure and already in the caption e.g., explain the key features and link this to your thesis concerns
* Consider adding markup e.g., letters or numbers so you can direct the reader to those

### References

* Include an indication of the reason this paper is worth including e.g., seminal work on _, recent, very similar goals to thesis statement, etc.
* Use APA style citations
  * Valuable, as the reader can see the author and year without searching
* Make sure references at the end are complete. Collect references using DOIs in Zotero and export to bibtex this way
* Only cite work you have actually read
  * If reading only relevant parts of a book, make sure you make that clear, or that the rest of the book is consistent with what you've read
  * Use indirect citations/secondary sources if you did not read the cited work
* Put citations with the author name(s) at the start of a sentence
  * e.g. Smoth and Blogs (2020) introduced a novel... vs. Smoth and Blogs introduced a novel... (Smoth and Blogs, 2020)

### Feedback process
* To get feedback send the PDF of:
  * At least whole chapters
  * Annotate to explain what is new and what you particularly want feedback on
  * Highlight parts you are concerned about and add a comment explaining
  * Make sure the date is clear
  * Rationale: avoid rush at the end of Semester 2, near the deadline

### Timeline
* Realistically, you want minimum chapters 1 (Introduction) & 2 (Literature Review) finalised before Semester 2
* Chapters 3 (Design) & 4 (Implementation) should also be underway

### KIT Gotchas

#### This is not replicating email

These projects are about prototyping for a very light-weight device that can connect to people who are the closest contacts of the elder.

There is literature indicating that this is typically a very small circle.

One version of KiT is a pairwise system. A sophisticated version could have a very tiny form factor. Two people who want to be in contact would buy a pair of them. If the elder wanted connection to another person, they could buy another pair.

The goal is to support close communication among the very small number of people who are closest to the older. Issues of scalability are simply different for something like email. There is a real risk of slipping you have slipped into assuming that we are simply replicating an email interface.

#### Over-apologising

You should state what you did and why

You should state the strengths (preferably with evidence)

Acknowledge limitations... often they are trade-offs, and you can justify this way


## Contributions

* Do a careful check that you include some detail about each other
* Name each other
* Worked together
* Specialised in aspects of the literature
* Each identified a concept to explore - conceptual contribution
* Rich discussion of what/how each peer contributed to your thesis


## Chapter 1 (Introduction)

### Thesis statement

* "This thesis aims to explore..."
* Starting with this immediately distinguishes your work from other similar projects
* Strictly defines the nature of communication we're trying to support:
  * Short messages
  * Frequency (~daily)
  * Duration (long-term, years)
  * Pairs of people who have a very close relationship and commit to be in contact - what sort of messages does this imply?
  * Medium (e.g., audio, video, etc.)

### Definitions

* Explain the thesis statement with one paragraph for each main concept (i.e., word/phrase) e.g., asynchronous. What & why (not how) including definitions, especially for terms like 'lightweight'
  * Should mention "asynchronous", "keep in touch", user population, "situated", "appliance"
  * Elders? Seniors?
    * From Abraham Elias ([2022](https://www.dropbox.com/s/xe80l8nvet6ljdv/2022-Abraham-Elias.pdf?dl=0)):
    "For the purpose of this thesis it is not necessary to define the elderly, or ‘elders’, by biological age, but rather associate the term with certain everyday contexts; a concept described by Brandt et al. (2010) as situated elderliness. For example, these contexts may be that:
      * They are unable to leave the home due to reduced mobility.
      * They have few active social contacts.
      * They are unable to partake in other forms of digital communication because of technological barriers"
  * Asynchronous
  * Situated
  * Appliance
  * Lightweight
  * Commmunication
  * Accessiblity needs of your population
* As you find and refer to terms in Chapter 2, consider adding them here in Chapter 1

### Research questions

* RQ1: How can we design a KIT device that...
* RQ2: How can we evaluate the KIT design for use in a co-design project
  * Background about the co-design project
  * Goal is to have prototypes for a co-design study to be conducted by Naseem Ahmadpour, Judy, and Bob
  * The co-design study involves a workshop with a group of potential target users who are in palliative care and may have cognitive loss and are likely to be elderly
  * This will start with an open exploration of participant needs and then this work will be used to provide participants with a small set of potential interfaces to explore. This is intended to give them a foundation for comparing these options and their earlier comments. Together these are intended to provide a foundation for creating KIT systems for use by this population
  * Ethical approvals with the relevant medical partners have been approved for the above leaders of the research
  * Paragraph explaining that the evaluation needs to inform the iterative refinement and assess whether KIT is ready for use in this context

### Thesis outline & contributions

* How & why is your idea good
* Brief overview of the final interface (user view)
* Overview of thesis and contributions:
  * Chapter 2: related work
    * Contribution: synthesis of research on _ and how to evaluate KIT systems
  * Chapter 3: design of KIT
    * Contribution: novel _ interface for _
  * Chapter 4: implementation
  * Chapter 5: evaluation design
  * Chapter 6: evaluation results and discussion
  * Chapter 7: conclusions and future work


## Chapter 2 (Literature Review)

* Start with thesis statement
* Paragraph about how this maps to the sections in this chapter
* Expect one section for each main aspect of your thesis statement (e.g., asynchronous, situated, etc.)
* Plus a section on evaluation/methods
* The goal is to identify a gap in the literature, to position your work

### Design

* Identify the main papers relevant to your work
  * A set of coordinated papers to really drive the literature review
  * Start by identifying 2-5 seminal papers i.e., older + impactful (highly cited)
  * Add a rationale
* Describe each system. Also include:
  * A description of what the authors stated were the goals of their work
  * One or more screenshots (see [Figures and Tables](#figures-and-tables))
  * State how it links to your thesis - key lessons
* Once you have a solid set, abstract the information and create a table for the start of each section (class of systems)
  * One row per system. Usually one paper, but may be a set of papers about the same system
  * Columns:
    * Give a short name for the system e.g., "Whereabouts Clock"
    * Main citation(s) in APA format (author & year)
    * Target users (e.g., elders only)
    * Multiple columns for key features relevant to your thesis e.g., asynchronous/synchronous, frequency of use
    * Key lessons
* The nature of this table is section-dependent
* Each table goes at the start of each section so a reader has an overview, and so you can easily refer them to the table to help them see the big ideas across the papers
* Consider adding a row for your own system - clearly distinguish design aspects

### Evaluation

* Table summary of literature
  * Goal is to demonstrate the breadth of your reading (we want lots of rows) and depth of your understanding (synthesis, i.e., compare papers in columns)
  * Columns:
    * Short name for the system e.g., "Whereabouts Clock"
    * Main citation(s) in APA format (author & year)
    * Participants
      * Number of people
      * Demographics
      * e.g., 10 pairs of elder-carer/friend/family (use the same terminology as the paper)
    * Evaluation type e.g., lab study, field study, etc.
    * Evaluation length e.g., 1 month
    * Key measures (to evaluate effectiveness) e.g., log data, interviews each week, etc.
  * Communicate
    * Relevant background for your work i.e., what informed the work
    * Situate the work - add a row at the end for your system

### Finding papers

* Book chapters tend to be tutorial level summaries of previous work (not bleeding edge). Usually reviewed, but not on the same level as the top conferences/journals
* Find seminal papers. Most in the field have read these and are likely to cite them
* Snowballing (find papers which cite seminal papers)

### Some references

* All benefit from design motivated to help people with special needs | Usability: Definitions and concepts, https://www.iso.org/obp/ui/#iso:std:iso:9241:-11:ed-2:v1:en ISO 9241-11:2018
* On merits of multiple design alternatives | Tohidi, Maryam, William Buxton, Ronald Baecker, and Abigail Sellen. "Getting the right design and the design right." In Proceedings of the SIGCHI conference on Human Factors in computing systems, pp. 1243-1252. 2006


## Chapter 3 (Design)

### Personas

* Table with one row for each persona briefly explaining why you considered each one useful
* Must explain why you need personas for young people (Kate and Sarah, before the fine details)
* Need to explain why you designed each of them as you did
  * Refer to literature in the chapter before and design goals of the work
* Show how you thought through the persona design process
* **Must explain how you used these personas**
  * Don't just define them and ignore them. This makes them totally useless
  * How you considered each as you explored the design space
  * Personas helped think about each design element and the bigger design picture
  * Ideally, a desk evaluation of the interface design, working through how it would be used by each persona
* Keep referring to personas throughout the chapter (by name)
  * Must explain that certain design decisions were made for Alice because of _ (insert something about Alice in the persona description)
* The older person is the primary persona - see UX Book (Hartson and Pyla)
  * In design trade-offs, you always design for the primary persona
* References
  * Hartson, Rex, and Pardha S. Pyla. The UX Book: Process and guidelines for ensuring a quality user experience. Elsevier, 2012.
  * Hartson, Rex, and Pardha Pyla. The UX book: Agile UX design for a quality user experience. Morgan Kaufmann, 2018.
  * Also look at https://www.nngroup.com/articles/persona/, https://www.usability.gov/how-to-and-tools/methods/personas.html


### User goals

* Stakeholders
  * Primary persona 1: person with some cognitive loss (likely older, frail)
  * Primary person 2: able person who needs to keep in touch regularly (likely younger)
  * Other potential personas: two older people, children, grandchildren (kindergarten-age), those with accessibility problems e.g., hearing loss
* … for asynchronous, assuming 1:1 communication
* Setup:
  * Elder (or younger) sets a goal for frequency of communication. Default daily?
  * Decide where to put the situated appliance
  * Decide on level of communication intended e.g., daily, roughly symmetric in volume, goal setting?
  * Configure the device (should consider how many times this needs to be performed. Once?)
    * Accessibility subgoals e.g., font size to meet recommendations
    * Simplicity of interaction subgoals e.g., easy to set up a connection to a single close contact (family or friend)
* Each day (assuming goal is daily):
  * Send:
    * Remember intention to communicate (potential for system initiative)
    * Decide whether to do so
    * A sends asynchronous message to B
      * A initiates recording
      * A completes recording and sends the message
      * A terminates the message (e.g., changed their mind, message was interrupted, etc.)
    * Have feedback on goal performance (support self-monitoring to check if message sent)
  * Listen:
    * Remember to check (potential for system initiative)
    * Decide to do so
    * A plays a "new" message (one they haven't previously played)
    * Perhaps review recent messages?
    * Perhaps review longer history and trends? (useful for assessing symmetry)
* Less often
  * Reflect on long-term success at meeting goals and potentially revise them
  * Replay "old" messages
* Other possibilities around history of use e.g., young person sets a target to send 3 messages a week. System helps them see if they have achieved their goals short- and long-term, with similar monitoring of older person (perhaps a counter for the number of times A has played a message?)
* Read/listened receipts? (awareness of the other end e.g., if a sent message has been played) - should we/how can we portray this?


## Chapter 4 (Implementation)

* ?


## Chapter 5 (Evaluation Design)

### Cognitive walkthrough

* No users. Performed by you (an expert)
* Evaluates learnability

### Overview of usability testing

* Think-alouds:
  * Other KIT students
  * Other students (or other people)
  * Elders
* Formative study
* Main/summative evaluation
  * Use system within the group for one week

### Example research protocol

Approach to usability/utility testing
* Step 1 : propose study to Judy, then refine
* Step 2: Two person trial - one inside the group + one fresh eyes, then refine
  * [Start by demo-ing TA](https://www.nngroup.com/articles/thinking-aloud-demo-video/)
  * Series of tasks
  * UMUX-lite
    * Lewis, James R., Brian S. Utesch, and Deborah E. Maher. "UMUX-LITE: when there's no time for the SUS." In Proceedings of the SIGCHI conference on human factors in computing systems, pp. 2099-2102. 2013.
    * "What is the best thing about this system?"
    * "If there was one thing you could change, what would it be?"
    * "Any other comments?"
* Step 3 - main study - 3-5 people from each persona type
  * "Authentic use"
* More questions for study - recruitment
  * Age ranges: 18-40, 41-60, 61+
  * Introduction spiel
    * "I have built … It is intended for use by diverse users, including young adults and elderly people, including those who may have some cognitive loss. At this stage I am refining the interface and the protocol for evaluating it. I will use the results of this session to do that refinement."
    * "This system was designed to make it very easy to have easy, regular social contact, especially to help older people keep in touch with their grandchildren - do you think this would be useful for you?"" Ask them to elaborate.
* Aim to have small qualitative study such as is planned for Naseem
  * 3 people who use more than 1 system

### Participants

* A subsection should explain the design of recruitment
  * How did you recruit participants? (e.g., convenience sample of university students) How many did you aim to recruit?
  * Must carefully justify the decisions
  * Must describe the benefits and acknowledge the limitations
  * Some references:
    * Lewis, J.R. Sample sizes for usability studies: Additional considerations. Human Factors 36, 368--378 (1994)
    * Bevan, Nigel, Carol Barnum, Gilbert Cockton, Jakob Nielsen, Jared Spool, and Dennis Wixon. "The" magic number 5" is it enough for web testing?." In CHI'03 extended abstracts on Human factors in computing systems, pp. 698-699. 2003.
    * Nielsen, J. Why you only need to test with 5 users. Alertbox (2000) www.useit.com/alertbox/2000319.htm
    * Virzi,R. Refining the test phase of usability evaluation: How many subjects is enough? Human Factors 34,457-468 (1992).
* Reference to justify asking participants to state their sex/gender
  * Heidari, Shirin, Thomas F. Babor, Paola De Castro, Sera Tort, and Mirjam Curno. "Sex and gender equity in research: rationale for the SAGER guidelines and recommended use." Research integrity and peer review 1, no. 1 (2016): 1-9
  * Note that sex is biological and gender is a social construct.
  * Your thesis should justify asking for details of the participant’s gender or sex.  This because it may be salient and the above paper can be cited as a reference that it is best practice to ensure it is considered as part of research.  Then you should justify the wording of questions in terms of what would be understood and acceptable to your target participants.
  * Note that this is currently a sensitive matter for some people.
* Need a paragraph about preliminary studies with thesis group members
  * Convenience sample
  * Carefully assess the implications of this, particularly in terms of their level of knowledge on the topic and level of expertise
  * Essentially, you must make clear that in your decision to recruit this particular group of people, you're also aware of the limitations this brings
  * In formative testing, 3-5 is considered to usually give valuable insights
    * Ensure you cover each relevant archetype group
    * Generally, you should stop as soon as you see things which need immediate improvement - often happens with the first user
  * In qualitative research, a study is typically continued until saturation is reaches i.e., you are not gaining new and useful insights

### Design of the materials for the study

* Explain the design of each part:
  * State what you did in enough detail that someone else could replicate what you did
  * Explain study design decisions (in detail) and the implications (strengths and limitations) so that someone who is considering replicating your work can evaluate your decisions
* Introduction: provide the precise details of any introduction. You need to explain precisely what you told the participants - ensure the text of the words is provided
* Ensuring the design avoids testing the user; refer to this as relevant e.g., "as the interface involves solving a word puzzle, I asked the participants to give a simple answer as we are testing the interface and do not need them to come up with a winning answer"

### Design of the user tasks

* You must explain your design of these tasks
* Should refer back to personas
* Should explain why you create a hypothetical family and ask people to role-play
* Must go through each of the tasks and explain how it tests something valuable in terms of usability
* One useful way to do this is a table with each of the tasks in rows, with columns for each of the main functional requirements of the system. You tick the overlaps
* Then, write text which refers to the table and to the actual text of the tasks and explains why you design each task in the way that you did
* It is common in usability testing to have multiple tests of the same user task
  * Users who need help on the first attempt might be able to complete the task independently on the second or later attempts. If this is the case, you should explain it

### Post-study questionnaire

* Recommended approach is UMUX-lite
* Must comment on the interpretation of the scores (see references below), and tell the reader what they mean
* With just a small number of scores (<5), simply look at the raw numbers and comment on those individually
  * Comment on the danger of calculating averages with a small sample size
* Be careful of significant figures - no more than 1 digit after the decimal place
* In tables of SUS/UMUX-lite scores, state the range
* References:
  * Lewis, James R., Brian S. Utesch, and Deborah E. Maher. "UMUX-LITE: when there's no time for the SUS." In Proceedings of the SIGCHI conference on human factors in computing systems, pp. 2099-2102. 2013.
  * Lewis, James R. "The system usability scale: past, present, and future." International Journal of Human–Computer Interaction 34, no. 7 (2018): 577-590.
  * Interpreting SUS (and more cautiously UMUX)
    * http://www.measuringu.com/sus.php
    * Bangor, Aaron, Philip Kortum, and James Miller. "Determining what individual SUS scores mean: Adding an adjective rating scale." Journal of usability studies 4, no. 3 (2009): 114-123.
  * Broader references:
    * Lazar, Jonathan, Jinjuan Heidi Feng, and Harry Hochheiser. Research methods in human-computer interaction. Morgan Kaufmann, 2017.
    * Sauro, Jeff, and James R. Lewis. Quantifying the user experience: Practical statistics for user research. Morgan Kaufmann, 2016.

### Reporting think-alouds

In general, you would report a think-aloud with:
* A table showing the success on each task
* You discuss this, often:
  * starting with key trends
  * then working through each of the tasks (rows)
  * then working through participants (columns)
* A summary of key comments made by participants, especially if they indicate why they had problems. This, too, could be a table based on the tasks
* Also expected are other observations from you, the tester, such as cases where people took a long time or looked confused, or look particularly happy. This, too, could be a table based on the tasks

### Formative study

* The first study
* Describe the study design (including the rationale)

### Summative evaluation

* Describe briefly how the initial study differed from the final version (referencing the previous chapter/section)


## Chapter 6 (Evaluation Results and Discussion)

* Report results
* Report outcome i.e., what changes were made to the device and, in the case of the formative evaluation, to the study design/evaluation protocol

## Chapter 7 (Conclusion)

* What is special about your system
* What did you learn about it
* Context of this thesis: briefly refer to all the others + some insights or lessons
* Longer term visions and issues
  * Lifetime of the messages

### Goals of the thesis

* Thesis statement
* Research questions

### Contributions

* Copy from Chapter 1 and write a paragraph about each one, referring to the relevant thesis chapters

### Limitations and future work

* Research questions defined the context of this work. Context of palliative care setting places severe constraints on the research that still remains
  * Months of evaluation
  * Out of scope of the thesis goals
  * A challenging research context
* Things you have thought of and cannot do
* Make clear you're aware of limitations of the user population in the studies (i.e., university students, family)

### Final notes
* We came up with this concept and explored it. Peers explored similar concepts - conceptual contribution

## Demo video
* Aim to have different people with very distinctive sounding voices to make it easier for people in the co-design workshop to hear the difference
* Make sure you do not speak too quickly
* Mention personas here, too. Introduce the scenario and the persona (and show their name on screen)
  * Mention how certain features could be used e.g., mention that Alice might be the daughter of one of these people
