# Mobi-e-rides

**Business Analysis & Process Modeling**

## Overview

Mobi-e-rides is a fictional e-bike rental startup serving residents and tourists. This academic case study applies core business analysis techniques to a proposed rental service in which customers check bike availability, reserve and pay, then collect and return a bike with employee assistance.

## Analysis scope

- Stakeholder identification and interview questions
- MoSCoW prioritization of launch requirements
- Requirements traceability
- Proposed requirements workshop, observation and customer survey
- Three complementary models: data structure, system interactions and rental process
- Basic systems analysis, risks and validation considerations

## Core requirements

| ID | Requirement | Model connection |
|---|---|---|
| REQ-01 | Easy booking | Reserve bike; Customer and Rental records |
| REQ-02 | Payment processing | Pay rental; payment status in Rental |
| REQ-03 | Bike availability tracking | View and update availability; Bike status |

## Models

### 1. Use Case Diagram

Shows how the Customer and Employee interact with the Mobi-e-rides rental system. The customer participates in the return, while the employee records receipt in the system.

<p align="center">
  <img src="assets/use-case-diagram.png" width="100%" alt="Mobi-e-rides use case diagram">
</p>

### 2. Entity Relationship Diagram (ERD)

Defines the Customer, Bike and Rental entities, including their primary and foreign keys and relationships.

<p align="center">
  <img src="assets/entity-relationship-diagram.png" width="100%" alt="Mobi-e-rides entity relationship diagram">
</p>

### 3. Rental Process Flowchart

Maps the rental journey from bike selection through payment, handover, return and availability update. It includes alternative paths for an unavailable bike and a rejected payment.

<p align="center">
  <img src="assets/rental-process-flowchart.png" width="100%" alt="Mobi-e-rides rental process flowchart">
</p>

## Project file

[Download the full case study (PDF)](docs/mobi-e-rides-business-analysis.pdf).

## Academic context

This is a proposed design exercise, not a live service or implementation. Interviews, workshops, observation and surveys are suggested analysis activities; they have not been conducted. No research findings or operating results are claimed.

The case adapts the IBM Business Analysis and Modeling for an eBike Rental Startup exercise using my own stakeholder questions, priorities and rental models.
