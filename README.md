# PSC-012Y Course Syllabus

## Course Information

### Friday Lecture

- **Meeting:** Friday Lecture
- **Time(s):** 10:00AM -- 11:50AM
- **Location:** Hart Hall 1116
- **Prerequisites:** None

### Weekly Virtual Tutorial

- **Format:** Online / asynchronous
- **Release:** Monday morning
- **Purpose:** Guided coding practice in `R`

### Instructor

- **Instructor:** Dr. William Rayo
- **TA:** Suryadyuti Baral
- **Course Email:** `datavis012Y@ucdavis.edu`
- **Course Site:** [Canvas](https://canvas.ucdavis.edu/courses/1089295)

### Laboratory Section 1

- **Lab Meeting:** Wednesday
- **Time(s):** 4:40PM -- 6:00PM
- **Location:** 73 Hutchison Hall

### Laboratory Section 2

- **Lab Meeting:** Wednesday
- **Time(s):** 6:10PM -- 7:30PM
- **Location:** 73 Hutchison Hall

## What Is This Course About?

Welcome to PSC-012Y. This course is a hands-on, beginner-friendly introduction to data visualization and introductory statistics for students in the social and behavioral sciences.

Throughout the quarter, we will use `R` and work using packages from the `tidyverse`. This gives us a consistent, readable workflow for importing data, cleaning and reshaping it, visualizing it, and communicating results in reproducible `Quarto` documents. My hope is that, by the end of the course, coding feels less intimidating and more like a practical tool you can use to ask questions, explore evidence, and communicate what you find.

This course emphasizes interpretation and practical use. Rather than trying to cover the theoretical detail behind every method, we will spend our time learning how to work with data, how to make sense of patterns and results, and how to communicate evidence clearly in relation to real questions in the social sciences. That choice is intentional. Many of the topics we touch on here could fill entire courses on their own, and our priority is to build a foundation that is useful, approachable, and immediately applicable.

A central goal of the course is to help you become more data literate. Data literacy is not just a technical skill; it is a way of making sense of the world. It helps you evaluate claims, interpret information more carefully, and communicate with greater precision and confidence. In a world filled with charts, statistics, and competing arguments, those skills matter.

You do not need to come in with preexisting programming or statistical expertise to succeed in this course. This course is designed for beginners who are willing to practice, stay curious, and learn by doing. If you leave the class feeling more comfortable writing code, more confident working with data, and more enthusiastic about continuing to build these skills, then the course will have done what it is meant to do.

## What Will I Learn To Do In This Class?

This course is organized around two complementary forms of knowledge: `Statistical Concepts` and `Programming Concepts`. By the end of the quarter, students who complete the course successfully should be able to:

- Distinguish between common types of social-science data, including categorical, continuous, and free-response text data.
- Explain what common introductory statistical tools are designed to help us learn from data.
- Read, clean, wrangle, and summarize data files in `R` using the `tidyverse`.
- Create clear and appropriate visualizations for categorical data, continuous data, group comparisons, relationships between variables, and introductory text analysis.
- Interpret basic statistical output in plain language and connect it to a research question.
- Communicate results in a reproducible `Quarto` document that integrates text, code, tables, and figures.

These goals are meant to help you become both a better reader of data and a more confident producer of it.

## What Materials Do I Need?

### Required

The laboratory and tutorial portions of this course require the statistical programming language `R`, the integrated development environment `RStudio`, and the ability to render `Quarto` documents. These are all available for free:

- `R` - <https://cran.r-project.org/>
- `RStudio` - <https://posit.co/download/rstudio-desktop/>
- `Quarto` - is bundled with `RStudio`

We will use the `tidyverse` from the beginning of the course, and later in the quarter we will also use introductory text-analysis tools such as `tidytext`. Instructions for installing any required packages will be provided in the weekly tutorials.

If your personal computer has difficulty running `R` and `RStudio`, you may use [Posit Cloud](https://posit.cloud/) as a backup option. The first laboratory meeting is designed in part to help students get a local installation working or get a cloud-based environment running.

**You will need regular access to a computer** so that you can complete the tutorials and prepare for lab outside of class time. If you do not have access to a personal computer, you may use one of the [Open Access Computer Labs](https://computerrooms.ucdavis.edu/openaccesslabs.html) on campus.

No textbook is formally required for this course. Any required readings, handouts, or reference sheets will be posted on Canvas. The goal is to keep the technical barriers to this course as low as possible while still giving you real practice with the tools used in data work.

### Supplemental

The following resources are optional, but many students find them helpful for connecting course concepts to `R` practice:

1. [Healy, K. (2018). *Data Visualization: A Practical Introduction*. Princeton University Press.](https://a.co/d/0riK9f2)
2. [Wickham, H., Cetinkaya-Rundel, M., and Grolemund, G. *R for Data Science (2e)*](https://r4ds.hadley.nz/)
3. [R for Beginners](https://cran.r-project.org/doc/contrib/Paradis-rdebuts_en.pdf)
4. [R and RStudio Basics](https://uc-r.github.io/basics)

## How Is The Course Organized?

PSC-012Y is a 4-unit course. The expected workload is approximately 12 hours per week. The course has three main parts:

1. **Friday lecture [2.0 hours]**  
   Lecture introduces the main statistical idea and programming workflow for the upcoming instructional unit. The goal is to help you understand what kind of question we are asking, what kind of data we need, and what kind of analysis or visualization is appropriate.

2. **Monday virtual tutorial [3.0 to 4.0 hours]**  
   Tutorials walk you through the `R` side of the course. They are designed to give you guided, hands-on practice with the `tidyverse` workflows and coding patterns you will use in lab.

3. **Wednesday laboratory [1.5 hours]**  
   Lab is where you apply what you learned in lecture and tutorial. You will work with additional datasets, practice relevant skills with support from your TA and peers, and complete in-lab assessments.

The weekly rhythm of the course is intentional:

- Friday lecture introduces the topic.
- Monday virtual tutorial gives you guided practice.
- Wednesday lab gives you a chance to apply both in a supported setting.

The **first week of the quarter is a small exception** to this pattern. Students will meet with their TAs in lab on Wednesday of Week 1 primarily to install `R`, `RStudio`, and `Quarto`, or to get a cloud-based setup working if needed. The first instructional unit then begins with the Friday lecture and continues into the following Monday tutorial and Wednesday lab.

This course is also intentionally structured so that `statistical concepts` and `programming concepts` are named clearly each week. One goal is to help students distinguish between:

- what they are learning about data and statistics, and
- what they are learning about coding in `R`.

Keeping up with this rhythm each week will make the course much more manageable. The design of the course is meant to help you build confidence gradually rather than feel like you are being asked to learn statistics and programming all at once with no support.

## What Will Be Graded?

### Participation (10%)

A meaningful part of learning is showing up mentally and contributing to the shared work of the class. Participation includes asking questions, responding to questions, and engaging with in-class activities during lecture and lab. In lecture, participation will often take the form of iClicker or Canvas-based check-ins.

### Virtual Tutorials via Lab Notebook (20%)

Each week, students will review tutorials to relate concepts in the lecture to code. By completing each tutorial, you will have everything you need to succeed in the following week’s lab meeting. You'll be required to keep a physical copy of your rendered `Quarto` code tutorials and bring them to lab sessions to use. These lab notebooks may also be used during the open-note sections of the mid-terms so make sure you're keeping your lab notebook up to date.

Teaching assistants will randomly conduct notebook inspections throughout the quarter to verify that students are following along with the tutorials.

### Lab Assignments (20%)

Students will complete weekly lab assignments during the in-person laboratory sections. These assignments will generally be submitted as rendered `Quarto` documents. Lab assignments are designed to show your growing familiarity with both the statistical concepts and the coding skills covered in lecture and tutorial. Since we know that life happens, we will drop the lowest lab assignment from your grade calculation.

### Midterm 1: Practical Lab Examination (25%)

The first open-note midterm will take place during the laboratory section after Unit 3. It will be submitted in a format similar to a lab assignment, but it carries greater weight and is intended to assess your independent understanding of the material covered in Units 1 through 3.

### Midterm 2: Practical Lab Examination (25%)

The second open-note midterm will also take place during the laboratory section near the end of the quarter. Like the first midterm, it will follow a lab-style format while assessing your individual mastery of course concepts from Units 4 through 7.

**Why?** The practical midterms are designed to assess whether you can put the skills into practice; read a dataset, choose an appropriate approach, carry out the analysis in `R`, select an appropriate visualization, and explain what the results mean.

### Real-World Data Reports (Optional Extra Credit)

These optional assignments provide an opportunity to apply course concepts to real-world data. The reports draw on material from both lecture and lab and are due around the same time as the midterm examinations.

Each of the Real-World Data Reports will replace the lowest lab assignment (two of them).

Full instructions, due dates, and any limits on extra-credit impact will be posted on Canvas.

Grading follows the standard percentage scale below:

- A (>= 93%)
- A- (90% -- 92%)
- B+ (87% -- 89%)
- B (83% -- 86%)
- B- (80% -- 82%)
- C+ (77% -- 79%)
- C (70% -- 76%)
- D (60% -- 69%)
- F (<= 59%)

## Course Policies

These policies are here to make expectations clear and to support a fair learning environment. This document is not exhaustive and may be updated during the quarter. Students are also responsible for policies outlined in the [UC Davis Code of Academic Conduct](https://ossja.ucdavis.edu/code-academic-conduct).

### Attendance

A large portion of the learning in this course happens through regular participation in lecture, tutorials, and lab. Missing class means missing both content and practice, and it can quickly make the course harder to follow.

If you know you will miss a meeting, please communicate as early as possible. When absences are unexpected, let me know as soon as you can so that we can consider whether any accommodation is appropriate.

**Why?** This course is structured as a sequence. Each week builds on the last, so staying engaged consistently matters more than cramming later.

### Late Work/Make-Ups

Please be proactive if you need more time or support. Most graded work in this course takes place through lab assignments completed during class time, so late work is generally **not** permitted unless approved by the instructor.

If an accommodation is granted, each day an assignment is late will result in a deduction of 25% from the total score. In the event that a lab assignment is missed, the Real-World Data Reports may be used to supplement missed work, subject to instructor approval and course policy.

### Diversity, Equity, and Inclusion

The University of California at Davis is committed to creating and fostering a campus environment that is inclusive, safe, and respectful for all. This course will be conducted with an atmosphere of collegiality with respect and recognition for the unique lived experiences and life histories inherent to each and every student. You are expected at all times to apply the highest academic standards to this course and to treat others with dignity and respect.

My goal is to help create a class environment in which students can take intellectual risks, ask questions, make mistakes, and learn without feeling that they have to already know everything.

### Accessibility, Disability, and Accommodations

If you require accommodations, please contact the [Student Disability Center (SDC)](https://sdc.ucdavis.edu/) as early as possible so that appropriate arrangements can be made. You are also welcome to communicate with me in the meantime, but formal accommodations **must** come through the SDC.

It can take time to put accommodations in place, so earlier communication is always better.

### Collaboration

In real research settings, collaboration is normal and valuable. In a course, however, collaboration has to be balanced with the need for each student to develop their own understanding and skills.

Students are welcome to discuss course material, strategies, and general approaches with one another. Collaboration should remain at a high level and should not extend to sharing full solutions. All submitted code and writing should be your own original work.

Students may also help one another with debugging, provided that the goal is to help the original solution function as intended rather than to rewrite or improve it. If someone helped you on an assignment, acknowledge that help.

### Academic Integrity, Plagiarism, and AI Use

Please review the [UC Davis Code of Academic Conduct](https://ossja.ucdavis.edu/code-academic-conduct). Any discovered plagiarism, including the use of generative AI tools (for example, ChatGPT) on work where they are not explicitly permitted, will result in a zero for the assignment and a referral to the Office of Student Support and Judicial Affairs (OSSJA).

**Why?** Learning happens when your brain actively struggles to make sense of new ideas. If AI removes that effort, the learning doesn’t actually happen.

I am actively doing research in this arena because I think AI has the potential to be a fantastic tool, but currently I do not recommend using it for most learning. TLDR: using AI is a fantastic tool that can help automate time-intensive tasks once you already know how to do the thing.

**Why not?** LLMs (large language models) work by predicting likely next words based on patterns in human writing, not by knowing facts or what any of those words mean. As a result, they can sound confident while still being wrong.

- [Visual explanation if you are curious](https://poloclub.github.io/transformer-explainer/)
- [Deeper dive by 3Blue1Brown: *Transformers, the tech behind LLMs | Deep Learning Chapter 5*](https://www.youtube.com/watch?v=wjZofJX0v4M)

LLMs can and often do give you the wrong answer. Ask AI to explain a topic you know very well and you will likely spot a bunch of incorrect details; this is called hallucination.

Using AI inappropriately can violate the UC Davis Code of Academic Conduct because it misrepresents your own learning and work. There can be serious consequences associated with disciplinary action.

Most importantly, learning happens when your brain actively struggles to make sense of new ideas. If AI removes that effort, the learning does not actually happen.

Interesting preliminary research on LLM (AI) use and learning outcomes: <https://www.brainonllm.com/>

Two figures related to that line of research are included below:

![Study design comparing `LLM`, search-engine, and brain-only groups across sessions.](images/ai-llm-study-design.png)

![Percentage of students in each group who struggled to quote anything from their essays, with the `LLM` group much higher than the search-engine or brain-only groups.](images/ai-llm-quote-results.png)

**How does this apply to this class specifically?** I want you to be able to accomplish the goals laid out in the course learning outcomes. These are measured in the assignments throughout the class. The practical midterms require you to work through tasks on your own using the skills you have built across lecture, tutorial, and lab. If you use AI on the parts of the course that are meant to build up those skills and that content knowledge, then you will likely be unable to do the task on your own.

If you do not develop the underlying skills in college, this raises an important question: what value would you offer an employer that AI could not?

## Appendix

### Tentative Schedule

**Course rhythm:** the course is organized into **7 core instructional units**. Each unit begins on Friday in lecture, continues with a virtual tutorial at the start of the following week, and concludes with a Wednesday lab. The first Wednesday meeting of the quarter is reserved for setup, and the final Friday meeting is used for course synthesis and wrap-up.

**First-week exception:** on **Wednesday, April 1, 2026**, students will meet with their TAs in lab for setup and installation support. The goal of that meeting is to get `R`, `RStudio`, and `Quarto` running on a personal computer or to get Posit Cloud working as a backup if local installation is not feasible.

| Phase | Friday Lecture | Virtual Tutorial Release | Wednesday Lab | Statistical Concept | Programming Concept | Optional Assignment(s) |
|---|---|---|---|---|---|---|
| Setup |  |  | **April 1:** TA setup and installation support | Orientation to course tools and workflow | Local `R` / `RStudio` / `Quarto` installation or Posit Cloud setup |  |
| Unit 1 | **April 3:** Foundations in `R`, `Quarto`, and Tidy Data | **April 6:** Getting Started with Data in `R` | **April 8:** First Data Exploration Lab | Units of observation, variables, research questions, tidy data | `read_csv()`, `glimpse()`, `select()`, `filter()`, first `ggplot()` |  |
| Unit 2 | **April 10:** Variable Types and Data Wrangling | **April 13:** Variable Types and Wrangling Practice | **April 15:** Wrangling Messy Survey Data | Categorical vs continuous, nominal vs ordinal, missing data | `mutate()`, `rename()`, `arrange()`, `count()`, `forcats` |  |
| Unit 3 | **April 17:** Categorical Data and Bar Charts | **April 20:** Categorical Data and Bar Charts | **April 22:** Categorical Analysis Lab | Counts, proportions, observed vs expected counts, introductory association testing | `count()`, grouped summaries, `geom_bar()`, `chisq.test()` |  |
| Midterm 1 | **April 24:** Review and Synthesis for Midterm 1 | **April 27:** Midterm Review and Practice | **April 29:** **Midterm 1** | Review of Units 1 through 3 | Review of core `tidyverse` workflows and interpretation | Real-World Data Report I |
| Unit 4 | **May 1:** Continuous Data and Distributions | **May 4:** Continuous Data and Distributions | **May 6:** Continuous Data Lab | Center, spread, skew, outliers | `summarise()`, `mean()`, `median()`, `sd()`, `IQR()`, histograms, density plots, boxplots |  |
| Unit 5 | **May 8:** Uncertainty and Comparing Groups | **May 11:** Uncertainty and Comparing Groups in `R` | **May 13:** Group Comparison Lab | Sampling variability, confidence intervals, two-group and multi-group comparisons, p-values in plain language | Summary tables, mean plots, error bars, `t.test()`, `aov()` |  |
| Unit 6 | **May 15:** Relationships Between Continuous Variables | **May 18:** Relationships Between Continuous Variables | **May 20:** Scatterplots and Trend Lab | Association, trend, correlation, regression as line-of-best-fit intuition | Scatterplots, `geom_smooth(method = "lm")`, `cor()`, simple `lm()` output reading |  |
| Unit 7 | **May 22:** Free-Response Text as Data | **May 26:** Free-Response Text as Data *(released Tuesday because of Memorial Day)* | **May 27:** Introductory Text Analysis Lab | Word frequency, stop words, sentiment, strengths and limits of word clouds | `unnest_tokens()`, stop-word removal, `count()`, joins, word clouds, simple sentiment summaries |  |
| Midterm 2 | **May 29:** Review, Communication, and Midterm 2 Preparation | **June 1:** Final Review and Results Writing Practice | **June 3:** **Midterm 2** | Review of Units 4 through 7; choosing the right figure and analysis | Synthesis of continuous distributions, uncertainty, group comparisons, continuous relationships, and text-analysis workflows | Real-World Data Report II |
| Wrap-Up | **June 5:** Course Synthesis and Wrap-Up |  |  | Communicating with data, reflecting on what we learned, connecting course skills to future work | Pulling together a complete workflow from question to interpretation |  |

**Note:** Topics and pacing may shift depending on class progress, university scheduling constraints, and course needs. Exact dates, deadlines, and assignment instructions will be posted on Canvas.
