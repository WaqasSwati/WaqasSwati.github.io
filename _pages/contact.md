---
layout: page
title: "Contact"
permalink: /contact/
---

<div style="display:flex; flex-wrap:wrap; gap:2rem; padding:1.5rem;">

  <!-- Left Column: Contact Info + Form -->
  <div style="flex:1; min-width:300px;">

  <h2 style="margin-top:0;">Get in Touch</h2>

  <p>
    You can reach me via email or through my social profiles below.<br>
    Or send me a direct message using the contact form.
  </p>

  <!-- Social Links with Icons -->
  <ul style="list-style:none; padding-left:0; line-height:2;">
    <li><i class="fas fa-envelope"></i> <a href="mailto:muhammad.waqas@unive.it">muhammad.waqas@unive.it</a></li>
    <li><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/muhammad-waqas-swati-18a574152/">LinkedIn</a></li>
    <li><i class="fab fa-x-twitter"></i> <a href="https://twitter.com/Waqas1swati">X (formerly Twitter)</a></li>
    <li><i class="fab fa-github"></i> <a href="https://github.com/waqasswati">GitHub</a></li>
    <li><i class="fab fa-researchgate"></i> <a href="https://www.researchgate.net/profile/Muhammad-Waqas-63?ev=hdr_xprf">ResearchGate</a></li>
    <li><i class="ai ai-google-scholar"></i> <a href="https://scholar.google.com/citations?user=rCTdcLQAAAAJ&hl=en">Google Scholar</a></li>
    <li><i class="ai ai-orcid"></i> <a href="https://orcid.org/0000-0001-6489-2819">ORCID</a></li>
  </ul>

  <!-- Contact Form -->
  <form action="https://formspree.io/f/xpwjvqkd" method="POST" style="margin-top:1rem;">
    <label>
      <small>Your Name (2–50 chars)</small><br>
      <input type="text" name="name" required minlength="2" maxlength="50" style="width:100%; padding:0.5rem;">
    </label><br><br>

    <label>
      <small>Your Email</small><br>
      <input type="email" name="_replyto" required maxlength="100" style="width:100%; padding:0.5rem;">
    </label><br><br>

    <label>
      <small>Message (10–1000 chars)</small><br>
      <textarea name="message" id="messageBox" rows="5" required minlength="10" maxlength="1000" style="width:100%; padding:0.5rem;"></textarea><br>
      <small id="charCount">1000 characters left</small>
    </label><br><br>

    <button type="submit" class="btn">Send</button>
  </form>

  <!-- Live Counter Script -->
  <script>
    const messageBox = document.getElementById('messageBox');
    const charCount = document.getElementById('charCount');
    const maxLength = messageBox.maxLength;

    messageBox.addEventListener('input', () => {
      const remaining = maxLength - messageBox.value.length;
      charCount.textContent = `${remaining} characters left`;
    });
  </script>

  </div>

  <!-- Right Column: Map -->
  <div style="flex:1; min-width:300px;">

  <h2 style="margin-top:0;">Location</h2>

  <p>Campus Scientifico – Università Ca’ Foscari, Via Torino 155, Mestre, Venice, Italy</p>

<iframe 
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2780.327311233326!2d12.2513866!3d45.4785946!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477eb4045095388f%3A0x346370066b6d8e20!2sUniversit%C3%A0%20Ca%27%20Foscari%20Informatica!5e0!3m2!1sen!2sit!4v1694258300000!5m2!1sen!2sit" 
  width="100%" height="400" style="border:0;" 
  allowfullscreen="" loading="lazy" 
  referrerpolicy="no-referrer-when-downgrade">
</iframe>



  </div>

</div>
