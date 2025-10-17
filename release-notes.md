# Release Notes — v1.0.0 (2025-10-17)

## 📦 Resumen
**Dorks para buscar empresas con bug bounty privado**: un arsenal de consultas OSINT para encontrar páginas de `security.txt`, políticas de divulgación responsable, formularios de reporte y pistas de recompensa **aunque la empresa no esté en plataformas conocidas**.

---

## 🧪 Problema que resuelve
Muchas compañías tienen VDP/BBP ocultos (o semipúblicos) fuera de H1/Bugcrowd/Synack. Sin dorks bien pensados, esos objetivos **no aparecen** en tu radar → menos oportunidades, menos recompensas.

---

## ⚙️ Qué aporta
- 🎯 **Descubrimiento** de programas y vías de reporte “off-platform”.
- 💸 **Señales de recompensa**: `reward`, `bounty`, `swag`, montos/monedas.
- 🌍 **Cobertura regional**: NL/EU/UK/DE/BR/IN/EDU/GOV.
- 🧭 **Pistas operativas**: páginas de seguridad, help/support, trust, HOF, powered-by.

---

## 🗂️ Dorks (listo para pegar)
> Reemplazá **{TARGET}** por el dominio raíz (ej.: `acme.com`).
>
> (site:{TARGET} OR site:.{TARGET}) inurl:/bug bounty
(site:{TARGET} OR site:.{TARGET}) inurl:/security
(site:{TARGET} OR site:.{TARGET}) inurl:security.txt
(site:{TARGET} OR site:.{TARGET}) inurl:security "reward"
(site:{TARGET} OR site:.{TARGET}) inurl:/responsible disclosure
(site:{TARGET} OR site:.{TARGET}) inurl:/responsible-disclosure/ reward
(site:{TARGET} OR site:.{TARGET}) inurl:/responsible-disclosure/ swag
(site:{TARGET} OR site:.{TARGET}) inurl:/responsible-disclosure/ bounty
(site:{TARGET} OR site:.{TARGET}) inurl:'/responsible disclosure' hoodie
(site:{TARGET} OR site:.{TARGET}) responsible disclosure swag r=h:com
(site:{TARGET} OR site:.{TARGET}) responsible disclosure hall of fame
(site:{TARGET} OR site:.{TARGET}) inurl:responsible disclosure $50
(site:{TARGET} OR site:.{TARGET}) responsible disclosure europe
(site:{TARGET} OR site:.{TARGET}) responsible disclosure white hat
(site:{TARGET} OR site:.{TARGET}) white hat program
(site:{TARGET} OR site:.{TARGET}) insite:"responsible disclosure" -inurl:nl
(site:{TARGET} OR site:.{TARGET}) intext responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site eu responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site .nl responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site responsible disclosure
(site:{TARGET} OR site:.{TARGET}) responsible disclosure:sites
(site:{TARGET} OR site:.{TARGET}) responsible disclosure r=h:nl
(site:{TARGET} OR site:.{TARGET}) responsible disclosure r=h:uk
(site:{TARGET} OR site:.{TARGET}) responsible disclosure r=h:eu
(site:{TARGET} OR site:.{TARGET}) responsible disclosure bounty r=h:nl
(site:{TARGET} OR site:.{TARGET}) responsible disclosure bounty r=h:uk
(site:{TARGET} OR site:.{TARGET}) responsible disclosure bounty r=h:eu
(site:{TARGET} OR site:.{TARGET}) responsible disclosure swag r=h:nl
(site:{TARGET} OR site:.{TARGET}) responsible disclosure swag r=h:uk
(site:{TARGET} OR site:.{TARGET}) responsible disclosure swag r=h:eu
(site:{TARGET} OR site:.{TARGET}) responsible disclosure reward r=h:nl
(site:{TARGET} OR site:.{TARGET}) responsible disclosure reward r=h:uk
(site:{TARGET} OR site:.{TARGET}) responsible disclosure reward r=h:eu
(site:{TARGET} OR site:.{TARGET}) "powered by bugcrowd" -site:bugcrowd.com
(site:{TARGET} OR site:.{TARGET}) "submit vulnerability report"
(site:{TARGET} OR site:.{TARGET}) "submit vulnerability report" | "powered by bugcrowd" | "powered by hackerone"
(site:{TARGET} OR site:.{TARGET}) site:.gov.* "responsible disclosure"
(site:{TARGET} OR site:.{TARGET}) intext:"we take security very seriously"
(site:{TARGET} OR site:.{TARGET}) site:responsibledisclosure.com
(site:{TARGET} OR site:.{TARGET}) inurl:'vulnerability-disclosure-policy' reward
(site:{TARGET} OR site:.{TARGET}) intext:Vulnerability Disclosure site:nl
(site:{TARGET} OR site:.{TARGET}) intext:Vulnerability Disclosure site:eu
(site:{TARGET} OR site:.{TARGET}) site:..nl intext:security report reward
(site:{TARGET} OR site:.{TARGET}) site:..nl intext:responsible disclosure reward
(site:{TARGET} OR site:.{TARGET}) "security vulnerability" "report"
(site:{TARGET} OR site:.{TARGET}) inurl"security report"
(site:{TARGET} OR site:.{TARGET}) "responsible disclosure" university
(site:{TARGET} OR site:.{TARGET}) inurl:/responsible-disclosure/ university
(site:{TARGET} OR site:.{TARGET}) buy bitcoins "bug bounty"
(site:{TARGET} OR site:.{TARGET}) inurl:/security ext:txt "contact"
(site:{TARGET} OR site:.{TARGET}) "powered by synack"
(site:{TARGET} OR site:.{TARGET}) intext:responsible disclosure bounty
(site:{TARGET} OR site:.{TARGET}) inurl: private bugbountyprogram
(site:{TARGET} OR site:.{TARGET}) inurl:/.well-known/security ext:txt
(site:{TARGET} OR site:.{TARGET}) inurl:/.well-known/security ext:txt intext:hackerone
(site:{TARGET} OR site:.{TARGET}) inurl:/.well-known/security ext:txt -hackerone -bugcrowd -synack -openbugbounty
(site:{TARGET} OR site:.{TARGET}) inurl:reporting-security-issues
(site:{TARGET} OR site:.{TARGET}) inurl:security-policy.txt ext:txt
(site:{TARGET} OR site:.{TARGET}) site:..* inurl:bug inurl:bounty
(site:{TARGET} OR site:.{TARGET}) site:help..* inurl:bounty
(site:{TARGET} OR site:.{TARGET}) site:support..* intext:security report reward
(site:{TARGET} OR site:.{TARGET}) intext:security report monetary inurl:security
(site:{TARGET} OR site:.{TARGET}) intext:security report reward inurl:report
(site:{TARGET} OR site:.{TARGET}) site:security..* inurl: bounty
(site:{TARGET} OR site:.{TARGET}) site:..de inurl:bug inurl:bounty
(site:{TARGET} OR site:.{TARGET}) site:..uk intext:security report reward
(site:{TARGET} OR site:.{TARGET}) site:..cn intext:security report reward
(site:{TARGET} OR site:.{TARGET}) "vulnerability reporting policy"
(site:{TARGET} OR site:.{TARGET}) "van de melding met een minimum van een" -site:responsibledisclosure.nl
(site:{TARGET} OR site:.{TARGET}) inurl:responsible-disclosure-policy
(site:{TARGET} OR site:.{TARGET}) "If you believe you've found a security vulnerability"
(site:{TARGET} OR site:.{TARGET}) intext:"BugBounty" and intext:"BTC" and intext:"reward"
(site:{TARGET} OR site:.{TARGET}) intext:bounty inurl:/security
(site:{TARGET} OR site:.{TARGET}) inurl:"bug bounty" and intext:"€" and inurl:/security
(site:{TARGET} OR site:.{TARGET}) inurl:"bug bounty" and intext:"$" and inurl:/security
(site:{TARGET} OR site:.{TARGET}) inurl:"bug bounty" and intext:"INR" and inurl:/security
(site:{TARGET} OR site:.{TARGET}) inurl:/security.txt "mailto" -github.com -wikipedia.org -portswigger.net -magento
(site:{TARGET} OR site:.{TARGET}) /trust/report-a-vulnerability
(site:{TARGET} OR site:.{TARGET}) site:.edu intext:security report vulnerability
(site:{TARGET} OR site:.{TARGET}) "cms" bug bounty
(site:{TARGET} OR site:.{TARGET}) "If you find a security issue" "reward"
(site:{TARGET} OR site:.{TARGET}) "responsible disclosure" intext:"you may be eligible for monetary compensation"
(site:{TARGET} OR site:.{TARGET}) inurl:"responsible disclosure", "bug bounty", "bugbounty"
(site:{TARGET} OR site:.{TARGET}) intext: we offer a bounty
(site:{TARGET} OR site:.{TARGET}) responsible disclosure inurl:in
(site:{TARGET} OR site:.{TARGET}) site:.br responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site:.at responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site:.be responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site:.au responsible disclosure
(site:{TARGET} OR site:.{TARGET}) site:/security.txt "bounty"
(site:{TARGET} OR site:.{TARGET}) inurl:bug bounty intext:"rupees"
(site:{TARGET} OR site:.{TARGET}) inurl:bug bounty intext:"₹"
(site:{TARGET} OR site:.{TARGET}) inurl:responsible disclosure intext:"INR"


---

## 🧠 Uso recomendado (workflow rápido)
1. Reemplazá `{TARGET}` por el dominio raíz.
2. Probá primero sin `{TARGET}` para **descubrimiento general** por región/idioma.
3. Guardá los resultados en tu **Gestor de Informes** (categoría “Prospectos VDP/BBP”).
4. Verificá **Términos/alcance** antes de cualquier prueba. Si hay recompensa → lee condiciones.

---

## 🛣️ Próximos pasos
- v1.1: JSON con dorks + tags (región/tema/señal).
- v2.0: script para generar dorks por lista de dominios.

