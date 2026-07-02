# Gaia Med — Site institucional

Landing page da **Gaia Med — Telessaúde**: atendimento remoto por telessaúde, com a mesma atenção e responsabilidade do atendimento presencial.

🔗 **Produção:** [gaiamed.com.br](https://gaiamed.com.br/)

## Sobre

Site estático de página única (single-page) com as seções:

- **Hero** — chamada principal, foto e CTAs de contato
- **Benefícios** — atendimento remoto, suporte contínuo e acesso facilitado
- **Como funciona** — os 3 passos do atendimento (agendamento, consulta por vídeo, acompanhamento)
- **Contato** — telefone e e-mail
- **Rodapé** — dados legais da empresa

## Estrutura de arquivos

```
index.html            Página principal (HTML + CSS embutido)
logo.png              Logo da Gaia
hero.jpg              Foto do hero (teleconsulta)
favicon.ico           Favicon
apple-touch-icon.png  Ícone para iOS
```

## Tecnologia

- HTML5 + CSS puro, sem dependências ou build
- Tipografia: [Sora](https://fonts.google.com/specimen/Sora) (títulos) e [Public Sans](https://fonts.google.com/specimen/Public+Sans) (texto), via Google Fonts
- Responsivo (breakpoint em 860px)

### Paleta

| Uso | Cor |
|-----|-----|
| Azul-marinho (principal) | `#0F2D4E` |
| Azul-petróleo (acento) | `#3585AC` |
| Azul claro | `#8FC3D9` |
| Fundo | `#F5F7F9` |

Cores derivadas do logo da Gaia.

## Como rodar localmente

Por ser um site estático, basta abrir o `index.html` no navegador. Para servir via HTTP:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Como editar

- **Textos e seções:** edite diretamente o `index.html`.
- **Foto do hero:** substitua o `hero.jpg` (mantendo o nome).
- **Cores:** ajuste as variáveis CSS em `:root`, no início do `<style>`.
- **Contato:** telefone e e-mail estão nas seções *Contato* e no rodapé.

## Dados da empresa

- **Razão Social:** Gaia Serviços de Apoio à Saúde Ltda
- **CNPJ:** 47.765.386/0001-96
- **Tipo:** Serviços de Apoio à Saúde — Telessaúde
- **Telefone:** (41) 3027-8527
- **E-mail:** correspondencias@gaiamed.com.br
