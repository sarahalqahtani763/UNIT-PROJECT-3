# UNIT-Project-3

## Create a Project of your own choosing

Base on what you’ve learned until now , create a project of your choosing. Impress us with your creativity and execution.


## Minimum Requirements
- Use Templates & Template Inheritance.
- Organize your project in apps as needed.
- Use models to represent you data.
- Use a CSS library to style your website.
- User Authentication & Authorization (register, login, logout, Limit access to some pages using permissions , etc.)
- Use naming conventions.
- Strive to make the user journey intuitive and complete.



## Example Projects :


1. **Task Management System:**
- **Overview:** Create a platform for managing tasks and projects within a team or organization.
- **Features:**
- User authentication and role-based access control.
- Task creation, assignment, and tracking.
- Project management with milestones.
- File uploads and comments on tasks.
- Notification system for task updates.


**Online Learning Platform:**

- **Overview:** Develop a platform for online courses, quizzes, and educational resources.
- **Features:**
- User registration and profile management.
- Course creation and enrollment.
- Quiz and assessment functionalities.
- Progress tracking and certificates.




**Crowdfunding Platform:**

- **Overview:** Build a crowdfunding website where users can create campaigns and seek financial support for their projects.
- **Features:**
    - User profiles with project history.
    - Campaign creation and customization.
    - Payment integration for contributions.
    - Progress tracking and updates.

**Job Board and Recruitment System:**

- **Overview:** Develop a platform for job seekers and employers to connect.
- **Features:**
    - User profiles with resumes.
    - Job posting and application functionalities.
    - Search and filter options for jobs.
    - Employer dashboards for managing postings.


**Inventory Management System:**

- **Overview:** Build a system for tracking and managing inventory for businesses.
- **Features:**
    - User authentication with roles (e.g., admin, staff).
    - Product catalog with stock levels.
    - Order processing and tracking.
    - Reporting and analytics.


**Recipe Sharing Platform:**

- **Overview:** Create a platform where users can share and discover recipes.
- **Features:**
    - User accounts with saved recipes.
    - Recipe creation and editing.
    - Search and categorization of recipes.
    - User ratings and reviews.
      
## Resources:

**Free high quality images :**

- https://www.pexels.com/
- https://unsplash.com

**Free sounds website:**

- https://mixkit.co/

**Free stock videos:**

- https://pixabay.com/videos/

**Free Fonts:**

- https://fonts.google.com

**Free Icons**

- https://fonts.google.com/icons
- https://icons.getbootstrap.com/

**CSS Library:**

- https://getbootstrap.com/
- https://get.foundation/index.html

**CSS Animation libraries:**

- https://animate.style
- https://www.minimamente.com/project/magic/


## Use python-dotenv to save your sensitive data.
- https://pypi.org/project/python-dotenv/


## Use a CDN or cloud storage provider to sore your large static files (videos, images, etc.), such as:
- https://firebase.google.com/docs/storage



## Use Git & Github to manage and track changes in your project.
- At lease commit and sync the changes once at the end of everyday.



## Edit the README.md file to include (include the info at the top):
- Project Name
- Project Description
- Features list.


-----------------------------------------------------------------------------

## Car Rental Application Project

The Car Rental website is a comprehensive web-based platform designed to streamline the process of renting and managing cars. Built using the Django web framework in Python, the application provides users with a user-friendly interface for browsing available cars, making bookings, and leaving reviews.


* The application offers the following key features:

- User authentication and authorization using Django's built-in User model.
- CRUD (Create, Read, Update, Delete) functionality for car listings.
- Rental transactions management, including pickup and return details.
- User reviews and ratings for rented cars.
- Advanced search functionality for finding available cars based on various criteria.

* Database "Models" :

- Car Model:
Attributes: name, year, image, available, vehicle_class, vehicle_type, color, seats, pags, air_conditioner, transmission_type, fuel_type, price, city.

- Rental Model:
Attributes: car, renter, rental_pickup_location, rental_return_location, rental_pickup_Datetime, rental_return_Datetime, total_cost, is_available.

- Review Model:
Attributes: car, reviewer, rating, comment, created_at.
Relationships are established between models, ensuring data integrity.

 

