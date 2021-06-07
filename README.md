# nextstorybook

Next.js + Storybook + Typescript : 2021 guide
https://dev.to/wonder2210/next-js-storybook-typescript-2021-guide-2ab4

mkdir nextstorybook
cd ./nextstorybook
yarn set version berry
yarn init

echo stable > .nvmrc
nvm use

git init

https://github.com/github/gitignore/blob/master/Node.gitignore

yarn add next react react-dom

mkdir pages
touch ./pages/index.tsx
touch tsconfig.json

yarn add --dev typescript @types/react @types/node

Add storybook

npx sb init
