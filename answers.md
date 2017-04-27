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

$('.action-icon-bg').css('color', 'black');

<!-- Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself". -->

$('#name').attr('placeholder', 'Identify Yourself');


<!-- Change the placeholder attribute of the message field to "state your business". -->

$('#message').attr('placeholder', 'State Your Business');


<!-- Give the name field a "value" attribute of "your nemesis". -->

$('#name').attr('value', 'Your Nemesis');


<!-- Change the value attribute of the email field to "koalathebear@gmail.com". -->

$('#email').attr('value', 'koalathebear@gmail.com');


<!-- Change the value of the submit button on the contact form to "En garde!". -->

$('#submit').attr('value', 'En Garde');

<!-- We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button  -->

$('#submit').attr('disabled','disabled');

<!-- We should help Panda protect their privacy by clearing their personal details from the sidebar. You can use empty() to do this. -->

$('.bio-info').empty()

<!-- That drawing of Pikachu is really cute. Let’s duplicate it using clone() and insert it at the bottom of the .portfolio-container using insertAfter() or appendTo(). -->

$('#right-image img').clone().appendTo('.portfolio-container');

<!-- Wow, that was so satisfying I think we should do it 10 more times. Use a for loop to help you do this. -->

for (i = 0; i < 10; i++){ pikachu.clone().appendTo('.portfolio-container')}



<!-- Let’s add a message about when the page was last updated. We'll do this by appending a new <li> element to the <ul> in the sidebar (you might need to refresh the page to bring back the list items that we emptied out earlier). -->
