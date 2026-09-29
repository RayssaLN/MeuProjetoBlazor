# MeuProjetoBlazor

Projeto desenvolvido como atividade prática da unidade curricular **UDWMJ** (Usabilidade, Desenvolvimento Web e Mobile com Java) do **6º período** do curso de graduação.

## 👤 Identificação

| Campo | Valor |
|-------|-------|
| **Aluno** | Eduardo Alves e Santos |
| **RA** | 124114208 |
| **UC** | UDWMJ |
| **Período** | 6º |

## 📋 Sobre o Projeto

Este é um projeto simples criado com **Blazor Server** (.NET 10) para exercitar os conceitos fundamentais do framework. A aplicação contém páginas de exemplo geradas pelo template padrão do Blazor, com pequenas personalizações, servindo como introdução ao desenvolvimento web com componentes Razor.

## 🚀 Funcionalidades

- **Home** — Página inicial com mensagem de boas-vindas.
- **Counter** — Contador interativo que demonstra o uso de eventos e data binding no Blazor.
- **Weather** — Tabela de previsão do tempo com dados simulados, demonstrando renderização de listas e streaming rendering.
- **Exemplo** — Página adicional com exibição de variável, demonstrando a diretiva `@code`.

## 🛠️ Tecnologias Utilizadas

- [.NET 10](https://dotnet.microsoft.com/)
- [Blazor Server](https://learn.microsoft.com/aspnet/core/blazor/) (Interactive Server Render Mode)
- C# / Razor Components

## 📁 Estrutura do Projeto

```
MeuProjetoBlazor/
├── Components/
│   ├── Layout/          # Layout principal e menu de navegação
│   ├── Pages/           # Páginas da aplicação (Home, Counter, Weather, Exemplo)
│   ├── App.razor        # Componente raiz
│   ├── Routes.razor     # Configuração de rotas
│   └── _Imports.razor   # Imports globais
├── wwwroot/             # Arquivos estáticos (CSS, JS, etc.)
├── Program.cs           # Ponto de entrada da aplicação
├── MeuProjeto.csproj    # Arquivo de projeto
└── appsettings.json     # Configurações da aplicação
```

## ▶️ Como Executar

1. Certifique-se de ter o [.NET 10 SDK](https://dotnet.microsoft.com/download) instalado.
2. Clone o repositório:
   ```bash
   git clone https://github.com/eduardoalvese13/MeuProjetoBlazor.git
   ```
3. Navegue até a pasta do projeto:
   ```bash
   cd MeuProjetoBlazor
   ```
4. Execute a aplicação:
   ```bash
   dotnet run
   ```
5. Acesse no navegador: `https://localhost:5001` (ou a porta indicada no terminal).

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.