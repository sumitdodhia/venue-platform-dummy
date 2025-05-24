
# FindToTable - Venue Bid Platform

## Product Overview

FindToTable is a B2B platform that connects corporate clients with venue suppliers (hotels, restaurants, and conference venues). The platform streamlines the process of finding and booking venues for corporate events, meetings, and accommodations through a unique bidding system.

### Key User Types

1. **Corporate Clients**: Businesses looking to book venues for events, accommodations, or dining
2. **Suppliers**: Hotels, restaurants, and conference venues looking to fill their spaces

## Core Features

### For Corporate Clients

- **Enquiry Submission**: Create detailed requests for venues based on specific requirements
- **Venue Marketplace**: Browse and filter venues by category, location, and amenities
- **Bid Management**: Review, compare, and accept venue proposals
- **Booking History**: Track past and upcoming bookings

### For Venue Suppliers

- **Venue Management**: Add and manage venue listings with detailed information
- **Enquiry Dashboard**: View and respond to client enquiries
- **Bid Submission**: Create competitive offers for client requests
- **Analytics**: Track performance metrics and booking trends

## Product Flow

### Corporate Client Journey

1. **Registration/Login**: Corporate users register or log in to the platform
2. **Browse Venues**: Explore the marketplace to find suitable venues
3. **Submit Enquiry**: Create a detailed request with specific requirements:
   - For Rooms: Dates, number of rooms, location, etc.
   - For Conferences: Date, attendee count, setup requirements, etc.
   - For Restaurants: Date, party size, cuisine preferences, etc.
4. **Review Bids**: Receive and compare proposals from interested venues
5. **Accept Bid**: Select the most suitable offer
6. **Manage Booking**: Track reservation details and communicate with the venue

### Supplier Journey

1. **Registration/Login**: Venue owners register their business
2. **Create Venue Profiles**: Add venues with detailed information:
   - For Hotels: Room types, amenities, availability, etc.
   - For Conference Spaces: Capacity, layout options, equipment, etc.
   - For Restaurants: Dining sections, menu options, private dining capabilities, etc.
3. **Monitor Enquiries**: View incoming client requests
4. **Submit Bids**: Create customized proposals for client enquiries
5. **Track Responses**: Monitor client interactions with submitted bids
6. **Manage Bookings**: Handle confirmed reservations

## Technical Architecture

- **Frontend**: React with TypeScript, Tailwind CSS, and Shadcn UI components
- **Backend**: Supabase for authentication, database, and storage
- **Database Structure**:
  - Users and profiles
  - Venues and venue-specific details
  - Enquiries with category-specific details
  - Bids and responses

## Key Workflows

### Enquiry Submission Flow

1. Client fills out category-specific enquiry form
2. System stores enquiry details in database
3. Relevant suppliers are notified
4. Enquiry appears in supplier dashboards

### Bid Response Flow

1. Supplier views enquiry details
2. Supplier creates customized bid with pricing and availability
3. Bid is submitted to client
4. Client receives notification of new bid
5. Client can review and compare multiple bids

### Booking Confirmation Flow

1. Client selects preferred bid
2. System notifies supplier of acceptance
3. Booking details are confirmed
4. Both parties can communicate further details

## Development Roadmap

- Phase 1: Core platform with basic enquiry and bid functionality
- Phase 2: Enhanced supplier profiles and advanced filtering
- Phase 3: Payment processing and automatic confirmations
- Phase 4: Reviews, ratings, and reputation system
- Phase 5: Mobile application and advanced analytics

## Getting Started

To run the project locally:

```sh
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd findtotable

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Project Structure

- `/src/components`: UI components organized by feature
- `/src/pages`: Main application pages and routes
- `/src/services`: API services and data fetching
- `/src/hooks`: Custom React hooks
- `/src/types`: TypeScript type definitions

## Deployment

The application is deployed using Lovable's built-in deployment tools. To deploy updates:

1. Click on "Publish" in the Lovable interface
2. Configure deployment settings if necessary
3. Confirm deployment

## Support and Documentation

For more information or support, please contact the development team or refer to the internal documentation.

