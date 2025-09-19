---
layout: page
title: "Contact"
permalink: /contact/
---

<style>
.contact-wrapper {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  padding: 1.5rem;
  background: #f9f9f9;
  border-radius: 8px;
}

.contact-column {
  flex: 1;
  min-width: 300px;
  background: #ffffff;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
}

.contact-column h2 {
  margin-top: 0;
  font-size: 1.4rem;
  color: #333;
  border-bottom: 2px solid #eee;
  padding-bottom: .5rem;
}

.contact-column ul {
  list-style: none;
  padding-left: 0;
  line-height: 2;
}

.contact-column ul li i {
  color: #0073aa;
  width: 20px;
  display: inline-block;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 8px;
}

.contact-form button {
  background: #0073aa;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 4px;
  cursor: pointer;
}
.contact-form button:hover {
  background: #005f88;
}
</style>

<div class="contact-wrapper">

  <!-- Left Column: Contact Info + Form -->
  <div class="contact-column">
    <h2>Get in Touch</h2>

    <p>You can reach me via email or through my social profiles below,  
    or send me a direct message using the contact form.</p>

    <!-- Social Links with Icons -->
    <ul>
      <li><i class="fas fa-envelope"></i> <a href="mailto:muhammad.waqas@unive.it">muhammad.waqas@unive.it</a></li>
      <li><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/muhammad-waqas-swati-18a574152/">LinkedIn</a></li>
      <li><i class="fab fa-x-twitter"></i> <a href="https://twitter.com/Waqas1swati">X (formerly Twitter)</a></li>
      <li><i class="fab fa-github"></i> <a href="https://github.com/waqasswati">GitHub</a></li>
      <li><i class="fab fa-researchgate"></i> <a href="https://www.researchgate.net/profile/Muhammad-Waqas-63?ev=hdr_xprf">ResearchGate</a></li>
      <li><i class="ai ai-google-scholar"></i> <a href="https://scholar.google.com/citations?user=rCTdcLQAAAAJ&hl=en">Google Scholar</a></li>
      <li><i class="ai ai-orcid"></i> <a href="https://orcid.org/0000-0001-6489-2819">ORCID</a></li>
    </ul>

    <!-- Contact Form -->
    <form action="https://formspree.io/f/xpwjvqkd" method="POST" class="contact-form" style="margin-top:1rem;">
      <label>
        Your Name:<br>
        <input type="text" name="name" required minlength="2" maxlength="50">
      </label><br><br>

      <label>
        Your Email:<br>
        <input type="email" name="_replyto" required maxlength="100">
      </label><br><br>

      <label>
        Message:<br>
        <textarea name="message" rows="5" required minlength="10" maxlength="1000"></textarea>
      </label><br><br>

      <button type="submit">Send</button>
    </form>
  </div>

  <!-- Right Column: Map -->
  <div class="contact-column">
    <h2>Location</h2>

    <p><strong>Campus Scientifico – Università Ca’ Foscari</strong><br>
    Via Torino 155, Mestre, Venice, Italy</p>

    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2780.032070839167!2d12.2535693!3d45.4923734!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477eb8a63d0b1c53%3A0x49ab4646671b2c!2sCampus%20Scientifico%20Via%20Torino%2C%20Ca%E2%80%99%20Foscari%20University!5e0!3m2!1sen!2sit!4v1699999999999"
      width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"
      referrerpolicy="no-referrer-when-downgrade">
    </iframe>
  </div>

</div>
