# Pesados Web

**Plataforma brasileira de classificados para veículos pesados e equipamentos.**

Marketplace completo que conecta compradores e vendedores de caminhões, cavalos mecânicos, carretas e implementos em todo o Brasil.

> **Site em produção:** [pesadosweb.com.br](https://pesadosweb.com.br)

---

## Sobre o Projeto

A Pesados Web foi desenvolvida do zero como uma plataforma SaaS de classificados voltada ao mercado de veículos pesados. O sistema conta com fluxo completo de publicação de anúncios, moderação administrativa, sistema de pagamentos integrado, marketing interno com créditos e geolocalização inteligente.

### Desenvolvedor

**João Vitor Moitinho Silva** — Arquitetura, desenvolvimento full-stack e deploy.

---

## Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| Frontend | Next.js 14 (App Router), React, Tailwind CSS, shadcn/ui |
| Backend | Next.js API Routes, Server Actions |
| Banco de Dados | PostgreSQL + Drizzle ORM |
| Autenticação | Better Auth (email/senha + Google OAuth) |
| Pagamentos | Asaas API (PIX, boleto, cartão) |
| CMS | Sanity (produtos de marketing) |
| Storage | AWS S3 + CloudFront CDN |
| Deploy | Vercel |
| Monitoramento | RD Station, Google Analytics |

---

## Funcionalidades

### Plataforma Pública
- Catálogo com filtros avançados (marca, categoria, tipo de carroceria, ano, preço, estado)
- Geolocalização automática — ordena anúncios por proximidade do comprador
- Detalhes completos do veículo com galeria de fotos e vídeo
- Contato protegido (WhatsApp e telefone liberados mediante cadastro)
- Sistema de favoritos
- Blog integrado
- FAQ e Central de Ajuda

### Área do Vendedor (Dashboard)
- Fluxo de criação de anúncio em steps (plano, conta, categoria, veículo, fotos, pagamento)
- 3 categorias: Caminhão, Cavalo Mecânico, Carreta/Implemento
- 23 tipos de carroceria
- Upload de até 25 fotos + 1 vídeo por anúncio
- Gerenciamento de anúncios (status, visualizações, edição)
- Checkout integrado com Asaas (PIX com QR code)
- Notificações em tempo real

### Painel Administrativo
- Dashboard com métricas (anúncios, usuários, crescimento mensal)
- Moderação de anúncios (aprovar, rejeitar com motivo)
- Gestão de usuários (roles, ban, verificação)
- Logs de auditoria
- Configurações do sistema

### Sistema de Marketing
- Painel de marketing com créditos
- Anúncios patrocinados em posições estratégicas (header, sidebar, catálogo, detalhes)
- Métricas de impressões e cliques por campanha
- Banners gerenciados via Sanity CMS

---

## Screenshots

### Home Page
![Home Page](screenshots/01-home-full.png)

### Catálogo de Veículos
![Catálogo](screenshots/02-catalogo.png)

### Detalhes do Veículo
![Detalhes](screenshots/03-detalhes-caminhao.png)

### Login
![Login](screenshots/04-login.png)

### Dashboard do Vendedor
![Dashboard](screenshots/05-dashboard-usuario.png)

### Meus Anúncios
![Meus Anúncios](screenshots/06-meus-anuncios.png)

### Fluxo de Anúncio - Escolha do Plano
![Anunciar Step 1](screenshots/07-anunciar-step1.png)

### Fluxo de Anúncio - Categoria
![Anunciar Categoria](screenshots/08-anunciar-step-categoria.png)

### Fluxo de Anúncio - Tipo de Carroceria
![Anunciar Tipo](screenshots/09-anunciar-step-tipo.png)

### Admin - Dashboard
![Admin Dashboard](screenshots/10-admin-dashboard.png)

### Admin - Moderação de Anúncios
![Admin Anúncios](screenshots/11-admin-anuncios.png)

### Admin - Gestão de Usuários
![Admin Usuários](screenshots/12-admin-usuarios.png)

### Painel de Marketing
![Marketing](screenshots/13-marketing-painel.png)

---

## Licença

Este software é propriedade intelectual de **João Vitor Moitinho Silva** (CNPJ: 55.942.611/0001-40).

**Todos os direitos reservados.** Nenhuma parte deste software pode ser copiada, modificada, distribuída ou utilizada sem autorização expressa e por escrito do autor.

Consulte o arquivo [LICENSE](LICENSE) para detalhes completos.
