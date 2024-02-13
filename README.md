# Projeto IAC com Apache - Servidor Web

## Descrição
Este projeto de infraestrutura como código (IAC) utiliza o Apache para criar um servidor web que hospeda um site moderno com páginas HTML, CSS (incluindo SCSS), JavaScript e Bootstrap. A automação visa facilitar a implementação e manutenção de servidores web.

## Estrutura do Projeto
- **`ansible/`**: Contém os arquivos Ansible para automação.
  - `playbook.yml`: Playbook principal para configurar o servidor web.
  - `files/`: Arquivos estáticos do site (HTML, CSS, JavaScript).
    - `scss/`: Arquivos SCSS para estilos.
  
- **`docs/`**: Documentação relacionada ao projeto.
  - `README.md`: Documentação principal do projeto.

## Uso
1. Clone o repositório:
   ```bash
   git clone https://github.com/PBorba18/linux-projeto2-iac.git
   cd linux-projeto2-iac
   ```

2. Execute o playbook Ansible para configurar o servidor:
   ```bash
   ansible-playbook ansible/playbook.yml
   ```

   O servidor web estará disponível em http://localhost.

## Páginas do Site
O site é composto por diversas páginas estáticas localizadas em `ansible/files/`:
- `index.html`: Página inicial.
- `about.html`: Página "Sobre Nós".
- `contact.html`: Página de contato.

## Tecnologias Utilizadas
- HTML
- CSS (incluindo SCSS)
- JavaScript
- Bootstrap

## Pré-requisitos
- Ansible instalado no ambiente de desenvolvimento.
- Sistema operacional compatível com o Ansible (Linux recomendado).
- Conexão à internet para instalação de dependências.

## Contribuição
Fique à vontade para contribuir com melhorias, correções de bugs ou novos recursos. Basta abrir uma [issue](https://github.com/PBorba18/linux-projeto2-iac/issues) ou enviar um [pull request](https://github.com/PBorba18/linux-projeto2-iac/pulls).

## Licença
Este projeto é distribuído sob a licença [MIT](LICENSE).
```

Certifique-se de revisar e ajustar conforme necessário para garantir que todas as informações estejam corretas para o seu projeto.
