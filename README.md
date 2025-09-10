# Quick-Bites
The development of a food ordering website involves creating a platform that streamlines the interaction between customers and restaurants, ensuring convenience, efficiency, and reliability
•	Objective: The primary goal of the website is to provide users with an intuitive platform to browse menus, place orders, while also offering local vendors a streamlined system to manage their operations.
•	User Interface: A user-friendly design is emphasized to ensure seamless navigation for customers. Features like search filters and personalized recommendations enhance the overall experience.
•	Payment Integration: Secure payment gateways are integrated to facilitate smooth transactions, offering payment option as UPI.

IMPLEMENTATION
        Structure
        <img width="1050" height="356" alt="image" src="https://github.com/user-attachments/assets/43febee1-6b8e-4a77-891c-d17723f4cd4d" />

4.1 HTML Elements:
1.	Head Section:
•	Includes metadata (charset, viewport settings) and imports for fonts (Poppins), icons (Font Awesome), and Bootstrap styles.
2.	Body Section:
•	Contains the main elements of the webpage such as the banner, navbar, carousel, menu cards, cart functionality, and footer.
<img width="1095" height="61" alt="image" src="https://github.com/user-attachments/assets/db017a4a-ded4-4003-a681-bbceeec5879a" />


            4.2 Features
1.	Hero Section:
•	Displays a banner with a logo and tagline encouraging users to order food.
•	The tagline includes an emoji (using Font Awesome).
 
Fig 4.1
2.	Navigation Bar (Navbar):
•	A responsive navbar created using Bootstrap.
•	Links include:
•	Home – highlights the main page.
•	Link – redirects to the app on Google Play Store.
•	A Sign-Up button triggers a modal.
 



3.	Sign-Up Modal:
•	A Bootstrap modal for user registration.
•	Collects user information (name, email, password) and displays an alert upon successful sign-up.
<img width="699" height="539" alt="image" src="https://github.com/user-attachments/assets/8ada3384-a5b3-4d1f-8556-e357b87e8556" />

 
Fig 4.2
4.	Carousel:
•	A Bootstrap carousel showcases rotating food images for visual appeal.
•	Contains three slides with placeholders for food items.
 
<img width="976" height="438" alt="image" src="https://github.com/user-attachments/assets/c99bf168-8660-4386-be2b-708c88687717" />
<img width="976" height="417" alt="image" src="https://github.com/user-attachments/assets/3a16d202-cec7-4585-a1ef-bbb2f6776804" />

 
Fig 4.3
5.	Food Menu (Cards):
•	A series of Bootstrap cards display the food items.
•	Each card includes:
•	An image.
•	A title (food name).
•	Description of the dish.
•	Price.
•	"Add to Cart" button to enable item selection.
<img width="343" height="487" alt="image" src="https://github.com/user-attachments/assets/f2df068b-3aa9-4f25-9b9b-29b94f0ee0c7" />

 
Fig 4.4

6.	Shopping Cart:
•	Dynamically updates when users add or remove items.
•	Displays:
•	Food items.
•	Individual prices.
•	A Total Price counter.
•	Implemented using JavaScript to manipulate the DOM.
<img width="972" height="427" alt="image" src="https://github.com/user-attachments/assets/e4d5ed87-63ea-4501-b3fc-7b54fad1d5bf" />

 
Fig 4.5

7.	Order Now and QR Code:
•	A button to finalize the order and generate a QR code representing the total bill.
•	The QR code section becomes visible upon clicking the button.
 <img width="713" height="463" alt="image" src="https://github.com/user-attachments/assets/0f5ef711-5cb7-4ed1-8fdc-a872104c1061" />

	Fig 4.6

8.	Footer:
•	Contains:
•	An "About Us" section.
•	Quick links to important pages (e.g., Services, Contact).
•	Contact details (email, phone, and address).
•	Social media links for user engagement.
<img width="913" height="281" alt="image" src="https://github.com/user-attachments/assets/cef53188-cb2c-4c7b-8a00-c7521c3e4641" />

 
Fig 4.7
   4.3 Styling and Dependencies
1.	CSS Styling:
•	External stylesheet styles.css for additional custom styles.
•	Inline styles for specific elements in the footer.
2.	External Libraries and Tools:
•	Font Awesome: For icons.
•	Google Fonts: For Poppins font.
•	Bootstrap: For responsive design and components like the navbar, modal, and carousel.
•	QR Code Generator: Dynamically creates a QR code for the total bill using JavaScript.

4.4 JavaScript Functionality
1.	Sign-Up Form:
•	Prevents default form submission and displays an alert with the entered details.
•	Closes the modal programmatically using Bootstrap's modal instance.
2.	Cart Management:
•	Uses event listeners to add/remove items to/from the cart.
•	Dynamically updates the DOM:
1.	Adds rows for each item in the cart.
2.	Updates the total price.
3.	Order Now (QR Code):
•	Displays a QR code with the total bill amount using QRCode.toCanvas().

Responsive Design
•	Utilizes Bootstrap's grid system and classes to ensure responsiveness across devices.
•	Features like the navbar collapse on smaller screens.

Key Functionalities Summary
•	User Interaction:
•	Adds items to the cart, calculates the total, and allows removal of items.
•	Shows a modal for user sign-up and a QR code upon ordering.
•	Responsive Layout:
•	Adjusts to different screen sizes for optimal viewing.
•	Dynamic Features:
•	JavaScript enables dynamic updates for the cart and QR code generation.
This implementation ensures a modern, interactive, and visually appealing user experience for ordering food online.

