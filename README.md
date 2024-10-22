# Opendesk for Confidential Hyperscaler Deployment 

Opendesk is a software suite designed for public administration and organizations seeking a sovereign workplace solution. It offers a range of office applications for daily tasks, including word processing, collaboration tools, shared file storage, video conferencing, chat, and project management.   

Key features of Opendesk include:

- Office Applications: Provides essential tools like word processing, spreadsheets, presentations, and email.   
- Collaboration Tools: Enables seamless teamwork with features like shared calendars, document sharing, and video conferencing.   
- Project Management: Helps plan and manage projects efficiently using Kanban boards, Gantt charts, and task management tools.   
- Knowledge Management: Facilitates the creation, collection, and sharing of knowledge and processes within organizations.   
- Security and Privacy: Prioritizes data security and privacy by being open-source and offering control over data storage and access.

Opendesk aims to reduce dependency on proprietary software and promote digital sovereignty.

It is a comprehensive solution that can be tailored to the specific needs of public administration and organizations seeking a secure and independent workplace. 

## Goal

This repo is intended for bootstrapping Opendesk in a confidential VM on Azure, GCP or AWS. Main emphasis is always given to:

- hyperscaler deployment such that the hyperscaler has not access to Opendesk and its storages
- key, identity and access management seperated from the hyperscaler
- optimised boot and installation time (currently: around 40 min)

## Versioning
Each OpenDesk version is stored in the corresponding branch:
- [v1.0.0](https://github.com/enclaive/enclaive-helm-opendesk/tree/v1.0.0)
