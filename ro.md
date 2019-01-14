Prep:

* account with accountbalance


Suggested test steps: 
(happy path)
* purachse a game with it different possibilities (duration, subscription, normal)
  * normal:
    * 1 draw and a winning
  * subscription:
    * 2 draws and a chancellation by the customer
  * duration:
    * 3 draws and the tickets will just stop then (generates an additonal mails )

check everything based on the list below, if it's done and you want to proceed to the steop of checking what happens when you won ping manuel hunck 

(unhappy path)
* purchase a game (which will not work due to switched conditions)
* ping manuel hunck and see the results of a broken ticket payment -> this will only generate a different set of mails and a different entries in the ticket history

Areas to check:

* WEBSHOP
  * GAMES_PAGE
    * navigate to them by the list on the left site - only entries in the JUCAȚI ACUM section
  * TICKETS
    * check the elements for having correct names
  * SEO_TEXTS
    * Texts below the games area
  * BASKET (you get there after submitting a ticket to the basket)
    * everything displayed should have correct texts
  * TICKET_HISTORY
    * /account/tickets . everything there (each entry can be opened)
      * to be checked after a pruchase and after the numbers are drawn
  * NUMBERS_AND_QUOTAS
    * /lotto-results
  * HELP_SECTION
    * /help - pick the games in the drop down and the check topics below
* MAILS
  * check recieved mails, therefore purchase the tickets, processing and timejumps needed will be dine by manuel hunck
