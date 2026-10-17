# Humanizador

Una skill para Claude que hace que escriba como una persona y no como una IA. Son 15 reglas que le quitan las muletillas, las palabras de robot y los cierres de chatbot.

## Cómo se usa

- Pega un texto y escribe /humanizador. Claude te lo devuelve reescrito.
- O pídele que te escriba un correo, un post o un guion. La skill se activa sola.

## Cómo instalarla

### En Claude (web, escritorio o móvil)

1. Descarga el zip desde aquí: https://github.com/samuelcifg-source/humanizador/raw/main/humanizador.zip
2. En Claude, ve a Ajustes > Funciones (Settings > Features) y sube el zip en la sección de skills.
3. Listo. Abre un chat nuevo y pruébala.

### En Claude Code

Copia la carpeta humanizador dentro de ~/.claude/skills/ y escribe /humanizador.

    git clone https://github.com/samuelcifg-source/humanizador.git
    cp -r humanizador/humanizador ~/.claude/skills/
