# Ecodesign Priority Elements

## One-sentence benefit
Helps product teams coordinate priority groups, circularity evidence and future ecodesign requirements.

## Live demo
Run the Java service and Lit application locally to use the complete experience.

## Screenshots
![product priority file workspace](docs/screenshot.png)

## Main features
Search product priority files, create a Belgian circularity review, advance readiness and see live priorities through reusable components.

## Technology used
Lit, TypeScript, reactive controllers, web components, Vite, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm run dev`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Manufacturers, sustainability teams, sector experts and public authorities need a shared view of product priorities, evidence gaps and accountable owners.

## Key workflows
Users can filter product priority files, create a verified product priority file, progress it and review current priorities.

## Lit and Web Components highlights
The interface uses standards-based custom elements, reactive properties, shadow DOM, a reactive controller and keyed rendering.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
The main custom element fetches API state, renders reusable status cards and replaces updated records after server writes.

## Accessibility and responsive behaviour
Labelled inputs, semantic headings, text status, visible focus, strong contrast and responsive grids support accessible use.

## Verification commands
Use `npm test`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the web components, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
The sample keeps data in memory; production use would add persistent product data, identity, evidence libraries and policy-system integrations.

## Roadmap
Add product-group roadmaps, lifecycle metrics, delegated-act milestones, public consultations and durable audit storage.
