Initial Features to implement
1.User Management :
    a) Registration (Admin , Seller , Buyer)
    b) Role Based Access Control 
        i) Admin - creates auction (with start time ,end time)
        ii) Seller - list their items in auction
        iii) Buyer - place Bids
    c) Login (Using Spring Security with JWT-JSON Web Tokens for user authentication)

2.Auction Management :
    Admin starts auction and closes at end time automatically
    Spring Boot Scheduler to automatically close auctions when time expires
