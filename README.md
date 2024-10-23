# London Property Viewer

## Project Overview

The **TechnoWiz Property Viewer** is a user-friendly graphical user interface (GUI) designed to view and manage a range of available Airbnb properties across London. This application allows users to search for properties based on their specific needs and provides hosts the capability to add new listings to the database.

## Features

### General Functionalities

- **User-Friendly Interface:**  
  The GUI is intuitive, with a welcome panel providing instructions on how to use the application.

- **Property Viewing:**  
  Users can browse Airbnb listings by selecting their desired price range, making it easy to find suitable properties.

- **Add Listings:**  
  Hosts can add their own Airbnb listings to the database, enabling them to join Airbnb easily.

### Application Window

- The application window serves as the main interface, featuring:
  - Two combo boxes for selecting price ranges.
  - Alert notifications for invalid selections.
  - Transition animations and sound effects when switching between panels.

### Welcome Panel

- The initial landing page that greets users and provides basic instructions.
- Features visually appealing property images to enhance user engagement.

### Map Panel

- **Interactive Map:**  
  Users can explore properties by London boroughs, with color gradients indicating the number of available listings per price range.
- **Property Listings:**  
  Users can view detailed property information, including:
  - Property name
  - Lister’s name
  - Price per night
  - Number of reviews
  - Minimum stay requirements
- **Alerts for Duplicate Views:**  
  Prevents multiple instances of the same property viewer to avoid confusion.

### Statistics Panel

- Provides key statistics to assist users in making informed decisions, including:
  - Average number of reviews per property.
  - Total number of available properties.
  - Comparison of property types (entire homes vs. private rooms).
  - Insights on crime rates, population density, GDP per capita, and property availability.

### Add Property Panel

- Allows new or existing hosts to input property details, ensuring a streamlined process to add listings.
- Required fields include:
  - Host name
  - Property description
  - Price per night
  - Minimum nights
  - Availability
  - Property type
  - Pet restrictions
  - Bedroom and bathroom count
  - Property location
- Validations ensure all fields are filled correctly, with alerts for errors.

## Unit Testing

The unit testing focused on the **Property Viewer Panel** class, allowing tests for functionalities such as:
- Clicking on properties to view details.
- Testing the "View on Map" feature using geographic coordinates.
- Reordering properties based on various criteria (price, alphabetical order, reviews).

## Extra Challenge Tasks

- **Visual and Audio Enhancements:**  
  Added a short introductory video that plays at startup (may not work on all systems). Each button click triggers a sound effect for improved user feedback.
- **Error and Success Notifications:**  
  Audio alerts for invalid inputs and confirmations of successful property additions enhance user experience.

## Conclusion

The TechnoWiz Property Viewer aims to simplify the process of finding and listing properties on Airbnb, providing users with valuable insights into the London property market while ensuring a seamless and engaging experience.

## Authors

- Krishna Prasanna Kumar (K21004839)
- Shozab Anwar Siddique (K21054573)
- Mohamed Shazeem Shaheen Nazeer (K21086651)
- Abbas Bin Vakas (K21013731)
