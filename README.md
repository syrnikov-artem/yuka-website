# Website YUKA — prototip cu pozele tale

Site-ul YUKA ca prototip funcțional, multi-pagină. Adaugi propriile fotografii (și clipurile video) și vezi exact cum ar arăta site-ul real — fără să atingi codul.

## Pagini
Acasă · Portofoliu · Cum lucrăm · **Fabrică & showroom** · **Parteneri** · Despre (25 de ani) · pagina de proiect.

## Cum adaugi pozele (3 pași)
1. Pune fișierele în folderele din `assets/images/`, cu **numele exacte** din tabel.
2. Salvează.
3. Deschide `index.html` în browser. Pozele apar automat.

> Unde nu există încă o poză, se afișează un **placeholder elegant**. Poți adăuga pozele pe rând.

**Format recomandat:** `.jpg` / `.webp`, sub ~400 KB. Coperți portofoliu = **portret**; galerie proiect, fabrică, VR = **peisaj**.

## Unde merge fiecare poză
| Unde apare în site | Pune fișierul aici |
|---|---|
| Imaginea mare de început (homepage) | `assets/images/hero/hero.jpg` |
| Fabrică + showroom (homepage, pag. Fabrică & showroom, Despre) | `assets/images/fabrica/fabrica.jpg` |
| Producție / utilaje (pag. Fabrică & showroom) | `assets/images/fabrica/productie.jpg` |
| Showroom (pag. Fabrică & showroom) | `assets/images/showroom/1.jpg` |
| Secțiunea VR | `assets/images/vr/vr.jpg` |
| Bucătărie minimalistă caldă cu insulă — copertă | `assets/images/bucatarii/p1.jpg` |
| Bucătărie minimalistă caldă cu insulă — galerie | `assets/images/bucatarii/p1-1.jpg`, `-2.jpg`, `-3.jpg` |
| Dressing walk-in cu uși din sticlă fumurie — copertă | `assets/images/dressinguri/p2.jpg` |
| Dressing walk-in cu uși din sticlă fumurie — galerie | `assets/images/dressinguri/p2-1.jpg`, `-2.jpg`, `-3.jpg` |
| Living cu bibliotecă integrată pe tot peretele — copertă | `assets/images/living/p3.jpg` |
| Living cu bibliotecă integrată pe tot peretele — galerie | `assets/images/living/p3-1.jpg`, `-2.jpg`, `-3.jpg` |
| Bucătărie de familie cu cămară ascunsă — copertă | `assets/images/bucatarii/p4.jpg` |
| Bucătărie de familie cu cămară ascunsă — galerie | `assets/images/bucatarii/p4-1.jpg`, `-2.jpg`, `-3.jpg` |
| Mobilier complet pentru apartament de închiriat — copertă | `assets/images/regim/p5.jpg` |
| Mobilier complet pentru apartament de închiriat — galerie | `assets/images/regim/p5-1.jpg`, `-2.jpg`, `-3.jpg` |
| Dormitor cu pat tapițat și depozitare ascunsă — copertă | `assets/images/dormitoare/p6.jpg` |
| Dormitor cu pat tapițat și depozitare ascunsă — galerie | `assets/images/dormitoare/p6-1.jpg`, `-2.jpg`, `-3.jpg` |
| Bucătărie lucioasă cu insulă mare — copertă | `assets/images/bucatarii/p7.jpg` |
| Bucătărie lucioasă cu insulă mare — galerie | `assets/images/bucatarii/p7-1.jpg`, `-2.jpg`, `-3.jpg` |
| Mobilare completă, apartament cu două camere — copertă | `assets/images/apartament/p8.jpg` |
| Mobilare completă, apartament cu două camere — galerie | `assets/images/apartament/p8-1.jpg`, `-2.jpg`, `-3.jpg` |
| Dressing cu insulă centrală și iluminat — copertă | `assets/images/dressinguri/p9.jpg` |
| Dressing cu insulă centrală și iluminat — galerie | `assets/images/dressinguri/p9-1.jpg`, `-2.jpg`, `-3.jpg` |

## Clipuri video „La 25 de ani”
Două secțiuni au tile-uri video (placeholder cu buton de play): **Despre** (clienți) și **Parteneri** (branduri/CEO). Vezi `assets/videos/_PUNE_VIDEO_AICI.txt`. Cel mai simplu: trimite-mi linkuri YouTube/Vimeo și le transform în embed-uri.

## Logo (`assets/logo/`)
- `sigla.png` — emblema Y (verde, transparent).
- `yuka-logo-light.png` — logotipul pe fundal închis.
- `yuka-logo-dark.png` — logotipul original, pentru fundaluri deschise.

## Note
- Pagina **Parteneri** folosește numele brandurilor ca text (fără logo-uri externe — evităm probleme de drepturi).
- Un singur `index.html` + `assets/`, navigare reală. Pentru producție se poate transforma în pagini separate / React.
