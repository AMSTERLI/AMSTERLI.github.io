---
permalink: /
title: "Bingle Li"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<!-- ======================================================================= -->
<!-- =                              Contents                               = -->
<!-- ======================================================================= -->

<p align="justify">
    Hi, I'm Bingle Li. Welcome to my personal profile website. This site is built on the academic Jekyll template and will be used to share my background, projects, and updates.
</p>

<p align="justify">
    You can find more about me in the sections above, including my CV, portfolio, publications, talks, and blog posts as I continue to update this site.
</p>

---

Education & Experience
======

+ Based in Shanghai.
+ Email: <a href="mailto:libingle9@gmail.com">libingle9@gmail.com</a>
+ GitHub: <a href="https://github.com/AMSTERLI">AMSTERLI</a>


<!-- ======================================================================= -->
<!-- =                                Utils                                = -->
<!-- ======================================================================= -->

<script>
function toggle(prefix, type) {
    function setDisplay(id, display) {
        var x = document.getElementById(id);
        x.style.display = display;
    }

    function toggleDisplay(id) {
        var x = document.getElementById(id);
        if (x.style.display === "none") {
            x.style.display = "inline";
        } else {
            x.style.display = "none";
        }
    }

    toggleDisplay(prefix + " " + type);
    toggleDisplay(prefix + " " + type + " open");
    toggleDisplay(prefix + " " + type + " close");

    const types = ["Abstract", "Bib"];
    types.forEach(function(t) {
        if (t !== type) {
        setDisplay(prefix + " " + t, 'none');
        setDisplay(prefix + " " + t + " open", 'inline');
        setDisplay(prefix + " " + t + " close", 'none');
        }
    });
}
</script>
