# Privacy and Security

Privacy and security are major reasons builders compare local AI, cloud AI, and hybrid AI systems.

Where AI runs affects what data is exposed, who controls it, and how much risk the system creates.

## Core Idea

The more sensitive the data, the more carefully the system should decide where that data is processed.

Not every task should be sent to the cloud.

## Local AI Privacy

Local AI can keep sensitive information closer to the user.

This is useful for:

* Personal notes
* Private files
* Health information
* Financial records
* Internal business data
* Device context
* Long-term memory

## Cloud AI Risk

Cloud AI can still be safe, but it requires stronger boundaries.

Main concerns include:

* Sending unnecessary data
* Storing sensitive prompts
* Third-party provider dependency
* Compliance requirements
* Account or API exposure
* Data retention policies

## Hybrid Privacy Strategy

A hybrid system can reduce risk by only sending the minimum needed context to the cloud.

Example:

1. Keep full memory local.
2. Summarize only the necessary context.
3. Remove sensitive details.
4. Send limited context to the cloud.
5. Store final results locally.

## Builder Rule

Before sending data to a cloud model, ask:

**Does this model need the full data, or only a smaller version of it?**

## Core Takeaway

Good AI architecture is not just about capability.

It is about knowing what data should move, what data should stay private, and what data should never leave the device.
