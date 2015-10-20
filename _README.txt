HOMEWORK 1 README -- DAVID SPARKMAN -- SPARKD

Why did you select the doctype you used?

I decided to use HTML 5 because it is the latest version of HTML and because it is the format that I am most familiar with.

------------------------------------------------------------------------------------------------------------------------

How does your doctype compare to other commonly seen (strict) doctypes?

HTML5 combines HTML 4.01 with XML 1.0 and allows for extensible markup. While I don't use any extensible or custom tags
within this file, it is much easier to use the file type now and allow for future expansion.

------------------------------------------------------------------------------------------------------------------------

How is the markup for your document semantically correct? Are there any non-semantic elements that you needed for styling
purposes? If you used divs and /or spans, be sure to account for them in your explanation.

This document uses several different divs, but all contain semantic meaning because of their class. Since each div is
logically named as to its content, it allows me to give it semantic meaning, as well as give each div its owns style should
I desire to do so, either now, or in the future. Within each div, I also use the <dd> and <dl> tags to allow for descriptive
lists, which not only look nice, when styled, but also convey a specific meaning to someone reading the code. The <ul>s
and <li>s provide additional meaning since they represent list items within each div.

The end of each section also contains a div of class "clear-area" that serves to not only divide the document when using
the correct CSS profile, but also serves to provide a divider for someone reading my code.

------------------------------------------------------------------------------------------------------------------------

In your own words, how is the hCard information you added useful to both humans and automated user agents trying to
access your content?

The hCard (vcard) allows automated systems to parse the HTML file and quickly find where the contact information and extract
it. Many devices and browsers now use this to give the user the option to create a contact or add to an existing contact.
This makes it easy for the user to add the information since they won't have to enter int manually.

On the human side, it makes it easy for someone ready my HTML to fine my contact information since all they have to do
is look for the vcard class.

The HTML and CSS are also commented to make it even easier to understand.

------------------------------------------------------------------------------------------------------------------------

RESOURCES AND COLLABORATORS

Stack Overflow
W3 Schools
Justin Etzine