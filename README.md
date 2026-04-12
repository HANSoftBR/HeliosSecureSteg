# Helios Secure Steg v1.0.0
**Status:** Descontinuado  
Este projeto não está mais em desenvolvimento ou manutenção ativa.

> **Status:** Descontinuado  
> Este projeto não está mais em desenvolvimento ou manutenção ativa.

📧 **Contato:** devhansoft@gmail.com  
📄 **Licença:** Licença Proprietária — HANSoft

---

## Descrição

**Helios Secure Steg** é um programa gratuito de **esteganografia com foco em segurança**.

Ele permite **ocultar arquivos dentro de imagens** utilizando proteção criptográfica avançada, combinando técnicas de esteganografia com algoritmos modernos de criptografia.

O objetivo do software é permitir que dados sensíveis sejam armazenados de forma discreta e segura dentro de imagens aparentemente comuns.

---

## Tecnologias de Segurança

O **Helios Secure Steg** utiliza múltiplas camadas de proteção:

- **Criptografia AES**
- **Autenticação HMAC-SHA256**
- **Esteganografia baseada em LSB (Least Significant Bit)**
- **Ofuscação de dados**
- **Inserção de bytes aleatórios**
- **Codificação customizada para dificultar análise**

Essas técnicas aumentam a resistência contra engenharia reversa, análise forense e tentativas de extração não autorizada dos dados ocultos.

---

## Como funciona a criptografia no Helios Secure Steg

A técnica utilizada insere **dados criptografados diretamente nos bits menos significativos (LSB)** de cada pixel da imagem.

Cada pixel é composto por três canais de cor:

- **Vermelho (R)**
- **Verde (G)**
- **Azul (B)**

Cada canal possui pequenos espaços onde é possível armazenar **bits de informação sem causar alterações visíveis na imagem**.

Isso permite que dados sejam ocultados de forma discreta.

Quanto maior a **resolução da imagem**, maior será a **capacidade de armazenamento de dados ocultos**.

---

## Sobre os formatos de imagem

As imagens utilizadas devem estar no formato **PNG**, pois este é um formato **sem perdas (lossless)**.

Esse tipo de imagem preserva os valores exatos dos pixels ao salvar, o que é essencial para manter a integridade dos dados ocultos.

Caso o usuário selecione uma imagem **JPEG**, o programa realizará automaticamente a **conversão para PNG** antes de inserir os dados.

---

## Recuperação do arquivo oculto

Durante o processo de **extração (esteganografia inversa)**:

- Os dados ocultos são localizados na imagem
- O conteúdo é **descriptografado**
- O arquivo original é **restaurado**

O arquivo recuperado será salvo no local escolhido pelo usuário com o **nome definido por ele**.

---

## Aviso de Responsabilidade

Ao utilizar este software, recomenda-se seguir boas práticas de segurança:

- Utilize **senhas fortes**, com pelo menos **12 caracteres**
- Combine **letras maiúsculas, minúsculas, números e símbolos**
- Recomenda-se **testar a descriptografia logo após criptografar**
- Tenha cuidado com os **meios de envio e armazenamento**
- **Mantenha backups dos arquivos originais**
- Erros podem ocorrer devido a **falhas de sistema**
- Não nos responsabilizamos por **perda ou acesso não autorizado aos seus dados**

Ao utilizar este programa, você **reconhece e aceita os termos descritos acima**.

---

## Aviso Legal

Este aplicativo é fornecido **"no estado em que se encontra" ("as is")**, sem garantias de qualquer tipo, expressas ou implícitas.

O desenvolvedor **não se responsabiliza por quaisquer danos, perdas de dados ou outros problemas decorrentes do uso deste software**.

---

## Licença

Este software está protegido por **licença proprietária da HANSoft**.

A redistribuição, modificação, engenharia reversa ou reutilização do código-fonte **não é permitida sem autorização prévia por escrito**.

Consulte o arquivo **LICENSE.md** para os termos completos da licença.
