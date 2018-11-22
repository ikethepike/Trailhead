# Trailhead

Trailhead is a rapid deployment, all-you-can-eat SCSS framework designed to allow you to hit the ground running in your projects.

## Structure

The framework is divided by hierarchy and function. First, the rules directory is initialized, it contains the key rules and functions to get Trailhead up and running.

## Rules

Rules contains everything you need to get your application styled right. It contains branding rules, like your color scheme, highlight and state specific application colors. It also contains a set of scaffolding rules, designed to enable you to quickly define and mark

**Structure**  
|- Rules (Main)  
|- Body  
|- Scroll  
|-- **Core Folder**  
|-- Core (Main)  
|-- Functions  
|-- Mixins  
|-- Reset  
|-- **Branding**  
|-- Borders  
|-- Branding (Main)  
|-- Colors  
|-- **Debugging**  
|-- Debugging (Main)  
|-- **Flow**  
|-- Breakpoints  
|-- Flow (Main)  
|-- Golden  
|-- **Gallery**  
|-- Animations  
|-- Filters  
|-- Gallery (Main)  
|-- Transitions  
|-- **Inputs**  
|-- Checkbox  
|-- Inputs (Main)  
|-- Text Inputs  
|-- Textarea  
|-- **Interactives**  
|-- Interactives (Main)  
|-- -- Buttons  
|-- **Scaffolding**  
|-- Dimensions  
|-- Flex  
|-- Grid  
|-- Legacy  
|-- Quick Classes  
|-- Scaffolding (Main)  
|-- Spacing  
|-- Transformations  
|-- **Text**  
|-- Anchor  
|-- Body Text  
|-- Fonts  
|-- Headings  
|-- HR  
|-- Labels  
|-- Text Classes  
|-- Text (Main)

### Core

Core initializes all the necessary functions and mixins, as well as performs a CSS reset.

### Branding

Branding contains all the necessary rules to create color palettes for your app, setting up highlight colors and setting the color scheme for error states [branding]. Also included are border rules [borders], and the ability to register first party color schemes as well as use established color schemes like Pantone and Flat UI Color, as well as the colors third party services like Facebook, Google or Twitter etc [colors].

### Debugging

Debugging contains a quick set of rules, designed to help you quickly and efficiently debug your styling, including features like wireframes, create grids overlays and device overlays [debugging].

### Flow

Flow contains the important rules that define how content, text and images, flow (width, height, margins) in the application [flow]. Here, you will also find the breakpoints of the app [breakpoints].

### Gallery

The gallery folder contains quick styling rules that can add effects or flair to the app. Animations contains some simple reusable animations [animations], while filters provides some quick filter classes [filters]. Here you can also define some default transition timings or functions [transitions].

### Inputs

Inputs contain styling rules for default input elements - such s checkboxes, text(ual) inputs, and textareas.

### Interactives

Interactives contain base styling rules for button elements (input[type="submit"], button, .button, a[role="button"]) [buttons].

### Scaffolding

Scaffolding are quick rules, designed to allow you to quickly mock up structures and templates in your app. It is not recommended that these are included in production, rather these are designed only to allow you to draft layouts and try them out, before defining custom styling rules. Dimensions define some quick, percentage based, widths and heights [dimensions]. Flex contains quick rules for flexbox [flex], grid contains basic grid styling rules [grid], legacy means that something has gone deeply wrong and you are forced to contend with IE-alpha-filter rules [legacy], quick classes are simple structural classes to hide, remove and set position rules [quick classes]. Spacing defines some customizable spacing rules, and provides quick rules for setting standardized spacing and margins [spacing]. Finally, transformation provides some quick and dirty transform rules [transformations].

### Text

Text provides essential text styling rules, such as anchor [anchor], body text [body-text], font imports both local and via Google fonts [fonts], heading rules [headings], horizontal rule styling [hr], label styling [labels], some simple text classes [text-classes], and the default import file [text].

## Hierarchy of code

Beyond the rules, the living heartbeat of Trailhead, code is structured into three tiers or levels. Starting off, we have elements which are specific elements, that are view-agnostic and are reusable anywhere, these may include application headers or footers. Views (pages), these are specific layouts or elements used only in a specific view or page. Finally, we have the broader templates which are highly reusable small template blocks, such as avatars, icons rules and blocks.

Included currently in templates are a few basic styling rules for avatars and icons, these are highly customizable, and hopefully usable in your rapp, should you need them. There are also some blocks, these are animated content blocks, that easily add some flair and movement to your app. These blocks have attached animations and have an slow ease in over multiple elements.

**Blocks**

1. Opacity blocks

   > Blocks that fade in with attached animation speeds.

2. Rotation blocks

   > Blocks that rotate in gradually

3. Slide blocks
   > Blocks that slide in from a set direction

In templates you will also find some simple shapes that you can use in your application, alongside some simple default rules to get article layouts working.

## Comments or suggestions

Trailhead is a work in progress, as of such, expect there to be some rough edges. Feel free to zip me any suggestions either on here, or zip me a message on [Twitter](https://twitter.com/ikethepike).

## Credits

I'd like to credit Niklaz Lönnqvist for helping to build up and stress test Trailhead. It's your baby too.
