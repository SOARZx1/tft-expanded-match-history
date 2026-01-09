TFT Expanded Match History (In-Client Analytics View)

Project Type - Feature Shipping Mock (Teamfight Tactics)

Role - Game Producer (Self-Directed)

Overview

This project proposes an expanded Match History feature for Teamfight Tactics that allows players to click into completed matches and view augment selections, economy history, and lobby context directly in the client.
The feature is designed to improve post-game learning, competitive integrity, and player engagement, while reducing reliance on third-party tools.

Problem Statement

Currently, Match History only displays a player’s final board state and placement.
Players who want to review their decisions must use external websites or apps to access:

- Economy history
- Augment selections
- Lobby context

This creates unnecessary friction and information asymmetry for competitive players.



Goals & Success Metrics

- Improve post-match clarity and learning
- Reduce dependency on third-party tools
- Preserve competitive integrity
- Increased Match History interaction rate
- Increased post-game session time
- Reduced player-reported reliance on third-party tools
- Positive ranked player feedback

Feature Scope

In Scope

- Augment Timeline
    - Augments selected at stages 2-1, 3-2, and 4-2
- Economy History
    - Gold totals by stage with roll vs save indicators
- Lobby Overview
    - Final placements and primary trait icons for all players
- Final Board View
    - Existing end-game board display
 
Out of Scope
- Unit positioning replays
- Item carousel replay
- Real-time or live match data

Cross-Discipline Collaboration

Design
- UX flow for expanded match history screen
- Progressive disclosure to prevent information overload

Engineering

- Backend data validation
- Client data binding and caching
- Performance safeguards

Art / UI

- Stage timeline visuals
- Trait iconography
- Clear visual hierarchy

QA

- Functional validation
- Edge-case testing
- Localization checks

Risks 

- Client performance impact
- Competitive integrity concerns	
- Feature creep	
- Data overload

QA Coverage

- Ranked vs normal matches
- Remakes and partial participation
- Cross-patch historical matches
- Localization text overflow
- Low-spec device performance

Project Management

This feature was planned and tracked using a Kanban workflow in Jira, managing work across Backlog, Ready, In Progress, QA, and Done to maintain scope control and delivery flow.

A single Jira board screenshot is included to demonstrate execution planning.

<img width="1608" height="763" alt="image" src="https://github.com/user-attachments/assets/da02cb4a-cbc0-408c-a81a-7359cf1d9674" />
