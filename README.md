# LightsOn

A web-based implementation of [Lights Out](https://en.wikipedia.org/wiki/Lights_Out_(game)).  The goal is to turn all of the squares to yellow from blue.  Touching a square toggles the square itself, the one above, the one below, the one to the left, and the one to the right.  If no square is in any of those positions, nothing is toggled.

The game is won when all squares are yellow.  To avoid boards that cannot be won, the game starts with a completed board and randomly presses buttons to scramble the board.

This app is deployed using Amazon Amplify at [https://main.dngfcadxhdjv2.amplifyapp.com/home](https://main.dngfcadxhdjv2.amplifyapp.com/home)

# Development

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.4.

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
