# System Design Challenge: Notification Event System

Prompt

Your company wants to build a notification system that allows businesses to subscribe to important updates occurring within their operations. You have been assigned the task of designing and leading the implementation of this notification system.
Businesses need to subscribe to notifications to get updates when key operational events occur.

 The notification payload should include:
    - The event type and timestamp.
    - Information about the affected resource (e.g., order ID, customer ID).
    - Additional metadata related to the event.


Your goal is to design a scalable and reliable notification system that can support multiple businesses subscribing to different event types. Consider how you would handle authentication, retries, and failures.

What We Want to Cover

Application Design: Architecture, components, and API structure.
Scalability: Handling multiple businesses, event processing at scale.
Quality and Reliability: Ensuring message delivery, retry mechanisms, and security.

Guiding Questions


System Architecture

How would you structure the system to support notification subscriptions?
What key components (e.g., event bus, message queue, database) would you use?


API Design

What endpoints would you expose for businesses to subscribe to notifications?
How would you handle authentication and authorization?

Event Processing

How will you ensure that notification events are processed and delivered reliably?
What mechanisms will you use to prevent data loss?

Scalability Considerations

How would your system handle a sudden spike in notifications?
How do you ensure high availability and fault tolerance?

Failure Handling & Security

How will you manage retries and failed deliveries?
What security measures should be in place to prevent abuse and unauthorized access?

Bonus

If you have time, implement a basic API design for the notification subscription system, including:
A RESTful or GraphQL API for subscribing to notifications.
A mechanism for event producers to trigger notifications.
A retry mechanism for failed deliveries.

Evaluation Criteria

Clarity of thought: How well-structured and reasoned is the design?
Scalability & reliability: Can the system handle increasing load and failures?
Technical depth: Use of best practices, appropriate technologies, and trade-offs considered.
Communication: How well can the candidate explain their design and decision-making?