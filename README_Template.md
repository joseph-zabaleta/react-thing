# Lab: Class 38: React 2

## Open Git Pull Requests  
 
## Overview  

Create a ReactJS web application that displays a list of things, and allows creating new things.

## Feature Tasks and Requirements  
- [] Create a web app with a top level App component
  - App component should…
    - [] have thingList data stored in its state.
    - render 3 nested components
      - [] Header
      - [] ThingList
      - [] Footer
- [] thingList should be an array of plain old JavaScript objects (aka POJO) that represent a thing that has a name.
  - E.g. {name:’rake’}
- Header component should…
  - [] receive a things count as a prop
  - [] display a heading
  - [] display the current count of things
- ThingList component should…
  - [] receive a list of things as a prop
  - [] receive a function to call when a new thing is created.
  - [] Display an unordered list composed of ThingItem components
  - [] Display a form that allows creation of a thing
  - [] When user creates new thing the rest of application should update appropriately.
    - [] Header thing count should update
    - [] ThingList should add a new ThingItem to end of list
- ThingItem component should…
  - [] receive a name as a prop
- Footer component should…
  - [] Display some placeholder text (e.g. lorem ipsum)

## Implementation Notes:  
Useful Terminal Commands
- `npx create-react-app thing-creator`  

Review the instructions provided with ReactApp:  
- [Instructions MD File](/instructions.md)

## User Acceptance Tests  
- [x] No testing required.  

## Dependencies  
- "@testing-library/jest-dom": "^4.2.4",
- "@testing-library/react": "^9.5.0",
- "@testing-library/user-event": "^7.2.1",
- "react": "^16.13.1",
- "react-dom": "^16.13.1",
- "react-scripts": "3.4.1"

## Authors  
- Software Developer: Joseph Zabaleta
  - [Official Github](https://github.com/joseph-zabaleta)  

## Collaborations  
- none  

## License  
This project is under the MIT License.

## Acknowledgements / Resources  
- none

## Version History  
- 1.0.0 20200701
    - Initial files created.  
