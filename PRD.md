# PRODUCT REQUIREMENTS DOCUMENT (PRD)

# Project Name: CampusBite – Campus Food Ordering System

**Course:** BU-209 Backend Engineering  
**Assignment:** Week 4  
**Document Version:** 1.0  
**Project Status:** Proposed

---

## 1. PRODUCT OVERVIEW

CampusBite is a web-based food ordering system designed to make food purchasing easier and faster for university students.

The platform allows students to view available meals, check prices, place orders online, and track their orders until they are ready for collection.

Food vendors can manage their menus, receive orders, and update order statuses through a dedicated dashboard.

The main purpose of CampusBite is to reduce unnecessary waiting times and improve the food ordering experience on campus.

## 2. PROBLEM STATEMENT

Students often experience long queues when purchasing food from campus cafeterias, especially during lunch breaks and busy periods.

This wastes valuable time that could be used for lectures, studying, and other academic activities.

Students may also have to visit cafeterias physically to discover available meals and prices. Food vendors, on the other hand, may struggle to manage multiple orders efficiently.

CampusBite aims to address these challenges by providing a centralized online platform for food ordering and order management.

**Research to be conducted:** Student and vendor interviews, questionnaires, and cafeteria observations will be used to verify the problem and understand its impact.

## 3. BUSINESS OBJECTIVES

The main business objectives of CampusBite are:

- Reduce the time students spend waiting to purchase food.
- Improve the efficiency of food ordering on campus.
- Help food vendors manage orders more effectively.
- Make food menus and prices easily accessible.
- Improve communication between students and vendors.
- Encourage the adoption of digital services within the university community.

## 4. TARGET USERS

The system will serve three main categories of users.

**Students:**
- Register and log in.
- Browse available meals.
- Check food prices.
- Place food orders.
- Track order progress.
- View previous orders.

**Food Vendors:**
- Manage food menus.
- Update meal prices and availability.
- Receive incoming orders.
- Accept or reject orders.
- Update order statuses.

**Administrators:**
- Manage student and vendor accounts.
- Monitor platform activities.
- Manage vendor access.
- Handle reported issues.

## 5. STAKEHOLDERS

The stakeholders are individuals or groups who are involved in or affected by the system.

The main stakeholders include:

1. **Students:** The primary users who order food through the platform.
2. **Food Vendors:** The individuals responsible for preparing and selling meals.
3. **University Management:** May support and approve the introduction of the platform on campus.
4. **System Administrators:** Responsible for managing and maintaining the platform.
5. **Development Team:** Responsible for designing, developing, testing, and maintaining the system.

## 6. USER STORIES

User stories describe what different users want to accomplish using the system.

**Student User Stories:**

- As a student, I want to create an account so that I can access the platform.
- As a student, I want to view available meals so that I can choose what to eat.
- As a student, I want to check food prices so that I can make informed decisions.
- As a student, I want to place orders online so that I can reduce waiting time.
- As a student, I want to track my orders so that I know when my food is ready.

**Vendor User Stories:**

- As a vendor, I want to add meals so that students can view my menu.
- As a vendor, I want to update food availability so that students do not order unavailable meals.
- As a vendor, I want to receive orders so that I can prepare them.
- As a vendor, I want to update order statuses so that students can monitor their orders.

**Administrator User Stories:**

- As an administrator, I want to manage user accounts so that the platform remains organized.
- As an administrator, I want to manage vendor accounts so that only approved vendors can operate.

## 7. FUNCTIONAL REQUIREMENTS

The system must provide the following functionalities:

**7.1 User Authentication**
- Allow students and vendors to register.
- Allow registered users to log in and log out.
- Provide role-based access to system features.

**7.2 Food Menu Management**
- Allow vendors to add food items.
- Allow vendors to update meal details and prices.
- Allow vendors to mark meals as available or unavailable.
- Allow students to browse available meals.

**7.3 Order Management**
- Allow students to select meals and place orders.
- Allow vendors to receive incoming orders.
- Allow vendors to accept or reject orders.
- Allow vendors to update order statuses.

**7.4 Order Tracking**
- Allow students to view the current status of their orders.
- Support the following statuses: Pending, Accepted, Preparing, Ready for Collection, Completed, and Cancelled.

**7.5 Order History**
- Allow students to view their previous orders.
- Allow vendors to view received orders.

## 8. NON-FUNCTIONAL REQUIREMENTS

These requirements describe how well the system should operate.

**Security:** User passwords must be securely hashed, and access must be restricted according to user roles.

**Performance:** The platform should respond quickly to user requests and load menus efficiently.

**Reliability:** The system should maintain accurate order records and prevent unintended duplicate orders.

**Usability:** The platform should have a simple and understandable interface.

**Scalability:** The system should support increasing numbers of students and vendors.

**Availability:** The platform should be accessible whenever users need to place or manage orders, subject to internet and service availability.

## 9. SCOPE AND PRIORITIES

This section defines what will be included in the first version of CampusBite and what will be introduced later.

**High Priority – MVP Features**

- User registration and authentication.
- Food menu creation and management.
- Viewing available meals and prices.
- Placing food orders.
- Vendor order management.
- Basic order status tracking.

**Medium Priority – Future Features**

- Online payment integration.
- Order notifications.
- Customer ratings and reviews.

**Low Priority – Long-Term Features**

- Food delivery services.
- Loyalty and reward programs.
- AI-based food recommendations.
- Advanced sales analytics.

The first version will focus on online ordering and collection rather than food delivery.

## 10. ACCEPTANCE CRITERIA

Acceptance criteria define the conditions that must be satisfied before a feature is considered complete.

**User Registration and Login**
- A new user must be able to register with valid information.
- Registered users must be able to log in with the correct credentials.
- Invalid login details must produce an appropriate error message.

**Food Menu**
- Vendors must be able to add food items.
- Students must be able to view available meals and their prices.
- Unavailable meals must not be orderable.

**Food Ordering**
- Students must be able to select meals and submit orders.
- The system must save successful orders.
- Vendors must be able to view incoming orders.

**Order Tracking**
- Vendors must be able to update order statuses.
- Students must be able to view updated order statuses.
- Completed and cancelled orders must be clearly identified.

**Order History**
- Students must be able to view their previous orders.
- Order information must be accurate.

## 11. ASSUMPTIONS AND OPEN QUESTIONS

**Assumptions**

- Students have access to smartphones or internet-enabled devices.
- Campus food vendors are willing to use the platform.
- Vendors can update their food availability regularly.
- Students are willing to adopt online food ordering.
- Internet access will be available when using the system.

**Open Questions**

- Will the university officially approve the platform?
- Will all campus cafeterias participate?
- Will students pay online or make payments physically when collecting food?
- Should orders be collected from the cafeteria or delivered?
- How will vendors handle orders they cannot prepare?
- What measures will be used to verify student accounts?

These questions will be investigated during stakeholder interviews and further research.

---

## CONCLUSION

CampusBite is designed to improve the food ordering experience within university campuses by providing a convenient platform for students and food vendors.

Through online menus, food ordering, and order tracking, the system aims to reduce unnecessary queues and improve order management.

The first version will focus on essential functionalities, while additional features will be introduced based on user feedback and future requirements.

The final product requirements will be refined using findings from student and vendor interviews, questionnaires, and direct observation.
