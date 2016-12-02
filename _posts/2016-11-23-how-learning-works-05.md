---
layout: post
title:  "How Learning Works 05"
date:   2016-11-23
categories: learning-and-teaching
comments: true
---


CHAPTER 5

---

What Kinds of Practice and Feedback Enhance Learning?
=

> **Principle**: Goal-directed practice coupled with targeted feedback are critical to learning.

The three players here are "Learning goals", "Practice", and "Feedback". As stated by the Principle above, they are closely interconnected. However, in the book, practice and feedback are discussed separately. 

I spent the last days (28/11-30/11) in an ELIXIR Train-the-Trainer (ELIXIR-TtT) course we ran in Slovenia and I will refer sometimes to this course in commenting chapter 5. 

I wrote 80% of this blog last weekend, in particular during my trip from Rome to Ljubljana (which included 5 hours train). On the 28th I started teaching the 4th ELIXIR-TtT course 2016 together with Pedro Fernandes, the ELIXIR-PT training coordinator. We had eight participants (a quite ideal number in my opinion) from different countries and very different background. I kept reading the last part of the book chapter late in the nights and nearly completed my comments to it in my (much quicker) trip back to Rome. In reading again what I had written before the ELIXIR-TtT and reflecting again on the entire chapter, I realised that the work on the book had profoundly affected my teaching in the previous days, thus modifying my thoughts and comments on chapter 5. Thus, I re-wrote most of this blog. 

The course lasted two days and it was made up of the following four sessions:

- Session 1: Learning principles and how they apply to training
- Session 2: Training techniques that can be used to enhance learner engagement and participation
- Session 3: Session, course, and materials design
- Session 4: Assessment and feedback in training

On day three (between Session 3 and 4), the TtT learners attended a Linux command line session (lasting half day) as observers and TAs (those who had experience on Linux), and learners (those with no prior experience on Linux). 
All wrote notes, comments and observations in the TtT course's Etherpad. After the Linux session, TtT instructors and learners met to complete Session 4 and provide and discuss feedback on the overall experience.

## Practice
**Focusing practice on a specific goal or criterion**

Goal-directed practice is crucial. "Goals provide students with focus for their learning, which leads to more time and energy going to that area of focus". It is good to know that instructors can help students by clearly articulating their goals. 
However, instructors sometimes are confused about their own learning goals. Before getting involved in ELIXIR Train the Trainer activities and SW/DC Instructor training training, I designed my lessons based on one or two general learning goals, but I didn't think a lot about goals specific to small tasks. My approach to teaching was much more based on intuition and experience.<br>
In order to learn how to focus practice on specific goals, I had (and still have) to work hard when I prepare practicals. Today, for each piece of practice, I write down an objective and then I build a task/excercise around it. The result is incredibly better, the time needed to achieve this is incredibly longer... I hope to become quicker and more effective in the future.

In the ELIXIR-TtT session on session preparation, learners struggled a lot in order to identify a single learning objective per task. This happened despite we discussed extensively the usage of learning objectives and outcomes in lesson, session, and course preparation. 
We also explained that concept maps may help better understand what are our goals and how many goals we are "loading" on a single task. We described concept maps and made examples on how to build and use them. 
Nevertheless, when learners gave their three-minute presentations and - even more - when they expanded from the three-minute presentations to detailed plans for entire sessions, they still tended to put together too many concepts.

The temptation of teaching "layers" of concepts instead of one clear skill at a time also affects instructors: I had a discussion with colleagues about teaching basic R to novices using or not the R studio interface and I'm not sure I convinced one of them that using R studio since the beginning might be overwhelming.

