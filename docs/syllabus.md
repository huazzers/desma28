
<!--jump to anchor tag adjusted to header height offset-->
<script>
// Get the header element
let header = document.querySelector('header');

// Get the height of the header
document.querySelectorAll('a[href^="#"]')
.forEach(function (anchor) {
    anchor.addEventListener('click', 
    function (event) {
        event.preventDefault();

        // Get the target element that 
        // the anchor link points to
        let target = document.querySelector(
            this.getAttribute('href')
        );
        
        let headerHeight = header.offsetHeight*2;
        
        let targetPosition = target
            .getBoundingClientRect().top - headerHeight;

        window.scrollTo({
            top: targetPosition + window.scrollY,
            behavior: 'smooth'
        });
    });
});

    window.onload = function(e){
        var cell = document.getElementById('component-site-name');
        var caseId = cell.innerHTML;
        cell.innerHTML = '';
        var link = document.createElement('a');
        link.href = '../';
        link.appendChild(document.createTextNode(caseId));
        cell.appendChild(link);
    }
</script>

# 📜 Syllabus

---

**LOCATION:** Broad Art Center 4220<br/>
**TIME:** Tuesdays and Thursdays, 2:00 p.m. - 5:00 p.m.

**INSTRUCTOR**<br/>
Office hours: Tuesdays 12:30 p.m. - 1:30 p.m. @ Game Lab (Broad 3252), by appointment only.<br/>
Email: huazzers@g.ucla.edu

**TEACHING ASSISTANT**<br/>
Office hours: Thursdays 1 p.m. - 2 p.m. @ 4th floor undergrad lounge, by appointment only.<br/>
Email: yjp324@g.ucla.edu



## Course Description
This course is an introduction to coding within the visual arts, with a focus on interactivity and how it relates to the following questions:

* how software has affected the visual arts?
* the potential of software within the visual arts?
* why a designer or artist would want (or need) to write software?

<br>

Writing code involves a different mode of thinking and making. We will consider:

* interactions with other people and the environment as the starting point for understanding interactions with code;
* the power relationships, inequities, and biases embedded within software and technology across different roles of race, gender, sexuality, disability, and class;
* strategic responses (as artists and designers) to the above structures within an increasingly software-driven world.

<br>

Each student will build a foundation in coding by applying these ideas and skills to a series of exercises and a final project. This foundation will serve as a core platform for future learning within the BA program and beyond. 

This course will focus on six sets of ideas:  

* Instructions and Statements  
* Variables and Data
* Conditionals and Response
* Repetition and Iteration
* Functions and Parameters
* Object-Orientation and Arrays

<br>

---

## Class Structure

We will spend most of the quarter working on short exercises for each topic (total of 6 exercises) that will eventually lead into a larger final project. 

<br>

The first half of the quarter will generally follow this rhythm below\*: 
> \**Note: Certain weeks will have some slight variation to this schedule! Always refer to our [schedule page](schedule.md) for the most up-to-date plan for that day.*

- Each week, we will introduce a new set of topics through Reading + Media assignments, workshops, and a simple exercise.
- **New Reading + Media assignments will be assigned on Tuesdays and are due at the start of Thursday classes the same week.**
- Thursday classes will review the assigned Reading + Media materials through lectures, workshops, and **a new exercise assignment that will be due the following Tuesday.**
- On Tuesdays when there's an exercise due, we will conduct **small group discussions** where students will share their work. 

<br>
The last two exercises (5 and 6) will have more time assigned to them than previous exercises, but will otherwise follow a structure similar to the above schedule. 

We will also have **TWO (2) mid-term reviews**, which will be conducted as individual meetings to discuss your previous exercises and general progress in the class thus far. 

The remainder of the quarter will be used for one-on-one meetings and open studio time to work on the final project. 

---

## Assignments and Grading

### Course Breakdown
> * Participation: 15%
> * Midterm Review 1 (Exercises 1~4): 40%
> * Midterm Review 2 (Exercises 5~6): 25%
> * Final Project: 20%
> * Optional Extra Credit: 2%

