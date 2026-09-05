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

# 🏠 Interactivity Spring 2026

Broad 4220<br/>
Tuesdays and Thursdays, 2 p.m. - 5 p.m.

**INSTRUCTOR**<br/>
Office hours: Tuesdays 12:30 p.m. - 1:30 p.m. @ UCLA Game Lab (Broad 3252), by appointment only.<br/>
Email: huazzers@g.ucla.edu

**TEACHING ASSISTANT**<br/>
Office hours: Thursdays 1 p.m. - 2 p.m. @ 4th floor undergrad lounge, by appointment only.<br/>
Email: yjp324@g.ucla.edu

---