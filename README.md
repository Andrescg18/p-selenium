# Proyectos Selenium - Automatización de Pruebas con POM

Repositorio de automatización de pruebas End-to-End (E2E) desarrollado con **Java**, **Selenium WebDriver**, **JUnit 5** y el patrón de diseño **Page Object Model (POM)**.

## 📋 Proyectos incluidos

### 1. `laboratorio-pom-adso`
Automatización del formulario web interactivo de [Formy Project](https://formy-project.herokuapp.com/form).

#### Arquitectura del Proyecto:
```text
laboratorio-pom-adso/
├── pom.xml
└── src/
    ├── main/java/com/adso/pom/pages/
    │   └── FormPage.java          <-- Page Object (encapsula localizadores By y métodos de interacción)
    └── test/java/com/adso/pom/tests/
        └── FormTest.java          <-- Clase de prueba JUnit 5 (@BeforeEach, @Test, @AfterEach)
```

#### Tecnologías y Dependencias:
- **Java**: 17+
- **Maven**: Gestor de dependencias y ciclo de vida
- **Selenium Java**: 4.18.1
- **WebDriverManager**: 5.7.0 (gestión automática de ChromeDriver)
- **JUnit 5 Jupiter**: 5.10.2 (pruebas unitarias y aserciones)
- **Surefire Plugin**: 3.2.5

---

## 🚀 Ejecución de Pruebas

Para compilar y ejecutar la suite de pruebas automatizadas:

```powershell
cd laboratorio-pom-adso
mvn clean test
```

---

**Autor:** Andres Guardia  
**Programa:** ADSO - SENA
