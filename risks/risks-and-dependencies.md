# Risks and Dependencies

This document records known product risks and dependencies for Smart Parking.

It is intentionally incomplete and should evolve as the product develops.

---

# Known Risks

## Sensor Accuracy

We do not yet know whether the available parking sensors provide the level of accuracy required by users.

### Potential Impact

Incorrect availability information could reduce user trust and lead to poor decisions.

### Status

Open

### Questions

- What is the current sensor accuracy?
- How frequently is data updated?
- How are sensor failures detected?

---

## Reservation No-Shows

If reservations are introduced, unused reservations may reduce the perceived availability of parking spaces.

### Potential Impact

The system may show little or no availability while physical spaces are actually empty.

### Status

Open

### Questions

- How should no-shows be detected?
- Should reservations expire automatically?
- Is a grace period required?

---

# Known Dependencies

## Parking Sensor Data

Real-time parking availability depends on access to reliable sensor data.

### Dependency Type

Technical / Data

### Current Status

To be validated

### Questions

- Which system owns the sensor data?
- Is there an API or another integration mechanism?
- What is the expected update frequency?

---

## Security Systems

Some parking flows may depend on existing vehicle access and security systems.

### Dependency Type

Technical / Operational

### Current Status

To be investigated

### Questions

- Is vehicle identification already available?
- Which security policies apply?
- Would Smart Parking need to integrate with access control?

---

# Areas to Be Investigated

Additional risks and dependencies should be identified as the product evolves.

Topics that may require further analysis include:

- privacy and vehicle-related personal data;
- accessibility requirements;
- reliability of real-time information;
- visitor parking;
- behavior during sensor or system outages;
- operational ownership;
- integration with existing office systems.

---

# Working Agreement

AI may help identify possible risks and dependencies by analyzing:

- Product Vision
- Business Goals
- User Research
- Backlog items
- Existing risks and dependencies

AI-generated risks should be treated as suggestions.

A human should review whether they are relevant, valid, and worth tracking.
