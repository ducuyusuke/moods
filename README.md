# 📚 Biblioteca dos Sonhos

A Biblioteca dos Sonhos é um app que recomenda livros com base no clima da sua cidade. Em dias chuvosos? Um suspense gótico. Céu limpo? Uma aventura leve. Conecte-se, escolha sua cidade, e receba sugestões que combinam com o seu dia — direto na sua caixa de entrada.

## 🚀 Funcionalidades

- Login e registro com Devise
- Regras de acesso com Pundit
- Consulta de clima em tempo real
- Recomendação literária via Google Books API
- Interface moderna com Bootstrap 5
- Atualizações dinâmicas via Hotwire (Turbo + Stimulus)
- Envio de recomendações semanais por email

## 🛠️ Tecnologias Usadas

- Ruby on Rails 7
- Devise + Pundit
- Turbo Frames + Stimulus
- Bootstrap 5
- HTTParty (chamadas HTTP)
- WeatherAPI + Google Books API
- Sidekiq + cron
- PostgreSQL

## 📦 Setup

```bash
git clone https://github.com/seu-usuario/biblioteca-dos-sonhos.git
cd biblioteca-dos-sonhos
bundle install
rails db:setup
rails s
