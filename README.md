<div align="center">

  <h1 id="welcome"></h1>

  <script>
    const welcomeTexts = ["Olá, eu sou o Eduardo!", "Bem-vindo ao meu perfil do GitHub!"];
    let index = 0;

    function typeWelcomeText() {
      const welcomeElement = document.getElementById("welcome");
      const currentText = welcomeElement.textContent;
      const targetText = welcomeTexts[index];

      if (currentText.length < targetText.length) {
        welcomeElement.textContent = targetText.substring(0, currentText.length + 1);
        setTimeout(typeWelcomeText, 100);
      } else {
        setTimeout(eraseWelcomeText, 2000);
      }
    }

    function eraseWelcomeText() {
      const welcomeElement = document.getElementById("welcome");
      const currentText = welcomeElement.textContent;

      if (currentText.length > 0) {
        welcomeElement.textContent = currentText.substring(0, currentText.length - 1);
        setTimeout(eraseWelcomeText, 50);
      } else {
        index = (index + 1) % welcomeTexts.length;
        setTimeout(typeWelcomeText, 500);
      }
    }

    typeWelcomeText();
  </script>

  ## Sobre Mim

  Atualmente estou trabalhando em um projeto pessoal de desenvolvimento web, onde estou aprendendo e aplicando HTML, CSS e JavaScript para criar um site responsivo e interativo.

  ## Habilidades

  - Linguagens de Programação: 
    -<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"> 
    -<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    -<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  - Tecnologias Web: 
    -<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
    -<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
    -<img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"> 
  - Banco de Dados: 
    -<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
    -<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"> 
  - Frameworks: 
    -<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"> 
    -<img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"> 
  - IDEs: 
    -<img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"> 

  ## Redes Sociais

  - [<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/eduardo-rodrigues-oliveira-28a046241?original_referer=https%3A%2F%2Feduardo-rodrigues%2Evercel%2Eapp%2F&originalSubdomain=br)

  ## Estatísticas do GitHub

  ![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=eduardohro&show_icons=true&theme=dark)

  ## Linguagens Mais Usadas

  ![Linguagens Mais Usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=eduardohro&layout=compact&theme=dark)

</div>