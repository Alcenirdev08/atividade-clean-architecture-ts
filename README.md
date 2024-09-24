src/
├── entities/
│   └── Item.ts
├── usecases/
│   ├── CreateItemUseCase.ts
│   ├── ListAllItemsUseCase.ts
│   ├── UpdateItemUseCase.ts
│   └── DeleteItemUseCase.ts
├── interfaces/
│   └── ItemRepository.ts
├── frameworks/
│   └── server.ts
└── main.ts

# Clean Architecture with TypeScript

## Aprendizados

Implementação da Clean Architecture em TypeScript com um CRUD simples.

## Estrutura de Pastas

- *entities/*: Contém as entidades do domínio.
- *usecases/*: Contém a lógica de negócios.
- *frameworks/*: Contém a configuração do servidor.

## Rodando o Projeto

1. Instalados as dependências:
   ```bash
   npm install