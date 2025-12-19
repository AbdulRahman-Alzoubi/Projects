Commerce Auction Platform
A comprehensive web-based auction site built with Python and Django, allowing users to post listings, place bids, and manage watchlists in a dynamic, secure environment.

🛠 Features

Auction Listings: Logged-in users can create new listings with titles, descriptions, starting prices, and optional image URLs/categories.


Active Listings View: The default route displays all currently active auctions, including prices and photos.


Bidding System: Implements bid validation logic ensuring new bids are higher than the current price and starting bid.


Watchlist & Comments: Users can add items to a personal watchlist and engage with others via a listing-specific commenting system.


Auction Closing: Listing creators can close auctions, automatically determining the winner based on the highest bid.


Category Browsing: Dedicated interface to filter active listings by categories such as Electronics, Fashion, or Home.

🏗 Technical Implementation

Architecture: Utilizes Django’s MVC (Model-View-Controller) pattern for clean separation of concerns.


Database Management: Uses Django ORM with SQLite for relational data handling of Listings, Bids, and Comments.


Security: Integrated Django’s user authentication system for secure registration, login, and restricted access to bidding/closing features.


Admin Interface: Configured Django Admin to allow site administrators to view, edit, and delete any content on the site.
