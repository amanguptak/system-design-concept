```markdown
# Frontend System Design Interviews

## Types of Interviews
1. System Design
2. Product Sense
3. UI Architecture
4. Machine Coding/Component Design

## Things to Consider in System Design Interviews

### 1. Requirements
#### Functional
- Demand/Supply
- Module Level Thinking
  - User Management
  - Help & Support
  - Payment Gateway
  - Pricing & Subscription
  - Product Listing
  - Cart Page
  - Account Management
- Feature Level Thinking

#### Non-Functional
- Mobile/Desktop
- Responsive/Adaptive
- Accessibility
- Asset Optimization (CSS, JS, Images)
- Performance (FCP, LCP, TTI, Web Vitals)
- CSR/SSR
- Authentication/Authorization
- Security
- Caching
- Offline Support
- Logging & Monitoring
- A/B Testing
- Testing
- Internationalization
- Localization
- Versioning
- PWA
- CI/CD

### 2. Scoping (Prioritization)
#### Functional
- Demand
- Module
  - Product Listing
  - Cart Page
  - Features
  - Search
  - Listing
  - Product Details
  - Reviews
  - Add Item to Cart/Wishlist
  - Cart List
  - Price Breakups
  - Add/Remove Products

#### Non-Functional
- Desktop
- Responsive
- Accessibility
- Asset Optimization
- CSR/SSR
- Caching

### 3. Tech Choices
- Library/Framework
- State Management
- Folder Structure
- Packages
- Dependencies (Canvas/SVG, WebRTC)
- Design System
- Build Tools (Webpack, Rollup, Parcel)

### 4. Component Architecture
- Component Hierarchy
- Routing
- Data Sharing

### 5. Data API & Protocols & Implementation
#### Protocols
- REST/GraphQL/SSE/rPF
- JSON/Protocol Buffers

## Requirements

### Functional
- **Demand/Supply**: Understanding what services or products the website will offer and the demand for them.
- **Module Level Thinking**: Breaking down the application into smaller parts, like:
  - **User Management**: Handling user accounts, registrations, and logins.
  - **Help & Support**: Offering customer service tools.
  - **Payment Gateway**: Processing payments.
  - **Pricing & Subscription**: Managing different pricing plans and subscriptions.
  - **Product Listing**: Showing a list of products or services.
  - **Cart Page**: A page where users can add items to purchase.
  - **Account Management**: Allowing users to manage their account settings.

### Non-Functional
- **Mobile/Desktop**: Ensuring the website works on both mobile devices and computers.
- **Responsive/Adaptive**: Designing the website to look good on any screen size.
- **Accessibility**: Making sure the website is usable by people with disabilities.
- **Asset Optimization**: Improving load times by optimizing images, CSS, and JavaScript files.
- **Performance**: Using metrics like FCP (how quickly the page shows content), LCP (how quickly the largest content item shows), TTI (how quickly the site becomes interactive), and Web Vitals (Google's metrics for a good user experience) to ensure the website is fast and responsive.
- **CSR/SSR**: Deciding between client-side rendering (CSR, where pages are generated in the browser) and server-side rendering (SSR, where pages are generated on the server).
- Other points cover security, the ability to work without an internet connection (offline support), logging and monitoring user actions, A/B testing (comparing two versions of a page to see which performs better), and internationalization (making the website usable in different countries).

## Scoping (Prioritization)

This section is about deciding what features are most important to work on first, including both functional and non-functional aspects.

## Tech Choices

These are decisions about the technical tools and frameworks to use, such as:
- **Library/Framework**: Choosing software like React or Angular to build the site.
- **State Management**: Tools for keeping track of user actions and data as they navigate the website.
- **Folder Structure**: How to organize the files that make up the website.
- **Build Tools**: Programs that help prepare the website for deployment to a server.

## Component Architecture

This refers to how the individual parts of the website (components) are organized and how they interact with each other.

## Data API & Protocols & Implementation

#### Protocols (How the website communicates with a server or other services):
- **REST/GraphQL/SSE/rPF**: Different ways of sending and receiving data.
- **JSON/Protocol Buffers**: Formats for structuring the data that's sent and received.

In web development, these points cover a wide range of considerations that affect both the creation and the operation of a site, from how it's built to how it feels to a user.
```