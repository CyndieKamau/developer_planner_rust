# A developer-centric Planner Desktop Application built with 🦀 Rust 🦀

## Introduction

Developer Planner is a desktop GUI application built with Rust, designed to streamline the workflow of developers by integrating essential tools and services directly into their desktop environment. 

This application focuses on providing a centralized platform for managing tasks, meetings, and notifications, enhancing productivity and organization for software developers.

## Features 

- **Calendar Integration:** Seamlessly connect with Google Calendar to view and manage your meetings and events. Stay on top of your schedule without leaving your development environment.
- **Email Notifications:** Get notified about important emails directly within the planner. Supports filtering notifications from specific sources such as work emails or GitHub.
- **GitHub Integration:** Keep track of your repositories, pull requests, and issues. The GitHub API integration allows developers to stay updated on their projects and collaborate effectively.
- **IDE Integration:** Direct integration with VSCode, enabling developers to open and manage their codebase and tasks within their preferred development environment.
- **Customizable GUI:** A user-friendly interface with customizable components to tailor the planner to your workflow. Includes features like task prioritization, project milestones, and daily stand-ups.


## Usage

- 🗓️ **Calendar View:** Access your daily, weekly, or monthly schedule through the calendar integration.
- 🔄 **Task Management:** Create, prioritize, and track progress on tasks and projects directly within the planner.
- 📩 **Email Alerts:** Customize which email notifications you receive, ensuring you never miss important communications.
- 💻 **GitHub Dashboard:** View your active pull requests, issues, and repository notifications in one place.
- 🔌 **IDE Shortcuts:** Use the planner to open projects and files in VSCode, streamlining your development process.


## Current Project Setup

```
.
├── Cargo.toml
├── src
│   ├── calendar
│   │   ├── google_calendar.rs
│   │   └── mod.rs
│   ├── email
│   │   ├── gmail_api.rs
│   │   └── mod.rs
│   ├── github
│   │   ├── github_api.rs
│   │   └── mod.rs
│   ├── gui
│   │   ├── components
│   │   ├── mod.rs
│   │   └── window.rs
│   ├── ide
│   │   ├── mod.rs
│   │   └── vscode.rs
│   ├── main.rs
│   └── utils
│       └── mod.rs
└── tests
    ├── calendar_tests.rs
    ├── email_tests.rs
    ├── github_tests.rs
    ├── gui_tests.rs
    └── ide_tests.rs

```