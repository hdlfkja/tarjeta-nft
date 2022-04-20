# Frontend Mentor: solución de componente de tarjeta de vista previa NFT

Esta es una solución al [desafío del componente de tarjeta de vista previa de NFT en Frontend Mentor] (https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Los desafíos de Frontend Mentor lo ayudan a mejorar sus habilidades de codificación mediante la creación de proyectos realistas.

## Tabla de contenido

- [Frontend Mentor: solución de componente de tarjeta de vista previa NFT](#frontend-mentor-solución-de-componente-de-tarjeta-de-vista-previa-nft)
  - [Tabla de contenido](#tabla-de-contenido)
  - [Visión de conjunto](#visión-de-conjunto)
    - [El reto](#el-reto)
    - [Captura de pantalla](#captura-de-pantalla)
    - [Enlaces](#enlaces)
  - [Mi proceso](#mi-proceso)
    - [Construido con](#construido-con)
    - [Que aprendí](#que-aprendí)
    - [Desarrollo continuo](#desarrollo-continuo)
  - [Autor](#autor)

## Visión de conjunto

### El reto

Los usuarios deben ser capaces de:

- Ver el diseño óptimo según el tamaño de pantalla de su dispositivo
- Ver estados de desplazamiento para elementos interactivos

### Captura de pantalla

![](./screenshot.png)

### Enlaces

- URL de la solución: [https://github.com/hdlfkja/tarjeta-nft.git]
- URL del sitio en vivo: [https://tarjeta-nft.netlify.app/]

## Mi proceso

### Construido con

- Marcado HTML5 semántico
- Propiedades personalizadas de CSS
- Caja flexible
- Animaciones CSS

### Que aprendí

Aprendi a como hacer animaciones en CSS

Para ver cómo puede agregar fragmentos de código, consulte a continuación:

```css
.imagen__hover {
    position: absolute;
    background-color: var(--cyanHover);
    border-radius: 1rem;
    width: 100%;
    height: 98%;
    display: flex;
    justify-content: center;
    align-items: center;
    top: 0;
    transform: scale(0);
    transition: transform .5s;
}
.imagen:hover .imagen__hover {
    transform: scale(1);
}
```

### Desarrollo continuo

.imagen__hover {
    position: absolute;
    background-color: var(--cyanHover);
    border-radius: 1rem;
    width: 100%;
    height: 98%;
    display: flex;
    justify-content: center;
    align-items: center;
    top: 0;
    transform: scale(0);
    transition: transform .5s;
}

Quiero seguir mejorando en la animacion CSS


## Autor

- Frontend Mentor - [@hdlfkja](https://www.frontendmentor.io/profile/hdlfkja)
- Twitter - [@JeanCar27866009](https://twitter.com/JeanCar27866009)

