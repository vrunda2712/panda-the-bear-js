1. Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

--->  profile = document.querySelector('.profile-image');

      profile.src = "images/self-portrait-snowbg.jpg";


2. Select the heading that says "Panda the Bear" and change it to your own name.

--->  heading = document.querySelector('h1.highlight');

      heading.innerText = 'Vrunda Patel';


3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)  

--->  employment = document.querySelector('#employment h3.info-title');

      employment.innerText = 'Working';


4. Change the colour of the body.

--->  bodycolor = document.querySelector('body');

      bodycolor.style.backgroundColor = '#403c3c';


5. Change the colour used by the highlight class.

--->  highlightcolor = document.querySelectorAll('.highlight');

      highlightcolor.forEach(function(item) { item.style.color = 'white'});


6. Change the font family of the h1 to 'monospace'.

--->  heading = document.querySelectorAll('h1');

      heading.forEach(function(item) { item.style.fontFamily = 'monospace' });


7. Find a way to select the round icons in the sidebar and then change their colour.

--->  icon = document.querySelectorAll('a.action-icon-bg');

      icon.forEach(function(item) { item.style.backgroundColor = '#0b3e1b' });


8. Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".

--->  namePlaceholder = document.querySelector('input#name.contact-info');

      namePlaceholder.placeholder = 'Identify yourself';


9. Change the placeholder attribute of the message field to "state your business".

--->  messagePlaceholder = document.querySelector('textarea#message');

      messagePlaceholder.placeholder = 'State your business';


10. Give the name field a "value" attribute of "your nemesis".

--->  nameField = document.querySelector('input#name.contact-info');

      nameField.value = 'Your nemesis';


11. Change the value attribute of the email field to "koalathebear@gmail.com".

--->  emailField = document.querySelector('input#email.contact-info');

      emailField.value = 'koalathebear@gmail.com';


12. Change the value of the submit button on the contact form to "En garde!".

--->  submitButton = document.querySelector('input#submit');

      submitButton.value = 'En garde!';


13. We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).

--->  submitButton = document.querySelector('input#submit');

      submitButton.disabled = true ;


14. We should help Panda protect their privacy by clearing their personal details from the sidebar. You can use reset() to do this.

--->  pandaBio = document.querySelector('ul.bio-info');

      <!-- pandaBio.reset(); -->
      pandaBio.remove();
