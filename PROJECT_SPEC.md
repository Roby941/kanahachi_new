# Kanahachi – Spaced Repetition Game / First Chat App

## Overview
A warm, cozy chat-style application featuring a kawaii cat mascot.  
The initial release focuses on a friendly messaging interface that also integrates spaced repetition elements for learning.  
Target audience: language learners, casual users who enjoy playful interfaces.

## Color Scheme
| Role                  | Hex      | Description         |
|-----------------------|----------|---------------------|
| Background (primary)  | #4A2F28  | Medium-dark brown   |
| Surface (light)       | #F1DFC8  | Beige               |
| Accent 1              | #8E67C6  | Purple              |
| Accent 2              | #F47C6B  | Coral               |
| Text on Brown         | #F7F0E7  | Light cream         |
| Text on Beige         | #3B221C  | Dark brown          |

- **Palette preview:**  
  -[Color Palette](https://drive.google.com/file/d/1JNCGZwB1tNeUPMJ9fDxSNBIvcEHOGi3d/view?usp=drivesdk)

## Mascot
- **Description:** Kawaii cat character, cream/beige fur, purple scarf, rosy cheeks, large glossy eyes.  
- **Capabilities:** Static poses, bobbing animation, blinking animation.  
- **Assets:**
  - [Mascot Variations](https://drive.google.com/file/d/1JRtPmf0timfDyhDJAYfZ3iL5x3-AGgYZ/view?usp=drivesdk)

## UI Inspiration
WhatsApp-like chat layout with:
- Brown background
- Beige (user) and coral (other) chat bubbles
- Purple mic button
- Sticker slots for cat character
- Playful yet clean UI

- **Example mockup:**  
  -[Chat Example](https://drive.google.com/file/d/1JDqnsfMK2lyU5-VHIKl3-nlzEm80SAvZ/view?usp=drivesdk)

## Tech Stack
- **Frontend:** Expo (React Native + TypeScript)
- **Styling:** NativeWind (Tailwind for RN)
- **Animations:** react-native-reanimated + Moti
- **State Management:** Zustand
- **Server State:** TanStack Query
- **Backend:** Firebase (Auth, Firestore, Storage, Cloud Functions)

## Style Rules
- Maintain accessible color contrast
- Brown/beige as primary foundation
- Purple for accents, coral for secondary highlights
- Token-based design system for consistent spacing, colors, and typography

## Firestore Structure (Initial Draft)
