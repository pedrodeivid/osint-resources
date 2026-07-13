<p align="center">
  <img src="https://raw.githubusercontent.com/daemonintel/osint-resources/main/assets/ILoveIMG.png" width="400">
</p>

<hr style="border: none; height: 1px; background-color: #30363d; opacity: 0.5; margin: 24px 0;">

<p align="center">
  <small>OSINT (Open-source intelligence)</small>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/contributors/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/issues/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/discussions/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/forks/daemonintel/osint-resources">
  <img src="https://img.shields.io/github/stars/daemonintel/osint-resources">
</p>

<p align="center" style="font-size: 13px; color: #8b949e;">
  <strong>Navegação:</strong>
  <a href="FLUXOGRAMAS.md">🔀 Fluxogramas</a> |
  <a href="RECURSOS.md">📚 Recursos</a> |
  <a href="CONTRIBUTING.md">🤝 Contribuições</a>
</p>

# Recursos OSINT

> **Finalidade e uso responsável**  
> Este material foi organizado para estudo, investigação digital legítima, pesquisa, jornalismo, due diligence, threat intelligence e outras finalidades lícitas. O uso deve respeitar a **LGPD**, termos de serviço, legislação aplicável, escopo autorizado e princípios de necessidade, proporcionalidade e minimização de dados.
>
> **Sobre esta lista**  
> Esta não é uma lista “bonita” e inflada para parecer completa: a proposta aqui é ser **acurada, prática e reaproveitável**. Os links foram mantidos, os nomes foram preservados e as descrições foram refinadas sem reduzir o conteúdo-base fornecido.  
> Ferramenta sozinha não resolve investigação: o valor real está em **correlação, contexto, validação cruzada e metodologia**.

---

## Navegação

