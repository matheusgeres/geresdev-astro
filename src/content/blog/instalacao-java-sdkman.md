---
title: Instalação do Java no Linux via SDKMAN
pubDatetime: 2019-08-21 00:30:58
featured: true
tags: 
  - linux
  - java
  - sdkman
  - ubuntu
  - linux mint
description:
    Instale o Java no Linux via SDKMAN e tenho um gerenciador poderoso para Java, gradle, maven e muito mais!
---
![SDKMAN Logo](@assets/images/instalacao-java-sdkman/sdkman.png)
A instalação do Java pode ser facilitada através do SDKMAN, ele configura as variáveis de ambiente e tem
várias versões do java.

Para instalar: https://sdkman.io/install

Já a configuração do Java é bem simples através dos seguintes comandos.
<!-- more --> 
```bash
sdk list java
```

![Lista dos Javas disponíveis do SDKMAN](@assets/images/instalacao-java-sdkman/print-sdkman-java.png)

Observe que temos várias versões do Java! 😁

Você pode instalar a versão do Java que a Amazon disponibiliza ou a do Zulu, que são empresas que criam versões da JDK que respeitam as diretrizes da Oracle e são compatíveis com a JDK da Oracle. Massa né?

Para instalar é super fácil, basta rodar o comando com a versão desejada da JDK.
```bash
sdk install <identifier da versão desejada>
```

Veja um exemplo de como rodar.

```bash
sdk install java 8.0.222-zulu
```

E pronto! O Java está configurado e as variáveis de ambiente setadas! Muito massa, né? 😉