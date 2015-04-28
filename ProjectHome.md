Stickrs is a web platform that implements sticker books functionalities integrated with other e-commerce websites, social network and enterprise marketing mechanism. Using stickers as vouchers, companies could promote their products in a funny and social media way.

Collecting those "stickrs", a customer can change it back for products, promotions, discounts or anything else.

A sticker album is a book where a person collects stickers to stick in the book on designated sections. Sticker album themes can be based around sporting events such as the FIFA World Cup or TV shows like Doctor Who, CVC travel company, GM automobile cars, and so on.


Stickrs components:

1) Stickrs-Core -> administration component for users/stickrsbook maintenance

2) Stickrs-Listener -> listener for all messages sent by Stickrs-Messages

3) Stickrs-Cache -> in memory database for all messages using Graph DB (SGBD)

4) Stickrs-Store -> persists the messages and audit events

5) Stickrs-Messages -> message handler, responsible to create/send messages and have the list of stickrs books and users related. This component is populated by Stickrs-Cache

6) Stickrs-UI -> PHP/Java web interface for users and admin

7) Stickrs-Engine -> responsible for stickrs hashcode creation, stickrs trading and integration of all Stickrs components