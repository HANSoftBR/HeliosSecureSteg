Helios Secure Steg v1.0.0
email: devhansoft@gmail.com
Licença: Este projeto está licenciado sob a licença MIT.

Descrição:
Helios Secure Steg é um programa gratuito de esteganografia com foco em segurança.
Ele permite ocultar arquivos dentro de imagens com proteção criptográfica, utilizando algoritmos avançados como AES e HMAC-SHA256.

Como funciona a criptografia no Helios Secure Steg:
A técnica utilizada insere dados criptografados diretamente nos bits menos significativos (LSB) de cada pixel da imagem.
Cada pixel é composto por canais de cor (vermelho, verde e azul), e cada canal oferece um pequeno espaço onde é possível armazenar um bit de informação,
sem causar alterações visíveis. Quanto maior a resolução da imagem (mais pixels), maior será a capacidade de ocultação de dados.

Sobre os formatos de imagem:
As imagens precisam estar no formato PNG, pois esse formato é sem perdas (lossless) e preserva os valores exatos dos pixels ao salvar.
Se o usuário selecionar uma imagem JPEG, o programa fará automaticamente a conversão para PNG antes de inserir os dados.

Recuperação e salvamento do arquivo oculto:
Durante a esteganografia inversa, o arquivo oculto será descriptografado e salvo em um local escolhido pelo próprio usuário,
com o nome definido por ele.

AVISO DE RESPONSABILIDADE:
- Utilize senhas fortes, com pelo menos 12 caracteres;
- Combine letras maiúsculas, minúsculas, números e símbolos;
- Recomenda-se testar a decriptografia logo após a criptografia;
- Tenha cuidado com os meios de envio e armazenamento;
- Mantenha sempre backups dos arquivos originais;
- Erros podem ocorrer devido a falhas do sistema;
- Não nos responsabilizamos por perda ou acesso não autorizado aos seus dados.
Ao utilizar este programa, você reconhece e aceita os termos descritos acima.

Aviso Legal
Este aplicativo é gratuito e fornecido "no estado em que se encontra" ("as is"), sem garantias de qualquer tipo, expressas ou implícitas.
O desenvolvedor não se responsabiliza por quaisquer danos, perdas de dados ou outros problemas decorrentes do uso deste software.
