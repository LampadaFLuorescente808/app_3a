
# Super Contadores Empresariais 2010 (atualizado)

<div align="center">
  <img src="https://i.imgur.com/B9hHOm3.png" width="300" alt="Logo do Super Contadores" />
</div>

---

## 🧾 Sobre

**Super Contadores Empresariais 2010** é um sistema atualizado voltado para a gestão contábil de pequenas e médias empresas. Ele tem como objetivo centralizar processos contábeis e financeiros, tornando-os mais eficientes e acessíveis para escritórios de contabilidade.

---

## 🛠️ Stack Utilizada

<p align="left">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-F55247?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

---

## ⚙️ Instalação

> Pré-requisitos: Docker, Docker Compose e Composer instalados.

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/super-contadores.git
   cd super-contadores
   ```

2. Copie o arquivo `.env`:
   ```bash
   cp .env.example .env
   ```

3. Suba os containers com Docker:
   ```bash
   docker-compose up -d
   ```

4. Instale as dependências com o Composer:
   ```bash
   docker exec -it app composer install
   ```

5. Gere a key da aplicação:
   ```bash
   docker exec -it app php artisan key:generate
   ```

6. Rode as migrations:
   ```bash
   docker exec -it app php artisan migrate
   ```

7. Acesse em: [http://localhost:8000](http://localhost:8000)

---

## ✅ Funcionalidades

- Cadastro de empresas, clientes e contadores
- Emissão de relatórios contábeis
- Controle de permissões e usuários
- Dashboard com KPIs e estatísticas
- Integração com APIs externas (ex: Receita Federal, NFSe)

---

## 📚 Aprendizados

- Estruturação de um projeto Laravel com Docker
- Conhecimento do padrão de projeto MVC

---

## 👥 Autores

- [Isaac Alves](https://github.com/LampadaFLuorescente808)
- [Ana Karoliny](https://github.com/karoliny00)
- [Thyago Tristão](https://github.com/jogandoalemdatela)

---

## 🤝 Contribuindo

Contribuições são bem-vindas!

1. Faça um fork do projeto
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m 'feat: minha nova feature'`
4. Push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

---

