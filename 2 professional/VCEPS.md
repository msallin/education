# Project VANTAGE – Vehicle Command and Event Processing System (VCEPS)

## Background

European municipalities are deploying semi-autonomous service vehicles (patrol cars, inspection drones, etc.).  
Field trials revealed delays in command execution, data loss, and fragmented monitoring.  
VCEPS will provide centralized, reliable, and responsive command, data collection, and analytics for the fleet.

## Purpose

- Real-time vehicle command execution  
- Reliable telemetry capture and storage  
- Historical insights and behavior analytics  
- Dashboards and alerts for fleet activity

## Users

- **Operators** – send commands via desktop app  
- **Fleet managers** – monitor status and performance  
- **City analysts** – analyze trends and optimize deployment

---

## Requirements

### 1. Vehicle (Simulated in .NET Console App)

- Communicate with Vehicle Control via MQTT v5  
- Receive and execute commands **exactly-once** (QoS + deduplication)  
- Send telemetry events (position, speed, state) **at-least-once** (QoS + outbox pattern)  

### 2. Vehicle Control (.NET WinForm App)

- Maintain vehicle registry in a key-value store (metadata in JSON)  
- Allow operators to send commands to registered vehicles (**exactly-once** over MQTT)  
- Receive vehicle events (**at-least-once**) and forward to Kafka (**at-least-once**)  

### 3. Vehicle Data Collector (.NET Console App)

- Consume events from Kafka (**at-least-once** processing)  
- Store events and current state in a document database (1 document per vehicle)  
- Store time-series event data in a time-series database  

### 4. Vehicle Intelligence Central (Razor Page Web Application)

- Render a time chart for a selected vehicle based on stored telemetry
