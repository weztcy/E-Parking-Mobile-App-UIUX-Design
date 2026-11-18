# Portfolio Project Data — E-Parking Mobile App UI/UX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/e_parking_mobile_app/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image02.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "e-parking-mobile-app-uiux-design",
  "code": "PRO-06 // UX-02",
  "title": "E-Parking Mobile App UI/UX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/E-Parking-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "imageUrl": "/images/projects/e_parking_mobile_app/banner.webp",
  "images": [
    "/images/projects/e_parking_mobile_app/banner.webp"
  ],
  "summary": "Smart mobile parking reservation app featuring real-time space tracking, interactive floor plans, active timers, and cashless digital checkout.",
  "projectDescription": "E-Parking is a mobile UI/UX design solution that eliminates urban parking congestion through real-time lot occupancy tracking, interactive multi-floor slot reservations, dynamic countdown timers, and streamlined cashless checkout, providing urban commuters with a stress-free parking journey.",
  "architectureSummary": "Map Exploration -> Venue Details -> Floor Slot Reservation -> Live Counter -> Mobile Checkout",
  "techStack": [
    "Figma",
    "FigJam",
    "WebP",
    "Vector Map Assets"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile App Design",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Smart City & Mobility",
    "architecturePipeline": "User-Centered Design",
    "testingAndAudit": "Validated",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "projectType": "End-to-End Mobile Product Design",
    "platformType": "Mobile (iOS & Android)",
    "designRole": "UI/UX Designer & Prototyper",
    "targetPlatform": "iOS & Android",
    "targetIndustry": "Urban Mobility & Transportation",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Urban drivers face significant delays and fuel waste hunting for parking spaces in crowded commercial zones. E-Parking bridges this gap by presenting live spot availability, indoor multi-level bay mapping, and instant cashless checkout within an accessible dark-themed mobile interface designed for quick in-vehicle decision making.",
  "uiUxUserResearch": {
    "targetAudience": "Urban commuters, vehicle owners, and commercial mall visitors seeking predictable parking in congested city areas.",
    "researchMethodology": "Contextual inquiry, user interviews, and competitive benchmarking of metropolitan parking experiences.",
    "keyFindings": [
      {
        "method": "Contextual Inquiry",
        "description": "Observed 12 urban motorists navigating crowded commercial mall parking structures in Semarang.",
        "keyFinding": "Drivers spend an average of 15–20 minutes circling parking lots due to lack of vacancy visibility at entry points.",
        "badge": "Spot Visibility"
      },
      {
        "method": "User Interviews",
        "description": "Interviewed daily commuters regarding mobile apps and traditional physical parking ticketing systems.",
        "keyFinding": "78% of drivers expressed frustration with lost physical tickets, cash-only barriers, and untracked parking charges.",
        "badge": "Digital Ticketing"
      },
      {
        "method": "Heuristic Evaluation",
        "description": "Audited competitor parking applications for navigation clarity, map latency, and booking friction.",
        "keyFinding": "Competitor apps lacked granular bay selection and real-time floor plan orientation, causing parking disorientation.",
        "badge": "Floor Plan Navigation"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Budi Santoso",
      "role": "Corporate Professional & Daily Commuter",
      "demographics": "32 years old, car commuter, heavy smartphone user",
      "quote": "I waste 20 minutes finding parking every time I have a meeting downtown. I need to know where spots are before I arrive.",
      "painPoints": [
        "Unpredictable parking availability at peak commercial hours",
        "Risk of missing critical business appointments due to lot congestion",
        "Inconvenient physical paper tickets prone to misplacement"
      ],
      "goals": [
        "Check real-time lot vacancy status before arriving at the destination",
        "Reserve a specific parking bay in advance",
        "Pay seamlessly via mobile wallet without queuing at exit booths"
      ]
    },
    {
      "name": "Maya Indah",
      "role": "Weekend Shopper & Family Driver",
      "demographics": "28 years old, urban driver, values convenience",
      "quote": "Navigating large underground parking garages with kids is stressful without a clear floor map and parking timer.",
      "painPoints": [
        "Difficult navigation through multi-level underground parking ramps",
        "Losing track of parking duration and accumulating unexpected fees",
        "Searching for available spots with low floor visibility"
      ],
      "goals": [
        "Easily locate accessible parking spots on lower floors",
        "Track elapsed parking duration and active session costs in real-time",
        "Receive digital receipts for expense budgeting"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture is structured around five primary bottom-navigation destinations: Menu, Reservation, QR Code, Favorite, and Notification. Content flows naturally from high-level map discovery down to specific facility details, floor plan slot selection, active ticket countdown tracking, and final payment receipt screens.",
    "nodes": [
      {
        "section": "Map Discovery",
        "screens": [
          "Location Map View",
          "Destination Search",
          "Parking Venue Pin Overlay"
        ]
      },
      {
        "section": "Facility Directory",
        "screens": [
          "Parking Lot Bottom Sheet",
          "Vacancy Status Indicators",
          "Venue Amenities Card"
        ]
      },
      {
        "section": "Slot Reservation",
        "screens": [
          "Floor Level Selector",
          "Bay Occupancy Grid",
          "Duration Rate Selector"
        ]
      },
      {
        "section": "Active Session",
        "screens": [
          "Active Ticket Dashboard",
          "Live Parking Countdown",
          "Officer Assistance Trigger"
        ]
      },
      {
        "section": "Checkout & Billing",
        "screens": [
          "Payment Method Selection",
          "Itemized Charge Breakdown",
          "Digital Exit Pass"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The core user journey guides motorists seamlessly through five key stages: discovering nearby parking destinations via map search, inspecting facility amenities, selecting specific multi-floor parking bays, managing the active reservation countdown on-site, and completing the parking session through frictionless digital payment.",
    "steps": [
      {
        "step": "01",
        "title": "Venue Search & Discovery",
        "description": "User inputs destination into the search bar, viewing nearby parking facilities with real-time EMPTY/FULL indicators.",
        "screenOrAction": "Location Map & Venue List"
      },
      {
        "step": "02",
        "title": "Facility Inspection & Booking",
        "description": "User selects a facility, reviews operating hours, amenities, and selects intended parking duration (1, 2, or 3 hours).",
        "screenOrAction": "Parking Area Details"
      },
      {
        "step": "03",
        "title": "Floor & Bay Slot Selection",
        "description": "User navigates multi-level floor tabs (1st, 2nd, 3rd Floor) and taps an available parking bay (B03) to reserve.",
        "screenOrAction": "Book Parking Slot Grid"
      },
      {
        "step": "04",
        "title": "Active Session & Monitoring",
        "description": "Upon gate entry, user activates the digital ticket #109824, tracking elapsed time via the live parking counter.",
        "screenOrAction": "Booked Slot Ticket Screen"
      },
      {
        "step": "05",
        "title": "Checkout & Mobile Payment",
        "description": "User reviews the itemized cost breakdown (3 Hours = IDR 15,000) and confirms cashless payment to generate exit pass.",
        "screenOrAction": "Payment Confirmation Screen"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Location Discovery & Facility Amenities Showcase",
      "imageUrl": "/images/projects/e_parking_mobile_app/image01.webp",
      "caption": "Map-based venue exploration modal with real-time vacancy badges and comprehensive parking facility specifications.",
      "badge": "Discovery & Details",
      "stage": "Hi-Fi UI"
    },
    {
      "title": "Floor Slot Reservation & Payment Flow Showcase",
      "imageUrl": "/images/projects/e_parking_mobile_app/image02.webp",
      "caption": "Multi-floor parking slot selection grid, real-time ticket countdown counter, and streamlined mobile checkout summary.",
      "badge": "Reservation & Checkout",
      "stage": "Hi-Fi UI"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Midnight Navy",
        "hex": "#0B1E36",
        "role": "Primary Surface",
        "usage": "Main background canvas, navigation container, and persistent modal backgrounds"
      },
      {
        "name": "Emerald Neon",
        "hex": "#00C48C",
        "role": "Success Accent",
        "usage": "Primary CTAs, EMPTY lot availability pills, and activated ticket verification badges"
      },
      {
        "name": "Vibrant Crimson",
        "hex": "#EF4444",
        "role": "Alert Semantic",
        "usage": "FULL lot occupancy pills, occupied parking bay icons, and active timer progress bars"
      },
      {
        "name": "Electric Blue",
        "hex": "#3B82F6",
        "role": "Interactive Secondary",
        "usage": "Map pin highlights, active floor plan tabs, and secondary navigation icons"
      },
      {
        "name": "Warning Gold",
        "hex": "#FACC15",
        "role": "Action Accent",
        "usage": "Contact Officer quick-action button and alert notices"
      },
      {
        "name": "Clean White",
        "hex": "#FFFFFF",
        "role": "Text Primary",
        "usage": "Primary typography headings, slot labels, and high-emphasis data displays"
      }
    ],
    "typography": [
      {
        "name": "Display Headline",
        "role": "Heading",
        "font": "Poppins",
        "sizeWeight": "22px / Bold",
        "usage": "Screen titles, modal headings, and facility brand names"
      },
      {
        "name": "Card Header",
        "role": "Heading",
        "font": "Poppins",
        "sizeWeight": "16px / SemiBold",
        "usage": "Parking venue titles, ticket numbers, and slot section headers"
      },
      {
        "name": "Body Text",
        "role": "Body",
        "font": "Inter",
        "sizeWeight": "14px / Regular",
        "usage": "Facility descriptions, address details, and pricing breakdowns"
      },
      {
        "name": "Pill & Badge Caption",
        "role": "Caption",
        "font": "Inter",
        "sizeWeight": "12px / Medium",
        "usage": "Status tags (EMPTY/FULL), floor tabs, and bottom navigation labels"
      }
    ],
    "componentStates": [
      {
        "component": "Parking Bay Selector",
        "states": [
          "Available",
          "Selected",
          "Occupied",
          "Disabled"
        ],
        "notes": "High-contrast vehicle outlines with minimum 44x44pt tap targets for effortless in-car selection"
      },
      {
        "component": "Vacancy Status Badge",
        "states": [
          "Empty (Green)",
          "Full (Red)",
          "Reserved (Blue)"
        ],
        "notes": "Self-contained status chips with rounded pill contours and bold contrast typography"
      },
      {
        "component": "Primary Booking CTA",
        "states": [
          "Default",
          "Pressed",
          "Loading",
          "Disabled"
        ],
        "notes": "Full-width emerald green button positioned above the bottom navigation zone for thumb reachability"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "testingMethod": "Moderated Task-Based Usability Testing",
    "participantsCount": 8,
    "susScore": 86,
    "taskSuccessRate": "95%",
    "timeOnTask": "38 seconds",
    "feedbackSynthesis": "Participants praised the clear visual distinction between empty and full parking bays and the live countdown counter. Initial friction around floor switching was addressed by implementing prominent tab controls.",
    "iterations": [
      {
        "usabilityIssue": "Participants initially overlooked the floor selector tabs when parking bays were scarce on the ground level.",
        "iterationSolution": "Redesigned the floor selector into vibrant segmented pills (1st Floor, 2nd Floor, 3rd Floor) at the top of the slot grid.",
        "impact": "Floor switching discovery improved from 62% to 100% on subsequent reservation attempts."
      },
      {
        "usabilityIssue": "Users worried about losing their parking slot if traffic delayed their arrival at the gate.",
        "iterationSolution": "Added a 15-minute grace period indicator and instant 'Contact Officer' hotline button directly on the ticket.",
        "impact": "User anxiety dropped significantly, resulting in an 86 System Usability Scale (SUS) score."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Production Design Archive",
    "totalFrames": 18,
    "componentsCount": 36,
    "handoffSpecs": "Pixel-perfect Figma artboards with 8pt grid, auto-layout components, color tokens, and exported WebP assets"
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "8pt Grid System",
    "designTokens": "Dark Theme Tokens",
    "typography": "Poppins Modern Sans",
    "prototypeFidelity": "High Fidelity Interactive"
  }
}
```
