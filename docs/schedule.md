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


    table tr:nth-child(1)>td:nth-child(2), table tr:nth-child(10)>td:nth-child(3){
        background-color:gray;
    }

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

|     |TUESDAY   | THURSDAY   |
| --- | --------- | ----------------- |
| W0  |   | **09/24**<br><p>Introductions + Syllabus Overview</p><p>Workshop I: Instruction Drawing</p><p>Lecture: Thinking in Code</p><p>Workshop II: [Intro to Processing](https://docs.google.com/document/d/1m4rn2RDK5RQsRuFXuc3frBn54Wh9xNg_-ku4pOyP6H0/edit?tab=t.j1lb40yw7ml8)</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>[Reading + Media 1](https://docs.google.com/document/d/1CE28O66Wjmiwe2nOXSMyOfWMV45vfsEUyYtuHlsVDEM/edit?tab=t.p4ope6rmzm68) (Due: W1 Tue, 09/29)</li><li>Exercise: [Instruction + Object Research](https://docs.google.com/document/d/1CE28O66Wjmiwe2nOXSMyOfWMV45vfsEUyYtuHlsVDEM/edit?tab=t.7ntmynw0hkux) (Due: W1 Tue, 09/29)</li></ul></div>    |
| W1  | **09/29**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 1</li><li>Exercise: Instruction + Object Research</li></ul></div><p>Workshop: Transforming Shapes, Blending Colors</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Assignment 1 (Due: W1 Thu, 10/01)</li></ul></div> | **10/01**<br><div class="due"><p>📌 DUE:</p><ul><li>Assignment 1</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 2 (Due: W2 Tue, 10/06)</li><li>Exercise: Data Collection + Sketch (Due: W2 Tue, 10/06)</li></ul></div> |
| W2  | **10/06**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 2</li><li>Exercise: Data Collection + Sketch</li></ul></div><p>Workshop: Variables and Data</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Assignment 2 (Due: W2 Thu, 10/08)</li></ul></div>  | **10/08**<br><div class="due"><p>📌 DUE:</p><ul><li>Assignment 2</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 3 (Due: W3 Tue, 10/13)</li><li>Exercise: Drawing Instructions (Due: W3 Tue, 10/13)</li></ul></div>   |
| W3  | **10/13**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 3</li><li>Exercise: Drawing Instructions</li></ul></div><p>Workshop: Conditionals + Input/Response</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Assignment 3 (Due: W3 Thu, 10/15)</li></ul></div>  | **10/15**<br><div class="due"><p>📌 DUE:</p><ul><li>Assignment 3</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 4 (Due: W4 Tue, 10/20)</li><li>Exercise: Community Code Research (Due: W4 Tue, 10/20)</li></ul></div> |
| W4  | **10/20**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 4</li><li>Exercise: Community Code Research</li></ul></div><p>Workshop: Loops + Iterations</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Assignment 4  (Due: W5 Tue, 10/27)</li></ul></div>   | **10/22**<br><div class="due"><p>📌 DUE:</p><ul><li>Any revised submissions for Assignments 1 ~ 3</li></ul></div><p>Mid Term Review 1:</p><blockquote><p>Individual meetings to review Assignments 1~3; and check in about Assignment 4 works-in-progress (also an opportunity to do test prints!)</p> |
| W5  | **10/27**<br><div class="due"><p>📌 DUE:</p><ul><li>Assignment 4</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 5 (Part I) (Due: W5 Thu, 10/29)</li></ul></div>  | **10/29**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 5 (Part I)</li></ul></div><p>Workshop: Text + Image + Graphics</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 5 (Part II) (Due: W6 Tue, 11/03)</li><li>Exercise: Non-linear Outline (Due: W6 Tue, 11/03)</li><li>Assignment 5 (Due: W6 Thu, 11/05)</li></ul></div>  |
| W6  | **11/03**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 5 (Part II)</li><li>Exercise: Non-linear Outline</li></ul></div><p>Workshop: Functions + Parameters</p> | **11/05**<br><div class="due"><p>📌 DUE:</p><ul><li>Assignment 5</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 6 (Part I) (Due: W7 Tue, 11/10)</li></ul></div> |
| W7  | **11/10**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 6 (Part I)</li></ul></div><p>Workshop: Objects + Motion</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Reading + Media 6 (Part II) (Due: W7 Thu, 11/12)</li><li>Exercise: Object Outline (Due: W7 Thu, 11/12)</li><li>Assignment 6 (Due: W8 Tue, 11/17)</li></ul></div> | **11/12**<br><div class="due"><p>📌 DUE:</p><ul><li>Reading + Media 6 (Part II)</li><li>Exercise: Object Outline</li></ul></div><p>Workshop: Arrays</p>  |
| W8  | **11/17**<br><div class="due"><p>📌 DUE:</p><ul><li>Assignment 6</li></ul></div><p>Small Group Discussions</p><div class="assign"><p>▶️ ASSIGN:</p><ul><li>Final Project<br>(Proposal due: Thursday 11/19)</li>  | **11/19**<br><div class="due"><p>📌 DUE: </p><ul><li>Final Project Proposal</li><li>Any revised submissions for Assignments 4 ~ 6</li></ul></div><p>Mid Term Review 2:</p><blockquote><p>Individual meetings to review Assignments 4~6 and Final Project Proposal</p></blockquote>  |
| W9  | **11/24**<br><p>Studio Time: <br>One-on-one meetings + Open work time</p>  | **11/26**  <br><br>No class (Thanksgiving Holiday).  |
| W10 | **12/01**<br><p>Studio Time: <br>One-on-one meetings + Open work time</p> | **12/03**<br><div class="due"><p>📌 DUE:</p><ul><li>Final Project</li></ul></div><p>Final Project Presentations</p> |