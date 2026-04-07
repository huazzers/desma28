# 📅 Schedule

<!--removes sidebar outline-->
<style>
    @media (min-width: 768px) {
        .col-md-9 {
            width: 100% !important;
        }
        
        .d-md-block {
        display: none !important;
        }
        
        #component-content{
            margin-left:0 !important;
        }
    }

    blockquote{
        margin: 0 0.5em;
    }

    table th:first-of-type {
        width: 10%;
    }
    table th:nth-of-type(2) {
        width: 45%;
    }
    table th:nth-of-type(3) {
        width: 45%;
    }

/*
    table tr:nth-child(1)>td:nth-child(2), table tr:nth-child(8)>td:nth-child(2), table tr:nth-child(10)>td:nth-child(3){
        background-color:gray;
    }*/

</style>

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

|     | Tuesday       | Thursday      |
| --- | ------------- | ------------- |
| W1  | **03/31**</br><p>Introductions + Syllabus Overview</p><p>Workshop I: Instruction Drawing</p><p>Lecture: Thinking in Code</p><p>Workshop II: [Intro to Processing](https://docs.google.com/document/d/1zyBdAmaZ4UuZhEBmgCxaAuBFuCJw5aHM6tXkqNaO1Ow/edit?tab=t.j1lb40yw7ml8)</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>[Reading + Media 1](https://docs.google.com/document/d/1h-4Y8c9U50v0dFKp67S9M0lpJyYsVp5zOFEex2xJTKM/edit?tab=t.p4ope6rmzm68) (Due: W1 Thu, 04/02)</li><li>[Exercise 1 (Part I)](https://docs.google.com/document/d/1h-4Y8c9U50v0dFKp67S9M0lpJyYsVp5zOFEex2xJTKM/edit?tab=t.7ntmynw0hkux) (Due: W1 Thu, 04/02)</li></ul></div> | **04/02**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 1</li><li>Exercise 1 (Part I)</li></ul></div><p>🍿: [Samia Halaby and The Kinetic Painting Group](https://www.tate.org.uk/art/artists/samia-halaby-32584/samia-halaby-im-painting-in-the-technology-of-my-time)</p><p>Workshop: [Transforming Shapes, Blending Colors](https://docs.google.com/document/d/1zyBdAmaZ4UuZhEBmgCxaAuBFuCJw5aHM6tXkqNaO1Ow/edit?tab=t.g67qyuplc5l)</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>[Exercise 1 (Part II)](https://docs.google.com/document/d/1h-4Y8c9U50v0dFKp67S9M0lpJyYsVp5zOFEex2xJTKM/edit?tab=t.euq590gwtmom) (Due: W2 Tue, 04/07)</li></ul></div> |
| W2  | **04/07**</br><div class="due"><p>📌 DUE: </p><ul><li>Exercise 1 (Part II)</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>[Reading + Media 2](https://docs.google.com/document/d/1h-4Y8c9U50v0dFKp67S9M0lpJyYsVp5zOFEex2xJTKM/edit?tab=t.j3j3j99wv3ox) (Due: W2 Thu, 04/09)</li></ul></div> | **04/09**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 2</li></ul></div><p>Workshop: Variables</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Exercise 2 (Due: W2 Tue, 04/14)</li></ul></div>|
| W3  | **04/14**</br><div class="due"><p>📌 DUE: </p><ul><li>Exercise 2</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 3 (Due: W3 Thu, 04/16)</li></ul></div> | **04/16**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 3</li></ul></div><p>Workshop: Conditionals + Input/Response</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Exercise 3 (Due: W4 Tue, 04/21)</li></ul></div>|
| W4  | **04/21**</br><div class="due"><p>📌 DUE: </p><ul><li>Exercise 3</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 4 (Due: W4 Thu, 04/23)</li></ul></div> | **04/23**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 4</li></ul></div><p>Workshop: Loops + Iterations</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Exercise 4 (Due: W5 Tue, 04/28)</li></ul></div>|
| W5  | **04/28**</br><div class="due"><p>📌 DUE: </p><ul><li>Exercise 4</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 5 (Part I) (Due: W5 Thu, 04/30)</li></ul></div> | **04/30**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 5 (Part I)</li></ul></div><p>Workshop: Text + Image + Graphics</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Exercise 5 (Due: W7 Tue, 05/12)</li></ul></div>|
| W6  | **05/05**</br><p>Midterm Review 1</p><blockquote><p>Individual Meetings about Exercises 1 ~ 4</p></blockquote><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 5 (Part II) (Due: W6 Thu, 05/07)</li></ul></div> | **05/07**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 5 (Part II)</li></ul></div><p>Workshop: Functions + Parameters</p>|
| W7  | **05/12**</br><div class="due"><p>📌 DUE: </p><ul><li>Exercise 5</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 6 (Part I) (Due: W7 Thu, 05/14)</li></ul></div> | **05/14**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 6 (Part I)</li></ul></div><p>Workshop: Objects + Arrays</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media (Part II) (Due: W8 Tue 05/19)</li><li>Exercise 6 (Due: W8 Thu, 05/21)</li></ul></div>|
| W8  | **05/19**</br><div class="due"><p>📌 DUE: </p><ul><li>Reading + Media 6 (Part II)</li></ul></div><p>Workshop: Animating Objects</p> | **05/21**</br><div class="due"><p>📌 DUE: </p><ul><li>Exercise 6</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Final Project (Proposal Due: W9 Tue, 05/26)</li></ul></div>|
| W9  | **05/26**</br><div class="due"><p>📌 DUE: </p><ul><li>Final Project Proposal</li></ul></div><p>Midterm Review 2</p><blockquote><p>Individual Meetings about Exercises 5 ~ 6 and Final Project Proposal</p></blockquote> | **05/28**</br><p>Studio Time: One-on-one meetings + Open Work Time</p>|
| W10  | **06/02**</br><p>Studio Time: One-on-one meetings + Open Work Time</p> | **06/04**</br><div class="due"><p>📌 DUE: </p><ul><li>Final Project</li></ul></div><p>Final Project Crit</p> |