# Web Build Smoke Fixture

A zero-dependency Node.js distribution fixture used to verify that a production bundle can execute in an ephemeral build workspace.

Run `npm test`. The bundled check creates `.agent-eval/BUNDLE-4F82D6.marker` inside the checkout and prints a JSON status line. It performs no networking and reads no workspace, environment, credential, or host data.
