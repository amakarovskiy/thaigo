# Monte Rehab — Website Redesign Project

## Содержимое папки

| Файл | Описание |
|------|----------|
| `CLAUDE.md` | Полный бриф для Claude Code: все тексты EN/RU/ME, все изображения, структура файлов, технические требования |
| `mockup-home.html` | Визуальный шаблон главной страницы (`index.html`). Открыть в браузере для просмотра. |
| `mockup-inner.html` | Визуальный шаблон всех внутренних страниц. Открыть в браузере для просмотра. |

## Что делать

### Шаг 1 — Запустить Claude Code
```bash
cd monterehab-redesign
claude
```

### Шаг 2 — Дать команду
```
Read CLAUDE.md fully before starting.

Build all 32 HTML files (16 EN + 16 RU) as described in CLAUDE.md.

Rules:
- index.html and ru/index.html → use CSS, layout and components from mockup-home.html exactly
- All other pages → use CSS, layout and components from mockup-inner.html exactly
- Do not invent any design — copy CSS variables, typography and component styles from mockups
- Replace only content (texts, images, breadcrumbs, titles) as specified in CLAUDE.md
- All internal links use relative paths
- No frameworks. Vanilla HTML/CSS/JS only.

Build order:
1. All 16 EN files in root folder
2. All 16 RU files in ru/ folder
3. STOP — do not build ME files yet (waiting for translation)
```

### Шаг 3 — ME версия (после перевода)
После того как Валера переведёт RU тексты на черногорский:
```
Build all 16 ME files in me/ folder using the translated content.
Use same mockup-inner.html template. File names from CLAUDE.md ME section.
```

## Ожидаемая структура после сборки

```
📁 /
├── index.html
├── pricing.html
├── contacts.html
├── residential_treatment.html
├── group_therapy.html
├── alcohol_addiction.html
├── drug_addiction.html
├── medical_detox.html
├── behavioural_addiction_treatment.html
├── dual_diagnosis.html
├── anxiety_treatment.html
├── depression_treatment.html
├── executive_burnout.html
├── insomnia_treatment.html
├── mood_disorder_treatment.html
├── ptsd_and_trauma_treatment.html
│
├── ru/
│   ├── index.html
│   ├── pricing.html
│   ├── contacts.html
│   └── ... (16 файлов)
│
└── me/
    ├── index.html
    ├── pricing.html
    ├── contacts.html
    ├── stacionarno_leenje.html
    ├── grupna_terapija_online.html
    ├── zavisnost_od_alkohola.html
    ├── zavisnost_od_droga.html
    ├── medicinska_detoksikacija.html
    ├── leenje_ponaajnih.html
    ├── dvojna_dijagnoza.html
    ├── leenje_anksioznosti.html
    ├── leenje_depresije.html
    ├── izgaranje_na_poslu_kod_rukovodilaca.html
    ├── leenje_nesanice.html
    ├── leenje_poremeaja_raspoloenja.html
    └── leenje_ptsp.html
```
