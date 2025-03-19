# Sprint 3 - CCR (Front-End)

Este repositório contém a implementação do front-end do projeto desenvolvido na Sprint 3 para a CCR. O objetivo do projeto é criar uma interface web responsiva e intuitiva para facilitar a interação dos usuários com a aplicação.

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript
- React.js
- NEXTJS
- TailwindCSS

## Responsividade do projeto
Decisão sobre a Não Utilização da Responsividade no Projeto

A decisão de não implementar responsividade neste projeto foi tomada com base nas necessidades específicas de exibição das telas e no contexto de uso da aplicação.

1. **Tela do Totem**: O projeto será executado em um totem com uma tela de tamanho fixo, variando entre 1200px e 1700px. Como não há variação significativa nas dimensões da tela, a responsividade não se fez necessária, pois a interface foi projetada para funcionar corretamente dentro dessas especificações fixas.

2. **Tela do Site**: A aplicação web foi desenvolvida para ser acessada exclusivamente em dispositivos com telas de tamanho igual ou superior a 800px. Isso garante que os dados sejam apresentados corretamente e de forma otimizada para a experiência do usuário. Como não há necessidade de suporte para dispositivos menores, como smartphones ou tablets, a responsividade foi dispensada.

Portanto, a escolha de não utilizar técnicas de design responsivo foi uma decisão estratégica baseada nas exigências do projeto e no ambiente onde a aplicação será utilizada. Caso futuramente haja a necessidade de adaptação para diferentes tamanhos de tela, a responsividade poderá ser implementada conforme as novas demandas.

## Estrutura do Repositório

```
Sprint3-CCR-FRONT/
│   README.md
│   package.json  # Dependências do projeto
│
├── public/
│   ├── index.html  # Página principal
│
├── src/
│   ├── components/  # Componentes reutilizáveis
│   ├── pages/  # Páginas principais
│   ├── services/  # Integração com APIs
│   ├── App.js  # Componente principal
│   ├── index.js  # Ponto de entrada da aplicação
│
└── assets/
    ├── images/  # Imagens utilizadas no projeto
    ├── styles/  # Estilos CSS globais
```

## Como Executar o Projeto

1. Clone este repositório:
   ```sh
   git clone https://github.com/MatheusHenriqueNF/Sprint3-CCR-FRONT.git
   ```

2. Acesse o diretório do projeto:
   ```sh
   cd Sprint3-CCR-FRONT
   ```

3. Instale as dependências:
   ```sh
   npm install
   ```

4. Inicie o servidor de desenvolvimento:
   ```sh
   npm start
   ```

A aplicação estará disponível em `http://localhost:3000/`.

## Equipe
- **Cleyton Enrike de Oliveira** – RM 560485 - Turma 1TDSQ
- **Matheus Henrique Nascimento de Freitas** – RM 560442 - Turma 1TDSQ
- **Matheus Pinheiro Ermacora Martin** – RM 557720 - Turma 1TDSZ

## Contribuição
Caso queira contribuir para este projeto, siga os passos:
1. Faça um fork do repositório.
2. Crie uma branch para suas alterações (`git checkout -b minha-branch`).
3. Commit suas mudanças (`git commit -m 'Minha contribuição'`).
4. Envie suas alterações (`git push origin minha-branch`).
5. Abra um Pull Request.

## Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

