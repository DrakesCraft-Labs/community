<p align="center">
  <img src="https://raw.githubusercontent.com/DrakesCraft-Labs/community/main/banner.svg" width="100%" alt="COMMUNITY Animated Banner" />
</p>

# DrakesCraft Labs — Community & Discussions

> ### 🏰 ¡Únete a la Comunidad Oficial de DrakesCraft!
> 
> * 🎮 **IP del Servidor**: `mc.drakescraft.cl` *(Java 1.21.11 & Bedrock)*
> * 💬 **Discord Oficial**: [discord.gg/drakescraft](https://discord.gg/rv3vtXZTk7)
> * 🌐 **Web & Guía**: [web.drakescraft.cl](https://web.drakescraft.cl) — 🛒 **Tienda**: [web.drakescraft.cl/store](https://web.drakescraft.cl/store.html)
> 
> *¡Juega con StarSuites y más de 80 expansiones optimizadas en vivo en nuestra network de supervivencia técnica!*

---

Repositorio central para discusiones de arquitectura, anuncios de desarrollo, coordinación de issues cross-repository y gobernanza técnica del ecosistema **DrakesCraft-Labs**.

---

## 🎯 Propósito

Servir como punto de encuentro unificado para el equipo de desarrollo, administradores y colaboradores de la red DrakesCraft para:
- Proponer nuevas mecánicas, plugins y módulos para **[StarSuites](https://github.com/DrakesCraft-Labs/Drakes-Suites)**.
- Planificar hojas de ruta (*roadmaps*) y actualizaciones mayores de temporada.
- Reportar problemas que involucren múltiples plugins o servicios externos.
- Gestionar plantillas de incidencias y lineamientos de contribución.

---

## 🌐 Ecosistema DrakesCraft-Labs & StarSuites

- **Monorepo Insignia**: [**StarSuites**](https://github.com/DrakesCraft-Labs/Drakes-Suites) (`drakes-core.jar` a `drakes-server.jar`)
- **Motor Central de Servidor**: `Star Engine` / `Odysseia` (`drakes-server.jar`)
- **Suite Multiverse (Autoría Chagui68)**: `MultiverseCreatures` & `MultiverseNets`
- **Aceleración Off-Heap en Rust**: [`Slimefun-Rust`](https://github.com/DrakesCraft-Labs/Slimefun-Rust) & `Star-Rust`
- **Jefes & Encuentros Divinos**: `DrakesBosses`, `DiosesDrakes`
- **Economía & Finanzas**: `sbank`, `DrakesSlimeMarket`
- **Portal Web & Tienda**: `drakescraft-web`

---

## 📜 Normas de Desarrollo

1. **Entorno Oficial**: Paper/Purpur 1.21.11 en Java 21 (Rama `main`) y Purpur 26.2 (Rama `26.x`).
2. **Directiva de Monorepo**: Todo desarrollo para plugins consolidados debe realizarse exclusivamente en `StarSuites`.
3. **Compatibilidad Sin Regresiones**: Preservar estrictamente las claves de Paper Data Components (`slimefun:slimefun_item`).
4. **Seguridad en Producción**: Prohibido enviar comandos de reinicio destructivos sin coordinación previa.
