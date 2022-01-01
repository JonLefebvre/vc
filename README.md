# VerifyCrypto - CS50X Project - Jonathan Lefebvre
#### Video Demo:  https://vimeo.com/661528757
#### Description:

Preface:
In 2021 over $10 Billion of investor's money have been stolen through various scams, mostly through fraudulent transactions. Our goal with VerifyCrypto is to help people recognize legitimate (or not-so-legitmate) cryptocurrency platforms and exchanges so that these investors don't lose their life savings.

We've created a database of curated exchanges, investment firms and wallets to help investors find the best platforms for them. With an easy to use search function, it's a breeze to find what you're looking for.

Design Choices:
I decided to go with Flask, Python, PostgreSQL and HTML/CSS/Bootstrap as this made the most sense for a simple web app, and I was the most comfortable with these because of CS50X.
Flask made it very easy to create routing to new pages, create dynamic headers and footers, and create simple forms (especially for search.) Search was the most difficult to develop because there were a lot of dependencies that were abandoned recently (such as werkzeug), 
so I had to make a simpler version of search based on WTForms.

I used the Simple Blog template as it cut down the time to create a nice looking website. It made it easier to add backgrounds, formatting, and sub-pages. The login functionaliy was easy because we did it in CS50X as well.

Finally, for the home page, I used my skills as a marketer to cut down on clutter and present the user with one call-to-action: the search bar. Here they can easily search the database for companies I had selected to present with this demo.

Stack:
VerifyCrypto is built with Flask, Python, PostgreSQL, HTML/CSS/Bootstrap.
