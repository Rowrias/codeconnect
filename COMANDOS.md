01. Criando um ambiente com React e Vite
    - npm create vite@latest codeconnect --  --template react
    - cd codeconnect
    - npm install
    - npm run dev (para rodar a aplicação)

02. gh-pages
    - npm install gh-pages --save-dev

    - Colocar esses comandos no scritp do package.json:
        "predeploy": "npm run build",
        "deploy": "gh-pages -d dist"
