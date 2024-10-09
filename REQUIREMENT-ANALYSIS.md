# Ride Sharing Project - Requirement Analysis

## Overview

This project aims to create a platform where students in the same college can share rides to save money and contribute towards fuel costs. The platform is currently limited to bike riders but will extend to car rides later. Students booking autos or cabs can connect with bike owners for a ride, ensuring security and familiarity since all users belong to the same college.

## 1. User Roles and Profiles

### Riders (Bike Owners)

- Register with personal details, bike information, daily travel schedule, and routes.
- Set the number of available seats (currently defaulted to 1 for bikes).
- Specify fuel contribution expected from ride sharers.
- Update daily availability (e.g., vacation or unavailability).

### Ride Sharers (Students looking for rides)

- Register with personal details, preferred travel times, and routes.
- Browse nearby riders based on routes and schedules.
- Book rides, view ratings, and rate riders after the ride.
- Apply filters such as rider reviews, ride frequency, etc.

### Security and Verification

- Registration requires a valid college ID and email.
- Implement a verification system (e.g., OTP) tied to the college database.

## 2. Ride Scheduling and Matching System

- Matching algorithm that pairs riders and sharers based on proximity, time, and destination.
- Support for real-time matching for spontaneous or scheduled recurring rides.
- Riders can post one-time or recurring rides based on their travel schedule.

<!-- ## 3. Payment and Contributions
- A fuel-sharing mechanism calculates the contribution amount for each ride.
- Integration with payment gateways (UPI, PayTM, GPay) for cashless transactions.
- Dynamic fuel contribution calculation based on distance and fuel rates. -->

<!-- ## 4. Rating and Feedback
- After each ride, both the rider and sharer can rate each other.
- Future matches should avoid consistently low-rated riders. -->

## 5. Route and Map Integration

- Integration with Google Maps (or another map service) for route planning.
- Live traffic information to calculate estimated arrival times.
- Riders can set pickup and drop points on their routes.
- Real-time ride tracking for sharers to view their rider’s location.

## 6. Safety and Emergency Features

- In-app emergency contact for safety, notified during any issues.
- Share real-time ride tracking with friends or family during the ride.
- Enable anonymous reporting of inappropriate behavior.

## 7. Notification and Reminders

- Notify users about ride matches, upcoming rides, and cancellations.
- Reminders for recurring rides and approaching pickup points.

<!-- ## 8. Group Rides (Future Car Integration)
- In the future, support group rides for cars with multiple available seats.
- The system will allow multiple sharers for a single car ride. -->

## 9. Cost Efficiency and Eco-Impact Tracking

- Display metrics on cost savings and environmental impact (e.g., reduced carbon footprint, money saved).
- Motivational eco-badges for regular ride sharers.

## 10. Community and Social Features

- Introduce a community feature where users can connect, plan rides together, or join groups.
- A community board to post ride requests or share updates.

## 11. Additional Ideas

- **Carpool Events**: Organize ride-sharing events during festivals, exams, or special occasions.
- **Gamification**: Reward frequent or eco-conscious users with points or badges.
- **Sustainability Badge**: "Green Campus Ambassador" for regular ride sharers.
- **In-app Chat**: Allow users to chat to coordinate rides.
- **Referral Program**: Offer incentives for referring friends to join the platform.

## Current Limitations:

- Only bike rides with one seat are supported for now, but the system will be designed to scale for carpooling later.
