# Development Proposal: Real-Time Manufacturing Status Dashboard

## Overview
This document outlines a proposal for the development of a real-time manufacturing status dashboard for **Daikibo**. This dashboard will provide a centralized view of the health status of the 9 machines in each of Daikibo’s 4 factories, enabling proactive monitoring and issue identification.  

The application will be accessible exclusively within Daikibo's intranet and will utilize their existing authentication system, providing a secure and seamless user experience.

---

## Scope
The primary function of this project is to create a **single-page dashboard** that displays the real-time status of all 36 monitored machines across Daikibo's four factories.  

### Key Functionalities
- **Machine Status**:  
  Each machine's current operational status (e.g., running, idle, error) will be displayed prominently, reflecting real-time telemetry data.

- **Factory/Device Hierarchy**:  
  The dashboard will utilize a collapsible/expandable structure, allowing users to view overall factory status and then drill down to individual machines.
  - **Factory level**: Displays aggregated status for all machines within a factory.  
  - **Device level**: Shows the detailed status of each machine, including a history of status changes.

- **Internal Access Only**:  
  The application will be accessible only through Daikibo’s intranet, ensuring data security and privacy.

- **Integrated Authentication**:  
  User authentication will be seamlessly integrated with Daikibo’s internal authentication server, leveraging existing company accounts.

- **Single-Page Interface**:  
  All functionality will be contained within a single, responsive web page for ease of use and navigation.

---

## Estimate

| Task | Estimated Hours |
|------|----------------|
| **Development** | 120 |
| Frontend Development (Dashboard UI) | 60 |
| Backend Development (API Integration and Data Handling) | 50 |
| Authentication Integration | 10 |
| **Testing** | 40 |
| Unit and Integration Testing | 20 |
| User Acceptance Testing | 20 |
| **Integration & Deployment** | 20 |
| **Total Estimated Man-hours** | 180 |

---

## Timeline

| Phase | Duration | Activities |
|-------|----------|------------|
| **Phase 1: Project Initiation & Setup** | 1 Week | Requirements Finalization and Environment Setup, Backend API development, Authentication integration |
| **Phase 2: Front-end Development** | 4 Weeks | Develop the dashboard UI, including status displays and the collapsible/expandable structure; Implement data visualizations |
| **Phase 3: Testing** | 2 Weeks | Rigorous testing of the system, including unit tests, integration tests, and user acceptance tests |
| **Phase 4: Integration and Deployment** | 1 Week | Deployment within Daikibo’s intranet and final review |

**Total Estimated Timeline:** 8 Weeks

---

## Support
We are committed to providing ongoing support for the dashboard, including:
- Bug fixes and issue resolution as they arise.
- Support through a dedicated support ticket system.
- Discussions regarding new functionalities and enhancements to improve the tool over time.

---

We are confident that this project will provide Daikibo with an effective real-time monitoring solution and are eager to begin work. Please do not hesitate to reach out with any questions or to discuss this proposal further.
