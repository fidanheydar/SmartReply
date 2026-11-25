# SmartReply

*Managing Uncertainty in AI-Generated Message Suggestions*

**University of Birmingham | Intelligent Interactive Systems | Assignment 2**

**README prose word count: 740 words**

## Project Overview

SmartReply is an interactive web prototype based on my Assignment 1 research into uncertainty in AI-generated communication. The project explores how selective clarification can help users recognise and correct assumptions without unnecessarily interrupting everyday conversations.

## Project Status

### Implemented

- Interactive messaging and email workspace
- Friendly, Professional and Concise tone selection
- Uncertainty warnings and selective clarification controls
- Editing, regeneration and rejection of suggested replies
- Independent message composition
- Visual feedback and personalisation settings
- Local calendar and scheduling conflict checks
- Contacts, notifications and activity history

### Simulated

- AI-generated reply suggestions
- Detection of uncertain intentions
- Reply updates based on clarification
- Message and email delivery

### Planned

- Live language model integration
- Validated uncertainty detection
- User evaluation

The prototype uses predefined scenarios and rule-based responses. No real messages are delivered, and no external accounts are connected.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Interface styling, layout and visual feedback |
| JavaScript | Interaction logic and simulated AI behaviour |
| LocalStorage | Browser-based storage of demonstration data |
| ChatGPT | Development, design and documentation assistance |

The prototype uses vanilla JavaScript and does not require external software libraries, a backend or API keys.

## Getting Started

1. Download or clone this repository.
2. Ensure that `index.html`, `styles.css` and `app.js` are in the same folder.
3. Open `index.html` in a modern web browser.

Alternatively, run the following command from the project directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## How to Use SmartReply

- Open Messages or Email from the navigation menu and select a conversation.
- Review the incoming message and the suggested reply in the SmartReply panel.
- Choose a preferred tone: Friendly, Professional or Concise.
- If an uncertainty warning appears, review the explanation and answer the clarification question if available. The suggested reply will update according to your selection.
- Use Edit to modify the suggestion, Regenerate to request an alternative or Reject to dismiss it.
- Alternatively, write your own response directly in the message input field.
- Select Send to submit the reply and observe the confirmation feedback.

The Calendar section allows users to manage local events and explore potential scheduling conflicts in predefined situations. Settings provides options to switch between selective questions and warnings-only interaction. Users can also restore the initial demonstration state using Reset demo.

All interactions take place within the simulation.

## Development Record

| Stage | Changes and reasoning |
|---|---|
| Initial concept | Developed the idea from Assignment 1, focusing on uncertainty and user intentions in AI-assisted communication. |
| Interface design | Expanded the initial concept into a familiar messaging workspace where users could review suggestions alongside incoming messages. |
| Selective clarification | Limited clarification to uncertain situations to avoid unnecessary interruptions during routine communication. |
| Uncertainty handling | Added explanatory warnings and an undecided response option to avoid misleading confidence scores and unconfirmed commitments. |
| User control | Introduced tone selection, editing, regeneration, rejection and manual composition to support personal expression. |
| Feedback | Added visible status changes and separated reply generation from sending so users retain control over the final response. |
| Extended functionality | Introduced email and local calendar interactions to explore the same design approach across different communication situations. |

The interaction logic was reviewed against the intended behaviour, particularly how clarification affects reply suggestions and how users retain control over their responses. Further browser testing and user evaluation are needed.

## AI Assistance

I used ChatGPT to support prototype development, code refinement, interface design and the preparation of the report, system diagram and storyboards.

Throughout development, I reviewed its suggestions and requested changes when they did not reflect my intended design. For example, I simplified the interface, refined uncertainty warnings and limited clarification to relevant situations.

I also revised the uncertain-deadline storyboard to show the initial suggested reply, uncertainty warning, clarification question and updated response in the correct order. The system diagram was refined to distinguish implemented functionality from simulated AI behaviour.

The storyboards are illustrative representations rather than screenshots of the application. ChatGPT was used as a supporting tool, while the final design decisions, academic claims and references remain my responsibility.

## Limitations and Future Development

The current prototype uses predefined rules and cannot reliably infer intentions from arbitrary messages.

Future development could involve integrating a language model and evaluating selective clarification against warnings-only interaction, considering intention alignment, response time, cognitive effort and perceived control.

## Additional Files

| File | Description |
|---|---|
| `index.html` | Main application structure |
| `styles.css` | Interface styling and layout |
| `app.js` | Interaction logic and rule-based simulation |
| `README.md` | Setup instructions and development record |

The accompanying project report contains the academic background, design rationale, system diagram, illustrative interactions and references.
