# Projeto RSA - Matemática Discreta

Grupo:

- Samuel Brederodes
- Antônio Sérgio
- Almir Dias
- Thiago Araújo


## Rodando a Aplicação

Certifique-se que o build system `meson` e a biblioteca `gmp` estejam instalados no seu sistema.
Em seguida:

```bash
meson setup builddir
meson compile -C ./builddir
./builddir/rsa
```

A aplicação poderá então ser acessada por `https://localhost:3000`.
