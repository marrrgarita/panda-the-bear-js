<!-- Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing. -->

$(".profile-image").attr('src', 'http://fillmurray.com/400/400');

$('#left-image img').attr('src', 'http://placebear.com/325/225');

<!-- Select the heading that says "Panda the Bear" and change it to your own name. (hint: use text()) -->

$('h1.highlight').text("Margarita the Bear")

<!-- Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector) -->

$('#employment h3').text("Things I Did")


<!-- Panda the Bear is lying about their skills! Take the "time travel" skill off the page to satisfy your personal sense of justice. Use your googling and docs-skimming skillz to find a jQuery function that will allow you to remove elements from the DOM. (hint: there are multiple ways of doing this, but the parent() function might be useful when it comes to selecting the right element) -->

$("#time-travel").parent().remove()

<!-- Change the colour of the body. (hint: use css()) -->

$('body').css('background-color', 'cadetblue');

<!-- Change the colour used by the highlight class. -->

$('.highlight').css('background-color', 'darkgrey');

<!-- Change the font family of the h1 to 'monospace'. -->

$('h1').css('font-family', 'monospace');

<!-- Find a way to select the round icons in the sidebar and then change their colour. -->

Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".

Change the placeholder attribute of the message field to "state your business".

Give the name field a "value" attribute of "your nemesis".

Change the value attribute of the email field to "koalathebear@gmail.com".

Change the value of the submit button on the contact form to "En garde!".
