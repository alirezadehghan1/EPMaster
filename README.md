# EPMaster

---

EPMaster is a comprehensive application developed using MATLAB that streamlines supply chain management for companies sourcing engineering and manufacturing parts globally. The app integrates a robust backend architecture where CSV-based relational databases—such as Customer.csv and PI.csv—ensure data integrity through ACID-compliant transactions. By employing dynamic querying techniques, including real-time data filtering and joining across 15+ tables, EPMaster consistently provides live updates and reliable data synchronization. The system automates critical workflows like PI/CI generation, inquiry closure, and payment reconciliation, reducing manual tasks by up to 90% and maintaining efficient state management for order statuses (e.g., Open, PI Issued, Delivered).

On the frontend, EPMaster presents a user-friendly multi-tab interface built with MATLAB App Designer, incorporating over 50 interactive components such as dynamic dropdowns, date pickers, and collapsible panels. The intuitive design is complemented by role-based access control (RBAC) implemented via a secure login system that employs SHA-256 password hashing and session management with timer objects for auto-logout. This approach not only enhances security by restricting sensitive financial tabs to authorized users but also ensures that the user experience remains dynamic with real-time updates and global clock displays. Key technical contributions include modular OOP design for maintainability and efficient data handling techniques like batch processing that support high-volume datasets.

EPMaster also features advanced functionality that extends its usability across multiple aspects of supply chain operations. Notable features include:
- **Excel Automation**: Integration with MATLAB-Excel ActiveX to generate templated PI/CI documents with formatted headers, merged cells, and formulas.
- **Multi-Currency Support**: A built-in currency converter fetching live exchange rates for automatic recalculations (e.g., USD/EUR).
- **Error Handling & Robust Data Management**: Custom exceptions to manage edge cases, optimized CSV read/write operations, and state-machine logic for real-time updates across linked CSV tables.

The application further highlights its versatility with core developed features across different domains:
- **User System & Security**: Secure login/logout functionalities with SHA-256 hashing, session timeouts, and role-based UI rendering.
- **Procurement & Financial Workflows**: Automated inquiry management, streamlined invoice processes, payment logging with multi-currency support, and comprehensive reporting that exports detailed reports in Excel format.
- **Cargo and Reporting Management**: Coordination of shipments through conceptual carrier API integration, generation of packing lists, and detailed visualizations of payment timelines and order statuses using MATLAB tables and charts.

EPMaster stands as a testament to modern full-stack development in a MATLAB environment, achieving a balance between complex backend processes and an efficient, accessible frontend. Its modular design, efficient data handling, and user-centric features make it a versatile solution for tackling the multifaceted challenges of global supply chain management.

---
