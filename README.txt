# Plan-It

Plan-It is an event planning application that helps you effortlessly plan and manage various events. Whether you're organizing a small gathering or a large-scale event, Plan-It provides the tools and features you need to stay organized and ensure a successful event. This README file provides an overview of the different files and functionalities available in the Plan-It application.

## Files

### `README.txt`

This file contains important information about the Plan-It application, its purpose, and instructions for installation and usage.

### `aboutus.php`

This file displays information about the Plan-It team or company. It provides details about the app's creators, their vision, and any other relevant information.

### `addtask.php`

Using this file, users can add new tasks to their event planner. It allows users to specify the task details, such as the task name, description, due date, and any other relevant information.

### `contactus.php`

This file provides a means for users to get in touch with the Plan-It support team or administrators. It may contain a contact form or contact information, such as email addresses or phone numbers.

### `deleteplanner.php`

This file enables users to delete an entire planner or event from their account. It typically requires user authentication to ensure the deletion is authorized.

### `deletetask.php`

Users can leverage this file to delete individual tasks from their event planner. It allows users to select the task they wish to remove, ensuring better task management.

### `edittask.php`

This file facilitates the editing of existing tasks in the event planner. Users can modify task details, such as the task name, description, due date, or any other relevant information.

### `login.php`

This file provides a login interface for users to access their Plan-It account. Users will typically need to provide their credentials, such as a username and password, to authenticate themselves.

### `logout.php`

Using this file, users can log out of their Plan-It account. It ensures that their session is terminated securely and helps maintain account security.

### `planit (3).sql`

This file contains the SQL code or script required to set up the database for the Plan-It application. It defines the tables, columns, and relationships necessary for storing user information, tasks, and other relevant data.

### `planner.php`

This file serves as the main interface for users to view and manage their event planner. It displays the list of tasks, allows users to add, edit, or delete tasks, and provides an overview of the event's progress.

### `profile.php`

This file allows users to view and update their user profile information. Users can edit details like their name, contact information, and other relevant data.

### `signup.php`

Using this file, new users can create an account for the Plan-It application. It typically requires users to provide essential details, such as their name, email address, and password.

### `template.php`

This file serves as a template or layout for other pages in the Plan-It application. It provides a consistent design and structure, ensuring a cohesive user experience throughout the app.

## Installation and Setup

To install and set up the Plan-It application, follow these steps:

1. Download the Plan-It application files from the designated source.
2. Ensure you have a web server (e.g., Apache) installed on your machine or a hosting provider with PHP support.
3. Create a MySQL database and import the `planit (3).sql` file to set up the required database schema.
4. Place the downloaded Plan-It files in the appropriate directory accessible by your web server.
5. Configure the database connection settings in the relevant PHP files (e.g., `config.php
