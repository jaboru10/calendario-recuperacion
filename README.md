# Calendario de Recuperación Médica

Una aplicación web optimizada para móvil que permite hacer seguimiento de cuidados post-operatorios cardiacos.

## Características

- **Optimizado para móvil**: Diseño responsive que se adapta perfectamente a dispositivos móviles
- **Almacenamiento local**: Los datos se guardan automáticamente en el navegador del dispositivo
- **Navegación por semanas**: Fácil navegación entre diferentes semanas
- **Seguimiento completo**: Registro de medicamentos, mediciones vitales y observaciones

## Funcionalidades

### Mediciones diarias
- Peso
- Tensión arterial
- Glucosa
- Temperatura
- Saturación de oxígeno

### Control de medicamentos
- **Mañana**: EUTIROX, TOUJEO, APIXABAN, TEVETEN, SYNJARDY, INCRESYNT, BISOPROLOL, FUROSEMIDA, PARACETAMOL
- **Tarde**: ALDARA, SINTROM, PARACETAMOL
- **Noche**: DUODART, ZOLPIDEM, ALZILPLUS

### Observaciones
- Campo libre para notas adicionales por día

## Instalación para desarrollo local

```bash
npm install
npm run dev
```

## Despliegue en Vercel

1. Sube todos los archivos a tu repositorio de GitHub
2. Conecta tu repositorio con Vercel
3. Vercel detectará automáticamente la configuración y desplegará tu app

## Estructura de archivos

```
/
├── index.html          # Aplicación principal
├── package.json        # Dependencias del proyecto
├── vercel.json         # Configuración de Vercel
└── README.md          # Documentación
```

## Uso

1. Abre la aplicación en tu navegador móvil
2. Navega entre semanas usando los botones "Anterior" y "Siguiente"
3. Desliza horizontalmente para cambiar entre días de la semana
4. Completa las mediciones diarias
5. Marca los medicamentos tomados
6. Añade observaciones según sea necesario

Los datos se guardan automáticamente en el almacenamiento local del navegador.

## Compatibilidad

- Compatible con todos los navegadores modernos
- Optimizado para dispositivos móviles (iOS Safari, Chrome Mobile, etc.)
- Funciona sin conexión una vez cargada
- Los datos persisten entre sesiones

## Soporte

Esta aplicación está diseñada para uso personal en el seguimiento de cuidados médicos post-operatorios. Consulta siempre con tu médico antes de realizar cambios en tu tratamiento.