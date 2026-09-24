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
</style>

<script>

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

# 🏠 Interactivity Fall 2026

Broad 4220<br/>
Tuesdays and Thursdays, 9 a.m. - 12 p.m.

**INSTRUCTOR**<br/>
Office hours: Tuesdays, 12:30 p.m. - 1:30 p.m. @ Game Lab (By appointment only)<br/>
Email: huazzers@g.ucla.edu

**TEACHING ASSISTANT**<br/>
Office hours: Thursdays, 2 p.m. - 3 p.m. @ Game Lab (By appointment only)<br/>
Email: nhanphan@g.ucla.edu

---