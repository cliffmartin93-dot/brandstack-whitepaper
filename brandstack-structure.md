---
title: BrandStack Structure
nav_order: 2
---

# BrandStack Structure

BrandStack is designed as a structured brand infrastructure rather than a collection of documents or assets.
Instead of storing brand guidelines in static files, BrandStack organizes every component of a brand into a connected system that teams can navigate, update, and use in real time.

At its core, BrandStack separates brand information into structured layers. Each layer represents a fundamental part of how a brand operates, ensuring clarity, consistency, and scalability as organizations grow.

This structure allows companies to move beyond static brand guidelines and manage their brand as a living system.
## Brand Architecture

Every brand inside BrandStack is structured through a modular architecture. Each component of the brand is stored as its own structured object, allowing teams to manage brand elements independently while maintaining overall consistency.
This architecture enables teams to quickly access the exact piece of brand information they need without navigating long documents or outdated folders.
## BrandStack System Example

Example of how a real brand could be structured inside BrandStack.

```
Brand: Nike

Brand_Foundation
  mission: "Bring inspiration and innovation to every athlete"
  positioning: "Performance-driven sports brand"
  values: ["Innovation", "Athletic excellence", "Inspiration"]

Visual_Identity
  logo: nike_swoosh.svg
  primary_color: #111111
  secondary_color: #FFFFFF
  typography: Nike Futura

Brand_Guidelines
  logo_usage: "Maintain clear space around logo"
  color_rules: "Use black as primary brand color"
  tone_of_voice: "Motivational and empowering"

Assets
  logos/
  templates/
  social_media_assets/
  marketing_materials/

Team_Access
  designers
  marketing_team
  external_agencies
```
• A brand is structured as a system rather than a document
• Each element of the brand is stored as a structured object
• Teams can access brand foundations, visual identity, and assets in one place
• Brand decisions become easier because the information is organized and searchable
Instead of static PDFs, BrandStack creates a living brand system teams can actually operate with.
## Brand Documentation Layer

BrandStack allows teams to document the reasoning behind brand decisions directly within the system. Instead of storing explanations in long guideline documents, BrandStack attaches contextual notes and usage rules directly to brand elements.
This ensures that every designer, marketer, and partner understands not only what the brand is, but why certain decisions exist.
### Single-line example

```
Brand_Color.primary = "#0A0A0A"   // Primary brand color used for main interfaces
Brand_Color.secondary = "#F5F5F5" // Neutral background color
```
### Multi-line comment example

```
/*
Brand Voice Guidelines

Tone: Confident and clear
Personality: Modern, intelligent, minimal
Avoid: Corporate jargon and overly technical language

Used across:
• Website copy
• Marketing campaigns
• Product messaging
*/
```
## Structured Brand Elements 

BrandStack treats brand elements as structured objects within the system.
Each component of a brand — such as colors, typography, logos, and messaging — is stored as a defined entity with attributes and usage rules.
This structured approach allows teams to update brand components without rewriting entire guideline documents.
### Brand Element Definitions

```
Brand_Color.primary   = "#000000"
Brand_Color.secondary = "#FFFFFF"

Brand_Font.primary    = "Inter"
Brand_Font.secondary  = "Roboto"

Brand_Logo.primary    = "logo_main.svg"
Brand_Logo.mark       = "logo_mark.svg"

Brand_Tone            = "Clear, confident, minimal"
Brand_Positioning     = "Modern brand infrastructure platform"
```
Foundational Elements – Mission, positioning, and brand narrative
Identity Elements– Logos, colors, typography, and visual assets
Communication Elements – Tone of voice and messaging rules
Operational Elements – Templates and reusable brand assets
## Brand Naming Standards

Brand elements must follow clear naming conventions
Each element belongs to a defined category (color, font, asset, guideline)
Names are consistent across teams and systems
Structured naming enables searchability and automation
## Brand Data Types 

BrandStack treats brand information as structured data rather than static documents.
Each component of a brand — from colors and logos to messaging and assets — is stored as a defined data type within the system.
This approach allows teams to organize, retrieve, and update brand information efficiently while maintaining consistency across the organization.
## Core Brand Data Types 

