1. Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead (hint: use attr()).

 -- $ ('.profile-image').attr('src', 'http://farm3.static.flickr.com/2547/4166513842_7322ea9e33_o.jpg')
 --

Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

-- $('#left-image img').attr('src', 'https://upload.wikimedia.org/wikipedia/en/8/8a/Frasier_Logo.JPG');  --

2. Select the heading that says "Panda the Bear" and change it to the name of a noted radio psychiatrist. (hint: use text())

-- $ ('h1.highlight').text('Frasier Crane') --

3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

-- ('#employment .info-title').text('Grand Exploits') --

4. Panda the Bear is lying about their skills! Take the "time travel" skill off the page to satisfy your personal sense of justice. Use your googling and docs-skimming skillz to find a jQuery function that will allow you to remove elements from the DOM. (hint: there are multiple ways of doing this, but the parent() function might be useful when it comes to selecting the right element)

-- $('#time-travel').parent().remove(); --

5. Change the colour of the body. (hint: use css())

-- $('body').css('background-color', 'purple'); --

6. Change the colour used by the highlight class.

-- $('.highlight').css('color', 'indigo'); --

7. Change the font family of the h1 to 'monospace'.

-- $ ('h1').css('font-family', 'monospace'); --

8. Find a way to select the round icons in the sidebar and then change their colour.

-- $('.action-icon-bg').css('background-color', 'yellow'); --

9. Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".

-- $ ('#name').attr('placeholder', 'Identify yourself'); --

10. Change the placeholder attribute of the message field to "state your business".

-- $ ('#message').attr('placeholder', 'Statechur Bizness'); --

11. Give the name field a "value" attribute of "your nemesis".

-- $ ('#name').attr('value', 'Yer nemesis, bub'); --

12. Change the value attribute of the email field to "koalathebear@gmail.com".

-- $ ('#email').attr('value', 'frasiercrane@gmail.com'); --

13. Change the value of the submit button on the contact form to "En garde!".

-- $ ('#submit').attr('value', 'En garde!'); --
