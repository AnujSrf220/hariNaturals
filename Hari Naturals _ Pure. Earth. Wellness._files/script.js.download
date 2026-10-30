/* =========================================================
   HARI NATURALS - JAVASCRIPT
   Static website only.
   The enquiry form currently does not send data anywhere.
   ========================================================= */

document.addEventListener("DOMContentLoaded", () => {
  // Automatically keep the footer copyright year current.
  const year = document.getElementById("year");

  if (year) {
    year.textContent = new Date().getFullYear();
  }

  // Demo form behaviour.
  // Later this can be connected to WhatsApp, email/Formspree,
  // Google Forms, PHP/backend, Node.js/API, etc.
  const enquiryForm = document.getElementById("enquiryForm");
  const formStatus = document.getElementById("formStatus");

  if (enquiryForm && formStatus) {
    enquiryForm.addEventListener("submit", (event) => {
      // Prevent the browser from refreshing/navigating away.
      event.preventDefault();

      // Static/demo confirmation for now.
      formStatus.textContent =
        "Thank you! Your enquiry form is ready. Submission will be connected later.";
    });
  }
});