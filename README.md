QB-Phone - NoPixel 4.0 Style
    A FiveM QBCore phone resource with NoPixel 4.0 style improvements and job system fixes.

🚨 Fixed Issues
    Job System Fix: Resolved the local FirstStart = true initialization issue

    Job Integration: Properly configured for Police, Ambulance, and Mechanic jobs

    Lawyer System: Added comprehensive lawyer job functionality

🛠️ Features
    Core Fixes
    Fixed job initialization sequence

    Resolved FirstStart variable handling

    Improved job assignment logic

    Enhanced job permission system

    Job Systems
    Police Job: Complete police department integration

    Ambulance Job: EMS and medical services functionality

    Mechanic Job: Vehicle repair and customization services

    Lawyer Job: Legal services and court system integration

    Phone Features
    NoPixel 4.0 styled interface

    Contact management

    Messaging system

    Banking integration

📁 Installation
    Download the resource

bash
`cd [resources]
git clone [repository-url] qb-phone
Database Setup `

sql
`-- Import the provided SQL file
source qb-phone.sql
Configuration`

lua
`-- Ensure proper job configuration in qb-core
Config.Jobs = {
    ['police'] = true,
    ['ambulance'] = true,
    ['mechanic'] = true,
    ['lawyer'] = true
}`
Start the resource

lua
`-- Add to server.cfg
ensure qb-phone`
