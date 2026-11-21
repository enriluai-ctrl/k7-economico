# k7-economico — JADEMIA Sentinel (robot.jademco.net)

Landing comercial del **JADEMIA Sentinel**: versión económica del Knightscope K7
(robot de patrulla autónoma de seguridad), construida sobre el proyecto `app\robot`.

- URL final: https://robot.jademco.net  (GitHub Pages + CNAME en Cloudflare)
- Repo: https://github.com/enriluai-ctrl/k7-economico
- Archivo único: `index.html` (autónomo, sin dependencias externas)
- Editar: cambiar este index.html → commit → push (Pages publica solo)

## Fuentes de cada dato (REGLA 0, verificación 21-nov-2026)
| Dato de la web | Fuente |
|---|---|
| K7: 16 km/h, 360°HD+PTZ+térmica+LPR, talk-down, 2.95m/349kg, solo EE.UU., no se vende (servicio ASF) | knightscope.com + knightscope.com/products/k7 (oficial) |
| K7 lista ~US$139,000 | robolist.ai "source not on file" — marcado con * y disclaimer en la web |
| Métricas Knightscope −46%/+27%/−68% | marketing propio del fabricante — atribuido en la web |
| Planes US$350-500 / 1,000-1,200 / 3,200-3,800 | `app\compras\robot_ia\RECOMENDACION_ROBOT_IA.md` §4 (Alibaba 01-nov-2026, POR COTIZAR) |
| Sensores (RGB+IR 2MP, PIR, AS608, MLX90640, UV 365nm) | mismo archivo §1/§3 |
| Pipeline IA: mAP50 0.83, 11,5 ms, 36 s, best.pt 6,5 MB | `INVESTIGACION_ROBOT.md` §1 (demo 8 fotos, probada) |
| Alertas WhatsApp 24/7 | bot.jademco.net (proyecto `app\Whatsapp`, vivo 07-nov-2026) |
| Disclaimer de no afiliación | footer de la web |
