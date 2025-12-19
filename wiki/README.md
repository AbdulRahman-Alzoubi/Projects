Wiki Encyclopedia
A Markdown-based encyclopedia application that allows users to create, edit, and search for entries. The platform dynamically renders human-friendly Markdown into browser-ready HTML.

🛠 Features
Entry Rendering: Visiting /wiki/TITLE displays the requested entry's content. If an entry doesn't exist, a custom 404 error page is rendered.


Advanced Search: Users can search for entries; exact matches redirect to the entry page, while partial matches provide a list of search results.


Content Creation: A "Create New Page" feature allows users to submit Markdown content for new entries with duplicate-title validation.


Entry Editing: Existing pages can be edited via a pre-populated textarea, allowing for seamless updates to documentation.


Random Discovery: A "Random Page" feature to navigate to a random encyclopedia entry instantly.

🏗 Technical Implementation

Markdown Processing: Utilizes the markdown2 library to convert Markdown syntax into HTML for rendering, ensuring entries remain human-readable in storage.


Persistent Storage: Entries are saved as .md files on disk, managed through a utility module to handle file I/O.


Django Forms: Employs Django Forms for robust input validation and secure processing of user-submitted content.


Dynamic Routing: Implements scalable URL routing to handle variable entry titles dynamically.
