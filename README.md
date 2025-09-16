# 📊 BetSight

## 🚀 Présentation

Ce projet vise à construire une plateforme permettant de scraper, stocker, analyser et visualiser des cotes sportives provenant de plusieurs sites spécialisés.

Il est structuré en plusieurs sous-projets indépendants (un repo GitHub par composant), reliés via ce dépôt central.


## 📂 Organisation des dépôts


Le projet est découpé en plusieurs sous-dépôts spécialisés.  
Ce dépôt central sert de **point d’entrée et de documentation**.

- 🔗 [scraping-engine](#) : moteur de scraping (BeautifulSoup, requests/httpx, gestion erreurs).  
- 🔗 [api-backend](#) : API REST FastAPI + SQLAlchemy.  
- 🔗 [frontend-react](#) : interface admin & dashboard (React + Tailwind).  
- 🔗 [data-analysis](#) : scripts d’analyse des cotes et visualisations avancées.  
