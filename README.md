WorldGenerator Plugin

Descrição

O WorldGenerator permite carregar mundos gerados com os tipos Flat e Void, incluindo compatibilidade com mundos antigos. O plugin também configura spawns automáticos para jogadores em mundos definidos.

Recursos

Suporte a geradores personalizados:

VoidGenerator: Mundos completamente vazios.

FlatGenerator: Mundos planos.


Compatibilidade com versões antigas.

Configuração de spawn por mundo via config.yml.



---

Instalação

```bash
1. Coloque o plugin na pasta plugins/ do seu servidor PocketMine.
```

```bash
2. Reinicie o servidor para gerar o arquivo config.yml.
```

```bash
3. Configure os mundos e spawns no config.yml como:

worlds:
  meu_mundo:
    spawn:
      x: 100
      y: 64
      z: 200
```

```bash
4. Reinicie o servidor para aplicar as configurações.
```

Requisitos

PocketMine-MP 4.0 ou superior.

PHP 8.0 ou superior.


Simples, funcional e perfeito para gerenciar seus mundos no servidor!
