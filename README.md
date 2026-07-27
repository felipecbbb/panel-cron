# panel-cron

Disparador externo del motor del panel (panel.felippecamara.com).
GitHub Actions llama a /api/cron/* cada dia, independiente del cron de Vercel.
Secrets: PANEL_URL, CRON_SECRET. Lanzar a mano: Actions -> Run workflow.
