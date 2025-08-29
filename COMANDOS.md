01. Criando um ambiente com React e Vite
    - npm create vite@latest codeconnect --  --template react
    - cd codeconnect
    - npm install
    - npm run dev (para rodar a aplicação)

02. Publicar com o gh-pages
    - npm install gh-pages --save-dev

    - Colocar esses comandos no script do package.json:
        "predeploy": "npm run build",
        "deploy": "gh-pages -d dist"

    - Colocar esse comando antes do script:
        "homepage": "https://Rowrias.github.io/codeconnect/",

03. Publicar com a Vercel:
    - npm install -g vercel
    - vercel :
        - continue with github
