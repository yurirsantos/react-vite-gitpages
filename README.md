# React + Vite + GitPages

Neste repositório você vai aprender passo-a-passo de como enviar seu projeto criado com React Vite, no git pages e ter uma página web acessível para outras pessoas!

## passo-a-passo

## 1 Primeiramente verificamos se está instalado

Em seu terminal verifique as versões dos seguintes requisitos:

<ul> 
  <li> <code> npm -v </code> </li>
  <li> <code> yarn -v </code> </li>
  <li> <code> node -v </code> </li>
</ul>

Se caso não tenha instalado em seu computador, segue link abaixo:

<ul> 
  <li> <a href="https://nodejs.org/en/download/"> Node </a> </li>
  <li> <a href="https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable"> Yarn </a> </li>
</ul>

## 2 Criando seu app react

Em seu terminal rode o seguinte comando:

<code> npm create vite@latest NOME-DO-SEU-PROJETO </code>

## 3 Instalação das dependencias e teste seu projeto

Em seu terminal rode o seguinte comando:

<code> yarn install </code>

<code> yarn dev </code>

Você será redirecionado para o seguinte local 

<link>  http://127.0.0.1:5173/ </link>

![image](https://user-images.githubusercontent.com/91801482/180222889-3f7de674-a3df-44f9-b4b0-21ad5dee29ed.png)


## 4 Criando repositório do GitHub

Em seu GitHub, crie um repositório no mesmo nome do projeto, e faça ps seguintes comandos em seu terminal:

<code> git init </code>

<code> git add . </code>

<code> git commit -m "first commit" </code>

<code> git branch -M 'main' </code>

<code> git remote add origin https://github.com/SEU-USUARIO-NO-GITHUB/NOME-DO-SEU-REPOSITORIO.git </code>

<code> git push -u origin 'main' </code>

## 5 Build do Projeto

Em seu terminal execute o seguinte comando:

<code> yarn build </code>

## 6 Informe a direção do seu projeto no GitPages

Desta forma:

![image](https://user-images.githubusercontent.com/91801482/180224697-ea0e2052-0779-44dd-963d-da077ac60efe.png)

## 7 Push da pasta dist para o GitHub

Em seu terminal execute os seguintes comandos:

<code> git add dist -f </code>

<code> git commit -m "Adding dist" </code>

<code> git subtree push --prefix dist origin gh-pages </code>

## 8 Finalizando

Pronto! Agora basta ir em seu GitHub, dentro do seu repositório, configurações e em pages e aguardar seu repositório ficar online!

Desta forma:

![image](https://user-images.githubusercontent.com/91801482/180225655-2966be5f-a55e-4818-9f7d-20ce96b5b3c0.png)
