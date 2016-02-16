This HTML code will allow you to create a more-or-less box that expands to show more when you click it. It can be a great addition to any website to grab the attention of the readers.

It's good to include some text whatever that may be in order to see what the box would look like in an actual website. 

Start by creating a js-fiddle account, this is to allow you to write code more easily. 

Like for any HTML page start by creating a h1 heading and include a title
the add some <P> with some text to give some body to your page

next create a div class called: "more-less-box" It should look like this: <div class="more-less-box">

inside it create a third heading and inside write Fact Box 

The create a par class called "more-less-area collapsed"

in it place some more text, this will be the text who is in your fact box

after that you will want to create a link for a website so start with an a and write the class "more or less button" it should look like this: <a class= "more-less-button" 

then write the following href: "javascript:void(0);"onclick="toggleMoreLess('.more-less-area')">Show/Hide

close the command with a </a> and then close the div you were working in

This should link to your javascript in which you need to write the following function: toggleMoreLess(areaClass){
$(areaClass).toggleClass('collapsed');

}

In the CSS you can design you box to look however you want. 

# more-less-box2
expandable box for news articles created for City's MA Interactive J
