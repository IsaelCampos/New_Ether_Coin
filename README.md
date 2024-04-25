# Criação de uma `Criptomoeda` derivada da rede `Etherreum`

Utilizando o padrão ERC-20 para implementação do nosso `Token`.

**O código está comentado para consultas futuras.**
---
Vamos utilizar:
* Solidity - https://solidity.w3d.community/;
* Truffle - https://archive.trufflesuite.com/;
* Ganache - https://archive.trufflesuite.com/ganache/;
* Remix IDE - https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.25+commit.b61c2a91.js;
* Metamask - https://metamask.io/;

obs: Necessário a instalação de `Nodejs`

**Linux**

`sudo apt update`

`sudo apt install npm curl`

`curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt install -y nodejs`

**Windows**

`https://nodejs.org/en`
---

## Passos.

1 - **Implementação do token ERC-20**

  A implementação do Token ERC-20 e a compilação, foram feitos na linguagem `Solidity` com `IDE-Remix`

2 - **Publicação do Token da Blockchain e rede teste**

  Vamos utilizar o `Ganache` como gerenciador de blockchain, visualizando os blocos criados e a transferência de tokens. Em conjunnto com nossa carteira `Metamask`

3 - **Receber e enviar transações**

  Utilizando a `IDE-Remix podemos visualizar o `envio` e `feedback` das transações.
