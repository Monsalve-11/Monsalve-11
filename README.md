# ¡Hola! Soy **JHON MONSALVE** 👋

<!-- reemplaza TU_USUARIO con tu usuario de GitHub -->

## 🧑‍💻 Sobre mí

* 🎯 Intereses: Backend, IA, Seguridad, DevOps
* 🛠️ Stack principal: **Laravel · React · Node.js · MySQL · GitHub**
* 📫 Contáctame: [LinkedIn](https://www.linkedin.com/in/Monsalve-11) · [Email](mailto:mjhon6811@gmail.com)

---

## 📊 Mis estadísticas


### Rendimiento general

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Monsalve-11\&show_icons=true\&theme=transparent\&hide_title=false\&include_all_commits=true\&count_private=true)

### Lenguajes más usados

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Monsalve-11\&layout=compact\&langs_count=8\&hide_progress=false)

### Racha de contribuciones

![GitHub Streak](https://streak-stats.demolab.com?user=Monsalve-11\&theme=default\&date_format=j%20M%5B%20Y%5D)

### Trofeos

![trophy](https://github-profile-trophy.vercel.app/?username=Monsalve-11\&margin-w=8\&no-bg=true)

---

## 🧰 Tecnologías y herramientas

<!-- Cambia o quita lo que no uses -->

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel\&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?logo=react\&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853d?logo=node.js\&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?logo=mysql\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=github-actions\&logoColor=white)

---

## 🚀 Proyectos destacados

<a href="https://github.com/TU_USUARIO/PROYECTO_1"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Monsalve-11&repo=PROYECTO_1" /></a> <a href="https://github.com/Monsalve-11/PROYECTO_2"><img src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=PROYECTO_2" /></a>

> Ve al repo de cada proyecto y activa **Settings → General → Topics** para etiquetar con `laravel`, `react`, etc. ¡Eso ayuda a entender tu stack!

---

## 🗓️ Actividad reciente (opcional con Actions)

> Esto requiere un workflow que actualiza tu README con tus últimos PRs/commits. Crea `.github/workflows/activity.yml` con:

```yaml
name: Update README Activity
on:
  schedule:
    - cron: '0 */12 * * *'  # cada 12 horas
  workflow_dispatch:
permissions:
  contents: write
jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Generate activity
        uses: jamesgeorge007/github-activity-readme@v0.3.0
        with:
          COMMIT_MSG: "chore: updated activity"
      - name: Push changes
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add README.md
          git commit -m "chore: update activity"
          git push
```

Agrega donde quieras:

```md
### 🔄 Actividad
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
```

---

## 📈 Métricas avanzadas (opcional)

Puedes generar una imagen completa con métricas usando **lowlighter/metrics** (requiere token clásico con `repo` y `read:user`). Añade este job:

```yaml
name: Metrics
on:
  schedule:
    - cron: '0 0 * * *'  # diario
  workflow_dispatch:
permissions:
  contents: write
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: TU_USUARIO
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: America/Bogota
          plugin_isocalendar: yes
          plugin_languages: yes
          plugin_languages_sections: most-used
          plugin_languages_details: percentage
```

Y coloca la imagen en tu README donde quieras:

```md
![Metrics](https://raw.githubusercontent.com/Monsalve-11/Monsalve-11/main/github-metrics.svg)
```

---
