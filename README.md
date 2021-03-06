Team Communicator

## A web app that helps distributed or remote teams communicate questions and stay in sync.

### PROBLEM:

Educational content is lost from zoom during remote calls that could be saved and reused. What if we could transcribe and save all student/attendee questions during online lectures/brown bags?

### SOLUTION:

Our goal is to create an app that works in sync with Zoom calls to fix an internal problem at Lambda School - Content is lost from Zoom calls that could be saved and reused from each cohort. What if we could transcribe and save all student questions during lecture and brown bags? Our goal is to give back to Lambda with our labs project by creating an app that takes content creation to a whole new level. Questions are no longer lost during lecture - each question is timestamped (when answered) for transcription. Instructors can choose to answer or punt questions. The major feature of our app is recording and pushing zoom calls directly to Youtube, transcribing the calls and pushing transcribed information to a GitHub Wiki page (in this case, it would be a test repo until permissions were granted to update the Lambda School wiki). This allows every lambda lecture to be searchable based on transcription results, editable by students and open source for all cohorts to come.

---

**Technology stack**:
MongodB
Express
React
NodeJS

**Status**: Initial build in progress.

**Links to production or demo instances:**

**Screenshots**:

## Dependencies

**Front-End**
Styled-Components
Redux
React-Redux
Redux-Saga
ESLint
React-Router-DOM
Prettier
Exact-Prettier

**Back-End**
Argon2 (vs Bcrypt)
CORS
Mongoose

## Installation

1. Make sure that you have Node.js v8.10 and npm v5 or above installed.

2. Clone this repo using `git clone https://github.com/Lambda-School-Labs/Labs8-TeamComms.git`
3. Move to the front-end directory: cd Labs8-TeamComms
4. Run `yarn install` to install front-end dependencies.
5. Move to the server directory: cd server
6. Run `yarn install` to install server dependencies.

## Usage

In the **base project** directory, you can run:

### `yarn start`

Runs the app in the development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

In the **server** directory, you can run:

### `node server.js`

Runs the server in development mode.

Open [http://localhost:3300](http://localhost:3300) to view it in the browser.

## How to test the software

## Known issues

Build in progress.

## Getting help

If you have questions, concerns, bug reports, etc, please file an issue in this repository's Issue Tracker.
[Our Issue Tracker](https://github.com/Lambda-School-Labs/Labs8-TeamComms/issues)

## Getting involved

While we are happy to add contributors, we will provide more details once our Lambda Labs MVP is complete.

---

## Open source licensing info

1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)

---

## Credits and references
