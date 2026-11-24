# DormFinder – UI/UX Design Guidelines

## 1. Design Direction

DormFinder should have a modern, professional, clean, and student-friendly accommodation platform design.

The interface should feel similar to established property discovery platforms, with a strong focus on property photos, accommodation details, maps, search functionality, and easy navigation.

The design must prioritize usability and readability over unnecessary animations and decorations.

**Design Keywords:**
- Modern
- Minimalist
- Professional
- Student-friendly
- Trustworthy
- Responsive

## 2. Visual Identity

### Color Palette

Maintain the existing DormFinder navy, blue, and yellow identity.

| Color | Hex Code | Usage |
|---|---|---|
| Dark Navy | #080F20 | Main background |
| Secondary Navy | #111B30 | Cards and sections |
| Primary Blue | #2563EB | Buttons and primary actions |
| Accent Yellow | #FFC928 | Brand highlights |
| White | #FFFFFF | Main headings |
| Light Gray | #CBD5E1 | Secondary text |
| Border Gray | #26344D | Card borders |
| Success Green | #16A34A | Available status |
| Danger Red | #DC2626 | Unavailable status |

Use the colors consistently throughout the system.

### Typography

Recommended font: Inter or Poppins.

- Page headings: Bold
- Section headings: Semibold
- Body text: Regular
- Buttons: Medium or Semibold
- Small labels: Medium

Maintain readable font sizes and consistent spacing.

## 3. Global Layout

All pages must share a consistent design system.

### Navigation Bar
- DormFinder logo on the left.
- Main navigation links where applicable.
- User profile and notification area after login.
- Sign In and Sign Up buttons for visitors.
- Sticky navigation when appropriate.

### Content Layout
- Centered content containers.
- Consistent spacing between sections.
- Rounded cards and subtle borders.
- Clear visual hierarchy.
- Responsive layouts for desktop, tablet, and mobile.

## 4. Landing Page

Improve the existing landing page without removing its established identity.

### Hero Section
- Retain the Minglanilla map background.
- Use a dark overlay for text readability.
- Display a strong headline.
- Add a short description of DormFinder.
- Include a prominent Browse Accommodations button.
- Add a secondary How It Works button.
- Keep statistics only when supported by actual database information.

### Accommodation Preview
Display selected property listings using image-based cards.

Each card should contain:
- Property image
- Property name
- Accommodation type
- Monthly rental price
- Location
- Room availability
- View Details button

### How It Works
Present the process in three simple steps:
1. Search for accommodations.
2. Explore property details.
3. Send a booking request.

### Features Section
Highlight the actual system functionalities using clean icons and short descriptions.

### Location Section
Display the Minglanilla interactive map and relevant accommodation locations.

### Contact Section
Maintain a clean contact form and contact information.

### Footer
Include the logo, quick links, user links, project scope, and copyright information.

## 5. Student / Boarder Interface

The student interface should prioritize finding accommodations quickly.

### Student Dashboard
- Welcome message
- Search accommodations
- Featured or recommended listings
- Recently viewed properties, if implemented
- Booking request summary
- Quick navigation

### Browse Accommodations
Use a property discovery layout.

- Search bar at the top.
- Filters in a sidebar or expandable panel.
- Property cards in a responsive grid.
- Sorting options where supported.

### Property Details
Use a structured property information layout.

- Large property photo gallery
- Property name and accommodation type
- Monthly rental price
- Full location
- Amenities
- Room information
- Availability status
- Owner information
- Map location
- Messaging and booking request actions

### Booking Requests
Display booking requests in organized cards or a table.

Use clear status indicators:
- Pending
- Approved
- Rejected
- Cancelled (if implemented)

### Messages
Use a clean messaging interface with a conversation list and chat area.

## 6. Property Owner Interface

The owner interface should focus on managing accommodation listings and booking requests.

### Owner Dashboard
- Total listings
- Available rooms
- Pending booking requests
- Recent activities

### Manage Listings
- Add new property
- Edit property information
- Upload property photos
- Update rental prices
- Update room availability
- View existing listings

### Booking Management
- View incoming requests.
- Review student booking information.
- Approve or reject requests.
- Track booking request statuses.

### Messages
Provide a conversation interface for communicating with students.

## 7. Administrator Interface

The administrator interface should prioritize system monitoring and management.

- Dashboard overview
- User management
- Property listing management
- System activity information
- Clear tables and organized actions

Only display administrative functions that are actually implemented.

## 8. Reusable Components

Create consistent reusable UI components.

- Buttons
- Navigation bars
- Property cards
- Search bars
- Filter panels
- Form fields
- Modal dialogs
- Status badges
- Tables
- Pagination
- Notification components
- Empty states
- Confirmation dialogs

## 9. Interaction and User Experience

- Provide hover and focus states.
- Show loading indicators when data is being retrieved.
- Display success and error messages.
- Validate forms before submission.
- Confirm important destructive actions.
- Use consistent button styles.
- Provide empty-state messages when there are no listings or booking requests.
- Avoid unnecessary animations.
- Ensure all buttons and links perform their intended actions.

## 10. Responsive Design

The system must support:

- Desktop computers
- Laptops
- Tablets
- Mobile phones

Use responsive CSS layouts, flexible grids, and appropriately sized navigation elements.

## 11. Design Consistency Rules

1. Do not randomly introduce new colors.
2. Maintain consistent typography.
3. Use consistent border radii and spacing.
4. Keep buttons and forms visually consistent.
5. Do not redesign individual pages in completely different styles.
6. Prioritize accessibility and readability.
7. Do not remove or break existing system functionalities.
8. Do not modify database structures or backend logic solely for visual improvements.
9. Use actual system data instead of fabricated statistics or property information.
10. Maintain the DormFinder brand identity across all user roles.

## 12. Overall Design Goal

The final DormFinder interface should look like a real-world accommodation discovery platform rather than a basic academic project.

The most important elements are property images, accommodation information, search and filtering, location maps, room availability, booking requests, and easy navigation.

Every page should feel like part of one unified platform.