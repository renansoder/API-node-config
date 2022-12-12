CONFIGURAÇÕES PARA PROJETO BACK - eslint, prettier, editorconfig, husky, lint-staged, jest

yarn init -y

yarn add typescript ts-node-dev rimraf @types/node -D

yarn tsc --init

yarn add eslint prettier eslint-config-prettier eslint-plugin-prettier eslint-plugin-simple-import-sort -D
yarn add -D eslint-plugin-import-helpers eslint-import-resolver-typescript

yarn eslint --init

Depois de commitar a primeira vez------------
npx husky-init && yarn

yarn add jest @types/jest ts-jest -D

yarn jest --init

yarn test
