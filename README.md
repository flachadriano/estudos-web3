# Roadmap

Este roadmap de estudos focado em Web 3 é baseado neste vídeo: [Roadmap de Estudos para Dev Web3](https://youtu.be/RbmUYb7n7lc?si=htESj0Hn8K8giRaT)

## Blockchain

[Resultado dos estudos deste tópico](./01-blockchain/README.md)

### Tópico: Blockchain Bitcoin
- Fundamentos de Criptomoedas
- Autonomia do Bloco
- Fundamentos da Mineração
- Fundamentos da Carteira Cripto
- Proof of Work
- Taxas de Transação
- Transações e UTXO
- Criptografia da Blockchain (SHA256 e ECDSA)

### Projeto: Protótipo de Blockchain
- Stack sugerida: TypeScript, Node.js, Express
- Orientada a Objetos
- Foco no Livro Razão
- Implementar Mempool
- 100% de cobertura de testes unitários
- Cliente de Mineração
- Cliente de Carteira
- Comunicação HTTP REST

## Smart Contracts

### Tópico I: Blockchain Etherium
- Fundamentos de Altcoins
- Diferença ETH x BTC
- EVM
- Fundamentos Smart Contracts
- Gás

### Tópico II: Solidity
- Remix
- Algoritmos em Solidity
- Estrutura de dados em Solidity
- Calls e Sends
- Enviar e Receber Pagamentos
- Objeto msg
- Constructor
- Design Patterns
- Eventos
- Function Modifiers
- Access/Visibility Modifiers
- Libraries
- Interfaces
- CRUD
- Otimização Básica em Contratos

### Tópico III: Deploy
- MetaMask
- Faucets
- Deploy via Remix
- Explorador de Blocos
- Verificação de Contratos

### Projetos: Jogos Simples
- Par ou Ímpar (PvP e CPU)
- Pedra, Papel ou Tesoura (PvP e CPU)
- Forca (PvP)
- Torneio de Jogos

### Tópico IV: HardHat Toolkit
- Solc
- JSON RPC
- Smart Contracts com HardHat
- Testes Unitários (100% cobertura)
- Scripts de Deploy
- EthersJS

### Tópico V: OpenZeppelin
- Contracts
- Libraries

### Projetos: Token ERC20
- Fundamentos do Padrão ERC-20
- Implementação do Padrão "raw"
- Implementação com OpenZeppelin
- Deploy
- Configuração na Carteira

## DApps

### Tópico I: Web3
- Web1 x Web2 x Web3
- Arquitetura Web3
- ReactJS
- Web3.js
- Backend Web3

### Tópico II: Web3 II
- Segurança de Dapps
- Event Listening
- Next.js
- TailWindCSS
- Deploy Descentralizado
- EthersJS

### Projetos I: Jogos Simples
- Pegar os jogos feitos na fase anterior e criar dapps para eles
- Fazer ajustes nos contratos para que atendam melhor aos dapps
- Usar o event listening para melhorar a experiência

### Projeto II: Protótipo DAO
- Temática que envolva votação. Ex: condomínio, orçamento participativo, congresso/câmara de deputados, urna eletrônica
- Frontend
- Arquitetura Híbrida
- Backend On-Chain
- Backend Off-Chain
- Banco de Dados Auxiliar
- Upload de Arquivos
- EthersJS (v6)
- Material Design

## NFT

### Tópico I: Tokens Não Fungíveis
- Fungível x Não-Fungível
- Aplicabilidade
- ERC721
- Extensões
- Metadados
- IPFS
- Otimizações (ERC721a)

### Tokens ERC721
- Fundamentos do Padrão ERC-721
- Implementação do Padrão "raw"
- Implementação com OpenZeppelin
- Deploy
- Configuração na Carteira
- Configuração na OpenSea

### Projeto II: Página de Minting
- Frontend
- Deploy Descentralizado
- Mídia e Metadados Descentralizados
- Pinata
- Fleek

### Tópico II: Multi-token
- Fungível x Não-Fungível x Semi-Fungível
- Aplicabilidade
- Contratos Multi-Token
- ERC1155
- Extensões

### Projeto III: Plataforma NFT
- Frontend
- Backend
- Banco de Dados
- Smart Contract de Intermediação

## DeFi

### Tópico I: Protocolos
- Fundamentos de DeFi
- Mercado DeFi
- Transferência Delegada (TransferFrom)
- Liquidity Mining
- Staking

### Projetos I: Protocolos
- Saving/Poupança
- Liquidity Mining
- Staking
- Cobrança Recorrente (Assinatura)

### Tópico II: Tokens
- Wrapped Tokens
- Collateral Backed Tokens
- Fiat Backed Stablecoins
- Asset Backed Stablecoins
- Algorithm Stablecoins
- Oracles

### Projetos II: Tokens
- Wrapped ETH
- Dollar Stablecoin (USDT-like)
- Dollar Stablecoin (DAI-like)
- Dollar Price Oracle

### Tópico III: Corretoras Descentralizadas
- Fundamentos de Dex
- Exchanges Centralizadas x Descentralizadas
- Automated Market Maker (AMM)
- Liquidity Provider
- Liquidity Pool
- Routing
- Uniswap v1 e v3

### Projetos III: Bots Dex
- Sinais
- Limit
- Trailing Stop
- Grid
- Flash Loan
- Sniping

## Projeto Final
- Temática envolvendo bots/dex
- Arquitetura Multi-Tenant
- Pagamento com Cripto (recorrente)
- Frontend NextJS (com TS)
- Tema Profissional (TailWindCSS)
- Backend Off-Chain (NestJS)
- Backend On-Chain (Smart Contract Solidity)
- Autenticação Web2 + Web3
- Jobs em Background
- Banco de Dados Auxiliar (MongoDB)
- Prisma ORM
