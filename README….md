# Auto Llamarist Luani Pjes

Inventar profesional për pjesë karrocerie me login, kategori, kërkim, foto dhe çmime.

## Si ta nisësh (lokalisht)
1. Sigurohu që ke **Node.js 18+**.
2. Hap terminalin në folderin e projektit.
3. Kopjo `.env.example` në `.env` dhe (opsionalisht) ndrysho `SESSION_SECRET`.
4. Installo varësitë: `npm install`
5. Nise serverin: `npm start`
6. Hape `http://localhost:3000` në shfletues.
   - Fjalëkalimi fillestar: **luani123**
7. Nga **Paneli > Cilësimet** mund të:
   - Ndryshosh fjalëkalimin
   - Aktivizosh/çaktivizosh aksesin me fjalëkalim

## Si të hostohet
- **Render / Railway / Fly.io** (Node + disk)
- Ose **VPS / Dedicated** (pm2 + nginx)
- Ngarko gjithashtu folderin `uploads/` që ruan fotot e pjesëve.

## Veçori
- Login i thjeshtë (një fjalëkalim për të gjithë) me bcrypt.
- Kategoritë: shto/fshi.
- Pjesët: emër, përshkrim, çmim, sasi, foto.
- Kërkim global.
- Panel administrimi.
- Cilësime: ndrysho fjalëkalimin, hiq/aktivizo kërkesën për login.
