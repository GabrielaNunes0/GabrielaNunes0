#  Olá, eu sou a Gabriela Nunes  

 Estudante de **Análise e Desenvolvimento de Sistemas (ADS)**  
 Apaixonada pelo universo da **Cibersegurança**  
 Atualmente focada em evoluir nas linguagens abaixo  

---

##  Tecnologias & Linguagens que estudo  
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=database&logoColor=white)  

---

<img src="./snake.svg" alt="Cobrinha que come commits" />


<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="640" height="140" viewBox="0 0 640 140" role="img" aria-label="Cobrinha que come commits">
  <title>Cobrinha que come commits</title>

  <!-- Fundo -->
  <rect width="100%" height="100%" fill="transparent" />

  <!-- Texto -->
  <text x="20" y="20" font-family="Arial, Helvetica, sans-serif" font-size="14" fill="#333">commit snake</text>

  <!-- Quadradinhos que representam "commits" -->
  <!-- positions: 60, 140, 220, 300, 380, 460 (px) -->
  <g id="commits">
    <rect x="60"  y="50" width="24" height="24" rx="4" ry="4" fill="#6ee7b7" opacity="1">
      <!-- Anima opacity: aparece -> some -> reaparece durante o loop (usando keyTimes) -->
      <animate attributeName="opacity" dur="6s" repeatCount="indefinite" values="1;0;1" keyTimes="0;0.08;1" />
    </rect>
    <rect x="140" y="50" width="24" height="24" rx="4" ry="4" fill="#60a5fa" opacity="1">
      <animate attributeName="opacity" dur="6s" repeatCount="indefinite" values="1;0;1" keyTimes="0;0.24;1" />
    </rect>
    <rect x="220" y="50" width="24" height="24" rx="4" ry="4" fill="#fca5a5" opacity="1">
      <animate attributeName="opacity" dur="6s" repeatCount="indefinite" values="1;0;1" keyTimes="0;0.40;1" />
    </rect>
    <rect x="300" y="50" width="24" height="24" rx="4" ry="4" fill="#fbbf24" opacity="1">
      <animate attributeName="opacity" dur="6s" repeatCount="indefinite" values="1;0;1" keyTimes="0;0.56;1" />
    </rect>
    <rect x="380" y="50" width="24" height="24" rx="4" ry="4" fill="#a78bfa" opacity="1">
      <animate attributeName="opacity" dur="6s" repeatCount="indefinite" values="1;0;1" keyTimes="0;0.72;1" />
    </rect>
    <rect x="460" y="50" width="24" height="24" rx="4" ry="4" fill="#34d399" opacity="1">
      <animate attributeName="opacity" dur="6s" repeatCount="indefinite" values="1;0;1" keyTimes="0;0.88;1" />
    </rect>
  </g>

  <!-- Trilho / pista -->
  <line x1="40" y1="62" x2="540" y2="62" stroke="#e6e6e6" stroke-width="4" stroke-linecap="round" />

  <!-- Cobrinha (um círculo com "olho") que percorre da esquerda para a direita -->
  <g id="snake" transform="translate(0,0)">
    <!-- corpo principal -->
    <circle id="head" cx="20" cy="62" r="12" fill="#16a34a" />
    <!-- olho -->
    <circle cx="24" cy="58" r="2.2" fill="#fff" />
    <circle cx="24.5" cy="58" r="1" fill="#000" />

    <!-- animação de movimento da cabeça (cx animado) -->
    <animate xlink:href="#head" attributeName="cx" from="20" to="520" dur="6s" repeatCount="indefinite" />

    <!-- uma sombra/clone menor para dar efeito de rastro -->
    <circle cx="8" cy="62" r="8" fill="#059669" opacity="0.85">
      <animate attributeName="cx" from="8" to="508" dur="6s" repeatCount="indefinite" />
    </circle>

    <!-- uma "linguinha" pontual que pisca -->
    <path d="M20 70 q6 4 12 0" fill="none" stroke="#dc2626" stroke-width="2" stroke-linecap="round" opacity="0.9">
      <animate attributeName="d" dur="6s" repeatCount="indefinite"
        values="
          M20 70 q6 4 12 0;
          M60 70 q6 4 12 0;
          M120 70 q6 4 12 0;
          M200 70 q6 4 12 0;
          M280 70 q6 4 12 0;
          M360 70 q6 4 12 0;
          M20 70 q6 4 12 0
        " />
    </path>
  </g>

  <!-- legenda pequena -->
  <text x="20" y="120" font-family="Arial" font-size="11" fill="#666">Cobrinha: simulando commits sendo 'comidos' — loop animado</text>
</svg>


---

##  Estatísticas do GitHub  

![Estatísticas GitHub](https://github-readme-stats.vercel.app/api?username=GabrielaNunes0&show_icons=true&theme=radical)  

![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielaNunes0&layout=compact&theme=radical)  

---

##  Onde me encontrar  
- [LinkedIn](https://www.linkedin.com/in/gabriela-nunes-648950351)  
- ✉️ E-mail: gabrielanuniezz@gmail.com  

---

 Obrigada por visitar meu perfil!   
