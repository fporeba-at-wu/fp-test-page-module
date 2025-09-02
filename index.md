---
name: "Florian Poreba"
prefix:
suffix: MSc
position: Research Assistant
tel: +43-1-31336-5017
email: florian.poreba@wu.ac.at
office: D2.2.044
hours: By appointment
unit: Faculty
---

# Hello Graphs 2!
This is my Page!  

You can embedd html into markdown (see below):
<div style="background:white">
Hello
<ul>
<li>Hello 1</li>
<img src="https://media.istockphoto.com/id/816752606/de/foto/tv-testkarte-oder-testmuster-generisch.jpg?s=612x612&w=0&k=20&c=Q4CCpLypL8bfmmlANGkfkpfnYrOSQV6zcLtmIbupVwQ=" alt="test image" width="500" height="600">
</ul>
<div id="demo">Hello Not</div>
</div>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>
<script type="text/javascript">
    async function load_home()
    {
        var content = document.getElementById("demo");
        content.innerHTML = await (await fetch('https://raw.githubusercontent.com/fporeba-at-wu/fp-test-page/refs/heads/main/fp-page.html')).text();
    }
    load_home()
</script>
