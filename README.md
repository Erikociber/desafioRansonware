Sistema de Criptografia e Descriptografia de Arquivos em Python

Este projeto foi desenvolvido em Python com o objetivo de realizar a criptografia e descriptografia de arquivos de forma simples e segura. A aplicação permite proteger informações contidas em arquivos, convertendo os dados para um formato ilegível sem a chave correta, e posteriormente restaurá-los ao seu estado original através do processo de descriptografia.

Objetivo

O principal objetivo deste projeto é demonstrar conceitos de segurança da informação, criptografia de arquivos e manipulação de dados utilizando Python. Além disso, o projeto foi utilizado como prática em ambiente Linux, proporcionando experiência com ferramentas de linha de comando e testes em sistemas voltados para segurança.

Ambiente de Teste

Os testes foram realizados no Kali Linux, utilizando o terminal para criar e manipular arquivos de teste. Para a criação do arquivo utilizado nos testes, foi empregado o editor de texto Nano, uma ferramenta leve e amplamente utilizada em sistemas Linux.

Criação do arquivo de teste
Shell
nano teste.txt
Mostrar mais linhas

Após a abertura do editor, foi inserido um conteúdo simples para validar o funcionamento do programa. Em seguida, o arquivo foi salvo e utilizado como entrada para os processos de criptografia e descriptografia.

Processo de Teste
Criação do arquivo teste.txt utilizando o Nano.
Execução do script Python para criptografar o arquivo.
Verificação da alteração do conteúdo para um formato criptografado.
Execução do processo de descriptografia.
Comparação do arquivo original com o arquivo recuperado.
Confirmação de que os dados foram restaurados corretamente sem perdas.
Resultados

Os testes demonstraram que o sistema foi capaz de criptografar e descriptografar os arquivos com sucesso. O conteúdo original permaneceu íntegro após o processo de recuperação, comprovando o funcionamento correto da implementação.

Tecnologias Utilizadas
Python 3
Kali Linux
Nano Editor
Terminal Linux
Conclusão

Este projeto serviu como uma aplicação prática dos conceitos de criptografia em Python, permitindo o aprendizado sobre proteção de dados e manipulação de arquivos em ambiente Linux. Os testes realizados no Kali Linux confirmaram a eficiência da solução desenvolvida e contribuíram para o aprimoramento dos conhecimentos em programação e segurança da informação.
