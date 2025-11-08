# Pi-Vate Cloud Defense Dossier (100 Questions)

This is a comprehensive, self-contained, client-side web application designed to present the full defense dossier for the "Pi-Vate Cloud" project.

The application allows users to easily navigate, search, and filter the 100 questions and answers covering the project's foundational concepts, financial viability, hardware, software, and security architecture.

## Features

- **100% Client-Side:** The application runs entirely within your web browser, requiring no server or backend setup.
    
- **Search Functionality:** Filter questions and answers in real-time based on keywords.
    
- **Category Filtering:** Narrow down the dossier to specific technical or financial sections (e.g., "Security," "Hardware," "TCO").
    
- **Collapsible Sections (Accordion):** Click headers to expand or collapse specific sections for focused reading.
    
- **Collapsible Questions:** Click individual questions to expand or collapse their answers.
    
- **Pure HTML/CSS/JS:** Built without frameworks (like React or Vue) for maximum simplicity and portability.
    

## Getting Started

Since this project is a single HTML file, getting started is extremely easy.

### Prerequisites

You only need a modern web browser (Chrome, Firefox, Edge, Safari, etc.).

### Installation and Execution

1. **Save the file:** Copy the entire code block provided (which includes the HTML, CSS, and JavaScript) and save it locally as **`PiVateCloudDossier.html`**.
    
2. **Open in Browser:** Double-click the saved file, or right-click it and choose **Open With > [Your Web Browser]**.
    

The application will launch immediately, displaying the interactive dossier.

## Project Structure

The entire application is contained within a single file, utilizing inline technologies:

|Component|Technology|Purpose|
|---|---|---|
|**HTML**|HTML5|Defines the structure, layout, and content container.|
|**CSS**|Inline `<style>` block|Implements modern styling, colors, and responsive design, replicating the look of Tailwind CSS utilities.|
|**JavaScript**|Vanilla JS|Handles the core functionality: data rendering, section/question toggling, and real-time search/filtering.|
|**Icons**|Lucide Icons|Used for vector icons (e.g., `server`, `shield`, `search`). Loaded via CDN for convenience.|

### Data

The core data (`sectionsData` array containing all 100 Q&A pairs) is embedded directly within a `<script>` tag at the top of the file, making the file completely self-contained.

## Dossier Sections

The 100 questions are logically organized into the following seven sections:

1. **I. Foundational Concepts & Project Rationale** (Q1-Q15)
    
2. **II. Financial Viability and Total Cost of Ownership (TCO)** (Q16-Q30)
    
3. **III. Hardware Architecture & Component Justification** (Q31-Q45)
    
4. **IV. Software Stack, OMV, and Containerization** (Q46-Q60)
    
5. **V. Security, Encryption (LUKS), and Authentication** (Q61-Q75)
    
6. **VI. Zero-Trust Network Access (ZTNA) Deep Dive** (Q76-Q90)
    
7. **VII. Performance, Empirical Analysis, and Future Work** (Q91-Q100)
    

## Usage

- **Search:** Type any keyword (e.g., "LUKS" or "Twingate") into the search box to filter results across all questions and answers.
    
- **Filter:** Use the dropdown menu to restrict the display to a single section (e.g., only show questions related to "Hardware Architecture").
    
- **Expand/Collapse Sections:** Click on any section header (e.g., **I. Foundational Concepts**) to view or hide its questions.
    
- **Expand/Collapse Questions:** Click on any individual question to view or hide its answer.