# HUBBLE
TCC para o curso técnico de informática para internet

# Descrição

A HUBBLE é um sistema web desenvolvido como projeto acadêmico com o objetivo de facilitar a organização e divulgação de eventos corporativos, sociais e festivos em âmbito nacional, com foco inicial no município de Uberlândia.

A plataforma foi idealizada para centralizar informações relacionadas a eventos, contratos, oportunidades e divulgações em um único ambiente, proporcionando praticidade tanto para organizadores quanto para usuários interessados. O sistema conta com áreas destinadas a login de usuários, divulgação de eventos, oportunidades de emprego, suporte e comunicação..


# Estrutura do protótipo

```
Protótipo/
├── index.html                  Página inicial
├── Sobre_nos.html, empresas_e_parceiros.html
├── Login.html, cadastro*.html, completo_cadastro_*.html
├── Hub.html, Evento.html, perfil.html, eventos_curtidos.html   Área do usuário
├── Hub_empresa*.html           Painel da empresa
├── css/
│   ├── base.css                Fontes, header e rodapé do site (todas as páginas)
│   ├── painel-empresa.css      Barra lateral, abas e tabela do painel da empresa
│   ├── vaga-card.css           Componente "card de vaga" (Hub e Evento)
│   └── <pagina>.css            Estilos específicos de cada página
├── fontes/
└── imagens/
```

Ordem dos estilos em cada página: Bootstrap → `css/base.css` → componentes
(`painel-empresa.css`, `vaga-card.css`) → CSS da página. Cada arquivo de página
termina com uma seção `RESPONSIVO` com as regras para telas menores
(breakpoints do Bootstrap: 576px, 768px, 992px, 1200px, 1400px).
