# Contribuciones de Aarón Flores Alberca

## Sprint 1:

### feature/llenado_modulos
- 2025-06-06: Creé el módulo de compute con `main.tf`, `outputs.tf` y `variables.tf`.
  Commit: `feat(compute): add terraform files for compute module`
  Pull request grupal: #25

- 2025-06-06: Agregué archivos terraform para el módulo de logging con configuración básica.
  Commit: `feat(logging): add terraform files for logging module`
  Pull request grupal: #25

- 2025-06-06: Implementé el módulo de monitoreo con declaraciones básicas y outputs de configuración.
  Commit: `feat(monitoring): add terraform files for monitoring module`
  Pull request grupal: #25

- 2025-06-06: Desarrollé el módulo de red con configuración de VPC CIDR y soporte NAT gateway.
  Commit: `feat(network): add terraform files for network module`
  Pull request grupal: #25

- 2025-06-06: Creé el módulo de seguridad con encriptación configurable y políticas de seguridad.
  Commit: `feat(security): add terraform files for security module`
  Pull request grupal: #25

- 2025-06-06: Implementé el módulo de almacenamiento con niveles de rendimiento y políticas de respaldo.
  Commit: `feat(storage): add terraform files for storage module`
  Pull request grupal: #25

### hotfix/network-err
- 2025-06-08: Corregí error en el plan de terraform debido a tipo de variable incorrecto en índice.
  Commit: `fix(network): Error when reproducing terraform plan due to variable of wrong type in index`
  Pull request grupal: #28

### feature/readme-update
- 2025-06-08: Actualicé el README según las especificaciones del sprint 1.
  Commit: `docs(README): Update README according to sprint 1 specifications.`
  Pull request grupal: #29

## Sprint 2:

### feature/write_markdown
- 2025-06-12: Agregué test de verificación simple para write_markdown que itera sobre el directorio docs.
  Commit: `feat(scripts): Add simple verification test for write_markdown`
  Pull request grupal: #34

- 2025-06-12: Completé la función write_markdown en terraform_docs que crea archivos markdown para cada módulo.
  Commit: `feat(scripts): Complete write_markdown function in terraform_docs`
  Pull request grupal: #34

- 2025-06-13: Agregué archivos Markdown como prueba de ejecución correcta de write_markdown.
  Commit: `feat(test): Add Markdown files as proof of correct execution of write_markdown`
  Pull request grupal: #34

- 2025-06-13: Modifiqué la función write_markdown para leer plantilla por separado.
  Commit: `feat(scripts): Modify the write_markdown function to read template separatedly`
  Pull request grupal: #34

- 2025-06-13: Creé template.md en un archivo separado.
  Commit: `feat(scripts): Create template.md in a separate file`
  Pull request grupal: #34

### feature/create_index
- 2025-06-13: Agregué ejecución en main y edité write_markdown.
  Commit: `edit(scripts): Add an execution in main and edit write_markdown`
  Pull request grupal: #37

- 2025-06-13: Agregué función create_index para crear automáticamente un index.md como punto de entrada.
  Commit: `feat(scripts): Add create_index function to automatically create an index.md`
  Pull request grupal: #37

- 2025-06-13: Creé directorio templates para almacenar archivos de plantilla Markdown.
  Commit: `feat(templates): Create templates directory to store template Markdown files`
  Pull request grupal: #37

### hotfix/default-dep
- 2025-06-14: Agregué valores por defecto en variables para módulos de monitoreo y red, y dependencia en seguridad.
  Commit: `fix(defaults): Add defaults values in variables for monitoring and network modules and dependency in security.`
  Pull request grupal: #39

## Sprint 3:

### feature/update-readme
- 2025-06-15: Agregué enlace al video del sprint 2 en el README.
  Commit: `update(readme): add link to sprint2 video`
  Pull request grupal: #42

- 2025-06-19: Actualicé los últimos cambios para el sprint 3 en el README.
  Commit: `update(readme): Update latest changes for sprint 3`
  Pull request grupal: #48

### feature/module-docs-update
- 2025-06-17: Actualicé archivos markdown de documentación con nuevas descripciones y scripts bash.
  Commit: `edit(docs): Update docs markdown files with new descriptions and bash scripts`
  Pull request grupal: #45

- 2025-06-17: Modifiqué write_markdown para adaptarse con parse_readme.
  Commit: `edit(script): Modify write_markdown to adapt with parse_readme`
  Pull request grupal: #45

- 2025-06-17: Agregué función parse_readme para extraer información de archivos readme de módulos IaC.
  Commit: `feat(script): add parse_readme to parse readme files`
  Pull request grupal: #45

- 2025-06-17: Edité plantilla para coincidir con nueva estructura con script bash.
  Commit: `edit(template): Edit template to match new structure with bash script`
  Pull request grupal: #45

- 2025-06-17: Agregué archivos readme.md en módulos iac con descripciones originales y scripts bash de ejemplo.
  Commit: `edit(iac): add readme.md files in iac modules`
  Pull request grupal: #45
