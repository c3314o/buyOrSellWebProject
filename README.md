# buyOrSellWebProject
Web application similar to craigslist that lets users to create account as a buyer or seller based on their intent to buy or sell products. Products might include TV, mobile, car etc.  


Features 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	1. Customer is able to create online account and use the account credentials to login. Forgot password feature is also implemented.
	2. Customer is able to post new advertisements, view advertisements of other users.
	3. Seller can add / update / delete advertisements at any time.
	4. Buyer can view different advertisements and can contact Seller via means of contact number and email address.
	5. We have used SAX Parser in order to store advertisement Categories which are loaded once Tomcat starts.

	6. Users account information and messages are stored in MySQL database.
	7. Seller advertisements are stored in MySQL database. Advertisement insert / delete / update are reflected in both MySQL database and HashMap. 
	8. Customers are able to submit reviews of both advertisement and seller.
	9. All the reviews are stored in MongoDB database    
	10. Added Trending data for Top 6 Viewed Advertisement, Top 6 Rated Seller, Top 6 Rated Advertisement.

	11. We have used combination of both JSP and Servlet along with Java Beans / POJO in our project.

	12. We have implemented search Auto-Completion feature using Ajax in order to search for required advertisements.
	When user types in search bar, then we search for the matching advertisements in our database using Ajax.

	13. We implemented Twitter integration where we are fetching last 100 tweets each from Bestbuy_deals, Newegg and Slickdeals twitter accounts.
	Then we are matching these tweets with our Advertisement Title and displaying the respective tweets in advertisement page.
