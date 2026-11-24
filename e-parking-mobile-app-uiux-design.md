# Portfolio Project Data — E-Parking Mobile App UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/e_parking_mobile_app/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image02.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "e-parking-mobile-app-uiux-design",
  "code": "PRO-02 // UX-02",
  "title": "E-Parking Mobile App UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/E-Parking-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "banner": "/images/projects/e_parking_mobile_app/banner.webp",
  "summary": "Mobile UI/UX design for real-time parking discovery, floor-by-floor slot booking, active session countdown tracking, and streamlined digital checkout.",
  "projectDescription": "A high-fidelity mobile UI/UX concept simplifying urban parking discovery, bay reservation, live session tracking, and payment checkout. Built over a city map with dark-navy modal sheets and semantic status badges, it guides drivers from finding garages to reserving exact floor slots.",
  "architectureSummary": "Persistent five-tab bottom navigation anchoring a six-screen map-to-checkout reservation flow",
  "techStack": [
    "Figma",
    "WebP"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile App UI/UX Design",
    "targetPlatform": "iOS and Android Mobile",
    "primaryDomain": "Smart Mobility and Urban Parking",
    "architecturePipeline": "Map Discovery to Bay Checkout Flow",
    "testingAndAudit": "Visual Hierarchy Review",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "platformType": "iOS and Android Mobile App",
    "designRole": "UI/UX Designer",
    "targetIndustry": "Smart Mobility & Urban Parking",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Drivers in dense urban commercial districts often face uncertainty over nearby garage vacancy, transparent hourly rates, and specific bay locations before arriving. This design concept consolidates map-based discovery, upfront facility metadata, floor-grid slot selection, and live session tracking into one mobile flow.",
  "uiUxUserResearch": {
    "keyFindings": [
      {
        "method": "Urban Wayfinding Domain Framing",
        "description": "Evaluated typical multi-step parking workflows from street-level destination search through garage entry, bay selection, and exit payment.",
        "keyFinding": "Drivers need immediate EMPTY/FULL vacancy cues, upfront hourly IDR rates, and exact bay labels (e.g., B03) prior to arrival.",
        "badge": "Vacancy Transparency"
      },
      {
        "method": "Active Session Continuity Analysis",
        "description": "Examined post-booking touchpoints where parkers verify active tickets, monitor elapsed durations, and locate support contacts.",
        "keyFinding": "Keeping ticket IDs, live counters, parked slot diagrams, and an officer contact button in one modal reduces checkout friction.",
        "badge": "Session Visibility"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Urban Mall Visitor",
      "role": "Daily Private Vehicle Commuter",
      "demographics": "Adults 22–45 navigating commercial city centers via smartphone",
      "quote": "I want to confirm an open spot near my destination, pick a convenient bay, and see exact hourly pricing before driving in.",
      "painPoints": [
        "Arriving at commercial garages only to discover all floors are full",
        "Unclear parking tariffs and forgotten bay locations after shopping"
      ],
      "goals": [
        "Compare nearby open parking venues with instant EMPTY/FULL badges",
        "Reserve a specific floor and slot while tracking elapsed parking time"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "A five-tab bottom navigation bar (Menu, Reservation, QR Code, Favorite, Notification) anchors the experience over a live city map, keeping the six-step Reservation flow accessible within layered dark-navy modal cards without losing geographic orientation.",
    "nodes": [
      {
        "section": "Reservation (Core Flow)",
        "screens": [
          "Interactive Map Discovery",
          "Nearby Parking Availability List",
          "Parking Area Details & Duration",
          "Book Parking Slot (Floor & Bay Grid)",
          "Booked Slot & Live Counter",
          "Payment Summary & Checkout"
        ]
      },
      {
        "section": "Menu",
        "screens": [
          "Application Hub & Quick Utilities"
        ]
      },
      {
        "section": "QR Code",
        "screens": [
          "Digital Entry & Gate Scan Pass"
        ]
      },
      {
        "section": "Favorite",
        "screens": [
          "Saved Parking Locations"
        ]
      },
      {
        "section": "Notification",
        "screens": [
          "Booking Alerts & Session Updates"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The primary task flow guides drivers from entering a target destination on the city map, scanning nearby open garages, reviewing venue pricing, selecting a floor and bay slot, monitoring an active parking timer, and completing an itemized digital payment checkout.",
    "steps": [
      {
        "step": "01",
        "title": "Search Destination on City Map",
        "description": "User enters a target location in the top floating search pill and inspects blue P parking markers around city landmarks.",
        "screenOrAction": "Interactive Map Discovery"
      },
      {
        "step": "02",
        "title": "Compare Nearby Venue Availability",
        "description": "User reviews the overlaid venue list showing 24-hour locations with high-contrast EMPTY (green) and FULL (red) status badges.",
        "screenOrAction": "Nearby Parking Availability List"
      },
      {
        "step": "03",
        "title": "Inspect Facility & Select Duration",
        "description": "User checks distance, remaining spots, security details, and chooses a 1, 2, or 3 hour pricing chip before tapping Book Parking Slot.",
        "screenOrAction": "Parking Area Details"
      },
      {
        "step": "04",
        "title": "Choose Floor & Parking Bay",
        "description": "User switches between 1st, 2nd, and 3rd Floor tabs, reads directional lane arrows, selects open bay B03, and taps Proceed with B03.",
        "screenOrAction": "Book Parking Slot"
      },
      {
        "step": "05",
        "title": "Monitor Active Session & Ticket",
        "description": "User views Activated status, ticket #109824, live countdown timer, parked bay diagram, and optional Contact Officer button before Checkout.",
        "screenOrAction": "Booked Slot Counter"
      },
      {
        "step": "06",
        "title": "Review Fees & Proceed to Payment",
        "description": "User verifies booking timestamps and the itemized white cost card (parking duration, tax, service fee, total) before tapping Payment Method.",
        "screenOrAction": "Payment Summary"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Map Discovery, Nearby Availability & Parking Area Details",
      "imageUrl": "/images/projects/e_parking_mobile_app/image01.webp"
    },
    {
      "title": "Floor & Bay Slot Selection, Active Counter & Payment Checkout",
      "imageUrl": "/images/projects/e_parking_mobile_app/image02.webp"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Deep Navy Surface",
        "hex": "#061852",
        "role": "Primary Surface",
        "usage": "Modal overlay cards, search pill, and persistent bottom navigation bar"
      },
      {
        "name": "Emerald Confirm",
        "hex": "#008868",
        "role": "Primary Action & Available",
        "usage": "Primary CTA buttons (Book Parking Slot, Proceed, Checkout) and EMPTY badges"
      },
      {
        "name": "Coral Alert",
        "hex": "#E83838",
        "role": "Semantic Alert & Occupied",
        "usage": "FULL availability badges, inactive floor tabs, duration chips, and active timer banner"
      },
      {
        "name": "Periwinkle Selection",
        "hex": "#98A0F8",
        "role": "Selection Highlight",
        "usage": "Active 1st Floor tab and selected/parked bay tile (B03)"
      },
      {
        "name": "Mint Nav Highlight",
        "hex": "#90F8E8",
        "role": "Active Navigation Indicator",
        "usage": "Highlighted container behind the active Reservation tab in the bottom bar"
      },
      {
        "name": "Signal Yellow",
        "hex": "#F8F800",
        "role": "Support Accent",
        "usage": "High-visibility Contact Officer action button on the active booking screen"
      },
      {
        "name": "Pure White",
        "hex": "#FFFFFF",
        "role": "Typography & Receipt Surface",
        "usage": "Primary headings, icon labels, Activated badge, and itemized payment breakdown card"
      }
    ],
    "typography": [
      {
        "name": "Modal Screen Header",
        "role": "Heading",
        "font": "Open Sans",
        "sizeWeight": "18px / SemiBold",
        "usage": "Top card titles such as Parking Area, Book Parking Slot, Booked Slot, and Payment"
      },
      {
        "name": "Venue & Section Title",
        "role": "Subheading",
        "font": "Open Sans",
        "sizeWeight": "14px / Medium",
        "usage": "Location names, ticket numbers, and section labels inside dark-navy cards"
      },
      {
        "name": "Detail Copy & Badges",
        "role": "Body & Label",
        "font": "Open Sans",
        "sizeWeight": "11px / Regular",
        "usage": "Facility descriptions, status pills (EMPTY/FULL), bay codes, and bottom tab captions"
      }
    ],
    "componentStates": [
      {
        "component": "Primary CTA Button",
        "states": ["Default", "Active"],
        "notes": "Full-width rounded emerald green (#008868) button with white centered label at modal bottom"
      },
      {
        "component": "Floor Selector Tab",
        "states": ["Default", "Selected"],
        "notes": "Selected floor uses periwinkle lavender (#98A0F8) with navy text; unselected floors use coral red (#E83838)"
      },
      {
        "component": "Parking Bay Tile",
        "states": ["Available", "Occupied", "Selected"],
        "notes": "Available slots show bay codes; occupied slots show magenta car icons; chosen bay highlights in #98A0F8"
      },
      {
        "component": "Bottom Navigation Item",
        "states": ["Default", "Active"],
        "notes": "Active tab swaps dark navy background for a mint cyan (#90F8E8) rounded square indicator"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "susScore": "Not Measured (Static Concept Showcase)",
    "taskSuccessRate": "Not Measured (Static Concept Showcase)",
    "timeOnTask": "Not Measured (Static Concept Showcase)",
    "iterations": [
      {
        "usabilityIssue": "Risk of losing geographic context when inspecting deep booking modals",
        "iterationSolution": "Framed booking, slot selection, and payment views as floating dark-navy cards over the live city map",
        "impact": "Preserves spatial orientation while keeping high contrast for foreground task controls"
      },
      {
        "usabilityIssue": "Potential confusion distinguishing open, occupied, and selected parking bays",
        "iterationSolution": "Combined magenta top-down vehicle icons for occupied spaces, explicit slot codes for open bays, and periwinkle fill for selected bay B03",
        "impact": "Improves scannability across multi-row A1 and B1 parking zones"
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "High-Fidelity WebP Showcase Archive",
    "totalFrames": 6,
    "componentsCount": 18,
    "handoffSpecs": "Six high-fidelity mobile UI screens exported as WebP showcase panels with consistent #061852 card surfaces, semantic status colors, and five-tab navigation."
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "Mobile Card Overlay Grid",
    "designTokens": "Navy Semantic Color Palette",
    "typography": "Clean Sans Serif Hierarchy",
    "prototypeFidelity": "High Fidelity Static Screens"
  }
}
```
