<div align="center">
  <img src="./.github/assets/generation-bg.png" alt="Logo" height="200">
  <h1 align="center"><strong>Conta Bancaria – Turma JavaScript 10</strong></h1>
  <p align="center">Simulação de um sistema bancário simples (CRUD de contas e operações).</p>
</div>

## **Sobre**

Projeto didático que implementa operações básicas de uma conta bancária: criação, listagem, busca, atualização, exclusão, saque, depósito e transferência entre contas. Desenvolvido como atividade prática da turma de JavaScript da Generation.

## **Funcionalidades**

- Criar, listar e consultar contas por número
- Atualizar e apagar contas
- Sacar e depositar valores
- Transferir valores entre contas
- Menu interativo via terminal (utilizando `readline-sync`)

## **Tecnologias**

- TypeScript
- Node.js (ES Modules)
- `readline-sync` para interação no terminal

## **Instalação**

1. Clone o repositório:

```bash
git clone [https://github.com/Lancellot/conta_bancaria](https://github.com/Lancellot/conta_bancaria.git)
cd conta_bancaria
```

2. Instale dependências:

```bash
npm install
```

3. Execute o programa com `ts-node` (necessário ter `ts-node` instalado globalmente ou como devDependency):

```bash
npx ts-node Menu.ts
```

Observação: o projeto está configurado para usar módulos ES (`"type": "module"` no `package.json`) e o `tsconfig.json` já contém ajustes para Node ESM.

## **Uso**

Ao executar `ts-node Menu.ts`, o aplicativo exibirá um menu no terminal. Digite o número da opção desejada e pressione Enter.

Exemplo:

```text
1 - Criar Conta
2 - Listar todas as Contas
...
9 - Sair
```

Ao escolher `9` o programa exibirá informações sobre o projeto e fará o encerramento.

## **Estrutura do projeto**

- `Menu.ts` (raiz) — arquivo principal que inicializa o menu e a interação
- `src/` — código fonte (algumas versões utilizam `src/Menu.ts`)
- `src/util/Colors.ts` — utilitário de cores para saída no terminal
- `package.json` — dependências e metadados do projeto
- `tsconfig.json` — configuração TypeScript

## **Contribuição**

Contribuições são bem-vindas. Para contribuir:

1. Fork o repositório
2. Crie uma branch com sua feature: `git checkout -b minha-feature`
3. Faça commits das suas alterações: `git commit -m "Descrição das mudanças"`
4. Envie para o repositório remoto: `git push origin minha-feature`
5. Abra um Pull Request descrevendo suas mudanças

## **Licença**

Licença aberta — adapte conforme necessário. Se desejar, adicione um arquivo `LICENSE`.

## **Contato**

Projeto desenvolvido como parte da formação Generation Brasil.

---

Se quiser, eu posso também:

- adicionar um script `start` no `package.json` para rodar com `npm start`;
- remover/normalizar extensões `.ts` nas importações;
- adicionar instruções de testes ou execução no Windows PowerShell.