BrandStack organizes brand information into several foundational data categories:
Brand Foundations – mission, vision, positioning, and values
Visual Identity – colors, typography, logos, and design elements
Messaging & Voice – tone, brand voice, and narrative
Brand Guidelines – rules governing how brand elements should be used
Assets – templates, marketing materials, and design files
Team Permissions – access controls for internal teams and external partners

Example:
Brand_Foundation {
    mission: "Define the long-term purpose of the brand"
    positioning: "Modern brand infrastructure platform"
}

Brand_Color {
    primary: "#000000"
    secondary: "#FFFFFF"
}

Brand_Font {
    primary: "Inter"
    secondary: "Roboto"
}

Brand_Tone {
    style: "Clear, confident, minimal"
}
## Extended Brand Structures

Some brand elements depend on multiple connected data components. BrandStack organizes these complex elements into structured relationships.
Brand Guidelines Sections – logo usage, typography rules, and color systems.
Asset Libraries – organized collections of brand files and templates.
Campaign Templates – reusable marketing frameworks.
Team Workspaces – environments where teams interact with the brand system.
Example:
### BrandStack System Objects Example

```
Brand {
    name: "Example Company"
}

Brand_Guideline_Section {
    section: "Logo Usage"
    rules: ["Clear space", "Minimum size", "Background control"]
}

Asset_Library {
    logos: ["logo_primary.svg", "logo_mark.svg"]
    templates: ["presentation_template.fig", "social_template.psd"]
}

Campaign_Template {
    name: "Product Launch"
    assets_required: ["logo_primary.svg", "brand_colors", "headline_style"]
}

Team_Workspace {
    designers: ["Design Team"]
    marketing: ["Marketing Team"]
    partners: ["External Agencies"]
}
```
## Brand Operations

BrandStack enables teams to interact with brand infrastructure through a set of core operations.These operations allow teams to manage brand elements, update guidelines, distribute assets, and maintain consistency across the organization.
## Brand Creation Operations

BrandStack allows teams to define and create new brand elements inside the system.

### Creating a Brand in BrandStack

```
Create Brand

Brand.name = "Example Company"

Create Brand_Color
primary_color = "#000000"
secondary_color = "#FFFFFF"

Create Brand_Font
primary_font = "Inter"
secondary_font = "Roboto"
```
## Brand Validation Operations

BrandStack ensures that brand usage follows predefined guidelines.
The system helps teams validate whether assets and design decisions comply with brand rules.
### Brand Guideline Validation Example

```
Validate Logo Usage

if (logo_size < minimum_size) {
    show_warning("Logo size below recommended minimum")
}

if (background_color == restricted_color) {
    show_warning("Logo cannot be used on this background")
}
```
## Brand Distribution Operations

BrandStack enables teams to distribute brand assets and guidelines across departments and external partners.

### Sharing Brand Assets

```
Share Asset Library

Share.logo_files → Design Team
Share.brand_guidelines → Marketing Team
Share.templates → External Partners
```
## The Broken State of Brand Management

Most companies manage their brand through a fragmented collection of documents, folders, and outdated guidelines.
Brand assets are often scattered across cloud drives, design tools, and internal documentation. Teams rely on static PDF brand guidelines that quickly become outdated or difficult to navigate.
As organizations grow, maintaining brand consistency becomes increasingly difficult.
Designers recreate assets that already exist.
Marketing teams improvise brand usage.
External partners receive incomplete brand documentation.
The result is a brand that slowly loses clarity and consistency across touchpoints.
## Common issues organizations face include:

```
• Brand guidelines buried in static PDFs
• Assets scattered across multiple platforms
• Designers guessing logo usage rules
• Marketing teams using outdated brand files
• External partners lacking clear brand direction
```

Without a structured system, managing a brand becomes an operational challenge rather than a strategic advantage.
BrandStack was built to solve this problem by transforming brand guidelines into an interactive brand infrastructure.


