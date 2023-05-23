Merci de nous aider pour rendre Astrone plus sûr 💙.

## Version supportée

La version supportée est la version disponible sur [astrone.app](https://www.astrone.app)

## Rapporter une vulnérabilité

La sécurité est de première importance et toutes vulnérabilités ou potentielles vulnérabilités devraient être rapportées à Astrone de manière privée, afin de minimiser le risque d'attaques contre les utilisateurs actuels d'Astrone, en attendant qu'elles soient corrigés. Les vulnérabilités seront analysées et corrigées à la prochaine version mineure aussi rapidement que possible.
En attendant, cette information devrait être gardée confidentielle.

Si vous pensez avoir trouvé une vulnérabilité dans Astrone, rapporter la nous IMMEDIATEMENT à **[example@monmail.com](mailto:example@monmail.com)**. Vous recevrez une réponse de notre part dans les 72 heures. Si la vulnérabilité est confirmée, nous déploierons une correction aussi rapidement que possible au vu de la complexité du correctif.

**INPORTANT: veuillez ne pas rapporter de vulnérabilités à travers une issue Github publique, l'onglet discussions, ou une pull request.**

### Contenu d'email conseillé

Afin de nous aider à mieux comprendre et à résoudre le problème, veuillez inclure le plus d'informations possibles de la liste ci-dessous :

- La catégorie du problème (buffer overflow, SQL injection, or cross-site scripting)
- La localisation du code source affecté (URL)
- Configurations requises pour reproduire le problème
- Instructions étape par étape pour reproduire le problème
- Preuve de concept ou code d'exploitation (si possible)
- Impact du problème, notamment comment un attaquant pourrait exploiter le problème

Cette information nous aidera à trier votre rapport plus efficacement.

## Correctif, mise à jour, et publication

L'équipe de sécurité d'Astrone répondra au rapport de vulnérabilité comme suit:

1. L'équipe de sécurité analysera la vulnérabilité et déterminera ses effets et sa criticité.
2. Si le problème n'est pas catégorisé comme vulnérabilité, l'équipe de sécurité vous donnera les détails de sa décision.
3. L'équipe de sécurité engagera, dans les 3 jours, une conversation avec le rapporteur.
4. Si la vulnérabilité est reconnue et qu'une feuille de route pour le correctif est établi, l'équipe de sécurité travaillera à l'élaboration d'un plan pour informer les personnes appropriées, entre autres les étapes de mitigations que les utilisateurs peuvent prendre pour se protéger en attendant la mise à jour contenant le correctif.
5. L'équipe de sécurité créera également une [CVSS](https://www.first.org/cvss/specification-document) grâce au [CVSS Calculator](https://www.first.org/cvss/calculator/3.0). La décision final pour le CVSS calculé revient à l'équipe de sécurité. Il est préférable d'agir rapidement plutôt que d'obtenir un CVSS idéal. La vulnérabilité peut également être rapportée à [Mitre](https://cve.mitre.org/) sur la base du [scoring calculator](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator). La CVE sera initialement privée.
6. L'équipe de sécurité travaillera à une résolution de la vulnérabilité et effectuera des tests internes avant la mise à jour du correctif.
7. La date de divulgation est négociée entre l'équipe de sécurité d'Astrone, et le rapporteur. Nous souhaitons qu'une publication complète de la vulnérabilité soit réalisée aussi rapidement que possible à partir du moment où la mise à jour du correctif est accessible. Il est entendu qu'une vulnérabilité ne devrait pas être divulguée si le correctif n'est pas pleinement implémenté, et que la solution n'a pas encore été suffisamment testé. Le moment de la publication peut être immédiat (en particulier, si elle est déjà publiée publiquement) jusqu'à quelques semaines. L'équipe de sécurité prendra la décision quant à la date de publication.
8. Une fois le correctif confirmé, l'équipe de sécurité corrigera la vulnérabilité à la prochaine mise à jour. À la publication de la version corrigée d'Astrone, nous suivrons le **process de publication**.

### Process de publication

L'équipe de sécurité publie un [public advisory](https://github.com/jerboas86/astrone-feedback/security/advisories) à la communauté Astrone via Github. Dans la plupart des cas, des communications supplémentaires via d'autres canaux seront initiées afin de mieux informer et de sensibiliser les utilisateurs d'Astrone.
