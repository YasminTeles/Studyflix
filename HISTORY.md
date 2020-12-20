# Software Architecture

**Registre tudo**: testes que foram executados, ideias que gostaria de
implementar se tivesse tempo (explique como você as resolveria, se houvesse
tempo), decisões que foram tomadas e seus porquês, arquiteturas que foram
testadas e os motivos de terem sido modificadas ou abandonadas. Crie um
arquivo HISTORY.md no repositório para registrar essas reflexões e decisões.
Quanto mais detalhes sobre a jornada, melhor.

## Technology

O projeto Studyflix foi desenvolvido utilizando os seguintes frameworks e plataformas:

* [Next.js](https://nextjs.org/)
* [React](https://reactjs.org/)

## Tests

For the automatic tests of the project, the following libraries are used:

* [Jest](https://jestjs.io/)
* [Testing Library](https://testing-library.com/)

The development of automated tests had the following premises and challenges:

* Use Test Driven Development.
* Write unit tests, integration and end-to-end.
* Have test coverage close or equal to 100%.

## Style Guide

To define a style guide, the following libraries are used:

* [Eslint](https://eslint.org/)
* [EditorConfig](https://editorconfig.org/)
* [Husky](https://github.com/typicode/husky)
* [lint-staged](https://github.com/okonet/lint-staged)

The style guide has:

* Use arbnb style. It is a popular style guide for react's project.
* Use react, react hook and react redux eslint rules.
* Use import sort, it is an eslint plugin.
* Use commit lint. It help a generate releases automatics and consists git commits.
* Use commit pipeline. It ensures that the code will be formatted and tested. In addition, it standardizes commit messages.