<br> 

**Optional Extra credit**: 
Write a response (500 word min.) about two interactive project (performance, website, game, installation), including the following:

* introduce the project (who made it, what it's about, its context / history / intention..., how one should interact with it)
* your personal experience + thoughts about the project (how *you* specifically interacted with it, what you thought or felt from the interaction, was it inspiring / could it be better / what worked and didn't work for you + explain why.)

This doesn't have to be about a project you like. Your response should justify your feelings, thoughts, and any arguments about the piece through analysis, observation, and/or concrete examples.

Email me your extra credit response by **Week 10 Friday (June 5), 11:59 p.m.**.

<br>

### Evaluation Criteria

All work will be evaluated based on the following considerations:

* Completion of the assigned prompt;
* The fundamental idea;
* Articulation of this idea through the "look and feel" of the work;
* The craft (e.g. details of images, motion, and interaction.)

Outstanding work will receive As, good work will receive Bs, sufficient work that does nothing more than meet requirements will receive Cs.
 
<br>

#### Reading + Media

Each project will be accompanied by a collection of readings, videos, and other media to look at. **You are expected to complete each item listed before the start of class the day it is due.** Doing so will make this class much easier and more enjoyable. If it is clear you are not doing this work, your grades will lower. 

<br>

#### Participation:

Your participation grade will be evaluated based on the following:

* **Attendance**
* **Contribution to class discussions, workshops, and critique**
* **Keeping up with the work and assignments**
* **Active communication with the instructor and TA in course-related matters, including project check-ins and attendance notices.**

<br>

#### Attendance Policy

**If you're more than 5 minutes late to class**, you will be marked as **late**.

**Two late marks will result in an unexcused absence.**

Unexcused absences will lower your grade. **More than three (>3) unexcused absences will result in an automatic fail**, and must be addressed on a case-by-case basis. 

**Any attendance-related disputes should be discussed with the TA within a week.**

**If you anticipate being late or absence**, inform the instructor AND the TA before class begins. It will also be your responsibility to catch up on materials and turn in assignments on time, or negotiate alternative plans with the instructor otherwise. 

<br>

#### Late Work
**On the day the project is due:**

* Projects should be **ready to present** prior to the beginning of class.
* Project files and documentation should be **submitted by 11:59PM** the same day.

**If you anticipate that you won’t be able to complete the work by the due date**, please contact the instructor *before* the due date so we can discuss options.

<br>

#### Appropriation, Fair Use, and Generated Content

**For all intents and purposes of this course, you should be writing your own code from scratch for all of your assignments in this class.** You are expected to be able to explain your workflow and intentions in your code through frequent commenting and during in-class discussions.

Although generative AI, template projects, and readymade assets can offer seemingly more "professional" results quickly, your purpose here to learn, and the best way to learn is to do it yourself or make things with others around you. Even if it means spending more time getting less done, or making mistakes along the way, I strongly advise against using any shortcuts while you're in this class.

<br>

**The bottom line:**

1. **No prompt-generating code from scratch -- we can tell.**
2. Referencing and borrowing code may be acceptable at a small scale on a case-by-case basis, as long as you're able to do the following:
    * mark all sections that were referenced / borrowed from elsewhere, and include the source in comments;
    * **AND** use your own comments to explain what each part of the code is trying to do;
    * **AND** justify the reason for referencing / borrowing this code, with prior consultation and approval from instructor and/or TA.
3. When in doubt, try the following instead: 
    * ask your peers -- I recommend setting up a group chat or community server where you can share resources and troubleshoot questions together. 
    * refer to your assigned readings, media, or other community-driven resources (e.g. Processing documentation and examples, Coding Train YouTube Channel, Stack exchange)
    * consult the instructor and/or TA through email, in class, or during office hours. 

**Any attempt to pass off uncited references and borrowed work (including prompt-generated results) as your own work will be considered a violation of academic integrity and will be evaluated accordingly. No credit will be given for plagiarized work.**

<br>

---

## Resources

### Coding References

- Processing.org, Reference documentation: [https://processing.org/reference](https://processing.org/reference)
- Ben Fry and Casey Reas, [Processing: A Programming Handbook for Visual Designers and Artists (Second Edition)](https://mitpress.mit.edu/9780262028288/processing/)
- Casey Reas, Chandler McWilliams, and LUST, [FORM + CODE in Design, Art, and Architecture](https://formandcode.com/)

<!--
### Sound Tools

- [freesound.org](https://freesound.org/) -- audio database that has search filters sorted by licenses. login required for downloading files. good source for adding sound effects and music to your projects. 
- [Audacity](https://www.audacityteam.org/) -- free software for recording and editing audio; the version without Muse Hub should suffice for your purposes.
- [Petaporon](https://pixwlk.itch.io/petaporon) -- browser-based minimalistic piano roll sequencer.
- [Lovely Composer](https://1oogames.itch.io/lovely-composer) -- retro chiptune music-making software for $9.

For more asset creation tools, check out this [exhaustive list of cheap and free tools compiled by Everest Pipkin](https://github.com/everestpipkin/tools-list#making-assets---images-models-sound-video).
-->
---

## Campus-wide resources and information

### Land Acknowledgement

> The University of California, Los Angeles occupies the ancestral, traditional, and contemporary Lands of the Tongva and Chumash peoples. Our ability to gather and learn here is the result of coercion, dispossession, and colonization. We are grateful for the land itself and the people that have stewarded it through generations. While a land acknowledgment is not enough, it is the first step in the work toward supporting decolonial and indigenous movements for sovereignty and self-determination. Read more about what land you’re occupying: [https://native-land.ca/](https://native-land.ca/) 

<!--UCLA is a land grant institution that continues to benefit from federal land theft and genocide of indigenous peoples. Statewide UC campuses are built upon Native American land, among which include sacred burial sites that have yet to be fully repatriated to their respective indigenous communities. Today, UCLA is one of the largest landlords in the region, and remains complicit in furthering the expatriation of indigenous peoples both locally and internationally. 

We're all living in the meta-game engine called the occupational forces of the US, and our ability to gather here is the result of the crimes against humanity outlined above. This acknowledgement should not serve to absolve one of settler guilt, but instead remind us of the deeply entrenched roots of colonialism, its mundane violence, and our subsequent participation in these systems as members of this campus.-->

Other resources on land repatriation: 

* [**UCLA Mapping Indigenous LA**](https://mila.ss.ucla.edu/) -- an online archive of a storymapping research project about indigenous Los Angeles peoples, histories, and geographies from past and present.
* [**California History (Winter 2023), Respecting the Ancestors: On Repatriating American Indian Remains**](https://online.ucpress.edu/ch/article/100/4/3/197683/Respecting-the-AncestorsOn-Repatriating-American) -- 2023 essay report on the history of repatriating indigenous peoples remains (mostly a lack thereof), including UC-specific case studies. 
* [**Decolonization is not a metaphor**](https://www.semanticscholar.org/paper/Decolonization-is-not-a-metaphor-Tuck-Yang/9e908da74710ecdcac794a847564939390008374) -- article on what is unsettling about decolonisation as a caution against the loose use of the term in advocacy and scholarship. 

### Know your Rights - ICE on Campus

This classroom is a place that honors the experiences of all students regardless of nationality, immigration status, or other factors. I understand that this quarter is likely to be a particularly challenging time for students navigating issues related to immigrant and international student rights. I pledge instructional flexibility including flexible deadlines, online documentation of course materials, and options for remote participation. You do not need to disclose your immigration or visa status to me to access these flexibilities. If you would like to request these accommodations, just let me know.
 
Students who have concerns about their legal rights as immigrants or international students may seek resources via the Undocumented Students Program, IDEAS, and the Dream Resource Center. You may also approach me for advice or help connecting to these resources. In particular, the Undocumented Student Program Legal Services provides legal advice and representation for undocumented UC students or UC students with undocumented family members. You can reach Gina Pech, the Supervising Attorney for the Legal Services Team at [gpech@saonet.ucla.edu](mailto:gpech@saonet.ucla.edu). If you are detained, or need urgent immigration related legal counsel, you may call Ms. Pech at 424-832-0977. 


### Commitment to Diversity & Safer Spaces
We understand the classroom as a space for practicing freedom; where one may challenge psychic, social, and cultural borders and create meaningful artistic expressions. To do so we must acknowledge and embrace the different identities and backgrounds we inhabit. This means that we will use preferred pronouns, respect self-identifications, and be mindful of special needs. Disagreement is encouraged and supported, however our differences affect our conceptualization and experience of reality, and it is extremely important to remember that certain gender, race, sex, and class identities are more privileged while others are undermined and marginalized. Consequently, this makes some people feel more protected or vulnerable during debates and discussions. A collaborative effort between the students, TA, and instructor is needed to create a supportive learning environment. While everyone should feel free to experiment creatively and conceptually, if a class member points out that something you have said or shared with the group is offensive, avoid being defensive; instead approach the discussion as a valuable opportunity for us to grow and learn from one another. Alternatively, if you feel that something said in discussion or included in a piece of work is harmful, you are encouraged to speak with the instructor or TA. 

*(Statement adopted from voidLab at [https://github.com/voidlab/diversity-statement](https://github.com/voidlab/diversity-statement))*

### COVID-19
It is important that everyone stay safe and avoid coming to class if you have any concerns about your health status.

If you find that external struggles and/or COVID related challenges are affecting your ability to attend class, please reach out to us. We want you to be successful in the class, but we care about your well-being more than anything else. Open communication with us is most important in this regard, please let us know if you're sick and/or require additional accommodations.

Students must adhere to the current campus directives related to COVID-19 mitigation, and refusal to do so may result in the student being asked to leave the classroom or referred to the Dean of Students. For more information about COVID-19 requirements on campus, please visit: [https://covid-19.ucla.edu/information-for-students/](https://covid-19.ucla.edu/information-for-students/). 

### Center for Accessible Education (CAE)
UCLA strives to make all learning experiences as accessible as possible. If you anticipate or experience academic barriers based on a disability, please let the instructor know as soon as possible. 

Students needing academic accommodations based on a disability should contact the Center for Accessible Education (CAE) at (310) 825-1501 or in person at Murphy Hall A255. When possible, students should contact the CAE within the first two weeks of the term as reasonable notice is needed to coordinate accommodations. For more information visit [www.cae.ucla.edu](https://www.cae.ucla.edu/). 

After registration with CAE, make arrangements with the instructor to discuss how to implement these accommodations.

### Academic Integrity and Information on Student Conduct
UCLA is a community of scholars. In this community, all members including faculty, staff and students alike are responsible for maintaining standards of academic honesty. As a student and member of the University community, you are here to get an education and are, therefore, expected to demonstrate integrity in your academic endeavors. You are evaluated on your own merits. Cheating, plagiarism, collaborative work, multiple submissions without the permission of the professor, or other kinds of academic dishonesty are considered unacceptable behavior and will result in formal disciplinary proceedings usually resulting in suspension or dismissal. As specified in the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/studentconductcode), violations or attempted violations of academic dishonesty include, but are not limited to, cheating, fabrication, plagiarism, multiple submissions or facilitating academic dishonesty. When a student is suspected to have engaged in academic dishonesty, Academic Senate regulations require that the instructor report the allegation to the office of the Dean of Students. For more information, see the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/studentconductcode).

### TITLE IX
UCLA prohibits gender discrimination, including sexual harassment, domestic and dating violence, sexual assault, and stalking. If you have experienced sexual harassment or sexual violence, there are a variety of resources to assist you.

### Confidential Resources
You can receive confidential support and advocacy at the CARE Advocacy Office for Sexual and Gender-Based Violence, 1st Floor Wooden Center West, [CAREadvocate@careprogram.ucla.edu](mailto:CAREadvocate@careprogram.ucla.edu), (310) 206-2465. Counseling and Psychological Services (CAPS) also provides confidential counseling to all students and can be reached 24/7 at (310) 825-0768.

### Non-Confidential Resources
You can also report sexual violence or sexual harassment directly to the University’s Title IX Coordinator, 2241 Murphy Hall, [titleix@conet.ucla.edu](matilto:titleix@conet.ucla.edu), (310) 206-3417. Reports to law enforcement can be made to UCPD at (310) 825-1491. These offices may be required to pursue an official investigation.

Faculty and TAs are required under the UC Policy on Sexual Violence and Sexual Harassment to inform the Title IX Coordinator—A NON-CONFIDENTIAL RESOURCE—should they become aware that you or any other student has experienced sexual violence or sexual harassment.

### Psychological Health, Well-Being and Resilience
UCLA is renowned for academic excellence, and yet we know that many students feel overwhelmed at times by demands to succeed academically, socially and personally.  Our campus community is committed to helping all students thrive, learn to cope with stress, and build resilience. Remember, self-care is a skill that is critical to your long-term success.  Here are some of the many resources available at UCLA to support you:

* **Counseling and Psychological Services (CAPS)**: [https://www.counseling.ucla.edu/](https://www.counseling.ucla.edu/) Provides counseling and other psychological/mental health services to students. Walk-in hours are Monday-Thursday 8am-4:30pm and Friday 9am-4:30pm in John Wooden Center West. Crisis counseling is also available 24 hours/day at (310) 825-0768.
* **Ashe Student Health and Wellness Center**: [http://www.studenthealth.ucla.edu](http://www.studenthealth.ucla.edu) Provides high quality and accessible ambulatory healthcare and education by caring professionals to support the academic success and personal development of all UCLA students.
* **Healthy Campus Initiative (HCI)**: [https://healthy.ucla.edu](https://healthy.ucla.edu) Provides links to a wide variety of resources for enhancing physical and psychological well-being, positive social interactions, healthy sleep, healthy eating, healthy physical activity and more.
* **Campus and Student Resilience**: [https://www.resilience.ucla.edu/](https://www.resilience.ucla.edu/) Provides programs to promote resilience and trains students to help support their peers.
* **UCLA Recreation**: [https://www.recreation.ucla.edu/](https://www.recreation.ucla.edu/) Offers a broad array of services and programs including fitness, yoga, dance, martial arts, meditation, sports, and much more.
* **Equity, Diversity and Inclusion**: [https://equity.ucla.edu/](https://equity.ucla.edu/) Committed to providing an equal learning, working and living environment at UCLA and supports a range of programs to promote these goals campus-wide.
* **UCLA GRIT Coaching Program**: [https://www.grit.ucla.edu/](https://www.grit.ucla.edu/) GRIT stands for Guidance, Resilience, Integrity and Transformation. In this program, UCLA students receive individualized support from trained peer coaches to manage stress, foster positive social connections, set goals, and navigate campus resources.

### Resources for Students Dealing with Financial Stress 

* **Economic Crisis Response**: [https://www.studentincrisis.ucla.edu/Economic-Crisis-Response](https://www.studentincrisis.ucla.edu/Economic-Crisis-Response) provides support and guidance to students who have self-identified, or are identified by UCLA faculty or staff, as experiencing a financial crisis that impacts their academic success at UCLA.
* **Bruin Shelter**: [http://www.bruinshelter.org/](http://www.bruinshelter.org/) provides a safe, supportive environment for fellow college students experiencing homelessness by fostering a collaborative effort between universities, community-based organizations, and service providers.
* **The CPO Food Closet**: [http://www.cpo.ucla.edu/cpo/foodcloset/](http://www.cpo.ucla.edu/cpo/foodcloset/) provides free food for any UCLA student who may be experiencing hunger and/or struggling to attain food due to financial hardships.