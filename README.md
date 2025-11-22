# 🐔 Animal Farming Guide Platform

## 1. Project Overview

This is the basic structural outline for a college minor project focused on providing comprehensive guides for various animal farming categories. The core idea is to combine farming techniques with practical considerations like Key Requirements and Environmental Suitability (e.g., tropical, arid, temperate zones).

## 2. File Structure

|File | Purpose | Notes |
|---|---|---|
| index.html | Core Application | Contains all HTML structure, CSS styling (via Tailwind and `<style>` tag), and JavaScript logic. |
| README.md | Documentation | Provides project context, setup instructions, and future plans. |

## 3. Technology Stack

- **HTML5:** Structure
- **Tailwind CSS (via CDN):** Modern, utility-first styling for responsiveness and aesthetics.
- **JavaScript (Vanilla ES6):** Logic for filtering, displaying data, and handling the modal view.
- **Data:** Currently uses a hardcoded JavaScript array (farmingData) for mock content.

## 4. Key JavaScript Functions

- **farmingData:** The mock dataset containing all guide details.
- **renderGuides(data):** Renders the summary cards in the main section based on filtered data.
- **setupCategories():** Populates the sidebar navigation and attaches filter event listeners.
- **filterAndRender():** The main control function that applies both category and environment filters before calling renderGuides().
- **showGuideDetail(id):** Handles opening the modal and populating it with the full guide, requirements, and environmental information.

## 5. Next Steps for Development

To turn this structure into a complete project, you should focus on these areas:

- **Data Expansion:** Add at least 10-15 more detailed mock guides covering diverse animals (e.g., goats, rabbits, bees, ducks) and different environmental challenges.
- **Guide Detail Enrichment:** Add images, charts (perhaps a placeholder chart to show projected growth), or tables within the modal view to make the information more professional and visually appealing.
- **Search Functionality:** Implement a search bar to filter guides by name or keyword.
- **Data Persistence (Advanced):** For a more robust project, you could explore using an actual database like Firebase Firestore to store and fetch your guides, instead of hardcoding the data in the JavaScript file.