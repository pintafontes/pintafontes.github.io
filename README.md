# pintafontes.github.io
Isto é un repositorio para gardar, ordenar, sincronizar e compartir a documentación dos meus proxectos persoais. Inclúe o traballo con repositorios GIT, a xestión de ordenadores con GNU/Linux, a construción e programación de dispositivos IoT e tamén como levar adiante unha pequena horta.

## Linguaxe Markdown
É unha linguaxe que permite dar un formato mínimo para o texto e as imaxes en moitos servizos web. É o que se usa para escribir en Github e outros servizos. Este mesmo arquivo está formateado con Markdown.

Markdown é moi fácil de usar: basta con escribir o texto *en claro* e acompañalo de caracteres especiais como `*` ou `#` para transformar o aspecto do documento.
#### Formateo básico
Aquí tes a miña **chuleta de Markdown**

Modificador | Resultado
----------- | ---------
\### Encabezado 3  | **Encabezado 3**
\*\*Grosa\*\* e \*Cursiva\*  | **Grosa** e _Cursiva_
\[Ligazon\]\(URL\)  | [Ligazon](URL)
\!\[Imaxe\]\(URL\)  | [Imaxe](URL)
\` Código\` | `Código`
\> Cita | Texto citado

* Para facer un novo parágrafo hai que deixar unha liña en branco.
* Pódese inserir calquera etiqueta de `HTML` no texto.
* En editores de texto como **Atom** e **VSCode** podemos atallar algunhas das operacións de formateo seleccionando o texto e aplicando o modificador unha soa vez.
* Para facer unha táboa hai que marcar os encabezados con guións por debaixo e as diferentes columnas con `|`:

```
Cabeza 1  | Cabeza 2
------ | -----
Elemento 1 | Elemento 2
```

Cabeza 1  | Cabeza 2
-------- | -------
Elemento 1 | Elemento 2

#### Para saber máis
Eu aprendín todo nestas dúas páxinas:
* Unha introducción básica en [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* Un titorial completo en [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## GIT e GitHub
**GIT** é un software que permite o traballo con diferentes versións dun mesmo conxunto de arquivos. Está pensado para desenvolver software colaborativamente entre varias persoas.

Hai unha lóxica propia detrás da idea de manipular de xeito consistente múltiples versións de múltiples arquivos modificados en diferentes momentos por diferentes persoas e aloxados en diferentes dispositivos. Esta lóxica non é nada intuitiva para principiantes coma min e é unha barreira difícil de superar se non adicamos un tempo a aprender e netender o sistema.

Eu recibín o impulso definitivo cando quixen sincronizar en dous ordenadores diferentes o código dos meus proxectos IoT. A sincronización fágoa habitualmente con Dropbox, pero cando empecei a usar `VSCode + Platform.io` había un problema coas rutas absolutas nos arquivos dos proxectos e non funcionaba. GIT vaime permitir solventar esta dificultade.

**GitHub** é un servizo na nube para xestionar diferentes versións de arquivos con GIT. Está pensado para traballar con proxectos de programación, pero pode ser usado simplemente para a xestión de versións de arquivos de calquera tipo.

GitHub ofrece contas gratuitas onde se poden xestionar un número ilimitado de repositorios públicos e privados.

Os entornos de desenvolvemento como VSCode ou Atom ofrecen unha integración total con GIT e GitHub, o que facilita moito o noso traballo.

Eu estou empezando a familiarizarme con este ecosistema construindo este repositorio, polo que só vou traballar coas funcións máis básicas de GIT.

* [An Intro to Git and GitHub for Beginners (Tutorial)](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
* [GitHub guides: Hello World](https://guides.github.com/activities/hello-world/)
