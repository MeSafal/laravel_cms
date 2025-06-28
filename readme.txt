CMS (Content Management System)
==============================================================

A comprehensive CMS built with Laravel featuring advanced CRUD generation, granular permissions, and intuitive content management.

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------
1. Features
2. Content Management
3. Role & Permission Management
4. Installation
5. Custom Commands
6. Security
7. Contribution
8. License

--------------------------------------------------------------
Features ✨
--------------------------------------------------------------
Core Functionality:
- ⚡ Instant CRUD Generation - Scaffold full modules with artisan commands
- 🔐 Role-Based Access Control - Granular permissions using Spatie
- 🔄 Dynamic Routing - Automatic route registration and optimization
- 📊 Dashboard Analytics - At-a-glance system overview
- 📱 Responsive Design - Mobile-friendly interface

--------------------------------------------------------------
Content Management 📝
--------------------------------------------------------------
Feature               | Description
----------------------|------------------------------------------------------
CRUD Interface       | Full-featured interface for content creation, listing, and management
Drag-n-Drop Sort     | Visually reorder items with intuitive drag-and-drop functionality
Publish States       | Toggle between published/draft states with instant status updates
Advanced Search      | Filter content using title with real-time results
Detailed View        | Comprehensive view showing creator, last editor, and details

--------------------------------------------------------------
Role & Permission Management 👥
--------------------------------------------------------------
Feature               | Description
----------------------|------------------------------------------------------
Roles Listing       | View all roles with assigned permissions
Role Creation       | Create new roles with permission checkboxes
User Assignment     | Assign roles to users through intuitive interface

--------------------------------------------------------------
CRUD Operations
--------------------------------------------------------------
Generate complete CRUD for a table:
```bash
php artisan crud:generate blogs
php artisan crud:delete blogs

