# Encryptor Pro Ultra

## Descrição
Este é um programa de criptografia em JavaScript que oferece três métodos diferentes para encriptar mensagens:

- **Cifra de César**: Desloca os caracteres do alfabeto por um número especificado de posições.
- **Cifra de Símbolos**: Substitui caracteres específicos por símbolos semelhantes.
- **Cifra Reversa**: Inverte a ordem das letras dentro de cada palavra da mensagem.

O programa pode ser utilizado de forma modular para aplicar uma dessas cifras individualmente ou combinar as três para criar um sistema de criptografia mais sofisticado.

---

## Instalação

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em seu sistema.

Clone este repositório e navegue até a pasta do projeto:

```sh
 git clone <URL_DO_REPOSITORIO>
 cd encryptor-pro-ultra
```

---

## Uso

### 1. Utilizando um método de criptografia individual

Para criptografar uma mensagem usando um método específico, execute:

```sh
node encrypt-inc.js [caesar|symbol|reverse] [amount]
```

**Exemplo:**

```sh
node encrypt-inc.js caesar 4
```

Após executar o comando, digite a mensagem e pressione `Enter` para ver o resultado criptografado.

### 2. Utilizando a criptografia completa (Encode e Decode)

O programa **Encryptor Pro Ultra** aplica uma combinação das três cifras para um método de encriptação mais seguro.

- Para encriptar uma mensagem:

  ```sh
  node encryptor-pro-ultra.js encode
  ```
  Digite sua mensagem e pressione `Enter`.

- Para descriptografar uma mensagem:

  ```sh
  node encryptor-pro-ultra.js decode
  ```
  Digite a mensagem encriptada e pressione `Enter` para obter o texto original.

---

## Exemplos

Entrada:
```sh
node encryptor-pro-ultra.js encode
> Olá, Mundo!
```

Saída:
```sh
> !dn0M ,@4l0
```

Decodificação:
```sh
node encryptor-pro-ultra.js decode
> !dn0M ,@4l0
```

Saída:
```sh
> Olá, Mundo!
```

---

## Contribuição
Sinta-se à vontade para contribuir com melhorias! Envie um pull request ou relate problemas na seção de Issues.

---

## Licença
Este projeto é distribuído sob a licença MIT.