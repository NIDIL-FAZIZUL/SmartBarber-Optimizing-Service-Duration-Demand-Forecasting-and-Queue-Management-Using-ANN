# User Stories

Format: As a student, I want to make my final year project, so that i can grade on my csp600 project.

1. As a customer, I want to view my live queue position and estimated wait time on my mobile device, so that I do not have to wait aimlessly inside the barbershop and can better manage my schedule.

Linked Requirement: FR1 (The system shall provide a live queue tracking dashboard that displays estimated wait times and real-time position updates for customers in line).

Acceptance Criteria:
i. Given a customer is in the queue, when they open the live tracking screen, the system must display their current numerical position (e.g., #3 in line) and an estimated time remaining in minutes.
ii. Given the customer's position in line changes, when a barber completes a service, the position number and estimated wait time must update automatically on the user's interface without manual refresh.



2. As a customer, I want to filter and search for barbers based on their style expertise, pricing, and availability, so that I can select and book a stylist who matches my specific haircut preferences and budget.

Linked Requirement: FR2 (The system shall allow customers to search, filter, and select barbers based on specific style expertise, pricing tiers, and real-time availability).

Acceptance Criteria:
i. Given a customer applies a filter for a specific hair style (e.g., "Fade Specialist") and price tier, the system must display only the barbers who match all selected criteria.
ii. Given a customer selects a filtered barber profile, the system must display that barber's real-time schedule, rating, and available booking slots.



3. As a barber, I want to update my current appointment status and adjust service durations in real time, so that the system can calculate accurate wait times and prevent scheduling overlaps during peak hours.

Linked Requirement: FR4 (The system shall enable barbers and shop managers to update appointment statuses, manage daily walk-ins, and reassign appointments dynamically).

Acceptance Criteria:
i. Given a barber is starting or finishing a haircut, when they tap "Start Service" or "Complete Service" on their dashboard, the system status must immediately update for that queue slot.
ii. Given a service takes longer than expected, when the barber extends the slot duration, the system must automatically recalculate and adjust the estimated wait times for all subsequent clients in that barber's queue.
