# Entregable 1 — Ingeniería de Sistemas (Universidad de la Amazonia)

Página web informativa del programa de Ingeniería de Sistemas.

## Estructura

```
entrega1/
├── index.html
├── vercel.json
└── css/
    └── styles.css
```

## Qué se usó

Solo HTML5 y CSS3, sin frameworks:

- HTML semántico: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- CSS: variables, `flex` + `flex-wrap`, `grid`, `position: sticky`, gradientes,
  `box-shadow`, transiciones, `media queries` para responsivo
- Metodología BEM para las clases (`.dato__etiqueta`, `.menu__enlace`)

## Datos usados

Tomados de la página oficial:
https://www.uniamazonia.edu.co/inicio/index.php/es/programas/pregrado/ingenieria/ingenieria-de-sistemas.html

- Título: Ingeniero de Sistemas
- Modalidad: Presencial · Jornada: Diurna
- Duración: 10 semestres · 178 créditos
- SNIES: 52384
- Registro Calificado: Resolución 001562 del 16 de febrero de 2022
- Plan de estudios: Acuerdo 44 del 02 de diciembre de 2020
- Sede: Florencia, Caquetá — Campus Florencia, barrio El Porvenir

## Publicar en GitHub (sin instalar Git)

1. Entra a https://github.com/new
2. **Repository name:** `ingenieria-de-sistemas-uniamazonia`
3. Deja todo lo demás por defecto y pulsa **Create repository**
4. En la página del repositorio, pulsa **uploading an existing file**
5. Arrastra la carpeta `entrega1` (o los archivos y la carpeta `css`) al área de carga
6. Espera a que salga el check verde y pulsa **Commit changes**

## Publicar en Vercel

1. Entra a https://vercel.com y crea cuenta (o inicia sesión con GitHub)
2. Pulsa **Add New → Project**
3. Importa el repositorio que acabas de crear
4. Vercel detecta HTML estático: deja **Framework Preset** en `Other`
   y **Build Command** vacío, **Output Directory** en `.`
5. Pulsa **Deploy**

Vercel te dará una URL tipo `https://ingenieria-de-sistemas-uniamazonia.vercel.app`
y cada `push` a GitHub actualiza la página automáticamente.

## Correo de entrega

Destinatario: `w.patino@udla.edu.co`

Asunto: `Entregable 1 - Ingeniería de Sistemas - [Tu nombre]`

Cuerpo:

```
Estimado profesor:

Adjunto las URLs del Entregable 1.

Repositorio (público): https://github.com/[TU-USUARIO]/ingenieria-de-sistemas-uniamazonia
Página desplegada:    https://[TU-USUARIO].vercel.app

Saludos cordiales,
[Tu nombre]
```