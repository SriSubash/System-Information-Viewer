# System-Information-Viewer

The System Information Viewer (SIV) Java project is a software application designed to display detailed information about the hardware and software components of a computer system. This type of application is useful for system administrators, developers, and tech enthusiasts who need to monitor and understand the specifics of their computer systems.

# Key Features
# Hardware Information:

CPU: Model, speed, cores, threads.
Memory: Total, used, available memory.
Storage: Information about hard drives and SSDs, including total and available space.
Network: Details about network interfaces, IP addresses, and connection status.
GPU: Information about graphics cards and their capabilities.

# Software Information:

Operating System: Name, version, architecture.
Java Runtime: Version, vendor, and runtime details.
Installed Software: List of installed applications and their versions.
Processes: Currently running processes and their details.

# System Monitoring:

Resource Usage: Real-time monitoring of CPU, memory, and network usage.
Event Logs: Access to system event logs for troubleshooting.
Temperature Monitoring: Readings from system sensors for CPU and GPU temperatures.

# Architecture and Design

The SIV Java project typically follows a modular architecture, allowing for easy maintenance and extension. Key components might include:

# Data Collection Modules:

These modules interact with the underlying operating system and hardware to gather information. For instance, on Windows, you might use the WMI (Windows Management Instrumentation) API, while on Linux, you might use /proc and /sys file systems.

# Core Logic:

The central part of the application where data processing and management occur. This might include classes for handling different types of information and utilities for converting raw data into human-readable formats.

# User Interface:

A graphical user interface (GUI) built using Java's Swing or JavaFX libraries. This component is responsible for displaying the collected information in an organized manner, providing charts, tables, and other visualization tools.

# Utility Libraries:

These include third-party libraries and custom utilities for tasks such as JSON parsing, file I/O, and network communication.
Example Technologies and Libraries
Java Development Kit (JDK): The base platform for writing and running the application.
Swing/JavaFX: For creating the graphical user interface.
JNA (Java Native Access): For accessing native system APIs.
OSHI (Operating System and Hardware Information): A Java library that provides cross-platform access to system information.
SLF4J (Simple Logging Facade for Java): For logging application events.
