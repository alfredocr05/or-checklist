# OR Setup Checklist Prompt Generator

## Overview

This browser‑based tool helps anesthesia teams quickly generate a structured list of supplies and equipment needed for operating room (OR) setup. By entering a few case details—patient age group, patient context, ASA classification, anesthesia type and surgical procedure—the tool outputs a one‑page prompt that can be used with Google Gemini (or any modern large‑language model) to produce a customized checklist.  
This can reduce interruptions during short turnover windows and ensure that assistants have all the necessary items ready before the next case.

## Who Is This For?

- **Anesthesiologists and assistants** who need fast, procedure‑specific setup guidance.
- **Students, trainees and evaluators** looking to understand operational implications of brief turnovers and procedure diversity.
- **Researchers and reviewers** interested in exploring AI‑assisted workflow tools in a clinical environment.

## Quick Start

1. **Open the live prompt generator:**  
   Visit **[alfredocr05.github.io/or-checklist](https://alfredocr05.github.io/or-checklist/)** in any modern desktop or mobile browser—no installation or login required.
2. **Enter case details:**  
   Choose the patient age group, context (inpatient/ambulatory), ASA classification, type of anesthesia, and list the scheduled surgical procedure(s).
3. **Generate & copy the prompt:**  
   Click **“Copy Prompt”** to copy the generated prompt to your clipboard.
4. **Use the prompt with Gemini:**  
   Paste the prompt into Google Gemini (or another LLM) to produce a one‑page supplies and equipment checklist for the anesthetic assistant.

## Access Options

| Option | Description |
| --- | --- |
| **Live web app** | [**alfredocr05.github.io/or-checklist**](https://alfredocr05.github.io/or-checklist/) – the easiest way to use the tool. |
| **QR code** | Scan the QR code below with your phone’s camera to open the live app directly. You can also print or save the QR code for later reference. |
| **Repository & documentation** | This GitHub repository contains the source code, README, screenshots and instructions. Non‑technical users generally do not need to clone or download the code. |
| **Archived release (DOI)** | For long‑term citation and preservation, a permanent snapshot is available via Zenodo: [10.5281/zenodo.20673373](https://doi.org/10.5281/zenodo.20673373). |

### QR Code

Below is a sample QR code that opens the live prompt generator.  
If you are viewing this file on GitHub, click the image to open or download it.  
The QR code page is also available in the `QR code/` folder and the manuscript release assets.

![QR Code – OR Setup Checklist](QR%20code/OR_setup_checklist_QR.png)

*Open your phone’s camera and point it at the code, or type the URL **alfredocr05.github.io/or-checklist/** into any browser.*  
To print or save the QR code page, open the file in the `QR code` folder or download the assets from the release page.

## Repository Structure

```
/
├── index.html              # main web application (live prompt generator)
├── Checklist Generator/    # assets and scripts for the prompt generator
├── QR code/                # printable QR code page and image assets
├── README.md / README.txt  # this documentation in Markdown/plain‑text
```

## Questions and Support

If you have questions, discover issues or have suggestions, please open an [issue](https://github.com/alfredocr05/or-checklist/issues) in this repository or contact the author through the correspondence information provided in the associated publication.
