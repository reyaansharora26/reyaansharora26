## 👋 Hi, I'm Reyaansh arora!
Welcome to my GitHub! I'm a passionate Full Stack Software Engineer with a strong foundation in frontend development and
expertise in modern web technologies like React.js, Angular, and Node.js. Currently, I'm honing my skills in Information
Technology Solutions at Humber College, and I'm always looking for new challenges to further enhance my technical skills.



      <svg
        width="300"
        height="165"
        viewBox="0 0 300 165"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #fff;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #9f9f9f;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .bold { font-weight: 700 }
    .lang-name {
      font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
      fill: #9f9f9f;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
      /* Animations */
      @keyframes scaleInAnimation {
        from {
          transform: translate(-5px, 5px) scale(0);
        }
        to {
          transform: translate(-5px, 5px) scale(1);
        }
      }
      @keyframes fadeInAnimation {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#151515"
          stroke-opacity="0"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >Most Used Languages</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <svg data-testid="lang-items" x="25">
      
  
      <mask id="rect-mask">
          <rect x="0" y="0" width="250" height="8" fill="white" rx="5"/>
        </mask>
        
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="0"
          y="0"
          width="65.78"
          height="8"
          fill="#3178c6"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="65.78"
          y="0"
          width="56.5"
          height="8"
          fill="#f1e05a"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="122.28"
          y="0"
          width="51.46"
          height="8"
          fill="#e34c26"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="173.74"
          y="0"
          width="33.18"
          height="8"
          fill="#663399"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="206.92000000000002"
          y="0"
          width="26.56"
          height="8"
          fill="#b07219"
        />
      
        <rect
          mask="url(#rect-mask)"
          data-testid="lang-progress"
          x="233.48000000000002"
          y="0"
          width="16.53"
          height="8"
          fill="#4F5D95"
        />
      
      
    <g transform="translate(0, 25)">
      <g transform="translate(0, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#3178c6" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        TypeScript 26.31%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#f1e05a" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        JavaScript 22.60%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#e34c26" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        HTML 20.58%
      </text>
    </g>
  </g></g><g transform="translate(150, 0)"><g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms">
      <circle cx="5" cy="6" r="5" fill="#663399" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        CSS 13.27%
      </text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms">
      <circle cx="5" cy="6" r="5" fill="#b07219" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        Java 10.62%
      </text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms">
      <circle cx="5" cy="6" r="5" fill="#4F5D95" />
      <text data-testid="lang-name" x="15" y="10" class='lang-name'>
        PHP 6.61%
      </text>
    </g>
  </g></g>
    </g>
  
    </svg>
  
        </g>
      </svg>
    

### 🛠️ **Tech Stack**

- **Frontend:** ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React.js-61DAFB?logo=react&logoColor=black) ![Next](https://img.shields.io/badge/next.js-000000?logo=nextdotjs&logoColor=white) ![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white)
- **Frontend:** ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React.js-61DAFB?logo=react&logoColor=black) ![Redux](https://img.shields.io/badge/Redux-764ABC?logo=redux&logoColor=fff) ![Next](https://img.shields.io/badge/next.js-000000?logo=nextdotjs&logoColor=white) ![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white) 
- **Backend:** ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/-Express.js-FFFFFF?logo=Express&logoColor=black) ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white)
- **Database:** ![MySQL](https://img.shields.io/badge/-SQL-4479A1?logo=MySQL&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white) ![OracleSQL](https://img.shields.io/badge/Oracle-F80000?&logo=Oracle&logoColor=white) ![Prisma ORM](https://img.shields.io/badge/-Prisma-5a67d8?logo=Prisma&logoColor=white)
- **Database:** ![MySQL](https://img.shields.io/badge/-SQL-4479A1?logo=MySQL&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?logo=mongodb&logoColor=white) ![OracleSQL](https://img.shields.io/badge/Oracle-F80000?&logo=Oracle&logoColor=white) ![Prisma ORM](https://img.shields.io/badge/-Prisma-5a67d8?logo=Prisma&logoColor=white)
- **Cloud:** ![AWS](https://img.shields.io/badge/Amazon_Web_Services-232F3E?logo=amazon-web-services&logoColor=white) ![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?logo=microsoft-azure&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
- **Tools & Platforms:** ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white) ![Github](https://img.shields.io/badge/-Github-000000?logo=Github&logoColor=white) ![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
