# PPS-Unidad2Actividad1-Raul_Albalat_Perez

# Trazado de Vulnerabilidad - CVE-2024-0204

## Descripción General
**CVE-2024-0204** es una vulnerabilidad crítica que afecta a **GoAnywhere MFT** de **Fortra**, que permite la **ejecución remota de código (RCE)**. Un atacante no autenticado puede explotar esta vulnerabilidad para ejecutar comandos arbitrarios en el servidor afectado, comprometiendo el sistema y los datos almacenados.

---

## Fuentes de Información

1. **CVE-2024-0204 en CVE.org**:  
   [CVE-2024-0204 - cve.org](https://cve.org/CVE-2024-0204)

2. **Base de datos de vulnerabilidades (NVD)**:  
   [CVE-2024-0204 en NVD](https://nvd.nist.gov/vuln/detail/CVE-2024-0204)

3. **INCIBE**:  
   [Artículo de INCIBE](https://www.incibe.es/empresas/avisos/vulnerabilidad-critica-de-omision-de-autenticacion-en-goanywhere-mft-de-fortra)

---

## Descripción de la Vulnerabilidad

La vulnerabilidad **CVE-2024-0204** en **GoAnywhere MFT** permite a los atacantes remotos ejecutar **código arbitrario** sin necesidad de autenticación previa. Esto puede ser explotado para obtener **acceso no autorizado** a los datos y sistemas, lo que representa un **riesgo grave** para la confidencialidad, integridad y disponibilidad de la infraestructura afectada.

- **Tipo de vulnerabilidad**: Ejecución remota de código (RCE)
- **Impacto**: Alto (confidencialidad, integridad, disponibilidad)
- **Nivel de severidad**: Crítico (CVSS 9.8)

---

## Información sobre el Riesgo y Criticidad

### **CVSS (Common Vulnerability Scoring System)**

- **Puntuación CVSS**: 9.8 (Crítico)
- **Vector de ataque**: Red
- **Privilegios requeridos**: Ninguno
- **Interacción con el usuario**: Ninguna

### **Métricas de Explotabilidad**:

- **Explotabilidad**: Baja (sin privilegios requeridos, sin interacción del usuario)
- **Alcance**: No modificado

### **Métricas de Impacto**:

- **Impacto en Confidencialidad**: Alto
- **Impacto en Integridad**: Alto
- **Impacto en Disponibilidad**: Alto

---

## Debilidades Explotadas (CWE)

### **CWE-425: Uncontrolled Resource Consumption (Consumo no controlado de recursos)**

Esta debilidad describe la falta de control sobre los recursos del sistema, que puede llevar a **consumo excesivo de recursos** o incluso a la ejecución de **código malicioso** en el sistema afectado. La vulnerabilidad **CVE-2024-0204** explota esta debilidad para ejecutar **comandos arbitrarios**.

#### [Más información sobre CWE-425](https://cwe.mitre.org/data/definitions/425.html)

---

## Información sobre Patrones de Ataque (CAPEC)

La vulnerabilidad **CVE-2024-0204** puede ser explotada mediante el patrón de ataque **CAPEC-152: Command Injection**.

### **CAPEC-152: Command Injection**
Este patrón de ataque describe cómo los atacantes pueden **inyectar comandos** maliciosos en el sistema afectado para ejecutar acciones no deseadas.

#### [Más información sobre CAPEC-152](https://capec.mitre.org/data/definitions/152.html)

---

## Registro CVE

El registro de CVE contiene información estandarizada sobre esta vulnerabilidad. Esta información puede ser utilizada por herramientas de seguridad para análisis automatizado.

- **Formato de registro CVE**: XML/JSON
- **Acceso a la información**: [CVE Record - CVE-2024-0204 en cve.org](https://cve.org/CVE-2024-0204)

---

## Referencias

- **Autenticación de Fortra en GoAnywhere MFT**:  
   [Enlace a la página de Fortra con más detalles](https://www.fortra.com/security)

- **NIST (National Institute of Standards and Technology)**:  
   [NVD - CVE-2024-0204 en NIST](https://nvd.nist.gov/vuln/detail/CVE-2024-0204)

---


**Autor**: Raúl Albalat  
**Fecha de realización**: Febrero 2025
