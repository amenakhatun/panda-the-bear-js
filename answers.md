 1) $('img.profile-image').attr('src', "http://classroomclipart.com/images/gallery/Clipart/Animals/Alligator_Clipart/TN_alligator-910.jpg");

 2) $('#left-image img').attr('src', 'http://classroomclipart.com/images/gallery/Clipart/Animals/Alligator_Clipart/TN_alligator-910.jpg');

3) $('h1').text('Amena Khatun');

4) $('#time-travel').text('Climb Trees');

5) $('body').css('background-color', 'purple');

6) $('.highlight').css('background-color', 'orange');

7) $('h1').css('font-family', 'monospace');

8) $('.action-icon-bg').css('background-color', 'yellow')

9) $('#name').text('identify your self');

10) $('.contact-info#name').attr('placeholder', 'idintify yourself');

11) $('#message').attr('placeholder', 'state your business');

 $('.contact-info#name').attr('value', 'your nemesis');

12) $('.contact-info#email').attr('value', 'koalathebear@gmail.com');

13) $('#submit').attr('value', "En Garde!");

1) $('#right-image').clone().insertAfter('#submit');

2) for(var i=0; i < 10; i++) {$('#right-image').clone().insertAfter('#submit')};

3)
var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);

$(listItem).attr('class', 'bio-info-item');
var rightSpan = document.createElement('span');
var d = new Date
var date = document.createTextNode(d);
rightSpan.appendChild(date);
listItem.append(rightSpan)
$('ul.bio-info').append(listItem)


var d = new Date
https://www.w3schools.com/jsref/jsref_obj_date.asp
use this formula for dates/times in the future.
