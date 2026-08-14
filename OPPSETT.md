# Publisering på GitHub Pages (gratis)

1. Opprett et nytt offentlig repo på github.com, f.eks. `forhandlingsteknikk`.
2. Last opp innholdet i denne mappen (index.html, assets/, CNAME) til repoets rot.
3. Repo → Settings → Pages → Source: "Deploy from a branch", velg `main` og `/ (root)`. Lagre.
4. Hos registraren din (DNS for forhandlingsteknikk.no):
   - A-poster for `@` (apex): 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME-post for `www` → `<ditt-brukernavn>.github.io`
5. Tilbake i Settings → Pages: skriv inn `forhandlingsteknikk.no` under Custom domain
   (CNAME-filen i repoet gjør dette automatisk ved deploy) og huk av "Enforce HTTPS"
   når sertifikatet er klart (kan ta opptil en time).

E-postadressen (mail@jan-erik.com) er allerede lagt inn i kontaktknappen – alt er klart til opplasting.
