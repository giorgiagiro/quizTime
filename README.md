# :question: Quiz Time
## Description

Quiz Time is an application developed using Dart programming language and the framework Flutter.
Essentially it is a quiz application that uses a API for retrieving quiz topics, getting random questions from a given topic, and for posting answers to questions to verify if the answers are correct or not.

The application opens with a first page ("HomeScreen") which allows the user to choose a category, once chosen the user is taken to the second page ("QuestionScreen") where there will be a question related to the category chosen on the previous page. When the user clicks on the answer he or she considers most appropriate, a ("ResultScreen") opens with positive feedback if the question was answered correctly, and negative feedback if the user got the answer wrong. The "HomeScreen" and the "ResultScreen" also show the player's statistics: how many questions were answered and how many of them were answered correctly.

## Features

- 3 navigable screens through buttons
- Responsive layout when the widht of the screen is under 600px
- StateProviders for the mamagement of the statistics and score thanks to flutter_riverpod package
- GoRoutes for navigating through the screens with the package go_router
- Dynamic list of options for questions
- Image when included in the API
- FutureBuilder for retrieving API

## Tech

- [Flutter](https://flutter.dev/) - Framework for building natively compiled, multi-platform applications.
- [Dart](https://dart.dev/) - Client-optimized language for developing apps on any platform.
- [Riverpod](https://riverpod.dev/) -  Flutter package for managing states and changes
- [go_router](https://pub.dev/packages/go_router) - Declarative Routing Package for Flutter

## Deployment

You can visit my app here [QuizTime](https://giorgiagiro.github.io/quizTime/#/)
