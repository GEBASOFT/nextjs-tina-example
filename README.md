# nextjs-tina-example
Simple next.js project using tinacms

Criar um arquivo .env.local contendo os seguintes campos:

```
NEXT_PUBLIC_TINA_CLIENT_ID=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
NEXT_PUBLIC_CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

NEXT_PUBLIC_USE_LOCAL_CLIENT=1
```

A primeira variável (NEXT_PUBLIC_TINA_CLIENT_ID) pode ser encontrada ao logar no site oficial da tina [aqui](https://app.tina.io/signin). Feita a autenticação, basta criar um novo projeto e pegar o ID fornecido.

Cloudinary é a plataforma para hospedar arquivos (imagem e vídeos).
Basta criar uma conta no [site](https://cloudinary.com/) deles e pegar as credenciais necessárias para colocar no .env.local.
