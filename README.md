# 📝 Tech Writing Templates Library  📝

> **Plantillas profesionales de documentación técnica listas para usar**  
> Por María Nadal - Technical Writer

[![Licencia: CC BY 4.0](https://img.shields.io/badge/Licencia-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Markdown](https://img.shields.io/badge/Markdown-100%25-blue.svg)]()
[![Contribuciones: Bienvenidas](https://img.shields.io/badge/Contribuciones-Bienvenidas-green.svg)]()

---

## 🎯 Propósito

Esta biblioteca ofrece **plantillas probadas en proyectos reales** para acelerar la creación de documentación técnica de calidad. Cada plantilla incluye:

✅ Estructura completa con secciones predefinidas  
✅ Ejemplos de contenido real  
✅ Guías de uso y personalización  
✅ Mejores prácticas incorporadas

---

## 📚 Catálogo de Plantillas

### 📘 Documentación de APIs

#### 1. **API Reference Guide**
```
/templates/api-reference/
├── README.md
├── template-api-overview.md
├── template-endpoint-reference.md
├── template-authentication.md
├── template-error-codes.md
└── examples/
```
**Úsala para:** Documentar REST APIs, endpoints, parámetros y respuestas

#### 2. **API Quick Start Guide**
```
/templates/api-quickstart/
├── template-quickstart.md
└── examples/
```
**Úsala para:** Guías de primeros pasos con tu API (tiempo de lectura: 5-10 min)

---

### 📗 Manuales de Usuario

#### 3. **User Manual - Complete**
```
/templates/user-manual/
├── template-user-manual-full.md
├── template-getting-started.md
├── template-faq.md
├── template-troubleshooting.md
└── examples/
```
**Úsala para:** Documentación completa de producto para usuarios finales

#### 4. **Quick Reference Card**
```
/templates/quick-reference/
├── template-cheatsheet.md
└── examples/
```
**Úsala para:** Guías rápidas de 1-2 páginas para tareas comunes

---

### 📙 Documentación de Producto

#### 5. **Release Notes**
```
/templates/release-notes/
├── template-release-notes.md
└── examples/
```
**Úsala para:** Comunicar cambios en cada versión del producto

#### 6. **Feature Specification**
```
/templates/feature-spec/
├── template-feature-spec.md
└── examples/
```
**Úsala para:** Documentar nuevas funcionalidades antes de desarrollo

---

### 📕 Documentación Organizacional

#### 7. **Technical Onboarding Guide**
```
/templates/onboarding/
├── template-tech-onboarding.md
└── examples/
```
**Úsala para:** Incorporar nuevos desarrolladores al equipo

#### 8. **Security Policy Documentation**
```
/templates/security-policy/
├── template-security-policy.md
└── examples/
```
**Úsala para:** Políticas de seguridad, compliance y trabajo remoto

---

## 🚀 Cómo Usar Esta Biblioteca

### Paso 1: Elige tu plantilla
Navega al directorio `/templates/` y selecciona la que necesitas

### Paso 2: Copia el archivo
```bash
# Clona el repositorio
git clone https://github.com/nadalm344/tech-writing-templates.git

# Navega a la plantilla que necesitas
cd tech-writing-templates/templates/api-reference/

# Copia la plantilla a tu proyecto
cp template-api-overview.md /tu-proyecto/docs/
```

### Paso 3: Personaliza
- Reemplaza `[PLACEHOLDERS]` con tu contenido
- Ajusta secciones según tus necesidades
- Revisa los ejemplos para inspiración

### Paso 4: Valida
- ✅ ¿Es claro para tu audiencia objetivo?
- ✅ ¿Responde las preguntas más frecuentes?
- ✅ ¿Es fácil de mantener actualizado?

---

## 🎨 Estructura de Cada Plantilla

Todas las plantillas siguen este formato consistente:

```markdown
# [TÍTULO DE LA PLANTILLA]

## 📋 Meta-información
- **Audiencia objetivo:** [Quién usará esta documentación]
- **Tiempo de lectura estimado:** [X minutos]
- **Última actualización:** [Fecha]
- **Nivel técnico:** [Principiante/Intermedio/Avanzado]

## 🎯 Objetivo
[Qué problema resuelve esta documentación]

## 📝 Contenido
[Plantilla con secciones predefinidas]

## ✅ Checklist de Calidad
[Lista de verificación antes de publicar]

## 📚 Recursos Adicionales
[Links y referencias útiles]
```

---

## 💡 Mejores Prácticas Incluidas

Cada plantilla incorpora estos principios:

### ✍️ **Plain Language**
- Frases cortas (menos de 25 palabras)
- Voz activa en lugar de pasiva
- Vocabulario simple sin jerga innecesaria

### 🎯 **Orientada al Usuario**
- Estructura "lo más importante primero"
- Títulos y subtítulos descriptivos
- Ejemplos prácticos y reales

### 📱 **Diseño Responsivo**
- Funciona en cualquier dispositivo
- Tablas con scroll horizontal
- Imágenes con texto alternativo

### 🔍 **SEO y Búsqueda**
- Headings jerárquicos (H1 → H6)
- Keywords relevantes en títulos
- Tabla de contenidos autogenerada

---

## 🛠️ Tecnologías y Herramientas

Estas plantillas están optimizadas para:

- ✅ **GitHub/GitLab**: Markdown nativo
- ✅ **MkDocs**: Compatible con Material theme
- ✅ **Docusaurus**: Funciona con MDX
- ✅ **ReadTheDocs**: Compatible con reStructuredText (con adaptaciones)
- ✅ **Notion/Confluence**: Importación directa

---

## 🤝 Cómo Contribuir

¿Tienes una plantilla que te gustaría compartir? ¡Genial!

### Proceso de Contribución

1. **Fork** este repositorio
2. **Crea una rama**: `git checkout -b nueva-plantilla-X`
3. **Agrega tu plantilla** siguiendo la estructura existente
4. **Incluye ejemplos** en la carpeta `/examples/`
5. **Documenta el uso** en el README de la plantilla
6. **Envía un Pull Request**

### Criterios de Aceptación
- ✅ Sigue el formato estándar de la biblioteca
- ✅ Incluye al menos un ejemplo real (anonimizado)
- ✅ Está escrita en español (o inglés con traducción)
- ✅ Es útil para al menos 3 escenarios diferentes

---

## 📖 Guías Complementarias

Para sacar el máximo provecho de estas plantillas:

1. **[Style Guide de Documentación](../style-guide/)** - Convenciones de escritura
2. **[Checklist de Calidad](./quality-checklist.md)** - Validación antes de publicar
3. **[Glosario de Términos](./glossary.md)** - Vocabulario técnico unificado

---

## 🎓 Recursos de Aprendizaje

### Documentación Técnica
- [Google Developer Documentation Style Guide](https://developers.google.com/style)
- [Microsoft Writing Style Guide](https://docs.microsoft.com/en-us/style-guide/)
- [Write the Docs Community](https://www.writethedocs.org/)

### Markdown y Herramientas
- [Markdown Guide](https://www.markdownguide.org/)
- [Mermaid Diagrams](https://mermaid-js.github.io/)
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)

---

## 📊 Métricas de Éxito

¿Cómo saber si tu documentación funciona?

| Métrica | Objetivo | Cómo Medirla |
|---------|----------|--------------|
| **Tiempo en página** | 3-5 minutos | Analytics |
| **Tasa de rebote** | < 40% | Analytics |
| **Tickets de soporte** | ↓ 30% después de publicar | Sistema de tickets |
| **Feedback positivo** | > 80% | Encuestas en página |
| **Búsquedas internas** | Términos encontrados | Search analytics |

---

## 📜 Licencia

Este trabajo está bajo licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**Puedes:**
- ✅ Compartir y adaptar el material
- ✅ Usar en proyectos comerciales

**Bajo estos términos:**
- 📌 Atribución apropiada
- 📌 Enlace a la licencia
- 📌 Indicación de cambios realizados

---

## 🙏 Agradecimientos

Estas plantillas se han refinado gracias a:
- Feedback de +50 technical writers
- Implementación en proyectos reales
- Best practices de Google, Microsoft y Mozilla
- La comunidad de Write the Docs

---

## 💬 Contacto y Soporte

**María Nadal** - Technical Writer

- 📧 [LinkedIn](https://www.linkedin.com/in/maria-nadal-399176232)
- 🐙 [GitHub](https://github.com/nadalm344)
- 💼 Consultoría y workshops disponibles

---

<div align="center">

### ⭐ Si estas plantillas te ayudan, considera dejar una estrella

**"Good documentation is like a well-designed API: intuitive, complete, and a pleasure to use."**

*Última actualización: Diciembre 2025*

</div>
