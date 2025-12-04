---
date: "2025-11-13"
description: Final statements
image: micare.jpg
math: true
enableEmoji: true
tags:
title: La narrativa de la transición energética
---




### Definición:
> <mark>**La transición energética global**, entendida como el proceso en el que las sociedades a escala mundial llevan a cabo estrategias para reducir el uso de combustibles de alto impacto ambiental (Naciones Unidas, 2023.)

### Contraste de emisiones Carbón vs. Gas Natural. 


![](./images/s8.jpg)

*Fuente: Elaboración propia con base en Allen, 2014; Lu et al., 2023)**





##  Consideraciones finales


La evidencia estudiada sobre el reciente impulso por construir 
proyectos para exportación de gas natural en las costas del Pacífico 
mexicano y en los estados fronterizos como Sonora, Chihuahua y Baja California, 
<span style="color: #46ECD5;">**contrasta con la tendencia negativa al desarrollo de estos proyectos en la costa oeste del suelo estadounidense.**</span>

* ##### *See the LULUS framework*.  <span style="color: #FCCEE8;">Locally Unwanted Land Uses</span>

[California Senate](https://sor.senate.ca.gov/sites/sor.senate.ca.gov/files/What%20is%20LNG.pdf)

* #### *In 2002 an LNG facility was proposed for Mare Island, a former naval shipyard in San Francisco Bay. Considerable citizen opposition prompted the <span style="color: #F54927;">withdrawal</span>  of this project.*

* #### *In 2004 the cabrillo Deepwater Port LNG facility was proposed off the coast of Malibu. <span style="color: #C11007;">The facility was denied</span> in a letter from the Governor and other state agencies*

* ####  *In 2004 a Long Beach onshore LNG facility was proposed, however, the California <span style="color: #FE9A37;">Supreme Court upheld the City of Long Beach’s decision not to review this project.</span>* 
 
* Ciudadanos en comunidades locales con relativa menor capacidad de gestión y organización social para prevenir proyectos en el marco de los  **LULU´s propuestos desde EE.UU**

* Mexico con una marco regulatorio ambiental robusto en papel pero con deficiente *enforcement* en la practica.

* Altos nivels de corrupción  institucional


### Conclusión


Importante estimar <span style="color: gold;">impactos **locales**</span> derivados de procesos **globales** que sustentados en la <span style="color: orange;">narrativa de "transición energética"</span> de hecho reflejan la prevalencia del <span style="color: gold;">interés económico</span> por sobre el cumplimiento de las metas 
de los acuerdos internacionales en materia climatica como el Acuerdo de Paris y los compromisos derivados de los encuentros COP.  

 México tiene una oportunidad actual de demostrar coherencia 
 con su política climática.  Que históricamente  se ha visto  moldeada por factores externos ajenos al interés público y por el contrario guiados 
 por una  perspectiva con beneficios privados de corto plazo. 
 

![](./images/qr4.jpg)


## <span style="color:  #fb8b2b;">II Foro Adaptaciones locales al cambio climático</span>
#####  El Colegio de la Frontera Norte
Diciembre 5, 2025.

jlmanzanaresrivera@colef.mx


<style>
/* Black background for this specific post */
main, .content, article, .post {
    background-color: #000000 !important;
    color: #ffffff !important;
    padding: 2rem !important;
    min-height: 100vh !important;
}

/* Add all the other styles from above */
</style>
  


---

<!-- Return to Home Page -->
<div style="text-align: center; margin: 2rem 0;">
  <a href="/" style="background-color: #2E86AB; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer; font-size: 14px; text-decoration: none; display: inline-block;">
    ← Return to Home
  </a>
</div>

<style>
.expandable-image {
    cursor: zoom-in;
    transition: transform 0.3s ease;
    border: 2px solid transparent;
}
.expandable-image:hover {
    transform: scale(1.02);
    border-color: #2E86AB;
}
.image-modal {
    display: none;
    position: fixed;
    z-index: 10000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.95);
    animation: fadeIn 0.3s;
}
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}
.modal-content {
    margin: auto;
    display: block;
    width: auto;
    max-width: 95%;
    max-height: 90vh;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    animation: zoomIn 0.3s;
}
@keyframes zoomIn {
    from { transform: translate(-50%, -50%) scale(0.8); }
    to { transform: translate(-50%, -50%) scale(1); }
}
.close-modal {
    position: absolute;
    top: 20px;
    right: 35px;
    color: #fff;
    font-size: 40px;
    font-weight: bold;
    cursor: pointer;
    z-index: 10001;
    background: rgba(0,0,0,0.5);
    border-radius: 50%;
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.close-modal:hover {
    color: #ccc;
    background: rgba(0,0,0,0.7);
}
.image-caption {
    color: #fff;
    text-align: center;
    padding: 15px;
    font-size: 14px;
    position: absolute;
    bottom: 0;
    width: 100%;
    background: rgba(0,0,0,0.7);
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
    // Crear el modal
    const modal = document.createElement('div');
    modal.className = 'image-modal';
    modal.innerHTML = `
        <span class="close-modal">&times;</span>
        <img class="modal-content" id="expanded-image">
        <div class="image-caption" id="modal-caption"></div>
    `;
    document.body.appendChild(modal);

    // Hacer las imágenes expandibles
    const images = document.querySelectorAll('img');
    images.forEach(img => {
        // No aplicar a botones o logos pequeños
        if (img.width > 100 && img.height > 100 && !img.closest('a')) {
            img.classList.add('expandable-image');
            
            img.addEventListener('click', function() {
                const modal = document.querySelector('.image-modal');
                const modalImg = document.getElementById('expanded-image');
                const caption = document.getElementById('modal-caption');
                
                modal.style.display = 'block';
                modalImg.src = this.src;
                modalImg.alt = this.alt;
                
                // Buscar el texto de fuente
                let sourceText = this.alt || '';
                let nextElement = this.nextElementSibling;
                
                // Buscar en los siguientes 2 elementos
                for (let i = 0; i < 2; i++) {
                    if (nextElement && nextElement.tagName === 'SPAN') {
                        if (nextElement.textContent.includes('Fuente:') || 
                            nextElement.textContent.includes('Source:')) {
                            sourceText = nextElement.textContent;
                            break;
                        }
                    }
                    if (nextElement) {
                        nextElement = nextElement.nextElementSibling;
                    }
                }
                
                caption.textContent = sourceText;
            });
        }
    });

    // Cerrar modal
    const closeBtn = document.querySelector('.close-modal');
    const modalElement = document.querySelector('.image-modal');
    
    closeBtn.addEventListener('click', function() {
        modalElement.style.display = 'none';
    });
    
    modalElement.addEventListener('click', function(e) {
        if (e.target === modalElement) {
            modalElement.style.display = 'none';
        }
    });
    
    // Cerrar con tecla ESC
    document.addEventListener('keydown', function(e) {
        if (e.key === 'Escape') {
            modalElement.style.display = 'none';
        }
    });
});
</script>