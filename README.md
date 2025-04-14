# Pawsome - Animal Shelter Adoption Platform

* **Project Status:** In-Progress
* **Live Demo:** https://pawsome-frontend.vercel.app/
* **Repository:** https://github.com/ngluunhatson/pawsome-frontend

## Project Overview

Pawsome is a web application designed to streamline the pet adoption process by connecting animal shelters with potential adopters. It functions as a "dating profile" system for animals, allowing shelters to showcase available pets and users to easily browse, search, and find their perfect companion. The platform features distinct user roles and a robust profile management system for shelters.

## Objectives

* Create a centralized platform for shelters to manage and display animals available for adoption.
* Provide an intuitive and user-friendly interface for the public to search and browse potential pets.
* Implement role-based access control for shelter staff (admin) and public users.
* Facilitate better communication and visibility for shelter animals.

## Key Features

### 1. User Accounts & Authentication
* **Secure Login System:** Users can register and log in to the platform.
* **Role-Based Access:**
    * **Admin/Shelter Accounts:** Can create, manage, and remove animal profiles.
    * **Public Accounts:** Can browse, search, and potentially save favorite profiles (future enhancement).

### 2. Shelter Management Portal (Admin View)
* **Create Animal Profiles:** Shelters can add new animals with the following details:
    * **Type of Animal:** Dog, Cat, Other.
    * **Breed:** Dropdown list of common breeds + "Other" option.
    * **Disposition:** Checkboxes for "Good with other animals", "Good with children", "Animal must be leashed at all times".
    * **Picture:** Upload functionality for animal photos.
    * **Availability Status:** Selectable status - "Not Available", "Available", "Pending", "Adopted".
    * **Description:** Free text area for personality, history, and specific needs.
    * **News Item:** A short blurb or update about the animal.
* **Edit Existing Profiles:** Ability to update any information on an animal's profile.
* **Remove Profiles:** Functionality to remove profiles when an animal is adopted or no longer at the shelter.

### 3. Public User Interface
* **Landing Page:** An attractive entry point introducing the platform and its purpose.
* **Browse Animals:** View all available animal profiles in a gallery or list format.
* **Search Functionality:** Users can filter and search for animals based on:
    * Type of Animal (Dog, Cat, Other)
    * Breed
    * Disposition criteria (using checkboxes)
    * Date profile was created/updated.

### 4. Animal Profile Details
* Each profile clearly displays all the information entered by the shelter, including the picture, description, type, breed, disposition, availability, and news item.

## Technology Stack

* **Frontend:** [NextJS]
* **Backend:** [Directus]
* **Database:** [Directus]
* **Authentication:** [Directus]
* **Hosting:** [Fly.io]

## Screenshots

* `![Screenshot-1](https://github.com/ngluunhatson/ngluunhatson/blob/main/image.png?raw=true)`
* `[Insert Screenshot 2: Search/Browse Page]`
* `[Insert Screenshot 3: Animal Profile Example]`
* `[Insert Screenshot 4: Admin Profile Creation Form]`

## Challenges & Future Enhancements

* **Challenge:** Implementing a flexible and efficient search system across multiple criteria.
* **Challenge:** Designing distinct yet intuitive interfaces for both admin and public users.
* **Future Enhancement:** Implement a "favorites" list for public users.
* **Future Enhancement:** Add email notifications for saved searches or status updates on favorited animals.
* **Future Enhancement:** Develop the "Daily News Feed" functionality outlined as a stretch goal.