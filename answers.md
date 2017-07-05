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
