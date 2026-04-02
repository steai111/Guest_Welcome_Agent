# Guest Welcome Agent

Operational messaging agent designed to detect next-day check-ins, prepare personalized welcome messages in the guest’s language, and deliver ready-to-send outputs through Telegram for final WhatsApp handling.

*Pre-communication workflow built to reduce manual friction in hospitality guest messaging while preserving human control over final delivery.*

Guest Welcome Agent is a focused operational system created to simplify a recurring hospitality task: preparing welcome communication for guests arriving the following day.

The project does not send messages directly through WhatsApp.  
Instead, it automates the preparation layer: identifying relevant bookings, extracting guest details, generating a personalized welcome message, and delivering a ready-to-use output through Telegram so a human operator can complete the final sending step.

## What it does

- Accesses the management system calendar and detects next-day check-ins
- Selects only the bookings relevant to the chosen arrival date
- Extracts guest details such as name, phone number, and country context
- Prepares a personalized welcome message using the guest’s name
- Adapts the message to the language associated with the guest’s country of origin
- Sends the ready-to-copy message package through Telegram for final human handling on WhatsApp

## System structure

- **Booking detection layer**  
  The system accesses the calendar and identifies bookings with check-in scheduled for the following day.

- **Selection layer**  
  Only the reservations relevant to the target date are included in the workflow.

- **Message preparation layer**  
  Guest data is used to prepare a structured welcome message with personalized content and language adaptation.

- **Delivery layer**  
  The final output is sent to Telegram as a ready-to-use message package for manual WhatsApp sending.

## Why it matters

Guest messaging is an important part of hospitality operations, but preparing personalized messages every day can become repetitive and operationally inefficient.  
This project exists to automate the preparation phase while preserving human supervision over the final communication step.

Its value lies in reducing manual workload, improving consistency, and accelerating guest-contact workflows without forcing full communication automation.

## Operational logic

Guest Welcome Agent is built around a hybrid workflow:

- detect relevant arrivals
- prepare the right message
- adapt it to the guest context
- deliver it in ready-to-send form
- leave final message sending under human control

This makes it a strong example of operational augmentation rather than full replacement.

## Status

Active internal project with functioning booking detection, guest-data extraction, language-based message preparation, and Telegram delivery flow.  
The system is already operational as a practical support layer for hospitality guest communication.

## Scope

This project is designed as a focused internal workflow automation system for a specific hospitality communication task.  
It is not intended as a general messaging platform, but as a custom operational layer built around booking visibility, guest context, and structured pre-communication support.
