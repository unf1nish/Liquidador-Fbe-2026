# Liquidador de Flete Aéreo y Marítimo

>Herramienta web para liquidar fletes aéreos y marítimos FCL. Desarrollada como recurso para estudiantes, docentes de comercio exterior, logística y negocios internacionales, pensado en la PYMES que quieran entender la estructura básica de liquidación de fletes antes de cotizar con un agente de carga.

## Este proyecto permite calcular los costos de flete en dos modalidades de transporte internacional:
- **Aéreo** - Calcula el costo según el peso real y el peso volumétrico de la carga, además incluye costos de Due Agent, FS y Aduana.
- **Marítimo (FCL)** - Calcula el costo para embarques en contenedor completo (Full Container Load). Incluye calculo para el valor de aduana con base al valor de la mercancía (Valor mercancia **x** 0,28%) con una minima de 104 USD.

Este proyecto es especialmente útil para proyectos de investigación relacionados al comercio exterior, logística internacional y negocios internacionales.

## ¿Cómo usarlo?

### Versión en línea (recomendada)

El liquidador está desplegado y listo para usar sin ninguna instalación:

**[https://unf1nish.github.io/CargoLiq/](https://unf1nish.github.io/CargoLiq/)**

Simplemente abre el enlace en tu navegador, selecciona la modalidad (**Aéreo** o **Marítimo FCL**) e ingresa los datos.

---

### Uso local (para modificar o adaptar)

Si deseas personalizar las tarifas o adaptar el liquidador a tus necesidades, puedes descargarlo y modificarlo fácilmente:

1. Descarga o clona el repositorio:
   ```bash
   git clone https://github.com/unf1nish/CargoLiq.git

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

## Aviso Legal / Disclaimer

Las tarifas utilizadas en este liquidador fueron recopiladas durante mi período de **práctica empresarial como aprendiz** en el área de comercio exterior. Por lo tanto:

- Las tarifas son **referenciales** y pueden variar según el agente de carga, la aerolínea, la naviera y las condiciones del mercado.
- Este proyecto es de carácter **estrictamente académico y educativo**.
- El autor **no se hace responsable** por decisiones comerciales o financieras tomadas con base en los valores aquí calculados.
- Para cotizaciones reales y vinculantes, consulta directamente con un **agente de carga certificado**
