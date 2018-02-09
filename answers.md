1. Change the profile image source
  - img = document.querySelector('.profile-image')
  - img.src = "https://placebear.com/400/400"
1. Change the sky image source
  - img = document.querySelector('#left-image img')
  - img.src = "https://seatgeek.com/tba/wp-content/uploads/2014/08/guitar-face_trey-e1408738818535.jpg"
1. Change "Panda The Bear" heading to my name
  - heading = document.querySelector('h1.highlight');
  - heading.textContent = "Jeff Rothwell"
1. Change the "Education" heading
  - employment = document.querySelector('#employment h3');
  - employment.textContent = "Make 'dem billzzz";
1. Change colour of body
  - body = document.querySelector('body');
  - body.style.background = '#29074f';
1. Change all the .highlight styled elements to a different colour
  - highlights = document.querySelectorAll('.highlight');
  - for(i = 0; i < highlights.length; i++){ highlights[i].style['background-color'] = "#82961e";}
1. Change h1 font-family to monospace
  - heading = document.querySelector('h1');
  - heading.style['font-family'] = 'monospace';
1. Select and change the color of the round side bar things
  - actionIcons = document.querySelectorAll('.action-icon-bg');
  - for(var i = 0; i < actionIcons.length; i++){ actionIcons[i].style['background-color'] = "#af4b2f";}  
1. Change "Name" placeholder in form to "Identify Yourself"
  - nameField = document.querySelector('#name');
  - nameField.form[0].placeholder = 'Identify Yourself';
1. Change the placeholder attribute of the message field to "state your business"
  - messageField = document.querySelector('#message');
  - messageField.form[2].placeholder = 'State Your Business';
1. Give the name field a "value" attribute of "your nemesis".
  - nameField.value = 'Your Nemesis';
1. Change the value attribute of the email field to "koalathebear@gmail.com".
  - emailField = document.querySelector('#email');
  - emailField.value = 'kalathebear@gmail.com';
1. Change the value of the submit button on the contact form to "En garde!".
  - submitButton = document.querySelector('#submit');
  - submitButton.value = 'En garde!';
1. Disable submit button
  - submitButton.disabled = true;
1. Erase panda's personal details
 - personalDetails = document.querySelectorAll('.bio-info-item span:nth-child(2n)')
 - for(var i = 0; i < personalDetails.length; i++){personalDetails[i].style.display = 'none';};

***Next Assignment***
1. Take the time travel skill off the page
 - skill = document.querySelector('#time-travel');
 - skillDiv = skill.parentElement
 - skillDiv.remove()
2. Duplicate pikachu
 - for(var i = 0; i < 10; i++){pikachu = document.querySelector('#right-image').cloneNode(true); document.querySelector('.portfolio-container').appendChild(pikachu);}
3. add page updated at to info
 - infoItem = document.querySelector('.bio-info-item').cloneNode(true);
 - infoItem.firstElementChild.innerText = 'Page last updated at';
 - today = new Date();
 - infoItem.lastElementChild.innerText = today
 - document.querySelector('.bio-info').appendChild(infoItem);
