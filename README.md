<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h1 align="center">CI/CD na Prática</h1>

  <p align="center">
    Repositório de exemplo para live MRV + dio
    <br />
    <a href="https://webapppreparacaolive.azurewebsites.net/Cat?image=true">Live Demo</a>
    ·
    <a href="https://github.com/chagretes/mrv-dio-devops/issues">Report Bug</a>
    ·
    <a href="https://www.youtube.com/watch?v=dNxjXewXJLA">Gravação da Live</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Indice</summary>
  <ol>
    <li>
      <a href="#descrição">Descrição</a>
      <ul>
        <li><a href="#feito-com">Feito Com</a></li>
      </ul>
    </li>
    <li>
      <a href="#começando">Começando</a>
      <ul>
        <li><a href="#requisitos">Requisitos</a></li>
        <li><a href="#executando-local">Executando Local</a></li>
      </ul>
    </li>
    <li><a href="#licença">Licença</a></li>
    <li><a href="#contato">Contato</a></li>
    <li><a href="#bibliografia">Bibliografia</a></li>
  </ol>
</details>



<!-- Descrição -->
## Descrição

[![Capa][product-screenshot]](https://github.com/chagretes/mrv-dio-devops/blob/main/doc/%5BMRV%5D%20CI-CD%20na%20Pr%C3%A1tica.pdf)

Este repositório serve de exemplo para o projeto de CI/CD utilizado durante a live .net Experts CI/CD na prática.

Ele contempla uma api simples e o yaml para publicação.

### Feito Com

* [Azure DevOps](https://azure.microsoft.com/pt-br/services/devops/)
* [.net Core](https://dotnet.microsoft.com/download/dotnet/3.1)
* [Azure Cloud](https://portal.azure.com/)



<!-- Começando -->
## Começando

Abaixo segue os requisitos para acompanhar a live assim como instruções de como rodar a api localmente

### Requisitos

É necessário ter o sdk do [.net Core](https://dotnet.microsoft.com/download/dotnet/3.1) instalado. Além disso uma conta microsoft deve ser criada tanto no [Azure Cloud](https://portal.azure.com/) quanto no [Azure DevOps](https://azure.microsoft.com/pt-br/services/devops/) para realizar a parte do CI/CD de fato.

### Executando Local

1. Clonar o repositório
   ```sh
   git clone git@github.com:chagretes/mrv-dio-devops.git
   ```
2. Copilar e executar a aplicação
   ```sh
   cd src
   dotnet run
   ```

<!-- LICENSE -->
## Licença

Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.



<!-- CONTACT -->
## Contato

* Felipe Chagas - [@chagretes](https://www.linkedin.com/in/chagretes/) - felipe@chagas.top
* [{entre chaves}](https://open.spotify.com/show/1ub9YZKamdMKdKbLia4YrX)
<!-- ACKNOWLEDGEMENTS -->
## Bibliografia
* [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performin](https://www.amazon.com.br/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
* [YAML schema reference](https://docs.microsoft.com/en-us/azure/devops/pipelines/yaml-schema?view=azure-devops&tabs=schema%2Cparameter-schema)
* [Build, test, and deploy .NET Core apps](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/dotnet-core?view=azure-devops&tabs=dotnetfive)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/chagretes/mrv-dio-devops.svg?style=for-the-badge
[contributors-url]: https://github.com/chagretes/mrv-dio-devops/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/chagretes/mrv-dio-devops.svg?style=for-the-badge
[forks-url]: https://github.com/chagretes/mrv-dio-devops/network/members
[stars-shield]: https://img.shields.io/github/stars/chagretes/mrv-dio-devops.svg?style=for-the-badge
[stars-url]: https://github.com/chagretes/mrv-dio-devops/stargazers
[issues-shield]: https://img.shields.io/github/issues/chagretes/mrv-dio-devops.svg?style=for-the-badge
[issues-url]: https://github.com/chagretes/mrv-dio-devops/issues
[license-shield]: https://img.shields.io/github/license/chagretes/mrv-dio-devops.svg?style=for-the-badge
[license-url]: https://github.com/chagretes/mrv-dio-devops/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/chagretes/
[product-screenshot]: images/capa.png
