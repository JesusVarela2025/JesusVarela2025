# ¡Hola! Soy Jesús David Varela 👾
print("¡Hola!") 
print("Soy Jesús David Varela 👾")

# Sobre mí
sobre_mi = {
    "En aprendizaje": ["Unity", "Unreal Engine 4", "Figma"],
    "Explorando": "Nuevas tecnologías, desarrollando soluciones de software y hacks rápidos",
    "Formación": ["Ingeniería de Software", "Programación", "Matemáticas"],
    "Rol": ["Desarrollador Backend", "Desarrollador Frontend"],
    "Intereses": ["Ciberseguridad", "Inteligencia Artificial", "Anime", "Modelado 3D", "Blender", "After Effects"],
    "Mantra": "La práctica hace al experto"
}

# Tecnologías
tecnologias = {
    "Lenguajes de Programación": ["JavaScript", "Java", "Python"],
    "Frontend": ["HTML5", "CSS3", "Tailwind CSS"],
    "Backend": ["Node.js", "SQL", "RESTful API"],
    "Idiomas": {"Inglés": "B1", "Español": "Nativo"},
    "Conocimientos": [
        "Test-Driven Development", "Clean Code", "Patrones de Diseño", "Redes", "Git", 
        "Office 365", "Google Workspace", "Soporte Técnico", "Mantenimiento de ordenadores",
        "Redacción de Informes", "Gestión de Archivos", "Atención al Cliente"
    ],
    "Herramientas": [
        "Git", "GitHub", "Visual Studio Code", "Visual Studio 2022", "Canva", 
        "UML", "NuGet", "Figma", "MySQL Workbench", "XAMPP", "Behance", "CodePen"
    ]
}

# Conectar conmigo
contacto = {
    "LinkedIn": "https://www.linkedin.com/in/jesus-david-varela-melendez-34866a259/",
    "Correo": "mailto:jesusvarela288@gmail.com",
    "Website": "Tu sitio web aquí",
    "Resumen": "Link a tu CV aquí"
}

# Muestra la información
print("\nSobre mí:")
for clave, valor in sobre_mi.items():
    print(f"{clave}: {valor}")

print("\nTecnologías:")
for categoria, items in tecnologias.items():
    print(f"{categoria}: {', '.join(items) if isinstance(items, list) else items}")

print("\nConecta conmigo:")
for plataforma, link in contacto.items():
    print(f"{plataforma}: {link}")
