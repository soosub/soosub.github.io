---
layout: default
title: Contact
---

# Contact

Feel free to reach out or follow me through any of the following:

<div class="contact-buttons">
  <a href="https://www.linkedin.com/in/jcpbus" class="contact-btn linkedin" target="_blank">
    <i class="fab fa-linkedin"></i> LinkedIn
  </a>
  <a href="https://scholar.google.co.uk/citations?user=7-n6MBQAAAAJ&hl=en" class="contact-btn scholar" target="_blank">
    <i class="fas fa-graduation-cap"></i> Google Scholar
  </a>
  <a href="mailto:joost.bus@hotmail.com" class="contact-btn email">
    <i class="fas fa-envelope"></i> Email
  </a>
</div>

<style>
.contact-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  margin-top: 20px;
}

.contact-btn {
  display: inline-flex;
  align-items: center;
  padding: 12px 20px;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 500;
  transition: all 0.3s ease;
  color: white;
}

.contact-btn i {
  margin-right: 8px;
  font-size: 1.1em;
}

.linkedin {
  background-color: #0077B5;
}

.linkedin:hover {
  background-color: #005582;
  transform: translateY(-2px);
}

.scholar {
  background-color: #4285F4;
}

.scholar:hover {
  background-color: #3367D6;
  transform: translateY(-2px);
}

.email {
  background-color: #EA4335;
}

.email:hover {
  background-color: #D33B2C;
  transform: translateY(-2px);
}

@media (max-width: 600px) {
  .contact-buttons {
    flex-direction: column;
  }
  
  .contact-btn {
    justify-content: center;
  }
}
</style>