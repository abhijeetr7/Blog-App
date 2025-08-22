# Blog-App

a fully functional single-page blog web app with all the requested features. Here's what the application includes:
Key Features Implemented:
✅ Core Functionality

Homepage with post listing - Displays blog posts in a responsive grid layout
Trending/Latest toggle - Sort by likes+views+date or by most recent updates
Search functionality - Real-time filtering by title and author
Post detail view - Full post content with navigation via URL hash routing
Like system - Toggle likes with instant UI updates and persistence
Comments system - Add and view comments with form validation

✅ Data & Persistence

6 mock blog posts with all required fields (id, title, author, summary, content, etc.)
localStorage integration for posts, comments, and user likes
View tracking - Increments when posts are opened
Data initialization - Seeds mock data on first load

✅ Routing & Navigation

Hash-based routing: #/ for list view, #/post/{id} for detail view
Back button preserves sort and search state
Direct URL access works for all routes

✅ UI/UX Design

Responsive design - Works on desktop, tablet, and mobile
Modern styling - Clean cards, shadows, hover effects, rounded corners
Accessibility - ARIA labels, keyboard navigation, screen reader support
Status announcements - Live regions for likes and comments

✅ Advanced Features

Smart sorting - Trending uses likes → views → date as tie-breakers
Search persistence - Maintains search when switching sort modes
Form validation - Required fields with user feedback
Error handling - Graceful localStorage and data handling



---
Built with ❤️ using HTML, CSS and Javascript
