<h1 align="center">
    <img  src="https://github.com/PF-Henrique/alexa-herois/blob/master/.docs/index.png" />
</h1>

<h1 align='center'>Interface de voz com Amazon Alexa</h1>

<p align="center">
  <a href="#-about-project">ℹ️ About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias-and-packages">💻 Tecnologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">🔖 Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">🚀 Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Contributing">🤝 Contributing</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">📚 License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;  
</p>

<h4 align="center">
     Siga os passos descritos nos README.md de cada diretorio
</h4>

# Alexa-Super-Hero

## 🌎 Demonstration
Vizualise a na imagem os testes realizados na plataforma de desenvolvimento da alexa.
<h1 align="center">
    <img src="https://github.com/AnGaIs/Amazon-Alexa/blob/master/docs/test.png" />
</h1>


## 🧰 Prerequisites
Make sure you have installed all of the following prerequisites on your machine:
* **[Git](https://git-scm.com/downloads)**;
* **[Node.js](https://nodejs.org/en/download/)** with npm package manager.
* **[vs-code](https://code.visualstudio.com/)** 
* **[Account amazom development](https://developer.amazon.com/)** 


## 🔧 Started

#### Siga a documentação para instalar a **[CLI](https://developer.amazon.com/en-US/docs/alexa/smapi/quick-start-alexa-skills-kit-command-line-interface.html)**.

```sh
# administrator powershell
$ npm install -g --production windows-build-tools
$ npm install -g ask-cli
```

```sh
# run config
$ ask configure
$ > create profile
$ ask init --hosted-skill-id  < na skill criada clique em "copy skill id" e cole o id aqui>
```

```sh
$ https://github.com/PF-Henrique/alexa-herois.git
$ cd api/
$ npm install -g yarn
$ yarn install
```



## 🤝 Contributing
There are many forms to contribute with the project, first of all you can give this github repo a Star.

If you want do help with the code follow the steps bellow

```ts
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.
$ gh repo fork PF-Henrique/Be-The-Hero

# Clone your fork
$ git clone {your-fork-url}
$ cd proffy

# Create a branch with your feature
$ git checkout -b {branch-name}

# Make the commit with your changes
$ git commit -m 'Feat: {feature-name}'

# Send the code to your remote branch
$ git push origin {branch-name}
```

Then send a Pull Request that will be analyzed and approved if it helps with the project



## 📝 License
#### This project is [MIT](LICENSE) licensed. 

