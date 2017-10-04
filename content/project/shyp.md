---
title: Bridge
company: Shyp
image: https://res.cloudinary.com/jobdoc/image/upload/t_project_tile/Bulk_label_print_e0xvyt.jpg
date: 2017-06-01
---

> A month long engagement porting a mission-critical operations application from Angular to React / Redux.

## The brief

Shyp had recently moved it's customer-facing site to React and Redux and wanted stack consistency between their customer-facing site and their operations application. I was hired on as a contractor to port the operations application from Angular to React and Redux.

The operations application is used by Shyp's courier, warehouse and packing teams on a daily basis to track and manage shipments, pickups and items. The application is used in each of Shyp's warehouses by the local operation team. 

All in all, Shyp needed about thirty pages ported and improved.

## Scoping

The engagement began with an in-person meeting to tour through the existing application, to obtain credentials and to get a sense for how the operations team functioned.

The Shyp team outlined the pages to convert and their associated links in a Google Document for the existing application.

I broke down the pages by the features they contained—filtering, pagination, sorting, CRUD controls, etc—and from there we established the timeline. Holistically understanding the feature set, later, helped me abstract the functionality into reusable components and higher order functions.

## Implementation

We began by establishing the communication protocol. The aforementioned Google Doc served as a roadmap. A Slack channel with various stakeholders worked as a way to collect quick feedback and an open forum to ask questions. A Github project board allowed myself, the project management team and QA to add and triage importance of development tasks. As pages and functionality were completed tasks would move across the board and would be indicated as complete in the Google Doc. Each invoice came with a summary of how many hours I had worked and what exactly those hours were spent doing.

The conversion was started by their internal team so a basic scaffolding and style guide was in place. 

### Deliverables
- 30 fully-functional converted pages
- Revised state management system
- Redux middleware for http calls to the backend
- Higher order component for handling and displaying tabular data
- Documentation
- A variety of additional React components
- Architectural feedback and recommended next steps

### Technologies used 
- Redux
- Redux-saga
- React
- Webpack
- Lodash
