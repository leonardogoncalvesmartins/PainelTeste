# PainelTeste — Dashboard Educacional FAETEC

Dashboard de indicadores de vagas, inscrições e matrículas da FAETEC (2018–2026), com login e administração de usuários embutidos no próprio arquivo HTML.

## Conteúdo
- `index.html`: o dashboard completo, autocontido (sem dependências externas). Os dados ficam criptografados (AES-256-GCM) dentro do arquivo e só são abertos após o login.

## Como usar
Abra `index.html` em um navegador. É necessário usuário e senha (peça as credenciais a quem administra este repositório).

Este HTML foi feito para funcionar publicado como Artifact do Claude (claude.ai), que fornece o serviço de banco de dados usado pela tela de Administração para gerenciar usuários. Aberto fora desse ambiente (direto do GitHub ou de um navegador comum), a tela de login aparece, mas a criação/edição de usuários pela Administração não funciona, porque depende desse serviço.

## Dados
Fonte: planilha "DADOS" (FAETEC), períodos de 2018/1 a 2026/2, atualizada em 26/09/2026.

## Aviso
Repositório marcado como privado. Mesmo assim, os dados dentro do arquivo estão criptografados; a senha é o único jeito de abri-los.