- [Username Enumeration](#username-enumeration)
- [Emails](#emails)
- [Celular](#celular)
- [Domínios / DNS](#domínios--dns)
- [Vazamentos / Breaches](#vazamentos--breaches)
- [Caches](#caches)
- [IPs](#ips)
- [Pessoas / Background](#pessoas--background)
- [Extensões](#extensões)
- [Frameworks e agregadores](#frameworks-e-agregadores)
- [Buscas unificadas](#buscas-unificadas)
- [Outros](#outros)
- [Blogs](#blogs-e-recursos-úteis-bônus)

---

## Username Enumeration

- [social-analyzer](https://github.com/qeeqbox/social-analyzer) — API, CLI e aplicativo web para localizar e analisar perfis de uma pessoa em mais de 1000 redes sociais e sites.
- [Namechk](https://namechk.com/) — verifica a existência e disponibilidade de usernames em múltiplas plataformas e redes sociais.
- [IDCrawl](https://www.idcrawl.com/) — busca por pessoas e usernames com boa utilidade para correlação de perfis.
- [WhatsMyName](https://whatsmyname.app/) — busca usernames em cerca de 600 sites; clássico e muito confiável para triagem inicial.
- [Social Searcher](https://www.social-searcher.com/) — focado em redes sociais e descoberta de presença pública.
- [Snoop](https://github.com/snooppr/snoop) — busca automatizada em mais de 5300 sites; amplo alcance para enumeração de nomes de usuário.
- [Maigret](https://github.com/soxoj/maigret/blob/main/README.md) — busca em cerca de 3000 sites; forte para cobertura ampla e automação.
- [Mailcat](https://github.com/sharsil/mailcat) — testa e correlaciona possíveis e-mails derivados de usernames; muito útil para pivoting.
- [usersearch](https://www.usersearch.com/) — busca unificada poderosa, não limitada apenas a usernames.
- [blackbird](https://github.com/p1ngul1n0/blackbird) — busca em cerca de 600 sites com abordagem prática e objetiva.
- [tookie-osint](https://github.com/Alfredredbird/tookie-osint) — busca em pelo menos 600 sites, estimativamente; útil como complemento de cobertura.
- [Sherlock](https://github.com/sherlock-project/sherlock/) - busca em 400 sites.

---

## Emails

- [Skymem](https://www.skymem.info/) — reverse lookup e indexação de e-mails; útil para descobrir aparições públicas e correlações.
- [OSINT Industries](https://www.osint.industries/) — serviço pago que agrega informações gerais de um e-mail com bom enriquecimento de dados.
- [Epieos](https://epieos.com/) — freemium; lembra o OSINT Industries e ajuda a correlacionar contas, perfis e sinais públicos ligados ao e-mail.
- [Reverse Contact](https://www.reversecontact.com/) — freemium com consultas grátis; busca empresa ou perfil do LinkedIn associado ao e-mail pesquisado.
- [Hunter](https://hunter.io/) — focado em e-mails corporativos e de mercado; faz busca reversa, validação, descoberta por domínio e costuma ser melhor para alvos estrangeiros.
- [InsE](https://chromewebstore.google.com/detail/inse-instagram-email-find/hboikjnbkhkjmllgdcflmbcojbpklcca/) — raspa e-mails públicos de usuários do Instagram e pode extrair seguidores.
- [EmailHippo](https://tools.emailhippo.com/) — validador de e-mail; bom para triagem e redução de ruído.
- [Minelead](https://minelead.io/) — semelhante ao Hunter, mas com base de dados diferente, útil para complementar resultados.
- [Poastal](https://github.com/jakecreps/poastal) — entrega informações úteis e específicas de um e-mail; vale consultar o repositório para entender o escopo exato.
- [yesitsme](https://github.com/0x0be/yesitsme) — tenta encontrar informações de usuários do Instagram por username ou e-mail.
- [zehef](https://github.com/N0rz3/Zehef) — extrai informações públicas associadas a um e-mail.
- [GHunt](https://github.com/mxrch/ghunt) — versão open source no estilo do OSINT Industries, focada em pivoting em ecossistema Google.
- [Holehe](https://github.com/megadose/holehe) — verifica se e-mail está registrado em serviços listados na ferramenta.
- [email2phonenumber](https://github.com/martinvigo/email2phonenumber) — faz scraping e força bruta em fontes abertas para tentar obter possível número de celular a partir

---

## Celular

- [Truecaller](https://www.truecaller.com/) — serviço global de reconhecimento de números; útil para identificação e contexto básico.
- [WhatsApp-OSINT](https://github.com/kinghacker0/WhatsApp-OSINT) — recupera fotos de perfil, faz análises profundas, coleta informações e reúne outros sinais úteis do WhatsApp.
- [NumVerify](https://numverify.com/) — API JSON para validação e consulta de números de telefone globais (freemium).
- [phoneinfoga](https://github.com/sundowndev/phoneinfoga) — busca automatizada em fontes públicas; clássico para triagem de números, quando ainda houver utilidade no cenário atual.
- [CheatBuster](https://www.cheaterbuster.com/pt/reverse-phone-lookup/) — identifica se o celular está cadastrado em apps de namoro; mais útil para números estrangeiros.
- [ignorant](https://github.com/megadose/ignorant) — interessante para cenários em que adicionar o celular aos contatos ajuda na investigação.
- [phone variant search](https://www.no-nonsense-intel.com/phone-variant-search) — automatiza dorks manuais usando variações de formatação do número.
- [get contact](https://getcontact.com/) — serviço pago de reconhecimento baseado em apelidos e identificação social do número.
- [Telegram Finder](https://www.telegram-finder.io/) — verifica se o número aparece no Telegram.
- [Moriarty](https://github.com/AzizKpln/Moriarty-Project) — busca automatizada com enriquecimento de dados voltado a celular.
- [GhostTrack](https://github.com/HunxByts/GhostTrack) — coleta informações de operadora e telefonia do celular e ainda traz outras funcionalidades como username e IP.
- [Eyecon](https://play.google.com/store/apps/details?id=com.eyecon.global) — semelhante ao Truecaller, com base de dados menor.

---

## Domínios / DNS

- [Whois](https://who.is/) — consulta informações de registro de domínios.
- [SecurityTrails](https://securitytrails.com/) — centraliza informações sobre domínios, subdomínios, endereços IP, registros DNS e WHOIS.
- [CMSeek](https://github.com/Tuhinshubhra/CMSeeK/) — toolkit voltado à identificação e análise de CMS.
- [Hoper](https://github.com/gabamnml/hoper/) — mostra o caminho de uma URL até seu destino final, útil para entender redirecionamentos.
- [WhatWeb](https://github.com/urbanadventurer/WhatWeb/) — ferramenta poderosa que funciona como um scanner web completo.
- [BuiltWith](https://builtwith.com/) — mostra tecnologias utilizadas em um site.
- [Netlas](https://app.netlas.io/host/) — reúne IPs, DNS, WHOIS, CVEs, SSL e outros dados técnicos.
- [DNSChecker](https://dnschecker.org/) — consulta de DNS com boa utilidade para verificação rápida.
- [OSINT.SH](https://osint.sh/) — agrega muitas ferramentas e fontes de domínio, como CT, WHOIS, DNS, registros históricos e mais.
- [Shodan](https://www.shodan.io/) — busca dispositivos e serviços expostos; ideal para banners, IoT e exposição de superfície.
- [Hunter](https://hunter.how/) — plataforma técnica para busca em infraestrutura exposta e dados relacionados.
- [Whois Data Center](https://whoisdatacenter.com/) — reverse WHOIS de forma ampla.
- [LeakIX](https://leakix.net/) — busca serviços mal configurados, vulnerabilidades, exposição indevida e vazamentos.
- [Favi Hash](https://www.favihash.com/) — procura informações sobre um domínio por meio do favicon hash.
- [DumpChromeSecrets](https://github.com/Maldev-Academy/DumpChromeSecrets) — ferramenta para extrair dados do Chrome.
- [Synapsint](https://synapsint.com/) — busca unificada incluindo SSL, ASN, CVE, IPs, Adsense e reverse WHOIS.
- [DNSDumpster](https://dnsdumpster.com/) — busca e enumeração de DNS.
- [NetCraft](https://www.netcraft.com/) — freemium; oferece informações generalizadas sobre sites e infraestrutura.
- [ViewDNS](https://viewdns.info/) — busca unificada massiva para IPs, WHOIS, históricos e mais.
- [BGP Toolkit](https://bgp.he.net/) — conjunto de recursos para IPs, ASN, roteamento e contexto de rede.
- [Censys](https://search.censys.io/) — indexa serviços mais rápido e de forma mais estruturada que muitos buscadores, com foco em certificados SSL/TLS e exposição técnica.

---

## Vazamentos / Breaches

> Aqui, além das ferramentas, o ideal é saber **como procurar**, interpretar contexto, validar amostragem, distinguir dado antigo de dado recente e entender o valor real de cada vazamento.

- [IntelX](https://intelx.io/) — consulta unificada de vazamentos; freemium e muito útil para pivoting.
- [LeeakPeak](https://leakpeek.com/) — consulta unificada de vazamentos, menos abrangente que o IntelX; freemium.
- [Have I Been Pwned](https://haveibeenpwned.com/) — confere em quais serviços um e-mail vazou e quando.
- [Breachdirectory](https://breachdirectory.org/) — entrega senhas em formato hash ou criptografadas.
- [LeakCheck](https://leakcheck.io/) — mostra mais dados que o Have I Been Pwned, como senhas, embora possa ter base menor em certos casos.
- [H8mail](https://github.com/khast3x/h8mail) — busca unificada em diversos serviços e fontes de leaks.
- [GhostProject](https://ghostproject.fr/) — mostra senhas vazadas completas, ciphertext ou plaintext.
- [Breach Vip](https://breach.vip/) — mostra vazamentos cifrados ou não, com foco em vazamentos recentes.
- [Grayhat Warfare](https://grayhatwarfare.com/) — busca buckets expostos e mal configurados.
- [LeakScraper](https://github.com/Acceis/leakScraper) — raspa credenciais vazadas; exige um servidor MongoDB funcionando.
- [OSINTLeak](https://osintleak.com/) — mostra senhas completas e monitora vazamentos.

---

## Caches

> Todas cumprem, em maior ou menor grau, a função de indexar páginas e servir como linha do tempo. Por isso, ter um agregador é útil. Muitas possuem nichos ou recortes próprios de indexação.

- [Quick Cache and Archive Search](https://cybdetective.com/quickcacheandarhivesearch.html) — agregador para consulta rápida em diversos serviços de cache e arquivamento.
- [Way Back Machine](https://web.archive.org/) — o clássico para histórico de páginas e versões arquivadas.
- [Archive.is](https://archive.is/) — arquivamento alternativo e útil para snapshots persistentes.
- [Webcitation.org](https://www.webcitation.org/) — serviço histórico de citação e arquivamento web.
- [Wikiwix Archives](https://archive.wikiwix.com/cache/) — arquivo/cache alternativo para páginas web.
- [Library of Congress archive](https://www.loc.gov/) — acervo institucional com material arquivado e valor histórico.
- [Archive-It](Archive-it.org) — plataforma de arquivamento voltada a coleções e instituições.
- [Croatian Web Archive](https://netpreserve.org/ga2019/haw/) — acervo web croata.
- [Slovenian Web Archive](https://guides.loc.gov/slovenian-collections/digital-resources-web-archiving) — referências e recursos sobre arquivamento web esloveno.
- [National UK Archive](https://www.nationalarchives.gov.uk/search/) — arquivos nacionais do Reino Unido.
- [Singapore Web Archive](https://eresources.nlb.gov.sg/webarchives/landing-page) — arquivo web de Singapura.
- [Trove (Australian Web Archive)](https://trove.nla.gov.au/help/navigating/viewing-web-archive) — arquivo web australiano via Trove.
- [UNHCR Web Archive](https://webarchive.archive.unhcr.org/) — arquivo web ligado ao ACNUR/UNHCR.
- [Estonian Web Archive](https://digital.library.unt.edu/ark:/67531/metadc1638385/) — referência relacionada a arquivamento web estoniano.
- [PRONI Web Archive](https://www.nidirect.gov.uk/services/search-proni-web-archive) — arquivo web PRONI.
- [UNESCO archives](https://webarchive.unesco.org/#!/) — arquivos da UNESCO.
- [End of Term Web Archive](https://eotarchive.org/) — acervo voltado a sites governamentais capturados em transições administrativas.
- [Czech Web Archive](https://www.webarchiv.cz/en/) — arquivo web tcheco.
- [Finnish Web Archive](https://www.kansalliskirjasto.fi/fi) — arquivo web finlandês / referência da biblioteca nacional.
- [Padicat. Web Archive of Catalonia](https://padicat.cat/en/) — arquivo web da Catalunha.
- [Ghost Archive](https://ghostarchive.org/) — arquivamento alternativo útil em alguns casos onde outros serviços falham.
- [Memento Time Travel](https://mementoweb.org/) — navegação temporal entre versões arquivadas de páginas.

---

## IPs

- [IPInfo](https://ipinfo.io/) — informações genéricas sobre IP.
- [AbuseIBPD](https://www.abuseipdb.com/) — denúncias, reputação e blacklists para IPs.
- [Zeus Grabber](https://github.com/drcrypterdotru/Zeus-Grabber) — IP reverso, gerador de IP, conversão de domínio para IP, busca no Google, SQLi e integração com Zone-H.

---

## Pessoas / Background

- [Whitepages](https://www.whitepages.com/) — bom para informações de negócios e contexto de pessoas em certos cenários.
- [IDCrawl](https://www.idcrawl.com/) — útil para buscas gerais, inclusive redes sociais e correlação de identidade.

> Para esse tipo de busca, a prática real costuma ser combinar **Google dorking + dados governamentais, como portal da transparência + montagem de variações de e-mail + validação + PIX (se houver contexto e legitimidade para uso)**.

---

## Extensões

- [Link Gopher](https://chromewebstore.google.com/detail/link-gopher/bpjdkodgnbfalgghnbeggfbfjpcfamkf) — raspa links de um site com rapidez.
- [Wappalyzer](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg) — identifica tecnologias usadas em um site.
- [Mitaka](https://chromewebstore.google.com/detail/mitaka/bfjbejmeoibbdpfdbmbacmefcbannnbg) — permite buscar IPs, hashes, domínios e outros indicadores diretamente pelo menu de contexto.
- [Instant Data Scraper](https://chromewebstore.google.com/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah) — raspa dados essenciais de um site e permite salvar em Excel ou CSV.
- [EXIF Viewer Pro](https://chromewebstore.google.com/detail/exif-viewer-pro/mmbhfeiddhndihdjeganjggkmjapkffm) — acesso rápido a dados EXIF de imagem/arquivo diretamente pela extensão.
- [E-mail Extrator](https://chromewebstore.google.com/detail/email-extract-email-extra/ejecpjcajdpbjbmlcojcohgenjngflac) — extrai e-mails de sites que você visita.
- [WayBack Machine](https://chromewebstore.google.com/detail/wayback-machine/fpnmgdkabkmnadcjpehmlllkndpkmiak) — acessa sites arquivados a partir da navegação e da própria extensão.
- [Vortimo](https://chromewebstore.google.com/detail/vortimo-osint-tool/mnakbpdnkedaegeiaoakkjafhoidklnf) — marque/registre páginas, armazene capturas de tela, extraia e enriqueça entidades. Encontra texto em todas as páginas e o destaca.

---

## Frameworks e agregadores

- [Caipora](https://caipora.pro/) — agregador voltado a dados abertos brasileiros.
- [OSINT Framework](https://osintframework.com/) — clássico e muito usado; agrega diversas fontes e ferramentas OSINT.
- [CAPIVARA OSINT](https://www.capivaraosint.cc/) — OSINT Framework brasileiro.

## Link Analysis

Todos aqui têm a função de servir como análise de links, relações e grafos.

- [Maltego](https://www.maltego.com/) — referência clássica em análise de vínculos e pivoting visual.
- [Spiderfoot](https://github.com/smicallef/spiderfoot) — framework automatizado com boa capacidade de coleta e correlação.
- [Horizon](https://shadowdragon.io/horizon/) — plataforma paga com foco investigativo e análise de relações.
- [Gephi](https://gephi.org/) — ferramenta robusta para visualização e exploração de grafos.
- [Crimewall](https://sociallinks.io/products/sl-crimewall) — solução paga voltada a análise visual e investigação.

---

## Buscas unificadas

- [PyOsint](https://github.com/syamsv/Pyosint) — busca usernames, subdomínios e links de sites.
- [OathNet](https://oathnet.org/) — cobre e-mail, vazamentos de redes sociais, Discord, IPs, domínios e outros pivots; o destaque está na capacidade de revelar vazamentos ligados a Discord.
- [Recon-ng](https://github.com/lanmaster53/recon-ng) — framework com módulos para robotx.txt, SQL, e-mails, usernames, subdomínios e mais.
- [DetectDee](https://github.com/willin22/DetectDee) — busca por e-mail, username e celular.
- [Telegram Finder](https://www.telegram-finder.io/) — também pode ser usado em consultas ligadas a LinkedIn, e-mail e telefone.
- [Signalhire](https://www.signalhire.com/) — lembra o Whitepages, mas para e-mails e celulares corporativos; costuma ser melhor para estrangeiros.
- [Infooze](https://github.com/devxprite/infoooze/) — consulta usernames, IPs, domínios, e-mails, metadados e muito mais.
- [Sherlockeye](https://app.sherlockeye.io/) — consulta e-mail, telefone, username, domínio, IP, CNPJ e CPF com buscas aprofundadas.
- [X-OSINT](https://github.com/TermuxHackz/X-osint/) — consulta IP, e-mail, domínios, portas, hosts, exploits, metadados e mais.
- [Toutatis](https://github.com/megadose/toutatis) — consulta celular, e-mails, usuários do instagram e muito mais.
- [WebVetted](https://webvetted.com/) - consulta celular, e-mails, usernames, nome e domínios, bom para footprinting de pessoas.

---

## Outros

- [GitFive](https://github.com/mxrch/gitfive) — ferramenta OSINT para investigar perfis do GitHub.
- [HuntItel](https://www.huntintel.io/) — busca geolocalização de publicações em redes sociais.
- [Instagram Monitor](https://github.com/misiektoja/instagram_monitor/) — monitora perfil do Instagram, seguidores, status, bio e até número de seguidores.
- [URLScan](https://urlscan.io/) — análise de segurança e contexto técnico de um site.
- [Venator Browser](https://venator.cyberyozh.com/) — navegador orientado a OSINT.
- [Unavatar](https://unavatar.io/#/) — baixa avatar de diferentes redes sociais.
- [Octocsuite](https://github.com/bellingcat/octosuite/) — aumenta a eficiência de OSINT no GitHub.
- [WayBackPack](https://github.com/jsvine/waybackpack/) — baixa histórico de arquivamentos específicos.
- [FBI Watchdog](https://github.com/DarkWebInformer/FBI_Watchdog/) — ajuda a configurar monitoramento DNS, onion, WHOIS e outros sinais; é mais técnico.

---

## Blogs e recursos úteis (bônus)

- [Bellingcat](https://www.bellingcat.com/category/resources/) - Bellingcat oferece recursos e metodologias para diversos casos reais de OSINT.
- [Resource-1](https://osintteam.blog/leaks-and-breaches-for-osint-a7e3eb6bb56f) - Panorama geral de como encontrar vazamentos e violações para OSINT, guias e ferramentas úteis.
- [Resource-2](https://www.osint.industries/project/know-your-enemy-how-osint-collaboration-can-profile-a-predator) - Caso prático de como OSINT pode ser usado para traçar o perfil de um predador
- [Resource-3](https://www.secjuice.com/use-osint-to-investigate-a-phishing-scam/) - Como investigar campanhas de phishing usando OSINT. 
- [OSINT-Brazuca](https://github.com/osintbrazuca/osint-brazuca/) - Projeto extremamente útil que agrega fontes de dados públicos, métodos e ferramentas para OSINT no contexto do Brasil, deem uma força lá!

---

## Notas práticas de uso

1. **Correlacione, não confie cegamente.**  
   Username, e-mail, celular e domínio raramente valem isolados. O valor aparece quando você cruza dados.

2. **Nem toda ferramenta serve para Brasil.**  
   Algumas são melhores para alvo estrangeiro, principalmente as ligadas a people search, telefone e e-mails corporativos.

3. **Freemium não é detalhe, é limitação operacional.**  
   Em investigação real, limite de consulta, profundidade de resposta e exportação mudam totalmente o valor da ferramenta.

4. **Histórico importa.**  
   Em domínio, cache, leaks e perfis, saber “como estava antes” muitas vezes vale mais do que o estado atual.

5. **Metodologia vence hype.**  
   Ferramentas entram e saem. O que permanece é a sequência lógica de recon, validação, pivoting, enriquecimento e documentação.

---

## Contribuições

Contribuições de quaisquer tipos são bem-vindas!
