# Estudiante Edson Azurduy de la carrera de Sistemas Informaticos realiza su examen parcial creando este proyecto donde usara html5 semantico sobre la empresa MANACO el cual tambien debe ser renponsivo..
# Explicación mejoras a11y

# Estructura semántica HTML5: utilicé header, nav, main, section, article, footer para que lectores de pantalla entiendan el orden lógico.

# Contraste validado: verifiqué que texto oscuro (#111) sobre fondo claro (#fff y #f9f9f9) cumple con WCAG AA puedes validar con WebAIM Contrast Checker

# Acceso por teclado: probé con la tecla Tab para recorrer menús, botones y el enlace de “Saltar al contenido principal”. El foco es siempre visible.

# Alt descriptivos: cada imagen tiene alt claro que describe el producto (ej. “Zapato deportivo Modelo 1 en color negro”).

# ARIA mínimo y prudente: solo añadí aria-label al menú principal y aria-labelledby a la sección de productos. No se abusó de ARIA porque la semántica nativa ya comunica bien.