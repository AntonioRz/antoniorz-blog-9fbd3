---
title: ¿Qué son los factores de autenticación y por qué debería usar más de uno?
subtitle: >-
  Cuando entiendes que tus contraseñas no son suficiente, estás listo para dar
  el siguiente paso.
date: '2022-01-26'
categories:
  - content/data/categories/general.yaml
  - content/data/categories/news.yaml
tags:
  - content/data/tags/informativo.yaml
  - content/data/categories/news.yaml
excerpt: 'Internet no fue hecho para ser seguro. Entonces, ¿Cómo nos protegemos?'
thumb_image_alt: Factores de autenticación
image_alt: Factores de autenticación
image_position: left
seo:
  title: ¿Qué carajos es la seguridad informática?
  description: Explicación sencilla de seguridad informática
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: ¿Qué carajos es la seguridad informática?
      keyName: property
    - name: 'og:description'
      value: Explicación sencilla de seguridad informática
      keyName: property
    - name: 'og:image'
      value: images/blog1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: ¿Qué carajos es la seguridad informática?
    - name: 'twitter:description'
      value: Explicación sencilla de seguridad informática
    - name: 'twitter:image'
      value: images/blog1.jpg
      relativeUrl: true
layout: post
thumb_image: /images/whoami.jpg
author: content/data/team/person-degljnwqn.json
image: /images/whoami-d250414d.jpg
---
Un **factor de autenticación** es aquel elemento que “*asegura*” que tú eres quien dices ser al acceder a una cuenta. El más claro ejemplo de esto es una contraseña. Una contraseña “*asegura*” que Antonio es @soyantoniorz porque Antonio es quien conoce esa palabra mágica para tener acceso a dicha cuenta. Sin embargo, las [contraseñas mal usadas](https://soyantoniorz.com/blog/password-seguro/) no son el elemento en el que más podemos confiar. Es por eso que debemos aprovechar el **uso de más de un factor de autenticación** siempre que sea posible.

*¿Pero cómo puedo poner dos contraseñas para una misma cuenta?* Bueno, no se trata de esto, sino de aprovechar **otros métodos que demuestran que tú eres quien dices ser**.

Otra forma de hacerlo es **tener **algo que demuestre que eres tú. Por ejemplo, cuando muestras tu gafete godin enmicado que demuestra que trabajas en el edificio X, o cuando muestras tu credencial del INAPAM para subir gratis al metro. El policía de la entrada (la entidad autenticadora) confía en que eres tú porque traes una credencial que así lo dice. Es importante recalcar aquí que **esta credencial debe ser generada por una entidad oficial**, por ejemplo, la administración del edifico donde trabajas o el Gobierno de tu ciudad.

El problema aquí es que no existe una oficina de administración del Internet que nos genere una credencial universal para ser acreditados como ciudadanos de Internet. Pero cada sitio es responsable de su propia administración y generación de “*credenciales*” de su servicio. Sin embargo, la generación de estas credenciales para cada usuario sería ineficiente. Lo anterior se sustituye con la **generación de códigos aleatorios** que “*aseguran*” que el usuario que tiene el código es quien dice ser. Estos códigos nos llegan en forma de **SMS o tokens** (*códigos de sólo un uso*). Por ejemplo los que son generados por tu aplicación de banco. Puesto que **este número sólo fue creado para ti en ese preciso momento** que lo solicitaste, es mucho más probable que \*\*sí \*\*seas tú.

El último factor de autenticación que tenemos \*\*somos \*\*nosotros mismos. Es decir, algo que nos identifique como únicos en el mundo, algo que sólo nosotros **somos**. Esto se logra con el uso de **chips biométricos** que leen tu identificador único (*huella digital, reconocimiento facial, iris*, etc.).

Uno podría pensar que el uso de factores de autenticación **biométricos es *más seguro*, sin embargo esto dependerá mucho de la calidad de su fabricación. Este tipo de sensores suelen tener un porcentaje de eficiencia que nunca será del 100%. Es por esto que lo ideal sería combinar dos o más factores de autenticación.**

> El uso de múltiples factores de autenticación aumenta la probabilidad de que realmente sí seas tú quien pide acceso a una cuenta, reduciendo así el riesgo a un “hackeo”.

Es probable que *ya estés usando múltiples factores de autenticación sin siquiera saberlo*. Por ejemplo, cuando inicias sesión en la app de tu banco con tu huella digital o FaceID. Aquí estás usando **algo que tienes** (tu teléfono celular) y **algo que eres** (tu huella digital o tu cara).

#### Muchos servicios web ya brindan la posibilidad de habilitar el uso de múltiples factores de autenticación.

La mayoría de ellos usan el envío de mensajes de texto o el uso de **apps de autenticación**. Estas apps generan códigos aleatorios que tendrás que introducir al tratar de iniciar sesión. Algunas de estas **aplicaciones son gratuitas** (Google Authenticator o Microsoft Authenticator). Aquí la recomendación es usar estas apps, puesto que hay más probabilidad de sufrir un hackeo en los SMS que en estas aplicaciones.

Una vez que habilitas el segundo factor de autenticación, **SIEMPRE guarda los códigos de emergencia** que son generados. Podrás hacer uso de estos códigos si es que pierdes el acceso a la app de autenticación o al teléfono que recibe los SMS. Si no tienes un respaldo de esos códigos, vas a sufrir mucho para recuperar el acceso a tu cuenta. Si usas una app de autenticación, entonces puedes *sincronizar los códigos aleatorios en algún otro teléfono*.

Espero que esta información te ayude a entender mejor cómo funcionan los factores de autenticación y por qué deberías usar más de uno. Intenta activarlos en tus redes sociales y si no te sientes cómodo, sólo deshabilítalo y listo, seguirás tan seguro como siempre con tu contraseña.
