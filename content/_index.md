---
layout: "profile"
---

<marquee behavior="alternate" direction="left" scrollamount="5" style="border: 1px solid #bb86fc; border-radius: 10px; padding: 10px; background: #1a1a1a;">
    🚀 <b>Selenium</b> &nbsp;&nbsp; | &nbsp;&nbsp; 🛠️ <b>Python</b> &nbsp;&nbsp; | &nbsp;&nbsp; 🐞 <b>Manual Testing</b> &nbsp;&nbsp; | &nbsp;&nbsp; 📊 <b>SQL</b> &nbsp;&nbsp; | &nbsp;&nbsp; 🌐 <b>Web Development</b> &nbsp;&nbsp; | &nbsp;&nbsp; 📝 <b>TestNG</b>
</marquee>

<h2 id="typing-text" style="color: #bb86fc;"></h2>

<script>
    const text = "QA Automation Engineer | Software Tester | Tech Enthusiast";
    let i = 0;
    function typeWriter() {
        if (i < text.length) {
            document.getElementById("typing-text").innerHTML += text.charAt(i);
            i++;
            setTimeout(typeWriter, 100);
        }
    }
    typeWriter();
</script>