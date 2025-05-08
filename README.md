# Gerenciador Financeiro

## Descrição
Sistema web para gerenciamento de finanças pessoais, desenvolvido com React, TypeScript e Tailwind CSS. Permite o controle de receitas e despesas, visualização de relatórios e análise de gastos por categoria.

## Índice
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Arquitetura](#arquitetura)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura de Dados](#estrutura-de-dados)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Funcionalidades
- ✅ Registro de receitas e despesas
- 📊 Gráfico de distribuição de gastos
- 🔍 Pesquisa e filtragem de transações
- 📅 Análise mensal de gastos
- 🌓 Tema claro/escuro
- 📱 Interface responsiva
- 💾 Persistência local de dados
- 🔔 Notificações de ações

## Tecnologias
- React 18.3.1
- TypeScript
- Tailwind CSS
- Vite
- Lucide React (ícones)
- React Hot Toast (notificações)
- Recharts (gráficos)

## Arquitetura

### Estrutura de Diretórios
```
src/
├── models/          # Classes e interfaces
├── docs/           # Documentação
├── components/     # Componentes React
└── styles/        # Estilos CSS
```

### Modelagem de Dados
O sistema utiliza três entidades principais:
- **Transaction**: Registros de receitas e despesas
- **User**: Informações do usuário
- **Category**: Categorias de transações

Para mais detalhes, consulte o [Diagrama ER](docs/DER.md).

## Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/gerenciador-financeiro.git

# Acesse o diretório
cd gerenciador-financeiro

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

Para criar uma build de produção:
```bash
npm run build
```

Para visualizar a build de produção localmente:
```bash
npm run preview
```

## Manutenção
Para atualizar o sistema, execute:
```bash
git pull origin main
npm install
```

## Equipe
Nossa equipe é composta por profissionais dedicados ao desenvolvimento e manutenção deste projeto:

### Desenvolvedores
- João Silva - Desenvolvedor Frontend
- Maria Santos - Desenvolvedora Frontend
- Pedro Oliveira - Desenvolvedor Full Stack

### Design
- Ana Costa - UI/UX Designer

### Gestão
- Carlos Mendes - Product Owner
- Beatriz Souza - Scrum Master

## Contribuição

### Processo
1. Fork o repositório
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

### Padrões
- Use TypeScript
- Siga as regras do ESLint
- Mantenha a formatação do Prettier
- Escreva testes para novas funcionalidades
- Mantenha os componentes React pequenos e focados
- Use Tailwind CSS para estilização

## Licença
Este projeto é licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.