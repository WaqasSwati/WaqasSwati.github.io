---
layout: page
title: "Contact"
permalink: /contact/
---

<div style="display:flex; flex-wrap:wrap; gap:2rem; margin:2rem;">

  <!-- Left Column: Contact Info + Form -->
  <div style="flex:1; min-width:300px;">

  <h2 style="margin-top:0;">Get in Touch</h2>

  <p>You can reach me via email or through my social profiles below,  
  or send me a direct message using the contact form.</p>

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

  <!-- Contact Form Card -->
  <div style="
    background:#f9f9f9;
    padding:1.5rem;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.05);
    margin-top:1.5rem;
  ">

  <form action="https://formspree.io/f/xpwjvqkd" method="POST">

    <label>
      Your Name <span style="color:red">*</span><br>
      <input type="text" name="name" required minlength="2" maxlength="50"
        style="width:100%;padding:0.6rem;border:1px solid #ccc;border-radius:6px;font-size:1rem;"
        onfocus="this.style.borderColor='#0066cc';" onblur="this.style.borderColor='#ccc';">
    </label>
    <div style="font-size:0.85rem; color:#555;">Please enter your full name (2–50 characters)</div>
    <br>

    <label>
      Your Email <span style="color:red">*</span><br>
      <input type="email" name="_replyto" required maxlength="100"
        style="width:100%;padding:0.6rem;border:1px solid #ccc;border-radius:6px;font-size:1rem;"
        onfocus="this.style.borderColor='#0066cc';" onblur="this.style.borderColor='#ccc';">
    </label>
    <div style="font-size:0.85rem; color:#555;">We will use this to reply to you</div>
    <br>

    <label>
      Message <span style="color:red">*</span> (max 1000 chars):<br>
      <textarea name="message" id="message" rows="5" required minlength="10" maxlength="1000"
        style="width:100%;padding:0.6rem;border:1px solid #ccc;border-radius:6px;font-size:1rem;"
        onfocus="this.style.borderColor='#0066cc';" onblur="this.style.borderColor='#ccc';"></textarea>
    </label>
    <div style="font-size:0.85rem; color:#555;">
      Tell me more (10–1000 characters). Characters left: <span id="charCount">1000</span>
    </div>
    <br>

    <button type="submit"
      style="background:#0066cc;color:white;padding:0.6rem 1.2rem;border:none;border-radius:6px;cursor:pointer;font-size:1rem;">
      Send Message
    </button>
    <div style="font-size:0.8rem; color:#555; margin-top:0.5rem;">
      <span style="color:red">*</span> Required fields
    </div>

  </form>
  </div>

  </div>

  <!-- Right Column: Map -->
  <div style="flex:1; min-width:300px;">

  <h2 style="margin-top:0;">Location</h2>

  <p>Università Ca’ Foscari Informatica, Via Torino, Mestre, Venice, Italy</p>

  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2780.327311233326!2d12.2513866!3d45.4785946!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477eb4045095388f%3A0x346370066b6d8e20!2sUniversit%C3%A0%20Ca%27%20Foscari%20Informatica!5e0!3m2!1sen!2sit!4v1694258300000!5m2!1sen!2sit" 
    width="100%" height="400" style="border:0;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,0.05);" 
    allowfullscreen="" loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>

  </div>
</div>

<script>
  // Live character counter for message box
  const textarea = document.getElementById('message');
  const charCount = document.getElementById('charCount');
  textarea.addEventListener('input', () => {
    charCount.textContent = 1000 - textarea.value.length;
  });
</script>