This made me think about the period I was teaching with no pedagogical clues. For example, when I prepared exercises for the Python parsing session, I only had one main learning goal, which was "students will be able to parse text files".
By gaining more experience, I realised that file parsing includes several different actions and each action should be connected to a different goal and practiced separately. For example: "reading a text file" has a learning goal per se (the student will be able to use the "open()" function to prepare a file for reading and use methods of file objects to read its content);  "write a for loop" has a different learning goal (the student will be able to write simple "for loops" and use them to run over the lines of a file"), etc. 
So, now, I have exercises for practicing file opening and reading, separate exercises to practice ```for``` loops, further exercises for ```if``` conditions, etc. Once learners are fluent in each of these tasks, I assign exercises on parsing, where these skills are combined together. 

***

**Note**: I've noticed that, in this book (and also in the SWC instructor training language), the folloeing terms: "Learning goals", "Learning outcomes" or "Learning objectives" are used interchangeably. 
However, in other contexts (e.g., ELIXIR-TtT), people pay a lot of attention to stress the difference between "Learning goals/objectives" and "Learning outcomes". In our courses we even provide two separate lists.

Here is an example of Learning Objectives and Learning Outcomes from our ELIXIR-TtT course:

```
Learning Objectives:

- To get acquainted with learning principles and how they apply to training
- To be able to select and utilise training techniques that can be used to enhance learner engagement and participation
- To learn about session, course, and materials design
- To learn how to use assessment and feedback in training

Learning outcomes:

- Learners can tell which learning principles a good trainer should have in mind
- Learners can describe at least three training techniques drawing on learning principles
- Learners can design a training session and a course
- Learners can develop assessment questionnaires
- Learners can tell what types of material are needed for each part of a training session

```

I quote from our TtT materials (adapted from [http://provost.rpi.edu/learning-assessment/learning-outcomes/objectives-vs-outcomes](http://provost.rpi.edu/learning-assessment/learning-outcomes/objectives-vs-outcomes)):

```
These two terms are often used interchangeably by the community.
Even worse, they are often abbreviated by the acronym (LO), thus introducing even more ambiguity. 
In our opinion there is no need. Objectives (aims) and Outcomes (results) may overlap, but are not genuinely the same. 
Here is an attempt to clarify this situation and remove the ambiguities:

Learning Objectives

- Objectives describe the goals and intentions of the instructor.
- Objectives, often termed the input in the course, state the purpose and goals of the course.
- Objectives focus on content and skills important within the classroom or program.
- Objectives may describe what the instructors will do.
- Objectives can often be numerous, specific, and detailed.

Learning Outcomes

- Student Learning Outcomes catalog the overarching "products" of the course and are the evidence that the goals or objectives were achieved.
- Learning Outcomes are statements that describe or list measurable and essential mastered content-knowledge—reflecting skills, competencies, and knowledge that students have achieved and can demonstrate upon successfully completing a course.
- Outcomes express higher-level thinking skills that integrate course content and activities and can be observed as a behavior, skill, or discrete useable knowledge upon completing the course.
- Outcomes are exactly what assessments are intended to show – specifically what the student will be able to do upon completing the course.
- An assessable outcome can be displayed or observed and evaluated against criteria.
- Outcomes are clear and measurable criteria for guiding the teaching, learning, and assessment process in the course.
```

Appendix D describes what Learing Objectives are and how we can use them. It also lists the four elements that make a learning objective clear and helpful.
In short, *clear* and *helpful* Learning Objectives should:

- be student-centered ("students should be able to....)
- break down the task and focus on specific cognitive processes 
- use action verbs (to focus on conrete actions and behaviours)
- be measurable (we should easily assess whether students have mastered a skill, e.g. solve a problem, state a theorem, etc.)

Based on these four elements, I would say that the Learning Objectives described in the book correspond to what we (in ELIXIR TtT) call "Learning Outcomes".

***

Another activity that may help goal-directed practice consists in developing performance criteria (rubrics) and share them with students. This is something I never did and - therefore - I don't currently teach in ELIXIR-TtT courses, but I would like to try to develop and use rubrics as soon as I have the chance. 

A thing that can be done only partially prior a course is to identify appropriate level of challenge for a given task. 
Indeed, this requires the ability to modify or even skip a task if we realise it is too advanced for a given group of students.
In order to understand whether a task is a too great challenge for a student or a group of students, I interact with the student/s as much as I can, and try to understand their limits and difficulties. Creating a relaxed class climate - where any kind of question is allowed - helps a lot.<br> 
By the way, I've found illuminating the definition of "optimal level of challenge for a students's learning" expressed by the Vygotsky's Zone of Proximal Development:

> *Optimal level of challenge for a students's learning* <br>
> A task that the student cannot perform successfully on his or her own but could perform succesfully with some help from another person or group.

Based on my experience, finding an appropriate level of challenge for students' practice is difficult but absolutely crucial in order to strengthen their self-confidence and, therefore, to help them gain motivation and remain motivated. 

Another key issue is *time on task*, i.e. the need for a sufficient *quantity* of practice.
One single opportunity to practice is generally not sufficient and both instructors and students underestimate the need for practice.
However, it is often difficult to increase the students' practice time. I think about two typical situations: 1) in a short training course, such as SW/DC ones; 2) in a high school semester course where only two hours a week are allocated for a given subject. What can we do in such cases? The research suggests that we use a given amount of practice time more efficiently by:

- focusing students' efforts on what they need to learn (rather than what they already know or may be more comfortable doing)
- setting their goals for performance at a reasonable and productive level of challenge.

My question here is: how can we apply these suggestions to a group of students with very different needs and levels of challenge? 
In short traning courses, we provide 

- very clear learning objectives and outcomes
- accurate description of the target audience
- description of the course
- a short questionnaire enquirying about the applicants' prior knowledge on course's topics

Moreover, in selecting candidates, despite we also accept applicants with different backgrounds, we try to form groups with similar needs, e.g. (in the Python course) either people with no previous knowledge of Linux or people with some or even good knowledge of Linux. We avoid putting together in the same course students with no experience at all and experts.

However, in some situations, teachers cannot choose their target audience (this happened in the SW/DC sessions in the RDA-CODATA school in Trieste, August 2016 and happens all the time in schools). This means that a teacher may have to face a situation in which the needs and the levels of challenge across the class may vary dramatically. 
What can be done in these situations (especially if, in addition, the time available is not much?)

### Strategies addressing the need for goal-directed practice.


- *Conduct a prior knowledge assessment to target an appropriate challenge level.* <br> This is what I do with questionnaires implemented in Google forms that I use as a guide in developing my teaching in order to make it as much specific as possible to a given audience (I described this method in the blog of Chapter 1). However, I think I should introduce some forms of performance assessment, since my pre-course questionnaires aim at understanding what students don't know or already know but do not allow me to understand what they *are able to do* or *how well* they master something, despite this knowledge is necessary to identify the appropriate challenge level. 
- *Be more explicit about your goals in your course materials*<br> This needs to be done in the course syllabus (general) as well as with each specific assignment (specific).
- *Use a rubric to specify and communicate performance criteria*<br> This is definitly something *I want* to start developing and use in my courses (though I'm not sure how to use rubrics in short training courses).
- *Build in multiple opportunity for practice*<br> Here, I learned something **very** useful I didn't know before: "Because learning accumulates gradually with practice, multiple assignments of shorter length or smaller scope tend to result in more learning than a single assignment of great length or large scope". That's simple to implement and good to know.
- *Build scaffolding into assignments*<br> I hadn't understood what scaffolding exactly was ("the process by which instructors give students instructional supports early in their learning, and then gradually remove these supports as students develop greater mastery and sophistication"). This is something I tend to spontaneously do, e.g., with my son. Glad to know it is supported by research findings.
- *Set expectation about practice*<br> I would translate this into: "Determine how much time is needed to accomplish a given task and tell it to students". The rule of thumb provided (in order to complete an assignment, students need three-to-four times as long as we instructors do need) is the one I usually adopt. 
- *Give example or models of target peformance*<br>or...."show examples of the exam they will have to pass". In some academic courses, I even provide students with a list of questions from which I will pick exam questions. The list contains about 150 questions covering the whole programme. So they know exactly what I expect from them and, in order to get good grades, they have to be able to answer questions on... the whole programme!
- *Show students what you do not want*<br> This is another very useful suggestion.
- *Refine your goals and performance criteria as the course progresses*<br> I think this is something most instructors "naturally" learn to do as they gain teaching expertise.


## Feedback

Goal-directed practice must be coupled to specific and timely ("soon and often") feedback. 

I've read the section on feedback immediately before the ELIXIR-TtT session on the same subject. It made me more aware of what we teach about feedback.<br>
In particular, I realised that, in short training courses, we use a lot of feedback questionnaires and other forms of more or less immediate feedback mostly *to collect students' feedback* with the main purposes of assessing students' prior knowledge and mental models (in order to adapt our teaching), assessing their progresses, measuring the impact of our training, and improving our performance. Therefore, in ELIXIR-TtT we teach how to use coloured sticky notes, Socrative and Google forms, how to write maximally informative multiple choice questionnaires, etc. 

Actually, as for the *feedback teachers should provide to students*, we don't teach much in our TtT courses. Even worse, I (and most of the instructors I've been teaching with) don't provide much targeted feedback during short, intensive courses. The only "justification" I have for this, is that providing targeted feedback and allowing enough practice to recognise and fix errors is not easy in short courses, though this is not the main reason why I don't do it sufficiently.

In school and university courses, teachers collect very little feedback from students, whereas they provide them with feedback in the form of grades. However, I've always thought grading's main purpose was assessing students' performance rather than supporting their learning. Therefore, also this type of feedback is eventually more useful to the teacher than to the student.

Based on my experience, in university courses, targeted feedback barely exists. Students attend classes, work a lot on their own and, at the end of the term, take exams (generally oral or written and oral). The result of an exam is a grade with no associated explanations (though students who want to see and discuss their written test can ask their teacher/professor). At this stage, any form of feedback is mostly pointless. 
In schools, the situation is different because both oral and written tests are more frequent. However, the most frequent feedback consists of grades with or without explanations which are normally provided one or more weeks after the test, i.e., when the class is working on new topics (and is likely to take a new test!).
Providing targeted feedback telling students where they are relative to the stated goals and what they need to improve, and *then* give students the chance to further practice their skills is something that does not belong to our school system. 

Tests generally are run at the end of the work of a class on a topic. 
It is clear that - if a student gets a very bad grade - he or she will generally tend to react, possibly working harder, but without learning much on where they are and what they need to improve.  

I believe there is *a lot* of room for improvement in both HOW, WHEN, and WHY provide feedback to students in many learning/teaching context, including short training courses, university courses and high schools. 

I mean to thoroughly discuss strategies addressing feedback both in the ELIXIR-TtT course materials and in my project on Instructor training in high schools.



{% if page.comments %}
<div id="disqus_thread"></div>
<script type="text/javascript">
       
    var disqus_shortname = 'allegravia';
    
    (function() {  
        
        var d = document, s = d.createElement('script');
        
        s.src = '//' + disqus_shortname + '.disqus.com/embed.js'; 
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>

{% endif %}
